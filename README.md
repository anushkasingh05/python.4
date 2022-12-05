# python.4
Python 3.10.6 (tags/v3.10.6:9c7b4bd, Aug  1 2022, 21:53:49) [MSC v.1932 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
l1=[i for i in range(1,10)]
print(l1)
[1, 2, 3, 4, 5, 6, 7, 8, 9]

l2=[i for i in range(1,10) if(i%2==0)]
print(l2)
[2, 4, 6, 8]

l3=[a*b for a in[1,2,3] for b in [10,20,30]]
print(l3)
[10, 20, 30, 20, 40, 60, 30, 60, 90]

l4=[a for a in [10,20,30,40] for b in [40,50,60,10] if(a==b)]
print(l4)
[10, 40]
