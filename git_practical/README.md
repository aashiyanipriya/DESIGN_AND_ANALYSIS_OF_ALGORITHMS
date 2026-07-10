def greet(name, greeting="Hello"):
    """Returns a greeting message for the given name."""
    return f"{greeting}, {name}!"

# Example usage
message = greet("Alex")
print(message)  # Hello, Alex!

message2 = greet("Priya", greeting="Welcome")
print(message2)  # Welcome, Priya!