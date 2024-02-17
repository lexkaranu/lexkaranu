- 👋 Hi, I’m @lexkaranu
- 👀 I’m interested in coding...
- 🌱 I’m currently learning information and systems technology...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me 0798223203...
- 😄 Pronouns: he/him...
- ⚡ Fun fact: I'm new here lol...

<!---
lexkaranu/lexkaranu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
practice ex 7


def areatriangle():
    base = int(input("Enter the base of the triangle: "))
    height = int(input("Enter the height of the triangle: "))
    return 0.5 * base * height

def areacircle():
    circle_radius = float(input("Enter the radius of the circle: "))
    return 3.141592653589793 * circle_radius**2
    
def arearectangle():
    length = int(input("Enter the length of the rectangle: "))
    width = int(input("Enter the width of the rectangle: "))
    return length * width
    
while True:
    area_choice = input("Kindly enter the shape that you want to calculate or type quit to exit the code: ").lower()
    if area_choice=="triangle":
        print(areatriangle())
    elif area_choice=="circle":
        print(areacircle())
    elif area_choice=="rectangle":
        print(arearectangle())
    elif area_choice=="quit":
        break
    else:
        print("The shape you entered is not available")
    
