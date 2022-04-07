# G103
Room for students
def print_n(s,n):

    if n <= 0:

        return

    print(s)
    print_n(s,n-1)

print(print_n("Hi",5))
