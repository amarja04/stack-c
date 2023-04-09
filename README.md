# stack-c

Stack:
Stack is an important data structure which stores its elements in an ordered manner. A stack is an Abstract Data Type (ADT), commonly used in most programming
languages.
It is a linear data structure which uses the same principle, i.e., the elements in a stack are added and removed only from one end, which is called
the TOP.

Hence, a stack is called a LIFO (Last-In-First-Out) data structure, as the element
that was inserted last is the first one to be taken out.

In stack terminology, insertion operation is called PUSH operation and removal
operation is called POP operation.

![image](https://user-images.githubusercontent.com/125913981/230797411-da6e5d93-1792-4410-bd29-9dbf3705cb58.png)


Basic Operations:

push() − Pushing (storing) an element on the stack.

Algorithm:

begin procedure push

    if stack is full
 
       return null
    
 endif
  
    top<--top+1
    
    stack[top]<--data
      

end procedure




pop()−Removing(accessing)anelementfromthestack.

Algorithm:

begin procedure pop

    if stack is empty
 
       return null
    
 endif
  
    data<-- stack[top]
    
    top<-- top-1
    
    return data
      

end procedure


IsEmpty: Check if the stack is empty.

Algorithm:

begin 

    if top less than 1
      
      return true 
      
   else
      
       return false
      
    endif

end procedure
   
   


IsFull: Check if the stack is full.

Algorithm:

begin 

    if top equals to MAXSIZE
      
      return true 
      
   else
      
       return false
    
    endif

end procedure

Peek: Get the value of the top element without removing it.

Algorithm:

begin 

      return stack [top] 
      
 end procedure
