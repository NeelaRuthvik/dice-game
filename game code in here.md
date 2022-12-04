# dice-game

import random
i=0
playerchoice='y'
while playerchoice=="y":
    a=int(input('Enter a number from 1 to 6:'))
    b=random.randint(1,6)
    if a==b:
        i+=100
        print('you win')
        print('your score is',i)
    else:
        i-=50
        print('you lost')
        print('your score is',i)
    print("do you want to continue? Type 'y' for yes and 'n' for no")
    playerchoice=input()  

