from tkinter import Tk, Button, Frame, Label
import time
import random

root = Tk()
root.geometry("381x500")
root.title("Zero-Kata")
root.resizable(width = 0, height = 0)

lst = [1,2,3,4,5,6,7,8,9]

def disable_all():
    btn1.config(state = "disable")
    btn2.config(state = "disable")
    btn3.config(state = "disable")
    btn4.config(state = "disable")
    btn5.config(state = "disable")
    btn6.config(state = "disable")
    btn7.config(state = "disable")
    btn8.config(state = "disable")
    btn9.config(state = "disable")

def reset_():
    global lst
    btn1.config(text = "", state = "normal")
    btn2.config(text = "", state = "normal")
    btn3.config(text = "", state = "normal")
    btn4.config(text = "", state = "normal")
    btn5.config(text = "", state = "normal")
    btn6.config(text = "", state = "normal")
    btn7.config(text = "", state = "normal")
    btn8.config(text = "", state = "normal")
    btn9.config(text = "", state = "normal")
    show.config(text = "")
    lst = [1,2,3,4,5,6,7,8,9]

def win():
    # 123, 456, 789, 147, 258, 369, 159, 357

    b1 = btn1.cget('text')
    b2 = btn2.cget('text')
    b3 = btn3.cget('text')
    b4 = btn4.cget('text')
    b5 = btn5.cget('text')
    b6 = btn6.cget('text')
    b7 = btn7.cget('text')
    b8 = btn8.cget('text')
    b9 = btn9.cget('text')

    if b1  == 'X' and b2  == 'X' and b3 == 'X':
        print("You Won!")
        show.config(text = "You Won!")
        disable_all()

    elif b1 == 'O' and b2 == 'O' and b3 == 'O':
        print("Computer Won!")
        show.config(text = "You Lost.")
        disable_all()
    
    if b4 == 'X' and b5 == 'X' and b6 == "X":
        show.config(text = "You Won!")
        disable_all()
    elif b4 == 'O' and b5 == 'O' and b6 == "O":
        print("Computer Won!")
        show.config(text = "You Lost.")
        disable_all()

    if b7 == 'X' and b8 == 'X' and b9 == "X":
        print("You Won!")
        show.config(text = "You Won!")
        disable_all()
    elif b7 == 'O' and b8 == 'O' and b9 == "O":
        print("Computer Won!")
        show.config(text = "You Lost.")
        disable_all()

    if b1 == 'X' and b4 == 'X' and b7 == "X":
        print("You Won!")
        show.config(text = "You Won!")
        disable_all()
    elif b1 == 'O' and b4 == 'O' and b7 == "O":
        print("Computer Won!")
        show.config(text = "You Lost.")
        disable_all()

    if b2 == 'X' and b5 == 'X' and b8 == "X":
        print("You Won!")
        show.config(text = "You Won!")
        disable_all()
    elif b2 == 'O' and b5 == 'O' and b8 == "O":
        print("Computer Won!")
        show.config(text = "You Lost.")
        disable_all()

    if b3 == 'X' and b6 == 'X' and b9 == "X":
        print("You Won!")
        show.config(text = "You Won!")
        disable_all()
    elif b3 == 'O' and b6 == 'O' and b9 == "O":
        print("Computer Won!")
        show.config(text = "You Lost.")
        disable_all()
    
    if b1 == 'X' and b5 == 'X' and b9 == "X":
        print("You Won!")
        show.config(text = "You Won!")
        disable_all()
    elif b1 == 'O' and b5 == 'O' and b9 == "O":
        print("Computer Won!")
        show.config(text = "You Lost.")
        disable_all()

    if b3 == 'X' and b5 == 'X' and b7 == "X":
        print("You Won!")
        show.config(text = "You Won!")
        disable_all()
    elif b3 == 'O' and b5 == 'O' and b7 == "O":
        print("Computer Won!")
        show.config(text = "You Lost.")
        disable_all()
    
    # return None



def b1(): 
    global l
    btn1.config(text = 'X', state = "disabled")
    lst.remove(1)
    r = []
    r = random.choices(lst)
    if r == [2]:
        btn2.config(text = "O", state = "disabled")
        lst.remove(2)
    elif r == [3]:
        btn3.config(text = "O", state = "disabled")
        lst.remove(3)
    elif r == [4]:
        btn4.config(text = "O", state = "disabled")
        lst.remove(4)
    elif r == [5]:
        btn5.config(text = "O", state = "disabled")
        lst.remove(5)
    elif r == [6]:
        btn6.config(text = "O", state = "disabled")
        lst.remove(6)
    elif r == [7]:
        btn7.config(text = "O", state = "disabled")
        lst.remove(7)
    elif r == [8]:
        btn8.config(text = "O", state = "disabled")
        lst.remove(8)
    elif r == [9]:
        btn9.config(text = "O", state = "disabled")
        lst.remove(9)
    print(lst)

def b2(): 
    btn2.config(text = 'X', state = "disabled")
    lst.remove(2)
    r = []
    r = random.choices(lst)
    if r == [1]:
        btn1.config(text = "O", state = "disabled")
        lst.remove(1)
    elif r == [3]:
        btn3.config(text = "O", state = "disabled")
        lst.remove(3)
    elif r == [4]:
        btn4.config(text = "O", state = "disabled")
        lst.remove(4)
    elif r == [5]:
        btn5.config(text = "O", state = "disabled")
        lst.remove(5)
    elif r == [6]:
        btn6.config(text = "O", state = "disabled")
        lst.remove(6)
    elif r == [7]:
        btn7.config(text = "O", state = "disabled")
        lst.remove(7)
    elif r == [8]:
        btn8.config(text = "O", state = "disabled")
        lst.remove(8)
    elif r == [9]:
        btn9.config(text = "O", state = "disabled")
        lst.remove(9)
    print(lst)

def b3(): 
    btn3.config(text = 'X', state = "disabled")
    lst.remove(3)
    r = []
    r = random.choices(lst)
    if r == [2]:
        btn2.config(text = "O", state = "disabled")
        lst.remove(2)
    elif r == [1]:
        btn1.config(text = "O", state = "disabled")
        lst.remove(1)
    elif r == [4]:
        btn4.config(text = "O", state = "disabled")
        lst.remove(4)
    elif r == [5]:
        btn5.config(text = "O", state = "disabled")
        lst.remove(5)
    elif r == [6]:
        btn6.config(text = "O", state = "disabled")
        lst.remove(6)
    elif r == [7]:
        btn7.config(text = "O", state = "disabled")
        lst.remove(7)
    elif r == [8]:
        btn8.config(text = "O", state = "disabled")
        lst.remove(8)
    elif r == [9]:
        btn9.config(text = "O", state = "disabled")
        lst.remove(9)
    print(lst)

def b4(): 
    btn4.config(text = 'X', state = "disabled")
    lst.remove(4)
    r = []
    r = random.choices(lst)
    if r == [2]:
        btn2.config(text = "O", state = "disabled")
        lst.remove(2)
    elif r == [3]:
        btn3.config(text = "O", state = "disabled")
        lst.remove(3)
    elif r == [1]:
        btn1.config(text = "O", state = "disabled")
        lst.remove(1)
    elif r == [5]:
        btn5.config(text = "O", state = "disabled")
        lst.remove(5)
    elif r == [6]:
        btn6.config(text = "O", state = "disabled")
        lst.remove(6)
    elif r == [7]:
        btn7.config(text = "O", state = "disabled")
        lst.remove(7)
    elif r == [8]:
        btn8.config(text = "O", state = "disabled")
        lst.remove(8)
    elif r == [9]:
        btn9.config(text = "O", state = "disabled")
        lst.remove(9)
    print(lst)

def b5():
    btn5.config(text = 'X', state = "disabled")
    lst.remove(5)
    r = []
    r = random.choices(lst)
    if r == [2]:
        btn2.config(text = "O", state = "disabled")
        lst.remove(2)
    elif r == [3]:
        btn3.config(text = "O", state = "disabled")
        lst.remove(3)
    elif r == [4]:
        btn4.config(text = "O", state = "disabled")
        lst.remove(4)
    elif r == [1]:
        btn1.config(text = "O", state = "disabled")
        lst.remove(1)
    elif r == [6]:
        btn6.config(text = "O", state = "disabled")
        lst.remove(6)
    elif r == [7]:
        btn7.config(text = "O", state = "disabled")
        lst.remove(7)
    elif r == [8]:
        btn8.config(text = "O", state = "disabled")
        lst.remove(8)
    elif r == [9]:
        btn9.config(text = "O", state = "disabled")
        lst.remove(9)
    print(lst)

def b6():
    btn6.config(text = 'X', state = "disabled")
    lst.remove(6)
    r = []
    r = random.choices(lst)
    if r == [2]:
        btn2.config(text = "O", state = "disabled")
        lst.remove(2)
    elif r == [3]:
        btn3.config(text = "O", state = "disabled")
        lst.remove(3)
    elif r == [4]:
        btn4.config(text = "O", state = "disabled")
        lst.remove(4)
    elif r == [5]:
        btn5.config(text = "O", state = "disabled")
        lst.remove(5)
    elif r == [1]:
        btn1.config(text = "O", state = "disabled")
        lst.remove(1)
    elif r == [7]:
        btn7.config(text = "O", state = "disabled")
        lst.remove(7)
    elif r == [8]:
        btn8.config(text = "O", state = "disabled")
        lst.remove(8)
    elif r == [9]:
        btn9.config(text = "O", state = "disabled")
        lst.remove(9)
    print(lst)

def b7():
    btn7.config(text = 'X', state = "disabled")
    lst.remove(7)
    r = []
    r = random.choices(lst)
    print(lst)
    if r == [2]:
        btn2.config(text = "O", state = "disabled")
        lst.remove(2)
    elif r == [3]:
        btn3.config(text = "O", state = "disabled")
        lst.remove(3)
    elif r == [4]:
        btn4.config(text = "O", state = "disabled")
        lst.remove(4)
    elif r == [5]:
        btn5.config(text = "O", state = "disabled")
        lst.remove(5)
    elif r == [6]:
        btn6.config(text = "O", state = "disabled")
        lst.remove(6)
    elif r == [1]:
        btn1.config(text = "O", state = "disabled")
        lst.remove(1)
    elif r == [8]:
        btn8.config(text = "O", state = "disabled")
        lst.remove(8)
    elif r == [9]:
        btn9.config(text = "O", state = "disabled")
        lst.remove(9)

def b8():
    print(lst)
    btn8.config(text = 'X', state = "disabled")
    lst.remove(8)
    r = []
    r = random.choices(lst)
    if r == [2]:
        btn2.config(text = "O", state = "disabled")
        lst.remove(2)
    elif r == [3]:
        btn3.config(text = "O", state = "disabled")
        lst.remove(3)
    elif r == [4]:
        btn4.config(text = "O", state = "disabled")
        lst.remove(4)
    elif r == [5]:
        btn5.config(text = "O", state = "disabled")
        lst.remove(5)
    elif r == [6]:
        btn6.config(text = "O", state = "disabled")
        lst.remove(6)
    elif r == [7]:
        btn7.config(text = "O", state = "disabled")
        lst.remove(7)
    elif r == [1]:
        btn1.config(text = "O", state = "disabled")
        lst.remove(1)
    elif r == [9]:
        btn9.config(text = "O", state = "disabled")
        lst.remove(9)

def b9(): 
    btn9.config(text = 'X', state = "disabled")
    lst.remove(9)
    print(lst)
    r = []
    r = random.choices(lst)
    if r == [2]:
        btn2.config(text = "O", state = "disabled")
        lst.remove(2)
    elif r == [3]:
        btn3.config(text = "O", state = "disabled")
        lst.remove(3)
    elif r == [4]:
        btn4.config(text = "O", state = "disabled")
        lst.remove(4)
    elif r == [5]:
        btn5.config(text = "O", state = "disabled")
        lst.remove(5)
    elif r == [6]:
        btn6.config(text = "O", state = "disabled")
        lst.remove(6)
    elif r == [7]:
        btn7.config(text = "O", state = "disabled")
        lst.remove(7)
    elif r == [8]:
        btn8.config(text = "O", state = "disabled")
        lst.remove(8)
    elif r == [1]:
        btn1.config(text = "O", state = "disabled")
        lst.remove(1)

# def B1(): 
#     btn1.config(text = 'O', state = "disabled")
#     return 1
# def B2(): 
#     btn2.config(text = 'O', state = "disabled")
#     return 2
# def B3(): 
#     btn3.config(text = 'O', state = "disabled")
#     return 3
# def B4(): 
#     btn4.config(text = 'O', state = "disabled")
#     return 4

# def B5():
#     btn5.config(text = 'O', state = "disabled")
#     return 5

# def B6():
#     btn6.config(text = 'O', state = "disabled")
#     return 6

# def B7():
#     btn7.config(text = 'O', state = "disabled")
#     return 7

# def B8():
#     btn8.config(text = 'O', state = "disabled")
#     return 8

# def B9(): 
#     btn9.config(text = 'O', state = "disabled")
#     return 9

btn1 = Button(root, command = lambda : [b1(), win()], height = 1, width = 3, font = ("bold", 50), relief = "groove", cursor = "tcross")
btn1.grid(row = 0, column = 0)

btn2 = Button(root, command = lambda : [b2(), win()], height = 1, width = 3, font = ("bold", 50), relief = "groove", cursor = "tcross")
btn2.grid(row = 0, column = 1)

btn3 = Button(root, command = lambda : [b3(), win()], height = 1, width = 3, font = ("bold", 50), relief = "groove", cursor = "tcross")
btn3.grid(row = 0, column = 2)

btn4 = Button(root, command = lambda : [b4(), win()], height = 1, width = 3, font = ("bold", 50), relief = "groove", cursor = "tcross")
btn4.grid(row = 1, column = 0)

btn5 = Button(root, command = lambda : [b5(), win()], height = 1, width = 3, font = ("bold", 50), relief = "groove", cursor = "tcross")
btn5.grid(row = 1, column = 1)

btn6 = Button(root, command = lambda : [b6(), win()], height = 1, width = 3, font = ("bold", 50), relief = "groove", cursor = "tcross")
btn6.grid(row = 1, column = 2)

btn7 = Button(root, command = lambda : [b7(), win()], height = 1, width = 3, font = ("bold", 50), relief = "groove", cursor = "tcross") 
btn7.grid(row = 2, column = 0)

btn8 = Button(root, command = lambda : [b8(), win()], height = 1, width = 3, font = ("bold", 50), relief = "groove", cursor = "tcross")
btn8.grid(row = 2, column = 1)

btn9 = Button(root, command = lambda : [b9(), win()], height = 1, width = 3, font = ("bold", 50), relief = "groove", cursor = "tcross")
btn9.grid(row = 2, column = 2)

reset = Button(root, text = "Start Again", font = ("bold", 16), relief = "solid", command = reset_, cursor = "circle")
reset.grid(row = 4, column = 1)

show = Label(root, font = ("consolas",  18))
show.grid(row = 6)

root.mainloop()
