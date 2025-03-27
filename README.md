# rockpaperscissor

import random
your_choice=int(input("enter any your choice: Type 0 for rock,1 for paper,2 for scissor"))
if your_choice >=3 or your_choice < 0:
    print("you entered invalid number and computer wins")
computer_choice = random.randint(0,2)
print("computer choice is")
print(computer_choice)
    
if computer_choice == your_choice:
    print("its a tie")
elif computer_choice > your_choice:
    print("user loose")
elif computer_choice < your_choice:
    print("user wins")
elif computer_choice == 0 and your_choice == 2:
    print("computer wins")
elif computer_choice == 1 and your_choice == 0:
    print("user wins")              
