print('Hello,Welcome to "DOCTOR KIDS"')
print('Patients entry to the hospital is entered for doctor*s reference')
print('patient 1 - injury')
print('patient 2 - cold')
print('patient 3 - cough')
print('patient 4 - fever')
print('Let us call the patients one by one')
doctor=input('wishing you a good day! what happen to u?: ')
score=0
if doctor.lower()=='injury':    
    doctor=input('do u met an accident(yes/no): ')
    if doctor.lower()=='yes':
        score+=1
        print('ok i will inform to police beforestarting treatmant for you')
    else:
        print('ok')
    doctor=input('let me plaster your wounds and suggest you some prescriptions')
    doctor=input('do you prefer (medicine/injection): ')
    if doctor.lower()=='medicine':
        score+=1
        print('IBUFROFEN')
        print('kindly follow this prescription!Get well soon')
    else:
        print('Ok.Let me use DEMOROL injection')
        print('kindly follow this prescription!Get well soon')
doctor=input('wishing you a good day! what happen to u?: ')
score=0
if doctor.lower()=='cold':    
    doctor=input('How long do you suffer?(less than a week/more than a week): ')
    if doctor.lower()=='morethan a week':
        score+=1
        print('ok let us take thyroid test')
        print('visit the lab and give this receipt to the lab technician there')
        print('ok doctor!')
    else:
        print('ok! I will give you some prescription')
    doctor=input('do you suffer by (stuffy nose/runny nose): ')
    if doctor.lower()=='stuffy nose':
        score+=1
        print('phenylephrine')
        print('kindly follow this prescription!Get well soon')
    else:
        print('diphenhydramine')
        print('kindly follow this prescription!Get well soon')
doctor=input('wishing you a good day! what happen to u?: ')
score=0
if doctor.lower()=='cough':
   doctor=input('How long do you suffer?(less than a week/more than a week): ')
   if doctor.lower()=='morethan a week':
        score+=1
        print('ok let us take throat scan')
        print('visit the lab and give this receipt to the lab technician there')
        print('ok doctor!')
   else:
        print('ok! I will give you some prescription')
   doctor=input('do you prefer(medicine/syrup): ')
   if doctor.lower()=='medicine':
        score+=1
        print('DEXTRONETROPHAN')
        print('kindly follow this prescription!Get well soon')
   else:
        print('DM Oral')
        print('kindly follow this prescription!Get well soon')  
doctor=input('wishing you a good day! what happen to u?: ')
score=0
if doctor.lower()=='fever':
    print('Let me check your body temperature')
    doctor=input('your body temperature(more than 273/less than 273): ')
    if doctor.lower()=='more than 273':
        score+=1
        print('oops! you have fever')
    else:
        print('it is mild fever so no need to worry')
    doctor=input('How long do you suffer?(lessthan a week/morethan a week): ')
    if doctor.lower()=='morethan a week':
        score+=1
        print('ok let us take blood test')
        print('visit the lab and give this receipt to the lab technician there')
        print('ok doctor!')
    else:
        print('ok! I will give you some prescription')
    doctor=input('do you prefer (medicine/injection): ')
    if doctor.lower()=='medicine':
        score+=1
        print('COLPHOL')
        print('kindly follow this prescription!Get well soon')
    else:
        print('ACITAMINOPHEN')
        print('Get well soon')
