import math
if n > 0:
    digits = int(math.log10(n))+1
elif n == 0:
    digits = 1
else:
    digits = int(math.log10(-n))+2 # +1 if you don't count the '-' 
