on = True

print("""
   +---------------------------------+
   | create by MD.IIMTIAZ KHAN SHAFE |
   | DATE : 15-05-2017               |
   +---------------------------------+
   | BY THIS PROGRAM YOU CAN check   |
   | WHAT IS PRESENT OR NOT PRESENT  |
   | IN LIST                         |
   +---------------------------------+
""")

platform = str(input("Where are you using this (school, business) : "))
platform = platform.upper()

if platform == "SCHOOL":
    student_list = input("Enter student's name : ")
    while on:    
        press = input("""
        Enter 1 to check value is precent in list     : 
        Enter 2 to check value is not precent in list : """)
        if press == '1':
            precent = input("Enter student name : ")
            if (precent in student_list) == True:
                print("Yes " + precent + " is in list\n")
            else:
                print("Sorry " + precent + " is not in list\n")
        elif press == '2':
            not_precent = input("Enter student name : ")
            
            if (not_precent not in student_list) == True:
                print("Yes " + not_precent + " is not in list\n")
            else:
                print("Sorry " + not_precent + " is in list\n")
            
        on = input("Want to check again?(y): ")
        if on == 'y':
            on = True
        else:
            on = False
            # input("Press Enter to end program")
            # break
            
elif platform == "BUSINESS":
    item_list = input("Enter item's name : ")
    while on:    
        press = input("""
        Enter 1 to check value is present in list     : 
        Enter 2 to check value is not present in list : """)
        if press == '1':
            precent = input("Enter item name : ")
            if (precent in item_list) == True:
                print("Yes " + precent + " is in list\n")
            else:
                print("Sorry " + precent + " is not in list\n")
        elif press == '2':
            not_precent = input("Enter item name : ")
            
            if (not_precent not in item_list) == True:
                print("Yes " + not_precent + " is not in list\n")
            else:
                print("Sorry " + not_precent + " is in list\n")
            
        on = input("Want to check again?(y) : ")
        if on == 'y':
            on = True
        else:
            on = False
            # input("Press Enter to end program")
            # break
else:
    input("\nSorry! This platform is not available right now ") 
