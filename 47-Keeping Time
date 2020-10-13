# Use your new skill to choose what to do: hero.time

while True:
    # If it's the first 10 seconds, attack.
    if hero.time < 10:
        enemy = hero.findNearestEnemy()
        hero.attack(enemy)
        pass
    # Else, if it's the first 35 seconds, collect coins.
    elif hero.time < 35:
        coin = hero.findNearestItem()
        if coin:
            hero.moveXY(coin.pos.x, coin.pos.y)
        pass
    # After 35 seconds, attack again!
    else:
        enemy = hero.findNearestEnemy()
        hero.attack(enemy)
        pass
