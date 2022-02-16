import random
import string

print("Welcome to the password generator")

len = int(input("\n Enter the length of the password: "))

upper = string.ascii_uppercase
lower = string.ascii_lowercase
num = string.digits
char = string.punctuation

all = upper + lower + num + char 

out = random.sample(all,len)

postout = "".join(out)
print(postout)
