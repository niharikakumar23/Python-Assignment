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
	
	
	
#Program 3

Unit = 400
Total = 0
if Unit > 250:
	Total = Unit * 1.5
elif Unit > 150 and Unit <= 250:
	Unit -= 150
	Total += (Unit * 1.2)		
	Total += (100 * 0.75)
	Total += (50 * 0.5)
	Unit += 150
elif Unit > 50 and Unit <= 150:
	Unit -= 50
	Total += (Unit * 0.75)	
	Total += (50 * 0.5)
	Unit += 50
elif Unit <= 50:
	Total += (Unit * 0.5)
Total += (Total * 0.2 )
print("Total Bill", Unit, "is", Total)



#Program 4


a = 5235
b = 1
tip = 0

if b > 5:
	print("Invalid")
else:
	if b == 1:
		tip = a * 0.05
	elif b == 2:
		tip = a * 0.1
	elif b == 3:
		tip = a * 0.15
	elif b == 4:
		tip = a * 0.2
	elif b == 5:
		tip = a * 0.25
	print("Tip of Rs.",a,"is Rs.",tip)

