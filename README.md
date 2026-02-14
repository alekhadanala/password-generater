# password-generater

import random  # for random number 
import string  # for whith type of string u need

length=int(input("enter password leangth...:")) #how much leanth u need

password=""
for i in range(length):
     password += random.choice(string.ascii_lowercase + string.ascii_uppercase + string.digits + string.punctuation)  #coditions of the password
     print("password is :", password)
     
