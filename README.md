# Ask-user-to-input-salary-and-print-his-her-net-bonus-amount-using-python
name= input('Enter Employee Name: ')
salary= input('Enter salary: ')
year=input('Enter years of service: ')
if int(year)>=5:
    bonus=(5/100)*int(salary)
print('Your Bonus is: ', bonus)
else:
print('Sorry! No Bonus')
