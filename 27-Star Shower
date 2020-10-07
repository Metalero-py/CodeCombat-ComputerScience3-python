# Pick up coins only if they are closer than 20m.
# Pick up all gems.

while True:
    item = hero.findNearestItem()
    distance = hero.distanceTo(item)
    # If the item's type is "gem"
    # OR the distance to the item less than 20 meters:
    if item.type == "gem" or distance < 20:
        # Move to item's position.
        hero.moveXY(item.pos.x, item.pos.y)
