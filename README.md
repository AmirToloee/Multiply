# Multiply
Multipliction with function and for
#multipliction tabale with function and for
#جدول ضرب با استفاده از تابع و حلقه for
class multiply:
    def __init__ (self,x,y):
                    for i in range(1,x+1):
                        for j in range(1,y+1):
                            print(format(i*j,'3d'),end='  ')
                        print('\n')
                        
class number(multiply):
    def __init__(self,x,y):
        super().__init__(x,y)

x=number(10,10)
