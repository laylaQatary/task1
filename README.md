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
        
