# mycaptain_projects
terms = int(input("Enter the number of terms: "))
a,b = 0,1
count = 0
if terms <= 0:
    print("Enter a positive integer and try again")
elif terms ==1:
    print("Fibbonacci sequence upto",terms,":")
    print(a)

else:
    print("Fibbonacci sequence:")
    while count < terms:
        print(a)
        c = a + b
        a = b
        b = c
        count+= 1
