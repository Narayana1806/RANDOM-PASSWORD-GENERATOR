# RANDOM-PASSWORD-GENERATOR

import random
import string

list = string.printable

num = int(input("Enter the length of your password: "))
word = ""
number = ""
symbol = ""


for i in range(num):
    char = random.choice(list)
    word = char + word + number + symbol
print(word)
     
