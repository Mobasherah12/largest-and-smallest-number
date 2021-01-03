# largest-and-smallest-number
num = 0
largest = -1
smallest = None
while True:
num = input(“Enter a number: ”)
if num == “done” :
	break
try :
	num1 = int(num)
except :
	print(“Invalid input”)
if smallest is None :
	smallest = num1
elif num1 < smallest :
	smallest = num1
elif num1 > largest :
	largest = num1
# print largest number
print(“Maximum is”, largest)
# print smallest number
print(“Minimum is”, smallest)
