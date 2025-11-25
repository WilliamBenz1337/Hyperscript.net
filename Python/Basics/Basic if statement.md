This is a basic If Statements that asks a user for input and checks their age.


```python3
age = int(input("Enter your age: "))               #Ask the user for their age    

if age >= 20:                                      #If age greater or equals to than 20 then
    print("You are allowed to drive a car!")       #then print this
elif age >= 70:                                    #If age greater or equals to 70 then
    print("You are a senior!")                     #Print this
else:                                              #ANYTHING OUTSIDE OF THESE VALUES
    print("Please try later!")                     #Print this
```
