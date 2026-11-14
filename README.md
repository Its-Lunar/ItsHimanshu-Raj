<div align="center">
  <h1>Himanshu Raj</h1>
  <p><b>BCA Student • Aspiring AI & Cybersecurity Engineer</b></p>
  <p><i>Building intelligent and secure systems, one project at a time.</i></p>

  <p>
    <a href="https://github.com/The-Lunar-Org">
      <img src="https://img.shields.io/badge/Org-The_Lunar_Org-181717?style=for-the-badge&logo=github&logoColor=white" alt="The Lunar Org" />
    </a>
    <a href="https://x.com/1tsRaj">
      <img src="https://img.shields.io/badge/X-@1tsRaj-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
    </a>
    <a href="https://instagram.com/1tsraj">
      <img src="https://img.shields.io/badge/Instagram-@1tsraj-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
    </a>
  </p>
</div>

---

### 🐍 About Me

```python
from dataclasses import dataclass, field


@dataclass
class Developer:
    name: str = "Himanshu Raj"
    education: str = "BCA Student"
    organization: str = "The Lunar Org"
    focus_areas: list[str] = field(
        default_factory=lambda: [
            "Machine Learning & Neural Networks",
            "Network Security & Ethical Hacking",
            "Privacy-First Defensive Systems",
        ]
    )

    def current_status(self) -> str:
        return "Learn. Build. Repeat."
