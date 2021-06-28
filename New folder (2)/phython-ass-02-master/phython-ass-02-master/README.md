# Question No. 1
english=int(input("Please Enter Your English Marks"))
mark=100*english/100
e1=mark
if english >=80 and english <=100:
    E="A"
    
elif english >=70 and english < 80:
    E="B"
    
elif english >=60 and english < 70:
    E="C"
else:
    E="F"

urdu=int(input("Please Enter Your Urdu Marks"))
mark=100*urdu/100
e2=mark
if urdu >=80 and urdu <=100:
    U="A"
    ​# Question No. 1
english=int(input("Please Enter Your English Marks"))
mark=100*english/100
e1=mark
if english >=80 and english <=100:
    E="A"
    
elif english >=70 and english < 80:
    E="B"
    
elif english >=60 and english < 70:
    E="C"
else:
    E="F"

urdu=int(input("Please Enter Your Urdu Marks"))
mark=100*urdu/100
e2=mark
if urdu >=80 and urdu <=100:
    U="A"
    
elif urdu >=70 and urdu < 80:
    U="B"
    
elif urdu >=60 and urdu < 70:
    U="C"
else:
    U="F"
math=int(input("Please Enter Your Mathematics Marks"))
mark=100*math/100
e3=mark
if math >=80 and math <=100:
    M="A"
    
elif math >=70 and math < 80:
    M="B"
    
elif math >=60 and math < 70:
    M="C"
else:
    M="F"
science=int(input("Please Enter Your Science Marks"))
mark=100*science/100
e4=mark
if science >=80 and science <=100:
    S="A"
    
elif science >=70 and science < 80:
    S="B"
    
elif science >=60 and science < 70:
    S="C"
else:
    S="F"
pysics=int(input("Please Enter Your Pysics Marks"))
mark=100*pysics/100
e5=mark
if pysics >=80 and pysics <=100:
    P="A"
    
elif pysics >=70 and pysics < 80:
    P="B"
    
elif pysics >=60 and pysics < 70:
    P="C"
else:
    P="F"

if english <=100 and urdu <=100 and math <=100 and science <=100 and pysics <=100 :
    total_marks=english+urdu+math+science+pysics
    
    mark=100*total_marks
    perc=mark/500
    grade=perc
    if english > 60 and urdu > 60 and math > 60 and science > 60 and pysics > 60:
        pa="You are Passed"
        if grade >=80 and grade <=100:
            a="A"
            
        elif grade >=70 and grade < 80:
            a="B"
            
        elif grade >=60 and grade < 70:
            a="C"
            
        else:
            a="F"
    else:
        pa="You are Failed"
        a="F"
       
    
    
    print("|S.No  | Subjects   |    Marks    |Percent | Grade |")
    print("|--------------------------------------------------|")
    print("| 01   | English    |   ",english,"      |",e1,"% |  ",E,"  |")
    print("| 02   | Urdu       |   ",urdu,"      |",e2,"% |  ",U,"  |")
    print("| 03   | Mathematics|   ",math,"      |",e3,"% |  ",M,"  |")
    print("| 04   | Science    |   ",science,"      |",e4,"% |  ",S,"  |")
    print("| 05   | Physics    |   ",pysics,"      |",e5,"% |  ",P,"  |")
    print("|--------------------------------------------------|")
    print("|      |            | t.mark  500 | t.Percent|Grade|")
    print("|__________________________________________________|")
    print("|Result|Total       |Mark obt",total_marks,"| ",perc,"%  |",a,"  |")
    print("---------------------------------------------------|")
    
    print("Your Percentage is : ", perc)
    print("Your Total Marks is : ",total_marks)
    print("        ",pa)
    
else:
    print("Plz check your marks if your marks is greater than 100 so your programe will not run")
elif urdu >=70 and urdu < 80:
    U="B"
    
elif urdu >=60 and urdu < 70:
    U="C"
else:
    U="F"
math=int(input("Please Enter Your Mathematics Marks"))
mark=100*math/100
e3=mark
if math >=80 and math <=100:
    M="A"
    
elif math >=70 and math < 80:
    M="B"
    
elif math >=60 and math < 70:
    M="C" 
else:
    M="F"
science=int(input("Please Enter Your Science Marks"))
mark=100*science/100
e4=mark
if science >=80 and science <=100:
    S="A"
    
elif science >=70 and science < 80:
    S="B"
    
elif science >=60 and science < 70:
    S="C"
else:
    S="F"
pysics=int(input("Please Enter Your Pysics Marks"))
mark=100*pysics/100
e5=mark
if pysics >=80 and pysics <=100:
    P="A"
    
elif pysics >=70 and pysics < 80:
    P="B"
    
elif pysics >=60 and pysics < 70:
    P="C"
else:
    P="F"

if english <=100 and urdu <=100 and math <=100 and science <=100 and pysics <=100 :
    total_marks=english+urdu+math+science+pysics
    
    mark=100*total_marks
    perc=mark/500
    grade=perc
    if english > 60 and urdu > 60 and math > 60 and science > 60 and pysics > 60:
        pa="You are Passed"
        if grade >=80 and grade <=100:
            a="A"
            
        elif grade >=70 and grade < 80:
            a="B"
            
        elif grade >=60 and grade < 70:
            a="C"
            
        else:
            a="F"
    else:
        pa="You are Failed"
        a="F"
       
    
    
    print("|S.No  | Subjects   |    Marks    |Percent | Grade |")
    print("|--------------------------------------------------|")
    print("| 01   | English    |   ",english,"      |",e1,"% |  ",E,"  |")
    print("| 02   | Urdu       |   ",urdu,"      |",e2,"% |  ",U,"  |")
    print("| 03   | Mathematics|   ",math,"      |",e3,"% |  ",M,"  |")
    print("| 04   | Science    |   ",science,"      |",e4,"% |  ",S,"  |")
    print("| 05   | Physics    |   ",pysics,"      |",e5,"% |  ",P,"  |")
    print("|--------------------------------------------------|")
    print("|      |            | t.mark  500 | t.Percent|Grade|")
    print("|__________________________________________________|")
    print("|Result|Total       |Mark obt",total_marks,"| ",perc,"%  |",a,"  |")
    print("---------------------------------------------------|")
    
    print("Your Percentage is : ", perc)
    print("Your Total Marks is : ",total_marks)
    print("        ",pa)
    
else:
    print("Plz check your marks if your marks is greater than 100 so your programe will not run")
    
    
    
# Question No. 2

user=int(input("Please Enter Your Number"))
if user % 2==0:
    print("Your number is Even")
else:
    print("Your number is ODD")
    
    
    
# Question No. 3
arr=["USAMA",125,5,8,9,6,2,4]
print(len(arr))
arr1=arr+["Sindh","Karachi"]
print(len(arr1))

# Question no. 4
arr=[6,8,9,2,3,4,5]
#print(sum(arr))
result=arr[0]+arr[1]+arr[2]+arr[3]+arr[4]+arr[5]+arr[6]
print(result)


# Question No. 5
arr=[10,8,9,5,3,2,1]
arr.sort()
print(arr)
larg=arr[-1]
print(larg)



# Question No. 6
a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]
lis=[]
for i in a:
    if i < 5:
      lis.append(i)
print(lis)    
