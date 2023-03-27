\begin{align}
    &\alpha_1 = Choose \space C_1 \\
    &\alpha_2 = Choose \space C_2 \\
    &\alpha_r = Reject \\
    &\begin{split}
    R(\alpha_1|x) & = 0*(P(C_1|x))+3*(P(C_2|x)) \\
    & = 3*(1-P(C_1|x)) 
    &\end{split} \\
    &R(\alpha_2|x)=2*(P(C_1|x)) \\
    &R(\alpha_r|x) = c \\
    &\text{Choose C1 if:} \\
    &R(\alpha_1|x) < c) => P(C_1|x)< \frac{c}{2} \\
    &\text{Otherwise, reject C1 and C2} \\\\
    &\text{1) if c = 0:} \\
    &\text{Choose C1 if P(C1|x) > 1 -> impossible} \\
    &\text{Choose C1 if P(C1|x) < 0 -> impossible} \\
    &\text{Therefore, always reject both C1 and C2} \\\\
    &\text{2) if c = 2:}\\
    &\text{Choose C1 if P(C1|x) > } \frac{1}{3} \\
    &\text{Choose C2 if P(C1|x) < 1} \\
    &\text{Now, we must compare C1 to C2:} \\
    &\text{When is } R(\alpha_1|x) < R(\alpha_2|x)? \\
    &\begin{split}
    3-3*(P(C_1|x)<2*(P(C_1|x)) \\
    3 < 5*(P(C_1|x)) \\
    P(C_1|x) > \frac{3}{5}
    &\end{split} \\ 
    &\text{Therefore, choose C1 if } P(C_1|x)>\frac{3}{5} \\
    &\text{Else, choose C2} \\\\
    &\text{3) if c = 1:} \\
    &\text{Choose C1 if } P(C_1|x) > \frac{2}{3} \\
    &\text{Choose C2 if } P(C_1|x) < \frac{1}{2} \\
    &\text{Else, reject both C1 and C2}
\end{align}
