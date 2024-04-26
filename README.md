# friendly-lamp
def greet(name):
    """
    This function greets the user with a friendly message.
    
    Args:
        name (str): The name of the user.
        
    Returns:
        str: A friendly greeting message.
    """
    return f"Hello, {name}! Welcome to our friendly community."

# Example usage
user_name = input("What's your name? ")
print(greet(user_name))

