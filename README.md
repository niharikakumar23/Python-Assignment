# Program 1

year=2004
if year%4==0 and year%100!=0:
    print(year,"is leap year")
else:
    print(year,"is not leap year")
    
    
   # Program 2
 
 angleSet = (50,40,90)
Sum = 0
for index, value in enumerate(angleSet):
	if index <= 2: 
		if value == 0:
			print("Value" , index)
			break
		else:
			Sum += value
			continue

if Sum == 180:
	print("Correct")
else:
	print("Incorrect")

