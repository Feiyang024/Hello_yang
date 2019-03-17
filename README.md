# Hello_yang
#b->β
#UC case
Solve[{w1 + b F x + (b F (-t - x))/(2 (1 - v - y)) - (b F (b x (1 - v - y) + (1 - b) (t + x y)))/(2 (1 - v - y)) == 0, w2 - (1 - 2 b) F x + 1/2 F (-t - x) (b/(1 - v - y) - ((1 - b) x)/(t + x y)) - 1/2 F (b/(1 - v - y) - ((1 - b) x)/(t + x y)) (b x (1 - v - y) + (1 - b) (t + x y)) == 0,  v w1 == 0, w2 y == 0}, {y, v, w1, w2}]
#Solution
 {{y -> 0, v -> 0, w1 -> -(1/2) b F ((-2 + b) t + x - b x),  w2 -> -((F (-2 b t^2 + x^2 + b^2 (t^2 - x^2)))/(2 t))},
 {y -> 0, v -> (-1 + b)/(-2 + b) - t/x, w1 -> 0, w2 -> -(((-1 + b) F x^2)/((-2 + b) t))},
 {y -> 1, v -> -((t + x)/x),w1 -> 0, w2 -> 0},
 {y -> (-2 b t x - x^2 + b^2 x (t + x) + Sqrt[ b (2 - b - 2 b^2 + b^3) x^2 (t + x)^2])/((-1 + 2 b) x^2), v -> 0, w1 -> (F (-b x (t + x) + b^2 x (t + x) + Sqrt[ b (2 - b - 2 b^2 + b^3) x^2 (t + x)^2]))/(2 (t + x)),  w2 -> 0},
  {y -> -(( 2 b t x + x^2 - b^2 x (t + x) + Sqrt[b (2 - b - 2 b^2 + b^3) x^2 (t + x)^2])/((-1 + 2 b) x^2)),  v -> 0, w1 -> -((F (b x (t + x) - b^2 x (t + x) + Sqrt[b (2 - b - 2 b^2 + b^3) x^2 (t + x)^2]))/(2 (t + x))), w2 -> 0}}
  #choose 1,4 as the right solution
