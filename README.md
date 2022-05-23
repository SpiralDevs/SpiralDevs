# Info

[<b>Gorilla Tag Discord</b>](https://discord.gg/YSQmmcb68y)

<h4><b>My Discord Spiral#1234</b></h4>

<details><summary>Portfolio</summary>
  
  # My Apps
  
  <details><summary>My Apps</summary>
    
  <details><summary>Texter</summary>
    
  [Texter Github Link](https://github.com/SpiralGaming/Texter)
    
  [Texter .zip download](https://github.com/SpiralGaming/Texter/releases/download/v1.0.0/Texter.zip)
    
  [Texter .msi download](https://github.com/SpiralGaming/Texter/releases/download/v1.0.0/Setup.msi)
    
  [Texter .exe download](https://github.com/SpiralGaming/Texter/releases/download/v1.0.0/setup.exe)  
    
  </details>  
    
  <details><summary>Counter</summary>
    
  [Counter Github Link](https://github.com/SpiralGaming/Counter)
    
  [Counter .zip download](https://github.com/SpiralGaming/Counter/releases/download/v1.0.0/Counter.zip)
    
  [Counter .msi download](https://github.com/SpiralGaming/Counter/releases/download/v1.0.0/Setup.Counter.msi)
    
  [Counter .exe download](https://github.com/SpiralGaming/Counter/releases/download/v1.0.0/setup.exe)
    
  </details>
  
  <details><summary>Mathiest</summary>
    
  [Mathiest Github Link](https://github.com/SpiralGaming/Mathiest)
    
  [Mathiest .zip download](https://github.com/SpiralGaming/Mathiest/releases/download/v1.0.0/Mathiest.zip)
    
  [Mathiest .msi download](https://github.com/SpiralGaming/Mathiest/releases/download/v1.0.0/Setup.Mathiest.msi)
    
  [Mathiest .exe download](https://github.com/SpiralGaming/Mathiest/releases/download/v1.0.0/setup.exe)
    
  </details>
  
  </details>
    
  # My Games
  
  <details><summary>My Games</summary>

    
<details><summary>Sword Fighters</summary>
  
   ## Sword Fighters
    
  [Sword Fighters Game](https://github.com/SpiralGaming/Sword-Fighters/releases/latest)

  [Sword Fighters Discord Bot](https://discord.com/api/oauth2/authorize?client_id=945462110366887938&permissions=8&redirect_uri=https%3A%2F%2Fsolo.to%2Fswordfighters&response_type=code&scope=bot%20identify%20applications.commands%20connections)

  [Sword Fighters Chrome Extenstion](https://chrome.google.com/webstore/detail/sword-fighters/lahfjghkoalcbfceadpocngnoeccagbb)

    
  </details>
    
  </details>
  
  <details><summary>Python</summary>
    
  <details><summary>Python Calculator</summary>
    
  [Python Calculator](https://github.com/SpiralGaming/Calculator-Python)
  
  [Python Calculator .exe download](https://github.com/SpiralGaming/Calculator-Python/releases/download/v1.0.0/calculator.exe)
    
  [Python Calculator .py download](https://github.com/SpiralGaming/Calculator-Python/releases/download/v1.0.0/calculator.py)
    
   # Source Code
    
```Python
#operand
print("+ for Addition")#
print("- for Subtraction")#
print("* for Multiplcation")#
print("/ for Division")#

while True:
    
    #input operand
    choice = input("Enter Operand: ")#
    
    if choice in ("+", "-", "*", "/"):

        #nums
        num1 = float (input("Enter First Number: "))#
        num2 = float (input("Enter Second Number: "))#
        
        # results
        addresult = num1+num2#
        subresult = num1-num2#
        mulresult = num1*num2#
        divresult = num1/num2#
        
        if choice == "+":
            print(num1, "+", num2, "=", addresult)#
        elif choice == "-":
            print(num1, "-", num2, "=", subresult)#
        elif choice == "*":
            print(num1, "*", num2, "=", mulresult)#
        elif choice == "/":
            if num2 == 0.0:
                print("Divide by 0 error")
            else:
                print(num1, "/", num2, "=", divresult)#

        else: 
            print("Invalid Choice")#
```
    
  </details>
    
  <details><summary>Python Password Generator</summary>
    
  [Python Password Generator](https://github.com/SpiralGaming/Python-Password-Generator)
  
  [Python Password Generator .exe download](https://github.com/SpiralGaming/Python-Password-Generator/releases/download/v1.0.0/random.password.generator.exe)
    
  [Python Password Generator .py download](https://github.com/SpiralGaming/Python-Password-Generator/releases/download/v1.0.0/random.password.generator.py)
    
   # Source Code
    
```Python
#Random Password Generator - by Spiral
#importing modules
import random
import string
#welcome text
print("Hello User, Welcome to Password Generator!\nType help for help\nType generate to generate a password without having to exclude anything\nType exclude to exclude a certain type from password.\nAvailable Items To Be Excluded:\nlowercase\nuppercase\nnumbers\nsymbols")

while True:
    option = input("Enter Option")
    if option in ("help", "generate", "exclude"):
        if option == "help":
            print("Type help to bring this text up again\nType generate to generate a password without having to exclude anything\nType exclude to exclude a certain type from password.\nAvailable Items To Be Excluded:\nlowercase\nuppercase\nnumbers\nsymbols")
        elif option == "generate":
            #password length
            passLength = int(input("Enter Password Length: "))
            #data
            lowercase = string.ascii_lowercase
            uppercase = string.ascii_uppercase
            number = string.digits
            symbol = string.punctuation
            #combine data
            data = lowercase + uppercase + number + symbol
            #generate password
            structure = random.sample(data,passLength)
            password = "".join(structure) 
            print(password)
        elif option == "exclude":
            print("Available Items To Be Excluded:\nlowercase\nuppercase\nnumbers\nsymbols")
            choice = input("Enter What You Want To Be Excluded: ")
            if choice in ("lowercase", "uppercase", "numbers", "symbols"):
                if choice == "lowercase":
                    #password length
                    passLength = int(input("Enter Password Length: "))
                    #data
                    uppercase = string.ascii_uppercase
                    number = string.digits
                    symbol = string.punctuation
                    #combine data
                    data = uppercase + number + symbol
                    #generate password
                    structure = random.sample(data,passLength)
                    password = "".join(structure) 
                    print(password)
                elif choice == "uppercase":
                    #password length
                    passLength = int(input("Enter Password Length: "))
                    #data
                    lowercase = string.ascii_lowercase
                    number = string.digits
                    symbol = string.punctuation
                    #combine data
                    data = lowercase + number + symbol
                    #generate password
                    structure = random.sample(data,passLength)
                    password = "".join(structure) 
                    print(password)
                elif choice == "numbers":
                    #password length
                    passLength = int(input("Enter Password Length: "))
                    #data
                    lowercase = string.ascii_lowercase
                    uppercase = string.ascii_uppercase
                    symbol = string.punctuation
                    #combine data
                    data = lowercase + uppercase + symbol
                    #generate password
                    structure = random.sample(data,passLength)
                    password = "".join(structure) 
                    print(password)
                elif choice == "symbols":
                    #password length
                    passLength = int(input("Enter Password Length: "))
                    #data
                    lowercase = string.ascii_lowercase
                    uppercase = string.ascii_uppercase
                    number = string.digits
                    #combine data
                    data = lowercase + uppercase + number
                    #generate password
                    structure = random.sample(data,passLength)
                    password = "".join(structure) 
                    print(password)
            else:
                print("Invalid Choice")
    else: 
        print("Invalid Option...")  
```
    
  </details>
   
    <details><summary>Python Number Generator</summary>
      
      [Python Number Generator](https://github.com/SpiralGaming/Python-Number-Generator)
      [Python Number Generator .exe download](https://github.com/SpiralGaming/Python-Number-Generator/releases/download/v1.0.0/random.number.generator.exe)
      [Python Number Generator .py download](https://github.com/SpiralGaming/Python-Number-Generator/releases/download/v1.0.0/random.number.generator.py)
      
      ```Python
      
      ```
      
      
    </details>
    
  </details>
  
 </details>
