
#program name: MathQuiz
#date: 2021-01-24
#purpose: to output a quiz for the user to solve with loops.

import random

#initialise and declare variables
numOne = ''
numTwo=''
numThree= ''
ansOne=''
ansTwo=''
ansThree=''
userAnsOne=''
userAnsTwo=''
userAnsThree=''
userChoice=''
ansWrong=''
start=''

#randomising numbers
numOne =random.randint(1,12)
numTwo=random.randint(1,12)
numThree= random.randint(1,12)
#intro to program
print('Welcome to the Math Quiz program!')
userName= input('what is your name?: ')
print('Here are your options below:')
print('1 = Addition Quiz')
print('2 = Subtraction Quiz')
print('3 = multiplication Quiz')
#asking for user input
print(''.center(90,'-'))
userChoice = input('please enter your choice:')
print(''.center(90,'-'))
#is user enters a non-number it asks them to reenter
while userChoice.isnumeric() == False:
    print(' I think you made a typo... please enter a number next time')
    print('')
    userChoice= input('please enter your choice again:')
 
#------------------------------------Addition----------------------------------------------
#asks user a seiries of questions(same for all of them so I will only write it once)
if int(userChoice) == 1 :
    print('You chose the addition quiz!'.center(90,'+'))
#asks user to begin and capitalises it incase user inputs a lowercase
    start=input('Type Y to begin :').capitalize()
#makes sure the user enters a letter that is Y and not a number. if not done correctly then asked to do it again
    while start.isnumeric() == True or start != 'Y' :
        print(' I think you made a typo... ')
        print('')
        start= input('please enter Y again: ').capitalize()
#sets a while loop for the quiz in case the user wants to re-take the quiz
    while start == 'Y':
        numOne =random.randint(1,12)
        numTwo=random.randint(1,12)
        numThree= random.randint(1,12)
        #finds adn records the answer to the question
        ansOne = numOne + numTwo
        #asks question
        userAnsOne= input('Question 1: what is ' + str(numOne) +'+'+ str(numTwo) +'?: ')
        print('')
        #makes sure the user enters a number. if not asks again
        while userAnsOne.isnumeric() == False:
            print(' I think you made a typo... please enter a number next time')
            print('')
            userAnsOne= input('Question 1: what is ' + str(numOne) +'+'+ str(numTwo) +'?: ')
            #sets up the answer wrong counter
        ansWrong=0
        #thsi shows when user gets it wrong ansd asks them to reenter. it also keeps track of the wrong answers.
        while ( ansOne != int(userAnsOne) ) :
            print('OOF looks like you got it wrong please try again:')
            print('')
            userAnsOne= input('Question 1: what is ' + str(numOne) +'+'+ str(numTwo) +'?: ')
            print(''.center(90,'_'))
            while userAnsOne.isnumeric() == False:
                print(' I think you made a typo... please enter a number next time')
            
                userAnsOne= input('Question 1: what is ' + str(numOne) +'+'+ str(numTwo) +'?: ')
        
            ansWrong= ansWrong + 1
            #this is for when the user gets it right it outputsa message and a line
        else:
            print('')
           
            print('Congrats you got it right!')
            gotRight= 1
            print(''.center(90,'_'))
#ques 2
        ansTwo = numTwo + numThree
        userAnsTwo= input('Question 2: what is ' + str(numTwo) +'+'+ str(numThree) +'?: ')
        while userAnsTwo.isnumeric() == False:
            print(' I think you made a typo... please enter a number next time')
            print('')
            userAnsTwo= input('Question 2: what is ' + str(numTwo) +'+'+ str(numThree) +'?: ')
        while ( ansTwo != int(userAnsTwo) ) :
            print('OOF looks like you got it wrong please try again:')
            print('')
            userAnsTwo= input('Question 2: what is ' + str(numTwo) +'+'+ str(numThree) +'?: ')
            while userAnsTwo.isnumeric() == False:
                print(' I think you made a typo... please enter a number next time')
                print('')
                userAnsTwo= input('Question 2: what is ' + str(numTwo) +'+'+ str(numThree) +'?: ')
        
            ansWrong= ansWrong + 1
        else:
            print('')
            print('Congrats you got it right!')
            gotRight= gotRight + 1
            print(''.center(90,'_'))
#ques 3
        ansThree = numThree + numOne
        userAnsThree= input('Question 2: what is ' + str(numThree) +'+'+ str(numOne) +'?: ')
        while userAnsThree.isnumeric() == False:
            print(' I think you made a typo... please enter a number next time')
            print('')
            userAnsThree= input('Question 2: what is ' + str(numThree) +'+'+ str(numOne) +'?: ')
        while ( ansThree != int(userAnsThree) ) :
            print('OOF looks like you got it wrong please try again:')
            print('')
            userAnsThree= input('Question 2: what is ' + str(numThree) +'+'+ str(numOne) +'?: ')
            while userAnsThree.isnumeric() == False:
                print(' I think you made a typo... please enter a number next time')
                print('')
                userAnsThree= input('Question 2: what is ' + str(numThree) +'+'+ str(numOne) +'?: ')
        
            ansWrong= ansWrong + 1
        else:
            print('')
            print('Congrats you got it right!')
            gotRight= gotRight + 1
            print(''.center(90,'_'))
            #displays number of times mistakes were made
            print('you finished with',ansWrong,' wrong attempts.')
            Attempts= ansWrong + 3
            finalScore= (gotRight/Attempts) * 100
            print( userName,', Your mark is', finalScore,'%')
            #this helps complete the loop and asks the user if they want to redo it. if yes it restarts
        start = input('play again ? (Y:yes) (N:no): ').capitalize()
    else:
        print('bye')
    #-------------------------------------subtraction----------------------------

if int(userChoice) == 2 :
        print('You chose the subtraction quiz!'.center(90,'-'))

        start=input('Type Y to begin :').capitalize()
        while start.isnumeric() == True or start != 'Y' :
            print(' I think you made a typo... ')
            print('')
            start= input('please enter Y again: ').capitalize()

        while start == 'Y':
            numOne =random.randint(1,12)
            numTwo=random.randint(1,12)
            numThree= random.randint(1,12)
            while numTwo >= numOne :
                numOne =random.randint(1,12)
                numTwo=random.randint(1,12)
            ansOne = numOne - numTwo
            userAnsOne= input('Question 1: what is ' + str(numOne) +'-'+ str(numTwo) +'?: ')


            while userAnsOne.isnumeric() == False:
                print(' I think you made a typo... please enter a number next time')
                print('')
                userAnsOne= input('Question 1: what is ' + str(numOne) +'-'+ str(numTwo) +'?: ')
                
            ansWrong=0
            while ( ansOne != int(userAnsOne) ) :
                print('OOF looks like you got it wrong please try again:')
                print('')
                userAnsOne= input('Question 1: what is ' + str(numOne) +'-'+ str(numTwo) +'?: ')
                while userAnsOne.isnumeric() == False:
                    print(' I think you made a typo... please enter a number next time')
                    print('')
                    userAnsOne= input('Question 1: what is ' + str(numOne) +'-'+ str(numTwo) +'?: ')
                    
                ansWrong= ansWrong + 1
            else:
                print('')
                print('Congrats you got it right!')
                gotRight= 1
                print(''.center(90,'_'))
        #ques 2

            while numThree >= numTwo :
                numThree =random.randint(1,12)
                numTwo=random.randint(1,12)
            ansTwo = numTwo - numThree
            userAnsTwo= input('Question 2: what is ' + str(numTwo) +'-'+ str(numThree) +'?: ')
            while userAnsTwo.isnumeric() == False:
                if int(userAnsOne) < 0 :
                        break
                print(' I think you made a typo... please enter a number next time')
                print('')
                userAnsTwo= input('Question 2: what is ' + str(numTwo) +'-'+ str(numThree) +'?: ')

            while ( ansTwo != int(userAnsTwo) ) :
                print('OOF looks like you got it wrong please try again:')
                print('')
                userAnsTwo= input('Question 2: what is ' + str(numTwo) +'-'+ str(numThree) +'?: ')
                while userAnsTwo.isnumeric() == False:
                    if int(userAnsOne) < 0 :
                        break
                    print(' I think you made a typo... please enter a number next time')
                    print('')
                    userAnsTwo= input('Question 2: what is ' + str(numTwo) +'-'+ str(numThree) +'?: ')
            
                ansWrong= ansWrong + 1
            else:
                print('')
                print('Congrats you got it right!')
                gotRight= gotRight + 1
                print(''.center(90,'_'))
        #ques 3

            while numOne >= numThree :
                    numThree =random.randint(1,12)
                    numOne=random.randint(1,12)
            ansThree = numThree - numOne
            userAnsThree= input('Question 3: what is ' + str(numThree) +'-'+ str(numOne) +'?: ')
            while userAnsThree.isnumeric() == False:
                if int(userAnsOne) < 0 :
                        break
                print(' I think you made a typo... please enter a number next time')
                print('')
                userAnsThree= input('Question 3: what is ' + str(numThree) +'-'+ str(numOne) +'?: ')
                if int(userAnsOne)<0:
                    continue
            while ( ansThree != int(userAnsThree) ) :
                print('OOF looks like you got it wrong please try again:')
                print('')
                userAnsThree= input('Question 3: what is ' + str(numThree) +'-'+ str(numOne) +'?: ')
                while userAnsThree.isnumeric() == False:
                    if int(userAnsOne) < 0 :
                        break
                    print(' I think you made a typo... please enter a number next time')
                    print('')
                    userAnsThree= input('Question 2: what is ' + str(numThree) +'-'+ str(numOne) +'?: ')
            
                ansWrong= ansWrong + 1
            else:
                print('')
                print('Congrats you got it right!')
                gotRight= gotRight + 1
                print(''.center(90,'_'))

                print('you finished with',ansWrong,' wrong attempts.')
                Attempts= ansWrong + 3
                finalScore= (gotRight/Attempts) * 100
                print( userName,', Your mark is', finalScore,'%')
            start = input('play again ? (Y:yes) (N:no): ').capitalize()
        else:
            print('bye')

#----------------------------------multiplication----------------------------------------------
if int(userChoice) == 3 :
    print('You chose the multiplication quiz!'.center(90,'*'))

    start=input('Type Y to begin :').capitalize()
    while start.isnumeric() == True or start != 'Y' :
        print(' I think you made a typo... ')
        print('')
        start= input('please enter Y again: ').capitalize()

    while start == 'Y':
        numOne =random.randint(1,12)
        numTwo=random.randint(1,12)
        numThree= random.randint(1,12)
        while numTwo >= numOne :
            numOne =random.randint(1,12)
            numTwo=random.randint(1,12)
        ansOne = numOne * numTwo
        userAnsOne= input('Question 1: what is ' + str(numOne) +'*'+ str(numTwo) +'?: ')


        while userAnsOne.isnumeric() == False:
            print(' I think you made a typo... please enter a number next time')
            print('')
            userAnsOne= input('Question 1: what is ' + str(numOne) +'*'+ str(numTwo) +'?: ')
            
        ansWrong=0
        while ( ansOne != int(userAnsOne) ) :
            print('OOF looks like you got it wrong please try again:')
            print('')
            userAnsOne= input('Question 1: what is ' + str(numOne) +'*'+ str(numTwo) +'?: ')
            while userAnsOne.isnumeric() == False:
                print(' I think you made a typo... please enter a number next time')
                print('')
                userAnsOne= input('Question 1: what is ' + str(numOne) +'*'+ str(numTwo) +'?: ')
                
            ansWrong= ansWrong + 1
        else:
            print('')
            print('Congrats you got it right!')
            gotRight= 1
            print(''.center(90,'_'))






    #-----ques 2----

        while numThree >= numTwo :
            numThree =random.randint(1,12)
            numTwo=random.randint(1,12)
        ansTwo = numTwo * numThree
        userAnsTwo= input('Question 2: what is ' + str(numTwo) +'*'+ str(numThree) +'?: ')
        while userAnsTwo.isnumeric() == False:
            if int(userAnsOne) < 0 :
                    break
            print(' I think you made a typo... please enter a number next time')
            print('')
            userAnsTwo= input('Question 2: what is ' + str(numTwo) +'*'+ str(numThree) +'?: ')

        while ( ansTwo != int(userAnsTwo) ) :
            print('OOF looks like you got it wrong please try again:')
            print('')
            userAnsTwo= input('Question 2: what is ' + str(numTwo) +'*'+ str(numThree) +'?: ')
            while userAnsTwo.isnumeric() == False:
                if int(userAnsOne) < 0 :
                    break
                print(' I think you made a typo... please enter a number next time')
                print('')
                userAnsTwo= input('Question 2: what is ' + str(numTwo) +'*'+ str(numThree) +'?: ')
        
            ansWrong= ansWrong + 1
        else:
            print('')
            print('Congrats you got it right!')
            gotRight= gotRight + 1
            print(''.center(90,'_'))
    #ques 3
        while numOne >= numThree :
                numThree =random.randint(1,12)
                numOne=random.randint(1,12)
        ansThree = numThree * numOne
        userAnsThree= input('Question 3: what is ' + str(numThree) +'*'+ str(numOne) +'?: ')
        while userAnsThree.isnumeric() == False:
            if int(userAnsOne) < 0 :
                    break
            print(' I think you made a typo... please enter a number next time')
            print('')
            userAnsThree= input('Question 3: what is ' + str(numThree) +'*'+ str(numOne) +'?: ')
            if userAnsOne<0:
                continue
        while ( ansThree != int(userAnsThree) ) :
            print('OOF looks like you got it wrong please try again:')
            print('')
            userAnsThree= input('Question 3: what is ' + str(numThree) +'*'+ str(numOne) +'?: ')
            while userAnsThree.isnumeric() == False:
                if int(userAnsOne) < 0 :
                    break
                print(' I think you made a typo... please enter a number next time')
                print('')
                userAnsThree= input('Question 2: what is ' + str(numThree) +'*'+ str(numOne) +'?: ')
        
            ansWrong= ansWrong + 1
        else:
            print('')
            print('Congrats you got it right!')
            gotRight= gotRight + 1
            print(''.center(90,'_'))

            print('you finished with',ansWrong,' wrong attempts.')
            Attempts= ansWrong + 3
            finalScore= (gotRight/Attempts) * 100
            print( userName,', Your mark is', finalScore,'%')

        start = input('play again ? (Y:yes) (N:no): ').capitalize()
    else:
        print('bye')
