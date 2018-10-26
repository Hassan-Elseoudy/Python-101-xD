```python
#Reverse a string
str = "python"
s = str[::-1] #nohtyp

#Print elements
for i in range (10):
  print (i), # to print elements sepearted by a space 0 1 2 3 4 5 6 7 8 9
  print (i) # to print elements sepearted by a new line 0 \n 1 \n 2 \n 3 \n 4 \n 5 \n 6 \n 7 \n 8 \n 9
  print(i, sep='', end='\n', file=sys.stdout) # to print elements sepearted by a 'sep' 0123456789

#Dictionary
  data = {}
  data.update({a:x}) # Updates if 'a' exists, else adds 'a'
  del data[key]  # Removes specific element in a dictionary
  data.pop(key)  # Removes the key & returns the value
  data.clear()  # Clears entire dictionary
  for key in data: # Iterates just through the keys, ignoring the values
  for key, value in d.items(): # Iterates through the pairs
  for key in d.keys(): # Iterates just through key, ignoring the values
  for value in d.values(): # Iterates just through value, ignoring the keys
  
#Formatting in Python3
  print ("Today's stock price: %f" % 50.4625)   # --> 50.462500
  print ("Today's stock price: %.2f" % 50.4625) # --> 50.46
  print ("Change since yesterday: %+.2f" % 1.5) # --> +1.50
  
#Strings
  print(x[0]) #first character
  print(x[0:1]) #first character, but we have explicitly set the end character
  print(x[0:2]) #first two characters
  print(x[-1]) #last character
  print(x[:3]) #This is a slice from the beginning of the string and stopping before the 3rd element.
  
  firstname = 'Christopher Arthur Hansen Brooks'.split(' ')[0] # [0] selects the first element of the list
  lastname = 'Christopher Arthur Hansen Brooks'.split(' ')[-1] # [-1] selects the last element of the list
  print(firstname) #Christopher
  print(lastname) #Brooks
  
  sales_record = {'price': 3.24,'num_items': 4,'person': 'Chris'}
  sales_statement = '{} bought {} item(s) at a price of {} each for a total of {}'
  print(sales_statement.format(sales_record['person'],sales_record['num_items'],                                               sales_record['price'],sales_record['num_items']*sales_record['price']))

```
