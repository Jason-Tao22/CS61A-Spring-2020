Expreesions(表达式):
    由数和代数组成：如 3, 3x , 3x+5a等

    Primitive expreesions:
    原始表达式
    
       eg:  2 (Number or Numeral)
            add (Name)
            "Hello" (String)

    Call expressions:
    调用表达式
        
        eg: max ( 2  ,  3  )

        max是Operator
        2是Operand
        3是Operand



Name(我的理解是变量)

为name绑定value有三种方式

1. import-->这种只能导入built-in function(内置函数)
   
2. assignment statement-->这种命名方式可以 give a value to a new name or to change the value bound to a name

        这种方式有个问题：变量之间不同步：

            radius=10
            area=radius^2*pi
            print(area)-->area=314.15926..
            radius=20
            print(area)-->area=314.15926..
            ## area的值并没有随着radius的改变而改变，变量之间不会绑定同步

        如果需要变量同步的话如何解决？
        不要把area定义成一个变量；而是把area定义成一个函数(def的方法): 

            def area(){
                area=raius^2*pi;    
                }

            ##此时area就是一个function储存
            print(area);
            ## function area at 0x....




3. def()-->这种创建自己设计的函数，同样是把值赋到name中