class EthicalHacker:
    def __init__(self):
        self.name = "Bm0047"
        self.country = "Tanzania 🇹🇿"
        self.role = "Cybersecurity Specialist"
        self.skills = [
            "Penetration Testing",
            "Vulnerability Assessment",
            "Network Security",
            "Web App Security",
            "Digital Forensics",
            "Malware Analysis"
        ]
        
    def __str__(self):
        return f"{self.name} | {self.role}"

me = EthicalHacker()
print(me)
