# Laundry Collection Challenge Answer

## Answer 1
```
# Code Here !
for i in range(2):
  agent.move("forward")
  pass

for i in range(3):
  agent.move("left")
  pass

pickupLaundry("back")

while (canWalkForward() == True):
  agent.move("forward")
  if (detectLaundry("right") == True):
    pickupLaundry("right")
    pass

agent.turn("right")

for i in range(4):
  agent.move("forward")
  pass

agent.turn("left")

for i in range(8):
  agent.move("forward")
  pass

agent.turn("left")

for i in range(4):
  agent.move("forward")
  pass

agent.turn("left")

agent.move("forward")

for i in range(7):
  walkDownstairs()
  pass

while (canWalkForward() == True):
  agent.move("forward")
  if (detectLaundry("left") == True):
    pickupLaundry("left")
    pass

pickupLaundry("forward")

for i in range(2):
  agent.turn("left")
  pass

while (canWalkForward() == True):
  agent.move("forward")
  if (detectLaundry("left") == True):
    pickupLaundry("left")
    pass

agent.turn("right")

for i in range(4):
  agent.move("forward")
  pass

agent.turn("left")

for i in range(8):
  agent.move("forward")
  pass

agent.turn("left")

for i in range(4):
  agent.move("forward")
  pass

agent.turn("left")

agent.move("forward")

for i in range(7):
  walkDownstairs()
  pass

while (canWalkForward() == True):
  agent.move("forward")
  if (detectLaundry("left") == True):
    pickupLaundry("left")
    pass

pickupLaundry("forward")

for i in range(2):
  agent.move("left")
  pass

for i in range(8):
  agent.move("forward")
  pass

agent.turn("left")

for i in range(9):
  agent.move("forward")
  pass

if (detectLaundry("forward") == False):
    placeLaundry("forward")
    pass

```
