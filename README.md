```python
import this as Python

from corporate import Company, Role
from world.humanity import Person


class ComputerEngineer:
    """Sith Academy dropout, had to learn to code. Still waiting for the sequel."""

    def __init__(self) -> None:
        self._person = Person(
            name="Łukasz Żmudziński",
            super_power=Python,
            current_job=Company(
                name="STX Next",
                roles=(
                    Role.BACKEND_TEAM_LEAD,
                    Role.SENIOR_BACKEND_ENGINEER,
                    Role.TECHNICAL_RECRUITER,
                ),
            ),
            contact={
                "website": "https://zmudzinski.sh",
                "github": "https://github.com/lukzmu",
                "linkedin": "https://www.linkedin.com/in/lukzmu/",
            },
        )

    def hello_there(self) -> str:
        return f"General {self._person.name}. You are a bold one!"
```
