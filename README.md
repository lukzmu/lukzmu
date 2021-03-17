```python
from typing import Tuple


class PythonDeveloper:
    def __init__(self):
        self.name = "Łukasz Żmudziński"
        self.social_media = {
            "linkedin": "https://www.linkedin.com/in/lukzmu/",
            "twitter": "https://twitter.com/lukzmu/",
            "personal_website": "https://zmudzinski.me",
        }
        self.company = "@merixstudio"
    
    def greet(self, you: str) -> str:
        return f"Hello there {you}! My name is {self.name}. Nice to meet you!"
    
    @staticmethod
    def get_back_end_frameworks() -> Tuple[str]:
        return ("Django", "Flask", "FastAPI")
```
