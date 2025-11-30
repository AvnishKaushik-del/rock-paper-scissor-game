import random
while True:
    a=input("enter a rock,paper,scissor")
    b=["rock","paper","scissor"]
    print(random.choice(b))
    if(a==b):
        print("draw")
    elif a==("paper"): 
        if b==("scissor"): 
            print("b win")
        else:
            print("a win")
    elif a==("rock"):
     if(a=="scissor"):
        print("a win")
     else:
        print("b win") 
        if b==("scissor"): 
          print("b win")
          
    else:
         print("a win")  
    break
else:
   print("choose right!rock,paper,scissor") 
