# Figur
ab = rectangle(80, 100, "solid", "brown")
cd = rectangle(50, 10, "solid", "navy")
ef = circle(60, "solid", "green")
gh = overlay-xy(cd, -100, -50, ab)
overlay-xy(ef, -15, -5, gh)
