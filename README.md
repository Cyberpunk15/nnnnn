def multiplication(num1, num2):
    product = num1 * num2
    if product <= 1000:
        return product
    else:
        return num1 + num2

number1 = 20
number2 = 30

print("\n")
result = multiplication(number1, number2)
print("The result is", result)

    
