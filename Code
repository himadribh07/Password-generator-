#To generate a secure password 

import string
import random
s1 = string.ascii_lowercase
    # s1 is used for taking lowercase which will be used in the password

s2 = string.ascii_uppercase
    # s2 is used for taking uppercase which will be used in the password

s3 = string.digits
    # s3 is used for taking digits which will be used in the password

s4 = string.punctuation
    # s4 is used for taking punctuation which will be used in the password

pwd_length = int(input("Enter the password length you want: "))
    # To know password length from the user 

s=[]
    # It is used to create a blank string

s.extend(list(s1))
    # List syntax is used to make any string into a list

s.extend(list(s2))
    # List syntax is used to make any string into a list

s.extend(list(s3))
    # List syntax is used to make any string into a list

s.extend(list(s4))
    # List syntax is used to make any string into a list

random.shuffle(s)
    # Random is used to create random secure password everytime the program runs

print("Your secure password is ready: ")
print("".join(s[0:pwd_length]))
    # The join() method takes all items in an iterable and joins them into one string.

    
