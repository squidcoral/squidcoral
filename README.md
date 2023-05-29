class SquidCoral:
    def __init__(self):
        self.name = "\U0001F991 Squid Coral \U0001F991"
        self.bio = '''
        \U0001F30A I am a passionate explorer of the vast seas of cybersecurity and IT. 
        My main programming language is Python, where I navigate the depths of code with precision and creativity.
        Developer of the renowned W4SP Stealer, I dive into challenges head-on. \U0001F4A5'''
        self.age = 17
        self.thm = "https://tryhackme.com/p/SquidCoral"
        self.htb = "https://app.hackthebox.com/profile/393384"
        self.dsc = ("SquidCoral#0001", 1060811799949226004)
        self.skills = {
            "python": "expert",
            "bash": "proficient",
            "c++": "learning...",
            "php": "learning..."
        }

squidcoral = SquidCoral()

# Accessing information
print("Name:", squidcoral.name)
print("Bio:", squidcoral.bio)
print("Age:", squidcoral.age)
print("TryHackMe:", squidcoral.thm)
print("HackTheBox:", squidcoral.htb)
print("Discord:", squidcoral.dsc)
print("Skills:", squidcoral.skills)
