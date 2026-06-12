#Food Ordering System
food =["yam", "jollof Rice", "Bread", "Amala", "Ewedu"]
order=str(input("Enter your food order: "))
if order in food:
  print("Your Order is:", order)
  print("Food is Available")
else:
  print("Your Order is: ", order)
  print("selected Item is not Available "
