
<img src="./img/computer-illustration.png" min-width="400px" max-width="400px" width="400px" align="right" alt="Computador iuriCode">


AboutMe = {
    'Name' : 'Octavio Benjamin',
    'Age' : 18,
    'Country' : 'Argentina',
    'email' : 'benjaminmen55@gmail.com',
    'twitter' : 'Benjxmin_'
} 

class student:
    def __init__(self):
        self.SoftwareSkill = ['Photoshop', 'Illustrator', 'VisualStudioCode', 'OfficeSoftware']
        self.Languages = ['Python', 'C++', 'HTML & CSS'] # Know and in improvement
me = student()

def GetContactInformation():
    return AboutMe.email
    return AboutMe.twitter
