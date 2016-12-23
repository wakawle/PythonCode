# PythonCode
一些python的神寫法


StackOverflow真是好地方：

Case:
Show non printable characters in a string,這個還滿方便用的 XD，運用到其他地方
import string
printable = string.ascii_letters + string.digits + string.punctuation + ' '
def hex_escape(s):
    return ''.join(c if c in printable else r'\x{0:02x}'.format(ord(c)) for c in s)
    
   
  
