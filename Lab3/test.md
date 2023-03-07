$$
w_{new} = w_{current} - \eta \frac{\partial L}{\partial w_{current}}
\\L = (y - t)^2
\\y = w_0 + w_1x_1+w_2x_1^2x_2+w_3e^{-x_1}+w_4\log(x_3)
\\L = (w_0 + w_1x_1+w_2x_1^2x_2+w_3e^{-x_1}+w_4\log(x_3) - t)^2
\\w_0^* = w_0 - \eta(2(y - t)(1)) = w_0 - \eta(2(y - t))
\\w_1^* = w_1 - \eta(2(y - t)(x_1)) = w_1 - \eta(2x_1(y - t))
\\w_2^* = w_2 - \eta(2(y - t)(x_1^2x_2) = w_2 - \eta(2x_1^2x_2(y - t))
\\w_3^* = w_3 - \eta(2(y - t)(e^{-x_1})) = w_3 - \eta(2e^{-x_1}(y - t))
\\w_4^* = w_4 - \eta(2(y - t)(\log(x_3)) = w_4 - \eta(2\log(x_3)(y-t))
$$