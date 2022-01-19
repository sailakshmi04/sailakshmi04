class cal():
    def __init__(self,a,b):
        self.a = a
        self.b = b
    def add(self):
        return self.a + self.b
    def sub(self):
        return self.a - self.b
    def multiply(self):
        return self.a * self.b
    def divide(self):
        return self.a / self.b
    def square(self):
        return self.a ** self.b
    def squareroot(self):
        return self.a **0.5
    def graph(self):
        return 1/self.a 
    

a = int(input('Enter First number : '))
b = int(input('Enter Second number : '))        
obj=cal(a,b)
while True:
    def menu():
        x = ('1. Add \n2. Sub \n3. Multiply \n4. Divide \n5. Square \n6. Squareroot \n7. Graph') 
        print(x)
    menu()
    choice = int(input('Please select one of the following : ')) 
    if choice == 1:
        print("Result: ",obj.add())
    elif choice == 2:
        print("Result: ",obj.sub())
    elif choice == 3:
        print("Result: ",obj.multiply())    
    elif choice == 4:
        print("Result: ",obj.divide())
    elif choice == 5:
        print("Result: ",obj.square())
    elif choice == 6:
        print("Result: ",obj.squareroot())
    elif choice == 7:
        print("Result: ",obj.graph())
    elif choice == 0:
        print('Again try one of the following')
        break
    else:
        print('Invalid option') 
        break       
print()
