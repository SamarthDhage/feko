# feko

# dipole
# l = 0.059
# fmin = 2e9
# fmax = 3e9
# wr = 1.5e-3

# line: (upper) start: N= l/2 and (lower) start: N= -l/2
# mesh = wire segment = wr/2


# horn
# f = 970e6
# wr = c0/f
# w = 0.7 *wr
# d = 0.3 *wr
# h = wr
# r = 2*wr
# theta = 10*pi/180

# flare: h = r*cos(theta/2)
#        f1 = w + 2 *r* sin(theta/2)
#        f2 = d + 2 *r* sin(theta/2)


# yagi-uda
# fmin = 300e6
# fmax = 500e6
# f = 400e6
# wl = c0/f

# wl1 = 0.503*wl
# wl2 = 0.474*wl
# wl3 = 0.58*wl
# wl4 = 0.450*wl
# wl5 = 0.438*wl
# wl6 = 0.432*wl
# wl7 = 0.431*wl

# wr1= 0
# wr2 = 0.15 * wl
# wr3 = 0.216 * wl
# wr4 = 0.338 * wl
# wr5 = 0.508 * wl
# wr6 = 0.707 * wl
# wr7 = 0.961 * wl
# wr = 3e-3

# lin1 = N = -wl1/2 and wl1/2
# line2: N = -wl2/2 and wl2/2  & v = -wr2 and wr2
# line3 :  N = -wl3/2 and wl3/2 &  v = -wr3 and wr3
# .......
# line 7:  N = -wl7/2 and wl7/2 + v = -wr7 and wr7


# parabloic:
# f = 915e6
# fmin = 800e6
# fmax = 1100e6
# wr = 1e-3
# wl = c0/f

# line: N = -wl/r to wl/4
# wire properties = wire radius= wr

# construct parabloic
# radius = 0.1
# rotate u and v
# trasform  = v from 0 to -wl/4 


# horn
# f = 970e6
# wl = c0/f1
# w = 0.7 *wl
# d = 0.3 *wl
# h = wl
# r = 2 *wl
# theta =  10 *pi/180

# cuboid: 
# width, depth,height = w,d,h
