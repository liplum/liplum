## How to generate Liplum
```python
from PlumStar import *
Liplum = """
1 girl,green hair,deep green hoodie,deep green hoodie cap,
deep green clothes,plum,plum hairpin,plum-shaped decoration,
deep red eyes,white face,white neck,eyelashes,
blushed,Minecraft zombie,medium breasts
"""

whats_Liplum = lambda:print(Liplum)

# You can generate your own Liplum.
whats_Liplum()
liplum = reproduce(Liplum).activate().join(WORLD)
while True:
  liplum.working()
liplum.die() # no, please no😢
```
