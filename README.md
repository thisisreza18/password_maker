# password_maker
Password_Maker With Python Programming Language

import string
from random import *

char = string.ascii_letters + string.punctuation + string.digits
password = "".join(choice(char) for x in range(randint(8 , 16)))
print('your password : ' , password)
