validations = 0
email = input("enter email")
len = email.__len__()
if email.find('@') != 0:
   validations += 1 
   if email.find('.') >= email.find('@') +2 :
       validations += 1
       if len - email.find('.') != 0: 
           validations +=1
if validations == 3:
   print("Valid")
else:
   print("Invalid")
