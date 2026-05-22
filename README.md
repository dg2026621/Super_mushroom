# Super_mushroom
a = cylinder(pos=vec(-0.2, 0, 0), axis=vec(3, 0, 0), length = 2.5, color = vec(239/255,219/255,174/255))
b = sphere(pos=vec(0, 0, 0), radius=2, color=color.red)
c = sphere(pos=vec(0, 0, 1.3), radius=1, color=color.white)
d = sphere(pos=vec(0.15, -2, 0), radius =1.01, color = vec(239/255,219/255,174/255))
e = sphere(pos=vec(-1, 0, -0.1), radius=1, color=color.white)
f = sphere(pos=vec(-2, 0, -0.1), radius=1, color=color.white)

x = compound([a,b,c])
x.axis = vec(0,-1,0)
