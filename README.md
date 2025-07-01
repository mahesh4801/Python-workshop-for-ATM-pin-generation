# Python-workshop-for-ATM-pin-generationpin=int(input("enter your 4-digit pin:"))
spin=1234
balance=5000
if pin==spin:
    print("access granted!!")
    withdraw=int(input("enter amount:"))
    if withdraw>balance:
       print("insufficent funds!!!!")
    else:
       print("amount withdraw:",withdraw)
       print("remaining balance:",balance-withdraw)
       print("thankyou for banking with ICICI")
else:
     print("access denied.....wrong pin")
output:
enter your 4-digit pin: 1234
access granted!!
enter amount: 2000
amount withdraw: 2000
remaining balance: 3000
thankyou for banking with ICICI
