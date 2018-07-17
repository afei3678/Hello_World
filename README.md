# Hello_World
Guess game
import random
def roll_Redball(Numbers=5,points=None ):
    if points is None :
        points =[]
    while Numbers >0:
        point=random.randrange (1,36)
        points.append(point )
        Numbers=Numbers-1
    return points
points=roll_Redball()
print( "These red balls are:",points )
