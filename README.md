# GreekApI
import tkinter as tk
from tkinter import ttk
 
app = tk.Tk() 
app.geometry('200x100')

labelTop = tk.Label(app,
                    text = "Distance1")
labelTop.grid(column=0, row=0)

comboExample = ttk.Combobox(app, 
                            values=[
                                    {
                                      "name":"Donlon",
                                      "distance1":100
                                    },
                                    {
                                      "name":"Enchi",
                                      "distance1":200
                                    },
                                    
                                   {
                                      "name":"jabing",
                                      "distance1":300
                                    },
                                    
                                    {
                                      "name":"Sapir",
                                      "distance1":400
                                    },
                                    {
                                      "name":"lerbin",
                                      "distance1":500
                                    },
                                    {
                                      "name":"pingnoor",
                                      "distance1":600
                                    },
                                 ])
pprint(dict(comboExample)) 
comboExample.grid(column=0, row=1)
comboExample.current(1)

print(comboExample.current(), comboExample.get())

app.mainloop()

import tkinter as tk
from tkinter import ttk
 
app = tk.Tk() 
app.geometry('200x100')

labelTop = tk.Label(app,
                    text = "distance 2")
labelTop.grid(column=0, row=0)

comboExample = ttk.Combobox(app, 
                            values=[
                                      {
                                      "name":"Donlon",
                                      "total_no":2,
                                       "max_distance":200,
                                       "speed":2
                                    },
                                     
                                    {
                                      "name":"Donlon",
                                      "total_no":2,
                                       "max_distance":300,
                                       "speed":2
                                    },
                                     
                                     {
                                      "name":"Donlon",
                                      "total_no":2,
                                       "max_distance":400,
                                       "speed":2
                                    },
                                     
                                     {
                                      "name":"Donlon",
                                      "total_no":2,
                                       "max_distance":600,
                                       "speed":2
                                    },
                            
                                     
                                    ],
                            state="readonly"
                                        )

comboExample.grid(column=0, row=1)
comboExample.current(0)

print(comboExample.current(), comboExample.get())

app.mainloop()
    import tkinter as tk
from tkinter import ttk
 
app = tk.Tk() 
app.geometry('200x100')

labelTop = tk.Label(app,
                    text = "Distance1")
labelTop.grid(column=0, row=0)

comboExample = ttk.Combobox(app, 
                            values=[
                                    {
                                      "name":"Donlon",
                                      "distance1":100
                                    },
                                    {
                                      "name":"Enchi",
                                      "distance1":200
                                    },
                                    
                                   {
                                      "name":"jabing",
                                      "distance1":300
                                    },
                                    
                                    {
                                      "name":"Sapir",
                                      "distance1":400
                                    },
                                    {
                                      "name":"lerbin",
                                      "distance1":500
                                    },
                                    {
                                      "name":"pingnoor",
                                      "distance1":600
                                    },
                                 ])
pprint(dict(comboExample)) 
comboExample.grid(column=0, row=1)
comboExample.current(1)

print(comboExample.current(), comboExample.get())

app.mainloop()

import tkinter as tk
from tkinter import ttk
 
app = tk.Tk() 
app.geometry('200x100')

labelTop = tk.Label(app,
                    text = "distance 2")
labelTop.grid(column=0, row=0)

comboExample = ttk.Combobox(app, 
                            values=[
                                      {
                                      "name":"Donlon",
                                      "total_no":2,
                                       "max_distance":200,
                                       "speed":2
                                    },
                                     
                                    {
                                      "name":"Donlon",
                                      "total_no":2,
                                       "max_distance":300,
                                       "speed":2
                                    },
                                     
                                     {
                                      "name":"Donlon",
                                      "total_no":2,
                                       "max_distance":400,
                                       "speed":2
                                    },
                                     
                                     {
                                      "name":"Donlon",
                                      "total_no":2,
                                       "max_distance":600,
                                       "speed":2
                                    },
                            
                                     
                                    ],
                            state="readonly"
                                        )

comboExample.grid(column=0, row=1)
comboExample.current(0)

print(comboExample.current(), comboExample.get())

app.mainloop()
    
    
    
    python
