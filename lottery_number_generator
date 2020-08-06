from future.moves.tkinter import *
import random


root = Tk()
root.geometry("487x155+400+200")
root.resizable(0, 0)
root.title("KEVIN's GAMBLING OFFICE")

# ================== All Variables ================== #
num1 = StringVar()
num2 = StringVar()
num3 = StringVar()
num4 = StringVar()
num5 = StringVar()
num6 = StringVar()


def lottery_no():
    num1.set(random.randint(0, 9))
    num2.set(random.randint(0, 9))
    num3.set(random.randint(0, 9))
    num4.set(random.randint(0, 9))
    num5.set(random.randint(0, 9))
    num6.set(random.randint(0, 9))


Label = Label(root, text="Lottery Number Generator", font=("impact 24 bold")).grid(row=0, column=0, columnspan=6,
                                                                                   padx=50, pady=5)
box1 = Entry(root, textvariable=num1, bd=10, width=5, relief=GROOVE, font=("arial 15 bold"), fg="#c41212",
             justify=CENTER).grid(row=1, column=0, padx=2)
box2 = Entry(root, textvariable=num2, bd=10, width=5, relief=GROOVE, font=("arial 15 bold"), fg="#c41212",
             justify=CENTER).grid(row=1, column=1, padx=2)
box3 = Entry(root, textvariable=num3, bd=10, width=5, relief=GROOVE, font=("arial 15 bold"), fg="#c41212",
             justify=CENTER).grid(row=1, column=2, padx=2)
box4 = Entry(root, textvariable=num4, bd=10, width=5, relief=GROOVE, font=("arial 15 bold"), fg="#c41212",
             justify=CENTER).grid(row=1, column=3, padx=2)
box5 = Entry(root, textvariable=num5, bd=10, width=5, relief=GROOVE, font=("arial 15 bold"), fg="#c41212",
             justify=CENTER).grid(row=1, column=4, padx=2)
box6 = Entry(root, textvariable=num6, bd=10, width=5, relief=GROOVE, font=("arial 15 bold"), fg="#c41212",
             justify=CENTER).grid(row=1, column=5, padx=2)
button = Button(root, width=10, bd=8, command=lottery_no, font=("times new roman", 13, "bold"), text="TRY", fg="white",
                bg='#273746').grid(row=2, column=0, columnspan=6, padx=10, pady=5)

root.mainloop()
