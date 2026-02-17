stack=[]
while True:
    print("1.Push 2.Pop 3.Display 4.Exit")
    ch=int(input())
    if ch==1:
        stack.append(int(input("Enter value: ")))
    elif ch==2:
        if stack:
            print("Popped:",stack.pop())
        else:
            print("Stack Empty")
    elif ch==3:
        print("Stack:",stack)
    else:
        break

Output:

Stack Empty
