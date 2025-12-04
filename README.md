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
    Desarrollador Full-Stack, con pasión por la seguridad y la eficiencia.
  </p>
</div>

---

## 💻 class Attributes(blackrann):

```python
from typing import Tuple, List, Dict

class blackrann:
    """
    Clase base para el desarrollador blackrann.
    """
    pass

class Attributes(blackrann):
    """
    Contiene atributos de vida, contacto y habilidades de codificación.
    """
    @property
    def contact(self) -> Tuple[str, str, str]:
        telegram = "t.me/TU_TELEGRAM"
        channel  = "t.me/TU_CANAL"
        email    = "tucorreo@ejemplo.com"
        
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
<h2 align="center">🛠️ Habilidades (Skill Icons)</h2> <div align="center"> <h3>Lenguajes Principales</h3> <img src="https://skillicons.dev/icons?i=python,javascript,go,rust,c,cpp" /> <h3>Frontend & Backend</h3> <img src="https://skillicons.dev/icons?i=html,css,react,nodejs,django,flask,nextjs" /> <h3>Bases de Datos & Cloud</h3> <img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,mongodb,docker,aws,azure" /> <h3>Herramientas & Otros</h3> <img src="https://skillicons.dev/icons?i=vscode,vim,git,github,linux,bash,kali" /> </div>
