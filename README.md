# Super_mushroom
a = cylinder(pos=vec(0, 0, 0), axis=vec(0.04, -2, 0), length = 2.2, color = vec(239/255,219/255,174/255))
b = sphere(pos=vec(0, 0, 0), radius=2, color=color.red)
c = sphere(pos=vec(0, 0, 1.2), radius=1, color=color.white)
d = sphere(pos=vec(0.15, -2, 0), radius =1.01, color = vec(239/255,219/255,174/255))
e = sphere(pos=vec(-1.2, 0, -0.1), radius=1, color=color.white)
f = sphere(pos=vec(1.4, 0, 0.1), radius=1, color=color.white)
g = cylinder(pos=vec(0.5, -2, 0,2), axis=vec(3, 0, 0), length = 0.1, color=color.black)
h = cylinder(pos=vec(-0.3, -2.2, 0.1), axis=vec(3, 0, 0), length = 0.1, color=color.black)
for i in range(-23,23):
    box(pos = vec(i,-7,0))
    box(pos = vec(i,-8,0))
x = compound([a,b,c])
x.axis = vec(0,-1,0)
if ' ' in k : 
    for b in boxes :
        if 'd' in k :
        b.pos.x = b.pos.x + 0.1
        if 'a' in k :
        b.pos.x = b.pos.x - 0.1
        if 'w' in k :
        b.pos.y = b.pos.y + 0.1
        if 's' in k :
        b.pos.y = b.pos.y - 0.1
