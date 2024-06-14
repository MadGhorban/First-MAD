print('Welcome to My Quiz')
answer=input('Are you ready to play this Quiz ? (y/n) :')
score=0
total_questions=3
 
if answer.lower()=='yes':
    answer=input('Question 1: What is your Favorite programming language?')
    if answer.lower()=='Python':
        score += 1
        print('true')
    else:
        print('false:(')
 
 
    answer=input('Question 2: Do you follow any author on AskPython? ')
    if answer.lower()=='yes':
        score += 1
        print('true')
    else:
        print('false:(')
 
    answer=input('Question 3: What is the name of your favourite website for learning Python?')
    if answer.lower()=='askpython':
        score += 1
        print('true')
    else:
        print('false:(')
 
print('Thankyou for Playing this small quiz game, you attempted',score,"questions correctly!")
mark=(score/total_questions)*100
print('Marks obtained:',mark)
print('BYE!')
