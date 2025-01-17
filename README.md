# Returning-a-function-from-a-function-Python
def outer_function():
    def inner_function():
        return "Hello from the inner function!"
    return inner_function

func = outer_function()  # This gets the inner_function
print(func())  # Calls inner_function and prints its return value
