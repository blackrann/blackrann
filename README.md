<div align="center">
  <pre>
    :::
  .::^YGP~ . . : . : .:.!J5BBP!
  .~7~. ~ : .^:~: .:YPGPJ7~.
  JB~ ~~.!? .! .^^Y: .~: ... :P#B7:.
  :5P: ^?Y^GJ 7Y J?JG^.77:~?~. ^~^7GBP:
  !BB. . :?P5#5 .GBP~:YBGBGP?~75!. .: .5#G5?:.
  </pre>
  
  <h1 align="center">blackrann</h1>
  
  <p align="center">
    Full-Stack Developer, passionate about security and efficiency.
  </p>
</div>

---

## 💻 class Attributes(blackrann):

```python
from typing import Tuple, List, Dict

class blackrann:
    """
    Base class for developer blackrann.
    """
    pass

class Attributes(blackrann):
    """
    Contains life attributes, contact information, and coding skills.
    """
    @property
    def contact(self) -> Tuple[str, str, str]:
        telegram = "@diegomunozzz"
        channel  = "https://t.me/swarveshop"
        email    = "yourmail@example.com"
        
        return telegram, channel, email

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['Spanish', 'English']
        age   = 20
        
        return langs, age
    
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['python', 'javascript'],
            'intermediate': ['go', 'bash'],
            'learning'    : ['c', 'c++', 'rust', 'typescript']
        }
        specialities  = [
            'reverse engineering',
            'fullstack development',
            'data science'
        ]
        ide           = ['vscode', 'pycharm', 'vim']
        pc            = {
            'Windows': {
                'custom': {
                    'processor': 'AMD Ryzen 7 5800X | 8 cores',
                    'ram'      : '16GB',
                    'gpu'      : 'NVIDIA 3070 | 5888 CUDA cores'
                }
            }
        }

        return langs, specialities, ide, pc
```
---

<h2 align="center">🛠️ Skills (Skill Icons)</h2> <div align="center"> <h3>Main Languages</h3> <img src="https://skillicons.dev/icons?i=python,javascript,go,rust,c,cpp" /> <h3>Frontend & Backend</h3> <img src="https://skillicons.dev/icons?i=html,css,react,nodejs,django,flask,nextjs" /> <h3>Databases & Cloud</h3> <img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,mongodb,docker,aws,azure" /> <h3>Tools & Others</h3> <img src="https://skillicons.dev/icons?i=vscode,vim,git,github,linux,bash,kali" /> </div>
