# py-29
swap case using python
def print_even(s):
    new=""
    for i in s:
            asc=ord(i)
            if(65<=asc<=90):
                ch=chr(asc+32)
                new+=ch
            elif(97<=asc<=122):
                ch=chr(asc-32)
                new+=ch
    return new
print(print_even("PYTHON"))
