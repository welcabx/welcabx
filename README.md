```Python

class careerShifter:

    def __init__(self):
        self.firstname = "Rowel"
        self.lastname = "Cababan"
        self.roles = [
            "Pythoneer", "Home Network Support Expert", "Technophile"
        ]
        self.country = "Philippines"

    def headline(self):
        return "Headline: {} | {} | {}".format(*self.roles)

    def about(self):
        return (f"Howdy! I am {self.firstname} from {self.country}."
                f" A tech driven professional with over 6 years of experience in delivering exceptional customer support."
                f" I specialize in providing technical support on home networking solutions.\n"
                f"A self-taught developer with strong focus on Python."
                f" I aim to merge and leverage my customer service expertise with my growing development skills.\n"
                f"Always eager to learn, collaborate and innovate.")

    def current_status(self):
        return f"We are in the process of moving so that is why I am inactive for a while here."

if __name__ == '__main__':
    me = careerShifter()
    print(me.current_status())
```
