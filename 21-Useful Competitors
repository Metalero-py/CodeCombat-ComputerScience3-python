# The coin field has been seeded with vials of deadly poison.
# Ogres are attacking, while their peons are trying to steal your coins!

while True:
    enemy = hero.findNearestEnemy()
    if enemy:
        # Attack the enemy only if the type is NOT equal to "peon".
        if enemy.type != "peon":
            hero.attack(enemy)
    item = hero.findNearestItem()
    if item:
        # Gather the item only if the type is NOT equal to "poison".
        if item.type != "poison":
            hero.moveXY(item.pos.x, item.pos.y)
        pass
