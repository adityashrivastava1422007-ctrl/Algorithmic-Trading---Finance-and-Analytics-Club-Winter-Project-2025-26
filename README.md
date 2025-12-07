[assignment2.ipynb.py](https://github.com/user-attachments/files/24016870/assignment2.ipynb.py)
# Question1

array = [1,2,3,4,5,6,7,8,9,3,4,56,67,33,44,56,23]
biggest = array[0]
for num in array:
    if(num>biggest):
        biggest = num
print(biggest)

#question2
a= input("Enter a word:")
b = a[::-1]

if(a==b):
    print("it is a palindrome")
else:
    print("no it is not a palindrome")

#Question3
array2 = [1,2,3,4,5,6,7,8,9,10,11,12,13,14]
array2.sort(reverse=True)
x=int(input("enter a number:"))
for i in range(len(array2)):
    for j in range(i+1,len(array2)):
        if(int(array2[i]-array2[j])==x):
            print("pair",i,j)



    
