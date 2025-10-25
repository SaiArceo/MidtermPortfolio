<h1>Shopping Cart Program</h1>


Source Code:


    menu = {
        "Burger": 35.00,
        "Tacos": 50.00,
        "Fries": 20.00,
        "Ice Coffee": 25.00
    }
    
    cart = []
    
    print("---------- M E N U ----------")
    for key, value in menu.items():
        print(f"{key:15}: ₱{value:0.2f}")
    print("------------------------------")
    
    while True:
        food = input("Select an item from the menu (q to quit): ")
        if food.lower() == 'q':
            break
        elif food not in menu:
            print("Item is not in the menu. Please choose from the menu.")
        else:
            cart.append(food)
    
    name = input("\nEnter Customer Name: ")
    age = int(input("Enter Customer Age: "))
    
    print("\nYour Orders are:")
    total = 0
    for food in cart:
        total += menu.get(food)
        print(food, end=', ')
    
    if age >= 60:
        discount = total * 0.20
        total -= discount
        print(f"\n20% Senior Discount Applied: -₱{discount:.2f}")
    
    print(f"\nTotal Purchased: ₱{total:.2f}")
    print(f"Thank you, {name}!")



Output:


<img width="442" height="725" alt="image" src="https://github.com/user-attachments/assets/c972082e-11e3-4cd3-8507-38cd1211f922" />
