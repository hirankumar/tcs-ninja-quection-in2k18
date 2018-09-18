# tcs-ninja-quection-in2k18
this converts the characters into spacial characters

ovel=input()
con=input()
upp=input()
o=[]
c=[]
u=[]
for i in  ovel:
	if i=='a' or i=='A' or i=='e' or i=='E' or i=='i' or i=='I' or i=='o' or i=='O' or i=='u' or i=='U':
		o.append("$")
	else:
		o.append(i)
for i in con:
	if i=='a' or i=='A' or i=='e' or i=='E' or i=='i' or i=='I' or i=='o' or i=='O' or i=='u' or i=='U':
		c.append(i)
	else:
		c.append("#")
for i in range(0, len(o)):
	print(o[i],end="")
print(" ",end="")
for i in range(0,len(c)):
	print(c[i],end="")
print(" ",end="")
print(upp.swapcase())
	
	
