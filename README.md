# Super_mushroom
a = cylinder(pos=vec(0, 0, 0), axis=vec(0.04, -2, 0), length = 2.2, color = vec(239/255,219/255,174/255))
b = sphere(pos=vec(0, 0, 0), radius=2, color=color.red, axis = vec(0,-1,0))
c = sphere(pos=vec(0, 0, 1.2), radius=1, color=color.white, axis = vec(0,-1,0))
d = sphere(pos=vec(0.04, -2, 0), radius =1.01, color = vec(239/255,219/255,174/255))
e = sphere(pos=vec(-1.2, 0, -0.1), radius=1, color=color.white)
f = sphere(pos=vec(1.2, 0, 0.1), radius=1, color=color.white)

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

