# shukla

#Write a program to check it is prime or not
N=int(input("ENTER THE NUMBER:"))
f=1
for i in range(2,N):
#for i in range(2,N):
						if(N%i==0):
										f=0
if(f==1):
			print(N," PRIME NUMBER")
else:
			print(N,"NOT A PRIME NUMBER")
				
