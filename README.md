## Python_test2
#### A file for quaraticequation
*# -*- coding: utf-8 -*  
a=input("请输入a值：")  #求一元二次函数
b=input("请输入b值: ")  
c=input("请输入c值: ")  
d=b*b-4*a*c  
if d<0:  
 print("无解！")  
else:  
 x1=(-b+(b*b-4*a*c) ** 0.5)/2*a  
 x2=(-b-(b*b-4*a*c) ** 0.5)/2*a  
print("解x1为{:.2f},解x2为{:.2f}".format(x1,x2))* 

*# -*- coding: utf-8 -* #缺少编码类型声明  
basic_salary=1500  #求员工工资  
salary_rate=0.02  
bonus_sale=200  
ca=input("请输入销售相机数量 ")  
price=input("请输入相机单价 ")  
salary=1500+ca*200+salary_rate*ca*price  
print("销售总额为:{:.2f}".format(salary))*

while True:  # 求一个数的平方
    i=int(input("enter a number:"))  
    if i<0:  
        continue  
    elif i==0:  
        break  
    print("pingfangshi{}".format(i**2))  
    break  
print("thank")  
