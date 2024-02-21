# Dynamic Contact Angle
This code is for analyzing advacing contact angle and receding contact angle.

## How to use
Download Dynamic_Contact_Angle.ipynb, make sure you have installed all required modulus in the requirements.

## Format of data
Data should be in .txt format. My data has titles splited into 2 rows, I merged them into header using the following code in my script:

'''
current_df.columns = (current_df.iloc[0] + '_' + current_df.iloc[1])
current_df = current_df.iloc[2:].reset_index(drop=True)
'''

The timeline, contact angle, and droplet base length are titled as 'Graph_Secs','Data_Angle', 'Data_Base' in my data, respectively. please make change to the code according to your data.
