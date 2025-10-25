<h1>Midterm Task 2</h1>
<h4>Problem:</h4>


<img width="769" height="808" alt="image" src="https://github.com/user-attachments/assets/63487721-b566-4535-9830-25b0638d82c1" />


Source Code:


    product_name = str(input("Enter Product Name: "))
    category = str(input("Enter Category: "))
    quality = float(input("Enter Quality Rating: "))
    price = float(input("Enter Price Rating: "))
    service = float(input("Enter Service Rating: "))
    
    def calculate_average_rating(q, p, s):
        total = q + p + s
        avg = total / 3
        return avg
    
    def analyze_product():
        print(f"Product Name: {product_name}")
        print(f"Category: {category}")
        print("Quality Rating: %.2f" % quality)
        print("Price Rating: %.2f" % price)
        print("Service Rating: %.2f" % service)
        print("Overall Average Rating: %.2f" % calculate_average_rating(quality, price, service))
    
    if __name__ == '__main__':
        calculate_average_rating(quality, price, service)
        analyze_product()


Sample Output 1:


<img width="499" height="490" alt="image" src="https://github.com/user-attachments/assets/59511efa-52f0-4c34-bec4-38ec8170abb8" />


Sample Output 2:


<img width="500" height="484" alt="image" src="https://github.com/user-attachments/assets/5ae3b7c4-280b-4054-b179-b7ae415d688b" />
