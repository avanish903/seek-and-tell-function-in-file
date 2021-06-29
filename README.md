# seek-and-tell-function-in-file
it is more about file
f=open("awanish.txt")
# print(f.tell())# it will tell on how many characters have read as 
print(f.readline())
# print(f.tell())
# f.seek(0)# it will set pointer to 0 so that following readline will again read the first line
f.seek(12)# it will start from 12th character
print(f.readline())
# print(f.tell())
# print(f.readline())
f.close()
