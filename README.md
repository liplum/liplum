## How to generate Liplum
```python
prompts = """
1 girl,green hair,deep green hoodie,deep green hoodie cap,
deep green clothes,plum,plum hairpin,plum-shaped decoration,
deep red eyes,white face,white neck,eyelashes,
blushed,Minecraft zombie,medium breasts
"""

# You can generate your own Liplum.
liplum = model(prompts)
liplum.activate().join(WORLD)

while True:
  liplum.working()
liplum.die() # no, please no😢
```
