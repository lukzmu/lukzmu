```python
from corporate import Company, Role
from world.humanity import Person


class ComputerEngineer:
    """Sith Academy dropout, had to learn to code. Still waiting for the sequel."""

    def __init__(self) -> None:
        self._person = Person(
            name="Lukasz Zmudzinski",
            current_job=Company(
                name="STX Next",
                roles=(
                    Role.DATA_ENGINEER,
                    Role.COMMUNITY_COORDINATOR,
                    Role.TECHNICAL_RECRUITER,
                ),
            ),
            contact={
                "website": "https://zmudzinski.me",
                "github": "https://github.com/lukzmu",
                "linkedin": "https://www.linkedin.com/in/lukzmu",
            },
        )

    def hello_there(self) -> str:
        return f"General {self._person.name}. You are a bold one!"
```
