## >>> sudo define -d Alexander
```python
class Alexander(Developer):
    def __init__(self):
        super().__init__()
        self.name = "Alexander"
        self.age = 18
        self.work = ["HSU Educational Foundation", "Navarre 3D Printing", "Independent Contractor"]
        self.education = ["Fort Walton Beach High School", "Florida Institute of Technology"]
        self.hobbies = ["Programming", "CAD Modeling", "Playing Saxophone"]

    def currentLocation(self):
        return "Fort Walton Beach, Florida"

    def nextLocation(self):
        return "Melbourne, Florida"

    def currently(self):
        return {
            "education": ["AP Calculus AB", "AP Physics", "PLTW Capstone Engineering"],
            "tinkering": ["Low Level Programming", "3D Printing", "CAD Modeling"]
        }
```
