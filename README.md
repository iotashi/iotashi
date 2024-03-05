# 👋 Hello, World! I'm Cedric (Iotashi)

Welcome to the source code repository of my coding adventures!

## 🚀 About Me

- 💻 Fullstack Developer with a knack for turning coffee into code.
- 🌐 Building scalable web applications and microservices.
- 🚀 Open-source contributor and tech enthusiast.

## 🛠️ Tech Stack


Here's a glimpse of the tools and technologies I wield in my coding toolbox:

```python
class FullstackDeveloper:
    """
    A class representing a Backend Developer with various skills and tools.
    """

    def __init__(self):
        # Initialize attributes related to languages, frameworks, databases, and tools etc...
        self.languages = ["Python", "JavaScript","TypScript", "C++"]
        self.frameworks = ["FastAPI", "Flask", "Express.js", "React", "Angular", "Bootstrap"]
        self.databases = ["PostgreSQL", "MySQL", "SQLite"]
        self.tools = ["Git", "VS Code", "Redis", "RabbitMQ"]
        self.cloud = ["AWS"]
        self.devops = ["Docker", "Kubernetes", "Nginx"]
        self.os = ["Red-hat", "Ubuntu","Windows"]
        self.other = ["nodejs"]


    def write_code(self, language="Python"):
        """
        Generate code based on the specified programming language.

        Parameters:
            - language (str): The programming language for which code needs to be generated.

        Returns:
            str: The generated code.
        """
        if language == "Python":
            return "print('Hello, World!')"
        elif language == "JavaScript":
            return "console.log('Hello, World!')"
        else:
            return "🤔🤔🤔🤔"

cedric = FullstackDeveloper()
cedric.write_code()
