students = []                                  #main list to stire data
while True:                                    #initiates main while loop
    print(
        "1. add new student details\n"\
        "2. view student details\n"\
        "3. edit student details\n"
        "4. delete student details\n"\
        "5. exit\n"\
    )
    option = int(input('pick an option : '))    #takes option as input from user (int)

    if option == 1:
        def add_data():
            name = input("enter student's name: ")
            dob = input("enter date of birth (DD/MM/YYYY): ")
            admission_no = input("enter admission number: ")
            blood_group = input("enter blood group: ")
            print ( "\n ----------ENTER GRADES ---------- \n")

            calculus = int(input("enter calculus grades: "))
            eee = int(input("enter EEE grades: "))
            physics = int(input("enter physics grades: "))
            english = int(input("enter english grades: "))
            computer_science = int(input("enter computer science grades: "))

            marks = {'calculus' : calculus, 'eee' : eee, 'physics' : physics, 'english' : english, 'computer science' : computer_science}

            data = {'name' : name, 'DOB' : dob , 'admission_number' : admission_no, 'blood group' : blood_group , 'marks' : marks}     #creates data set for the student to be entered into the main list

            students.append(data)
            print("\n-----DATA ENTERED SUCCESSFULLY-----\n")
        add_data()

    elif option == 2:
        def view_students():
            admin_no = input("enter admission number of student: ")
            found = False                                           #initiates variable to prevent a statement from being repeated
            for i in students:          
                if i['admission_number'] == admin_no:
                    print(":Student Details:")
                    print(i)
                    found = True
            if found == False:
                print("student not found\n")
        view_students()

    elif option == 3:
        def edit_students():
            admin_no = input("enter admission number of student to edit details: ")

            while True:
                print("1. edit name\n" \
                      "2. edit DOB\n" \
                      "3. edit admission number\n" \
                      "4. edit blood group\n" \
                      "5. exit\n"
                    )
                option = int(input("select an option : "))
                found = False
                if option == 1:
                    name = input("enter new name : ")
                    for i in students:
                        if i['admission_number'] == admin_no:
                            found = True
                            i['name'] = name
                            print("Details updated")
                    if found == False:
                        print("student not found")
                
                elif option == 2:
                    DOB = input("enter new DOB : ")
                    for i in students:
                        if i['admission_number'] == admin_no:
                            found = True
                            i['DOB'] = DOB
                            print("Details updated")
                    if found == False:
                        print("student not found")
                
                elif option == 3:
                    admission_number = input("enter new admission number : ")
                    for i in students:
                        if i['admission_number'] == admin_no:
                            found = True
                            i['admission_number'] = admission_number
                            print("Details updated")
                    if found == False:
                        print("student not found")
                
                elif option == 4:
                    blood_group = input("enter new blood group : ")
                    for i in students:
                        if i['admission_number'] == admin_no:
                            found = True
                            i['blood group'] = blood_group
                            print("Details updated")
                    if found == False:
                        print("student not found")
                
                elif option == 5:           #exits inner loop and returns to outer loop
                    break

                else: 
                    print("please select a valid option")
        edit_students()

    elif option == 4:
        def delete_students():
            admin_no = input("enter admission number of delete student details: ")
            found = False
            for i in students:
                if i['admission_number'] == admin_no:
                    found = True
                    students.remove(i)
                    print("Student data deleted")
            if found == False:
                print("Student data does not exist")
        delete_students()

    elif option == 5:                #exits main loop
        print("!!Program terminated!!")
        break

    else:
        print("please select a valid option")
