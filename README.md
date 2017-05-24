# BOTON2017A
Integrantes: Liz, Byron, Luis, Paul, David


def nombre():
    print("Luis Falconí")
def nombre5():
    print("DAVID REVELO")
    
from tkinter import *
tk = Tk()
btn = Button(tk, text = "Click me", command = nombre)
btn.pack()

def nombre2():
    print ("Byron Paredes")

btn2 = Button(tk, text = "Click me", command = nombre2)
btn2.pack()

def nombre3():
    print("Paul Valle")

btn = Button(tk, text = "Click me", command = nombre3)
btn.pack() 

def nombre4():
    print("Lizbeth Borja")

btn = Button(tk, text = "Click me", command = nombre4)
btn.pack()     



btn5 = Button(tk, text = "Click Aqui", command = nombre5)
btn5.pack() 


# hay que agregarle al ing tambien para que vea como estamos trabajando.
#Si esta agregado tranquilos
