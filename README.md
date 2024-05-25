```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class Dev:
    def __init__(self):
        self.name = "Valéria Blanch"
        self.role = "back-end dev"
        self.language_spoken = ["pt_BR", "en_UK"]

    def say_hi(self):
        print("thanks for dropping by")


me = Dev()
me.say_hi()
