class SquidCoral:
    def __init__(self):
        self.name = "Squid Coral"
        self.passion = "coding"
        self.innovation = True
        self.clean_code = True
        self.learning = True
        self.collaboration = True
        self.creation = True

    def bio(self):
        return f"{self.name}: Passionate {self.passion} exploring the digital realm. Building innovative solutions with clean and efficient code. Constantly learning, collaborating, and creating."

# Instantiate Squid Coral
squid_coral = SquidCoral()

# Print bio
print(squid_coral.bio())
