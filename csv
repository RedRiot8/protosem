import csv
from random import randint as rand
import os

def fill():
   for i in range(0,):
           p=[]
           p.append(i+1)
           for j in range(0,5):
               p.append(rand(0,100))
           print(p)
           writer.writerow(p)
           #n+=1
           #del p

fields=['#','Num1','Num2','Num3','Num4','Num5']
n=0
b=0
with open("file.csv","w")as file:
   writer=csv.writer(file)
   writer.writerow(fields)
   while True:
       b= os.path.getsize("file.csv")
       if b<2048:
             fill()
       else:
           n+=1,
           with open("file_"+n+".csv","w") as n:
               fill()
