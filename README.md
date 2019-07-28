   #Program 1

year=2004
if year%4==0 and year%100!=0:
    print(year,"is leap year")
else:
    print(year,"is not leap year")
    
    
    #Program 2
 
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
	

#Program 5

AMT = 100250
Y = {"2000":0,"500":0,"100":0,"50":0,"20":0,"10":0}

div = AMT // 2000
if div >= 1:
	Y["2000"]=div
	AMT -= (2000 * div)

if AMT >= 500:
	div = AMT // 500
	if div >= 1:
		Y["500"]=div
		AMT -= (500 * div)

if AMT >= 100:
	div = AMT // 100
	if div >= 1:
		Y["100"]=div
		AMT -= (100 * div)

if AMT >= 50:
	div = AMT // 50
	if div >= 1:
		Y["50"]=div
		AMT -= (50 * div)

if AMT >= 20:
	div = AMT // 20
	if div >= 1:
		Y["20"]=div
		AMT -= (20 * div)

if AMT >= 10:
	div = AMT // 10
	if div >= 1:
		Y["10"]=div
		AMT -= (10 * div)

print("2000=",Y["2000"],",500=",Y["500"],",100=",Y["100"],",20=",Y["20"],",10=",Y["10"])

#Program 6

for Value in range(1,51):
	if Value % 7 != 0 and ((Value - 7) % 10) != 0:
		print(Value)
		
#Program 7

squaresum = 0
for value in range(10,20):
	square = value ** 2
	squaresum += square
print("square is",squaresum)


#Program 8

Number = 50
while Number > 1:
	if Number % 2 == 0:
		Number = Number // 2
		print(Number)
	else:
		Number = (Number * 3) + 1
		print(Number)
		
#Program 9

A = 10
B = 100
x = 0
if A > B:
	x = A
else:
	x = B

while (A * B) >= x:
	if (x % A == 0) and (x % B == 0):
		break
	x += 1
print(x)

		
#Program 10 :

x = 123456789
ReverseNum = 0
while x > 0: 
    ReverseNum = (ReverseNum * 10) + (x % 10)
    x = x//10

print(ReverseNum)




	

