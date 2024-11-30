import random

def random_number_generator(min_value, max_value):
  """ Generates a random integer between min_value and max_value (inclusive)."""
  return random.randint(min_value, max_value) 

# Example usage:
min_num = 1
max_num = 10
random_number = random_number_generator(min_num, max_num)
print(f"Random number between {min_num} and {max_num}: {random_number}")
