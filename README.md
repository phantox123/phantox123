- 👋 Hi, I’m @phantox123
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
phantox123/phantox123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
from random import randint 

print("Nhap Dam, La, Keo:")
player = input()
computer = randint(0,2)

if computer == 0:
	computer = "Dam"
if computer == 1:
	computer = "La"
if computer == 2:
    computer = "Keo"

    print(computer)
	
    if player 
        if computer == "Keo":
            print("Draw")

    if player == "Dam":
        if computer == "Keo":
            print("Win")
        if computer == "Dam":
            print("Draw")
        if computer == "La":
            print("Lose")
            
    if player == "La":
        if computer == "Keo":
            print("Lose")       
        if computer == "Dam":
            print("Win")
        if computer == "La":   
            print("Draw")
