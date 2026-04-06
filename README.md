# this-is-luke-repository
My first repository
and i am leraning linux and i will show some codes
and this a code that says what your take to school fo r lunch

#!/usr/bin/env bash

for snackdraw in lays talkies doriatos cheesto "grilled chesse" "fried chicken"
do
    if [[ $snackdraw == "lays" ]]
    then
        echo "Today is Monday and I take $snackdraw to school"

    elif [[ $snackdraw == "talkies" ]]
    then 
        echo "Today is Tuesday and I take $snackdraw to school"
    
    elif [[ $snackdraw == "doriatos" ]]
    then 
        echo "Today is Wednesday and I take $snackdraw to school"
    
    elif [[ $snackdraw == "cheesto" ]]
    then 
        echo "Today is Thursday and I take $snackdraw to school"
    
    elif [[ $snackdraw == "grilled chesse" ]]
    then 
        echo "Today is Friday and I take $snackdraw to school"

    elif [[ $snackdraw == "fried chicken" ]]  
    then
        echo "Today is Saturday and i am going to eat $snackdraw"
    fi
done

and this for lunch app on python and if you tap the students name it saws there grade and what there having for lunch and this is the code you can Modify any way you want and this is the code



import tkinter as tk

# Student database
students = {
    "Luke": {"first": "Luke", "last": "Ntanda", "grade": "6", "lunch": "Pizza"},
    "John": {"first": "John", "last": "Smith", "grade": "7", "lunch": "Burger"},
    "Sarah": {"first": "Sarah", "last": "Brown", "grade": "5", "lunch": "Rice"},
    "Mike": {"first": "Mike", "last": "Johnson", "grade": "8", "lunch": "Chicken"},
}

# Window
window = tk.Tk()
window.title("School Lunch App")
window.geometry("400x300")

# Function
def show_student():
    name = entry.get()
    
    if name in students:
        student = students[name]
        result_label.config(
            text="First Name: " + student["first"] +
                 "\nLast Name: " + student["last"] +
                 "\nGrade: " + student["grade"] +
                 "\nLunch: " + student["lunch"]
        )
    else:
        result_label.config(text="Student not found")

# UI
title = tk.Label(window, text="School Lunch App", font=("Arial", 16))
title.pack(pady=10)

entry = tk.Entry(window)
entry.pack()

button = tk.Button(window, text="Search Student", command=show_student)
button.pack(pady=10)

result_label = tk.Label(window, text="")
result_label.pack()

window.mainloop()
