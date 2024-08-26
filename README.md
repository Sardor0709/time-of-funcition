import time 
from turtle import*
start_time=time.time()

def decoratortime():
    
    start_time=time.time()
    for _ in range(1000000):
      pass
    end_time=time.time()
    elapsed_time=end_time-start_time
    print(f"Vaqt:{elapsed_time:4f}soniya")

decoratortime()
def  funcsion():
    
pass 

funcsion()    
