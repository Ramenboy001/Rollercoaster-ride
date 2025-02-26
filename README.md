# Rollercoaster-ride
# An easy rollercoaster machine
print("Welcome to Orji's rollercoaster ride")

height = int(input("Enter your height in cm?: "))

age = int(input("Enter your age: "))

bill = 0

if height < 120:

 print("Sorry for security reasons ,you are not tall enough to take this ride")

elif age < 13: 

    print("Sorry you are not old enough to take this ride.")      
    
elif age >= 13 and age <= 17:

    bill = 12 
    
    print("Children tickets are $12.")

elif age >= 18 and age <= 60:

    bill = 20
    
    print("Adult tickets are $20.")   
    
elif age > 60:

    print("Please enjoy a free ride.")
    
elif age > 70:

    print("Sorry you are to old to take this ride.")   

else: 

    print("You are really tall.")
   
photos = input("Do you want photos?: Y or N: ") 

if photos == "Y":

    bill += 3
    
if bill > 0:

    print((f"Your total bill is ${bill}"))
