## Petrov Artem
### Contact information:
**Location:** Belarus \
**Email:** svinpetr18@gmail.com \
**Github:** <https://github.com/FYMG>  
**Telegram:** <https://t.me/Fyyoops>
### Some words about myself:
As a highly motivated and technically proficient individual, I am passionate about programming and technology. I have gained extensive experience in programming with Python, which has enabled me to develop complex applications and solutions to real-world problems. My proficiency in coding has enabled me to successfully complete several freelance projects, where I helped clients solve their business challenges and increase efficiency using technical solutions.

I graduated from Kingisepp College of technologic and service with a degree in Information Technology, where I honed my skills in system analysis, design, and development. During my college years, I gained invaluable experience working on several technology projects, which helped me develop my analytical and critical thinking skills. I also worked on several technology-related extracurricular activities, which allowed me to work collaboratively with other IT professionals to create innovative solutions.

As I seek new opportunities, I am excited to apply my passion, creativity, and technical expertise to help companies achieve their business goals through technology.
### Code example:
#### Python:
task: The observed PIN(4 kyu)
``` 
def get_pins(observed):
    pins = [""]
    num_dict = {'0':["0","8"],
    '1':["1","2","4"],
    '2':["1","2","3","5"],
    '3':["2","3","6"],
    '4':["1","4","5","7"],
    '5':["2","4","5","6","8"],
    '6':["3","5","6","9"],
    '7':["4","7","8"],
    '8':["5","7","8","9","0"],
    '9':["6","8","9"]} 
    len_pins = len(pins)
    for i in observed:
        for z in num_dict[i]:
            for y in range(len(pins[:len_pins])):
                pins.append(pins[y]+z)
        pins = pins[len_pins:]
        len_pins = len(pins)
        return pins 
```
#### JS: