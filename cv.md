# [rsschool-cv](https://ant0ha301184.github.io/rsschool-cv/) #
# Anton Kolnobritskiy #
# ![Foto](foto.png "My Foto") #
## Junior Frontend Developer ##

---
### **Contact information:** ###
* **Address:** Uzbekistan, Tashkent
* **Phone:** +998 93 5385454
* **E-mail:** ant0ha301184@gmail.com
* **GitHub:** [Anton Kolnobritskiy](https://github.com/ant0ha301184)

---

### **About Me:**
 *My full name is Kolnobritskiy Anton Valerevich. I was born in Tashkent, Uzbekistan in 1984. I'm 37 years old. About my appearance, I'm tall and heavy-bodied (probably), I have brown eyes and hair. About my character, I am very friendly, but only with people that I think are quite good. I happen really impatient and curious, but I do not consider it a disadvantage. I do not think my life is boring because every day confronted with something new and interesting for me. For example: meeting new people or a meeting with the best friends.*

---

### __Skills:__
1. HTML
2. CSS
3. Git/GitHub
4. Python


---


### __Code Example:__

#### Python code:

```python 
import sys
from tkinter.messagebox import *

rezult = {}

if len(sys.argv) != 2:
    print("Передайте имя файла в качестве аргумента!")
    quit()

try:
    with open(sys.argv[1], "r") as file:
        data = file.readline()

        while data != "":
            # data = data.rstrip()
            data = data.lower()
            for i in data:
                if i == "\n":
                    continue
                if i not in rezult.keys():
                    rezult[i] = 1
                else:
                    rezult[i] += 1

            data = file.readline()
except IOError:
    showwarning("Ошибка при доступе к файлу!")

print(rezult)
```


---


### **Education:**
* Tashkent University of Information Technologies
    * Telecommunications
* SOS Academy
    * Python programming


---


### Languages:
* Russian - native speaker
* English - A2
