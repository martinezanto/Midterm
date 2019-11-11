def sums():
   
   #TODO: Initialize a variable called first_sum and store the sum of 
   # 2 and 2
   first_sum = 2 + 2

   #TODO: Store to first_sum the value of first_sum times 10
   first_sum = first_sum * 10

   #TODO: Initialize a variable called secret and assign it the value 
   # of first_sum plus 2
   secret = first_sum + 2

   return secret

def string_manip(first_name):

   # TODO: Initialize a variable called name and assign it the 
   # parameter.
   name  = first_name


   # TODO: Use builtin string functions and slices to replace None with 
   # the appropriate manipulation of your name. I've done the first one.
   all_caps = name.upper()
   all_lowercase = name.lower()
   first_five_letters = name[:5]
   last_two_letters = name[-2:]

   return [all_caps, all_lowercase, first_five_letters, last_two_letters]

def greeter_bot():

   # TODO: Use the input() function to prompt the user for their name.
   # Then assign the value to a variable called name and print a greeting.
   # I have started it for you, but you need to modify the input and 
   # print functions.
   # Hint: to get the test to pass, the greeting should be "Hello, input name"
   name = input("Hi, friend! What is your name?") # Changed syntax, to match video.
   print("Hello, {}!".format(name)) #Added everything after hello.

def temp_calculator():

   # TODO: Write code that prompts the user for a temperature in degrees
   # fahrenheit and prints the equivalent temperature in degrees celsius.
   # The formula is C = (F - 32) * (5/9). 
   temp_f = float(input("What is the temperature in Fahrenheit?"))
   temp_c = (temp_f -32) * last_two_letters(5/9)
   print(temp_c)


   #Old Code:
  # fahrenheit = float(input("Enter temperature in fahrenheit: "))
   #celsius = (fahrenheit - 32) * 5/9
  # print('%.2f Fahrenheit is: %0.2f Celsius' %(fahrenheit, celsius))

def equitable_bill_splitter():
   
   # TODO: Read the following code and add comments to each line explaining what
   # it does. To write a comment, begin the line with an octothorpe (hashtag, #)
   # ask user for input, convert input into integer, and store in variable called people.
   people = int(input("How many people are paying? ")) #Assigning the variable "people" a number inputted by the user.
   salaries = [] #print values in salaries
   total = 0 #Assiging the variable "total" to 0.
    
   for i in range(people): #Run a loop of all people.
      sal = int(input("What is the salary of person {}?".format(i+1))) #"sal" is a variable for salary and it asks user what the salary of each person is.
      total += sal #Add what this person makes to the total salary of everyone.
      salaries.append(sal) #Update value to existing list.
   
   total_bill = int(input("How much is the bill? ")) #Defining the varaible "total_bill" the cost of the bill, which is input by user.
   
   for j in range(len(salaries)): #Run loop for the salaries.
      print("Person {} should pay ${}\n".format(j + 1, round((total_bill * (salaries[j]/total)), 2))) #Give me the total for each person to pay.
