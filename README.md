# Adrian_System_Chess

This is a chess system that I made.If x is one players rating and y is the other players rating. It works like this. There is a number called expected result, which is x/(x+y) then, we calculate the expected result minus the real result(which is either 0, 0.5, or 1). Then, we multiply this by 20. We will add this to x to get a new value of x and subtract y by this to get the new value of y.  So, the formula for the new x(assuming r is the result of the game) is x+(((x/x+y)-r)*20) and for the new y it is y-(((x/x+y)-r)*20).
