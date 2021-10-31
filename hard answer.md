# Bookshelf on the stairs Answer

## Suggest Answer
```
for i in range(2):
  if (detectBooks("right") == True):
    pickupBooks("right")
    agent.move("forward")
  pass

for i in range(5):
  agent.move("forward")
  pass

agent.turn("right")

for i in range(2):
  agent.move("forward")
  pass

agent.turn("right")

agent.move("forward")

for i in range(4):
  walkUpstairs()
  pass

agent.move("forward")

agent.turn("right")

for i in range(2):
  agent.move("forward")
  pass

agent.turn("right")

for i in range(3):
  walkUpstairs()
  pass

for i in range(4):
  agent.move("forward")
  pass

agent.turn("left")

for i in range(12):
  agent.move("forward")
  pass

agent.turn("left")

for i in range(2):
  agent.move("forward")
  pass

for i in range(2):
  placeBooks("right")
  agent.move("forward")
  pass
```

## Advance Answer
```
for i in range(2):
  if (detectBooks("right") == True):
    pickupBooks("right")
    agent.move("forward")
  pass

for i in range(5):
  agent.move("forward")
  pass

agent.turn("right")

for i in range(2):
  agent.move("forward")
  pass

agent.turn("right")

agent.move("forward")

for i in range(4):
  walkUpstairs()
  pass

agent.move("forward")

agent.turn("right")

for i in range(2):
  agent.move("forward")
  pass

agent.turn("right")

for i in range(3):
  walkUpstairs()
  pass

for i in range(4):
  agent.move("forward")
  pass

agent.turn("left")

for i in range(12):
  agent.move("forward")
  pass

agent.turn("left")

for i in range(2):
  agent.move("forward")
  pass

for i in range(2):
  if (detectBooks("right") == False):
    placeBooks("right")
    agent.move("forward")
  pass
```
