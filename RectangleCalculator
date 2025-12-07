# Samantha Cameron
# CIS261
# Lab: Rectangle Calculator

print("----------Rectangle Calculator----------")

class Rectangle:
    def __init__(self, height, width):
        self.height = height
        self.width = width

    def area(self):
        return self.height * self.width

    def perimeter(self):
        return 2 * (self.height + self.width)

    def print_rectangle(self):
        for _ in range(self.height):
            print('*' * self.width)

while True:
    try:
        height = int(input("Enter the height of the rectangle: "))
        width = int(input("Enter the width of the rectangle: "))
    except ValueError:
        print("Please enter valid integers for height and width.")
        continue
    rect = Rectangle(height, width)
    print(f"Area: {rect.area()}")
    print(f"Perimeter: {rect.perimeter()}")
    print("Rectangle:")
    rect.print_rectangle()

    cont = input("Do you want to continue? (y/n): ").strip().lower()
    if cont != 'y':
        print("Goodbye!")
        break
def print_rectangle(self):
    for row in range(self.height):
        if row == 0 or row == self.height - 1:
            print('*' * self.width)
        else:
            if self.width > 1:
                print('*' + ' ' * (self.width - 2) + '*')
            else:
                print('*')
