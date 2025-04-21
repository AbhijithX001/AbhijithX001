```python
# 🧠💻 Abhijith P - Not your average engineer.

class AbhijithP:
    def __init__(self):
        self.name = "Abhijith P"
        self.alias = "Code Strategist | Tech Explorer"
        self.current_location = "ANNA UNIVERSITY CHENNAI"
        self.mission = "Lead with logic. Build with purpose. Adapt like a warrior."
        self.status = "Engineering Student (CSE) | Future-ready Technophile"

    def skills(self):
        return [
            "🐍 Python",
            "☕ Java (Basics)",
            "📊 Pandas & EDA",
            "🔧 Git & GitHub",
            "📱 Mini Projects (QR Scanner, To-Do App, Calculator, Tic-Tac-Toe)",
            "🤖 Affective Computing Concepts"
        ]

    def connect(self):
        return {
            "📧 Email": "abhijithprakash22334a@gmail.com",
            "🌐 GitHub": "https://github.com/AbhijithP",
            "🔗 LinkedIn": "https://www.linkedin.com/in/abhijith-p11"
        }

    def __str__(self):
        return f"""
        Hello world, I'm {self.name} 👋
        A curious mind with a keyboard, turning coffee into code and visions into variables.
        Based in {self.origin}, building the future one Python script at a time.
        """

if __name__ == "__main__":
    me = AbhijithP()
    print(me)


