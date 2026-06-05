# Super_mushroom
a = cylinder(pos=vec(0, 0, 0), axis=vec(0.04, -2, 0), length = 2.2, color = vec(239/255,219/255,174/255))
b = sphere(pos=vec(0, 0, 0), radius=2, color=color.red, axis = vec(0,-1,0))
c = sphere(pos=vec(0, 0, 1.2), radius=1, color=color.white, axis = vec(0,-1,0))
d = sphere(pos=vec(0.04, -2, 0), radius =1.01, color = vec(239/255,219/255,174/255))
e = sphere(pos=vec(-1.2, 0, -0.1), radius=1, color=color.white)
f = sphere(pos=vec(1.2, 0, 0.1), radius=1, color=color.white)

for i in range(-20,20):
 box(pos=vec(i,-3.5,0),color=vec(128/255,82/255,24/255))
 box(pos=vec(i,-4.5,0),color=vec(128/255,82/255,24/255))

for i in range(-13,-3):
 box(pos=vec(i,4,0))

for i in range(-4,3):
 box(pos=vec(i,15,0))
 
 for i in range(10,17):
  box(pos=vec(i,8,0))

sphere(pos=vec(0, 20, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(-1, 19, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(1, 19, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(0, 19, 0), radius=1, color=vec(132/255, 189/255, 241/255))

sphere(pos=vec(10, 30, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(9, 29, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(11, 29, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(10, 29, 0), radius=1, color=vec(132/255, 189/255, 241/255))

sphere(pos=vec(-20, 25, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(-19, 24, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(-21, 24, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(-20, 24, 0), radius=1, color=vec(132/255, 189/255, 241/255))

sphere(pos=vec(20, 20, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(19, 19, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(21, 19, 0), radius=1, color=vec(132/255, 189/255, 241/255))
sphere(pos=vec(20, 19, 0), radius=1, color=vec(132/255, 189/255, 241/255))

sphere(pos=vec(20, 30, 0), radius=3, color=vec(237/255, 205/255, 74/255))

x = compound([a,b,c,d,e,f])

while True :
    rate(100)
    k = keysdown()
    if ' ' in k : 
        x.pos = vec(0,0,0)
    if 'd' in k :
        x.pos.x = x.pos.x + 0.1
    if 'a' in k :
        x.pos.x = x.pos.x - 0.1
    if 'w' in k :
        x.pos.y = x.pos.y + 0.1
    if 's' in k :
        x.pos.y = x.pos.y - 0.1

