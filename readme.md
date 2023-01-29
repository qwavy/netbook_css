1
#a = int(input("Введит число от 1 до 1000:"))
#b = int(input("Введите число от 1 до 1000:"))
#if a > b:
    #print(a)
#else:
   # print(b)
   
2
#a = int(input("Введите первое число:"))
#b = int(input("Введите второе число:"))
#if a > b:
    #print("1")
#elif a < b:
    #print("2")
#else:
    #print("0")
    
3
#a = int(input("Введите первое число:"))
#b = int(input("Введите второе число:"))
#c = int(input("Введите третье число:"))
#if a>b and a>c:
    #print(a)
#elif b>a and b>c:
    #print(b)
#else:
    #print(c)

4
#a = int(input("Введите год:"))
#if a%4 == 0 and a%100 == 0 and a%400 == 0:
    #print("YES")
#else:
    #print("NO")
    
5
#a1 = int(input("Введите число от 1 до 8:"))
#a2 = int(input("Введите число от 1 до 8:"))
#b1 = int(input("Введите число от 1 до 8:"))
#b2 = int(input("Введите число от 1 до 8:"))
#if (a1+a2) - (b1+b2) == 1:
#     print("YES")
# elif (b1+b2) - (a1+a2) == 1:
#     print("YES")
# elif (a1+a2) - (b1+b2) == -1: 
#     print("YES")
# elif (b1+b2) - (a1+a2) == -1:
#     print("YES")
# else:
#     print("NO")

7
a1 = int(input("Введите число от 1 до 8:"))
a2 = int(input("Введите число от 1 до 8:"))
b1 = int(input("Введите число от 1 до 8:"))
b2 = int(input("Введите число от 1 до 8:"))
if a1 %2 == 0 and a2 %2 == 1 and b1 %2 == 0 and b2 %2 == 1:
    print("YES")
elif a1 %2 == 1 and a2 %2 == 0 and b1 %2 == 1 and b2 %2 == 0:
    print("YES")
else:
    print("NO")