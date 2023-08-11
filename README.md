# Arthemetic-operation
import sys
for welcome in range(0,2):
 print('''    .. ðŸ  ðŸ™ƒ HI FRIENDS ðŸ™ƒ  ðŸ.. 
 press any number to continue''' )
 break
s=int(input()) 
if s == 1010:
 print("Thanks Come Again")
 sys.exit()
p=float(input("enter first number:"))
q=float(input("enter second number:"))
r=input("operation to be done:")
if r=="addition":
 print("addition value:",p+q)
if r=="subtraction":
 print("subtraction value:",p-q)
if r=="multiplication":
 print("multiplication value:",p*q)
if r=="divison":
 print("division value:",p/q)
if r=="modulus":
 print("modulus value:",p%q)
if r=="power":
 print("exponintial value:",p**q)
if r=="floor division":
 print("floor division value:",p//q)
 print("THANK YOU FOR USING THIS PROGRAM")
