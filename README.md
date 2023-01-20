while(True):
    command=input('add/ sub/ mult/ div or stop')
    if(command =='stop'):
        break
    elif(command=='add'):
        result= add()
        print(result)
    elif(command=='sub'):
        
        result= sub()
        print(result)
    elif(command=='mult'):
        
        result= mult()
        print(result)
    elif(command=='div'):
        
            result= div()
            print(result)
        
def add():
    num1=int(input('enter number1:'))
    num2=int(input('enter number1:'))
    result= num1+num2
    return result
    
def sub():
    num1=int(input('enter number1:'))
    num2=int(input('enter number1:'))
    result= num1-num2
    return result
    
    
def mult():
    num1=int(input('enter number1:'))
    num2=int(input('enter number1:'))
    result= num1*num2
    return result
    
    
def div():
        num1=int(input('enter number1:'))
        num2=int(input('enter number1:'))
        result= num1/num2
        return result    
