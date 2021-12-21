Number = int(input("Enter a number: "))
isdivisble = False
i = 2;

while i < Number:
    if Number % i == 0:
        isdivisble=True
        print("{} is divisble by {} ".format(Number,i))
    i +=1

if isdivisble:
    print("{} not a prime number ".format(Number) )

else:
   print("{} is a Prime Number".format(Number))
