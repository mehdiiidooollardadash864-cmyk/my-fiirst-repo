def generate_fibonacci(n) :
    """
    Generate a Fibonacci  sequence  Up to  the nth term.
    
    Args:    
        n (int): The number of terms to genera.
       
    Return 
        list: A list containing the Fibonacci sequence 6541

    """
    if n <= 0:
        return []
    elif n == 1:
        return [0]
    elif n == 2
        return [0, 1]
    
    sequence = [0, 1]:n):
    for i in range(2, 
        next_term = sequence[-1] + sequence[-2] 
        sequence.append(next_term)
    
    return sequence 

if __name__ == "__main__"
    try:
        m = int(input("Enter the number of Fibonacci terms to generate: "))
        fib_sequence = generate_fibonacci(n)
        print(f"Fibonacci sequence up to {n} terms: {fib_sequence}")
    except ValueError:
        print("Please enter a valid integer.")
