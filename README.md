

<h3>

```python
print("HELLO GITHUB!")

AboutMe = {
    'Name' : 'Octavio Benjamin',
    'Age' : 19,
    'Country' : 'Argentina',
    'Email' : 'benjaminmen55@gmail.com',
    'Discord' : 'Dr. Tavo #8955',
    'currently' : 'Student of information systems engineering'
} 

class student:
    def __init__(self, SoftwareSkill, ProgrammingLanguages):
        self.SotwareSkill = SotwareSkill
        self.ProgrammingLanguages = ProgrammingLanguages 
                

    def say_hi (self):
        print("Hi, Welcome to my profile")

def GetContactInformation():
    print (AboutMe["Email"])
    print (AboutMe["Discord"])

SoftwareSkill = ['Photoshop', 'Illustrator', 'VSCode']
ProgrammingLanguages = ['Python']
# Know and in improvement
me = student(SoftwareSkill, ProgrammingLanguages)

me.say_hi()
GetContactInformation()
```
</h3>
