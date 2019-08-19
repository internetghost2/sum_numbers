# Sum Numbers
using a document and converter a list, then just sum the numbers with python3

"""

DAY 1 Advetocode

This program takes numbers from another document and calculate the solution 

by Marc Hortelano

"""

    path = 'file' # Change this to your document locate

    with open(path) as f:
      lst = [int(x) for x in f.read().split()]
      sol = 0
    
    for i in lst:
	    sol = sol + i 
    print (sol)
