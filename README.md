# function
function programs
def arm(n):
    sum=0
    c=len(str(n))
    while n!=0:
        ld=n%10
        n=n//10
        sum+=ld**c
    return sum
def am(m,n):
    for i in range(m,n):
        if arm(i)==i:
            print(i)
am(1,300)'
