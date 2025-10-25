Midterm Lab Task 1


Problem 1. Use Appropriate Escape Sequence( \n, \t \b \ ..etc) for the problem below


<img width="1076" height="616" alt="image" src="https://github.com/user-attachments/assets/7360df91-856d-4b07-a654-e5acd5ce445d" />


Source Code:


    print("Database Record\n")
    print("\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\")
    print("Name:\t\tJohn Doe")
    print("Email:\t\tjohn.doe@example.com")
    print("University:\tABC University")


Output:


<img width="598" height="222" alt="image" src="https://github.com/user-attachments/assets/6269c319-b715-4800-82c4-2083b35422b0" />


Problem 2. Using Placeholders for Email Details: Use appropriate type specifiers %s, %d, %f etc… for this task


<img width="833" height="568" alt="image" src="https://github.com/user-attachments/assets/2caa5375-4294-470c-86a6-bdf25c258bdf" />


Source Code:


    sender = "Jane"
    subject = "Greetings"
    version = 1.2
    discount = 10.50
    status = "A"
    code = "ABCD123"
    location = "City XYZ"
    age = 30
    company = "ABC Corporation"
    website = "www.example.com"
    phone = "+1 123-456-7890"
    job_title = "Software Engineer"
    department = "Engineering"
    
    print("Dear John, I hope this email finds you well.")
    print("I wanted to reach out and say hello.")
    print("I hope you are doing well and enjoying your day.")
    print("It's been a while since we last spoke, and I wanted to catch up with you.")
    print("Let's plan to meet up soon and have a great time together!")
    print(f"Subject: {subject}")
    print(f"Sender: {sender}")
    print(f"Version: {version}")
    print(f"Discount: {discount:.2f}%")
    print(f"Status: {status}")
    print(f"Code: {code}")
    print(f"Location: {location}")
    print(f"Age: {age}")
    print(f"Company: {company}")
    print(f"Website: {website}")
    print(f"Phone: {phone}")
    print(f"Job Title: {job_title}")
    print(f"Department: {department}")


Output:


<img width="609" height="487" alt="image" src="https://github.com/user-attachments/assets/ce5b01ad-1864-4d3f-90f0-b549ba6d8548" />


Problem 3. Book Reservation; Accept User Input


<img width="770" height="278" alt="image" src="https://github.com/user-attachments/assets/7452f065-e417-4753-975b-b2378c4e326e" />


Source Code:


    title = input("Enter the book title: ")
    author = input("Enter the author: ")
    year = int(input("Enter the year of publication: "))
    genre = input("Enter the genre: ")
    library = input("Enter the library: ")
    member_id = input("Enter your member ID: ")
    return_date = input("Enter the return date: ")
    
    print(f"\nYou have successfully reserved the book '{title}' by {author}.")
    print(f"Year of Publication: {year}")
    print(f"Genre: {genre}")
    print(f"Library: {library}")
    print(f"Member ID: {member_id}")
    print(f"Return Date: {return_date}")


Output:


<img width="610" height="392" alt="image" src="https://github.com/user-attachments/assets/9dd799d1-a7a9-419a-be95-11ebd7017bfc" />


Problem 4. Day Identifier


<img width="714" height="603" alt="image" src="https://github.com/user-attachments/assets/3aae1e23-c281-41d7-8267-718d50e08eeb" />


Source Code:


day = int(input("Enter day: "))

    if day == 1:
        print("Monday")
    elif day == 2:
        print("Tuesday")
    elif day == 3:
        print("Wednesday")
    elif day == 4:
        print("Thursday")
    elif day == 5:
        print("Friday")
    elif day == 6:
        print("Saturday")
    elif day == 7:
        print("Sunday")
    else:
        print("Invalid input")


        Output:


<img width="615" height="621" alt="image" src="https://github.com/user-attachments/assets/cf8002ee-3905-4fc8-ba1d-4bd22646e68a" />



