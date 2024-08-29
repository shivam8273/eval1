# eval1
d1={}
d2={}
def bmi(h,w):
    bm=(w**2)/h
    return int(bm)

for i in range (0,2):
    name=input("enter name : ")
    clas=int(input("enter class :"))
    height=int(input("enter height :"))
    weight=int(input("enter weight : "))
    food=input("enter food eat : ")
    cal=int(input("enter calorie : "))
    if(i==0):
        d1.update({"name" : name})
        d1.update({"class" : clas})
        d1.update({"height" : height})
        d1.update({"weight" : weight})
        d1.update({"food" : food})
        d1.update({"calorie" : cal})
        b=bmi(height,weight)
        print(b)
    elif(i==1):
        d2.update({"name" : name})
        d2.update({"class" : clas})
        d2.update({"height" : height})
        d2.update({"weight" : weight})
        d2.update({"food" : food})
        d2.update({"calorie" : cal})
print(d1)
print(d2)
