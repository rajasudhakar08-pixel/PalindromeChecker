# PalindromeChecker
# This code checks if the number given by the user is a palindrome or not
x = int(input('Enter a number'))
n = x
reverse = 0
if x == abs(x):
  while (x!=0):
    digit = x%10
    reverse = reverse*10 + digit
    x = x//10
  print(reverse)   
  if n == reverse:
    print('true')
  else:
    print('false') 
else:
  print('false')
