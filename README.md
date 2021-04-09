# Project-3
Assignment 3
fname = input("Enter first name: ")
lname = input("Enter last name: ")
fullnames = (fname + " " + lname)

#phone and email details
phone=input("Enter customer's phone number: ")
email=input("Enter customer's email address: ")

#Price of a used car
price = 10000
has_good_credit = True

ifhas_good_credit:
down_payment = 0.1 * price
else:
down_payment = 0.2 * price
print()
print("Full Names: " + fullnames)
print("Phone: " + phone)
print("Email: " + email)
print(f"Down Payment: {'{:.2f}'.format(down_payment)}")
