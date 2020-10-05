# Tell the wizard the distance to the coming ogres.

# This function finds the nearest enemy and returns the distance to it.
# If there is no enemy, the function returns 0.
def nearestEnemyDistance():
    enemy = hero.findNearestEnemy()
    result = 0
    if enemy:
        result = hero.distanceTo(enemy)
    return result

while True:
    # Call nearestEnemyDistance() and
    # save the result in the variable enemyDistance.
    enemyDistance = nearestEnemyDistance()
    # If the enemyDistance is greater than 0: 
    if enemyDistance > 0:
        # Say the value of enemyDistance variable.
        hero.say(enemyDistance)
