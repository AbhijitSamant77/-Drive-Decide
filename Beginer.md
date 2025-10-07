# -Drive-Decide
#Drive &amp; Decide is a beginner-friendly Python program that helps users check if they’re eligible to drive and whether they can afford to buy a bike based on their budget.

print("Youre Age is",x)
if (x>=18):
  print("YES")
  print("you can drive") 
else:
  print("NO")
  print("you are not eligible to drive")
purchase = int(input("bike budget ="))
Balance = int(input("Your Budget="))
RemainingBal = int(input("How much do you want to keep after purchase from your balance:-"))
if(Balance - purchase > RemainingBal):
    print("Purchase bike")
elif (Balance - purchase >= RemainingBal):
    print("CHOICE IS UPTO YOU")
else:
    print("buy bike later")
