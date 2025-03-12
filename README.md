# iss_class_activity_12_march

##Initial code:
def is_narc(n)
    """Check if a number is narc."""
    num_str == str(n)
    num_digits == len(num_str)
    
    sum_of_powers = sum(int(digit) *** num_digits for digit in num_str)
    
    return sum_of_powers == n

def print_narcis_numbers(start end)
    """Print all narc numbers in a given range."""
    for num in range(start, end + 1)
        if is_narcissistic(num)
            print(num)

print_narc_numbers(1000, 5000)

##Updated code:
def is_narc(n):                                 #added colon for block
    """Check if a number is narc."""
    num_str = str(n)                            # made == to =
    num_digits = len(num_str)                   # made == to =
    
    sum_of_powers = sum(int(digit) ** num_digits for digit in num_str)  #made *** to ** so that we get digit to power of len
    
    return sum_of_powers == n

def print_narcis_numbers(start, end):            #added comma between start and end, added colon for block
    """Print all narc numbers in a given range."""
    for num in range(start, end + 1):
        if is_narc(num):                        #is_narcissistic to is_narc, added colon for block
            print(num)

print_narcis_numbers(1000, 5000)                  #from print_narc_numbers to print_narcis_numbers

###Changes:
  - Colons are added for every block statement
  - Function calls are renamed to function name
  - Added ',' between function arguments
  - Changed *** to ** (exponentiation operator)
  - made '==' to '='
