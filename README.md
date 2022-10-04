# geeks-for-geeks-practise-solutions
# Python program for reverse of subarray
arr=[1,2,4,3,7,8,9,4,8,0]
K=3
rev=[]
i=0
size=len(arr)
while(i<size):
    l=arr[i:i+K][::-1]
    rev.extend(l)
    i=i+K
for i in rev:
    print(i,end=" ")
    
 # extend : This keywords adds the list of elements to the end of the list
 
 
 # By taking array as user input
 
arr=[]
n=int(input("enter no. of arr: "))
for i in range(0,n):
    ele=int(input("Enter array elements : "))
    arr.append(ele)
k=int(input("enter how many ele to be reversed: "))
j=0
rev=[]
while(j<n):
    l=arr[j:j+k][::-1]
    rev.extend(l)
    j=j+k
for s in rev:
    print(s,end=" ")
    
    
    
