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
  data.update({n:x}) # Updates if 'a' exists, else adds 'a'
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

```
