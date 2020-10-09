# Move right to reach the oasis,
# Move left to avoid nearby yaks.
while True:
    x = hero.pos.x
    y = hero.pos.y
    enemy = hero.findNearestEnemy()
    if enemy and hero.distanceTo(enemy) < 10:
        # Subtract 10 from x to move left.
        x = x - 10
        # Use moveXY to move to the new x, y position.
        hero.moveXY(x, y)
        pass
    else:
        # Add 10 to x to move right.
        x = x + 10
        # Use moveXY to move to the new x, y position.
        hero.moveXY(x, y)
        pass
