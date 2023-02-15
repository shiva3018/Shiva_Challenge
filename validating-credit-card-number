import re 

pattern = r"^(?!.*([0-9])(-?\1){3})[456]\d{3}(?:-?\d{4}){3}$"

testCreditCardNumber = "4123-1112-2233-3123"
result = re.match(pattern, testCreditCardNumber)

if (result):
    print("Valid.")
else:
    print("Invalid.")
