# Program to display the Fibonacci series numbers up to the n-th terms

nterms = int(input("How many terms? "))

#first two terms
n1,n2 =0,1
count =0

#check if the number is valid or not
if nterms <=0:
    print("Please enter a positive integer ")
elif nterms == 1:
    print("Fibonacci series upto",nterms,":")
    print(n1)
else:
    print("Fibonacci series numbers: ")
    while count < nterms:
        print(n1)
        nth =  n1 + n2
        #update values
        n1 = n2
        n2 = nth
        count +=1
