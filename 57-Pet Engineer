# Move your pet to the left or right button as needed.

def onHear(event):
    # Find the guards to listen to.
    archer = pet.findNearestByType("archer")
    soldier = pet.findNearestByType("soldier")
    # If event.speaker is the `archer`:
    if event.speaker == archer:
        # Move to the left button.
        pet.moveXY(32, 30)
    # If event.speaker is the `soldier`:
    if event.speaker == soldier:
        # Move to the right button.
        pet.moveXY(48, 30)

pet.on("hear", onHear)

# You don't have to change the code below.
# Your hero should protect the bottom right passage.
while True:
    enemy = hero.findNearestEnemy()
    if enemy:
        hero.attack(enemy)
