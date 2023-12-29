import pyautogui
from tkinter import *
def ssp():
    while True:
        pyautogui.write("write")
        pyautogui.press("enter")
def ocsp():
    blade.destroy()
blade = Tk()

blade.geometry('500x500')
blade.title('keyspam')
blade["bg"] = "lightblue"

button = Button(text = 'начать спам', bg='blue', command=ssp)
button.pack()
button = Button(text = 'остановить спам', bg='blue', command=ocsp)
button.pack()

blade.mainloop()
