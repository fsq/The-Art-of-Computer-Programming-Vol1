
# Chapter1
Skipped some trivial ones. 
## 1.2 Mathematical Preliminaries
### 1.2.1 Mathematical Induction
2. The deduction is assuming $a^{(n-1)-1}=a^{n-2}=1$. So prove of $P(n+1)$ depends on $P(n)$ and $P(n-1)$. 
  But $P(2)$ is false.

3. The proof should begin with $n=2$.  
  Then: $$
    \frac{1}{1\times2} \neq \frac{3}{2}-\frac{1}{2}
  $$

7. $F(n) = \frac{1}{2}n(1+n)$   
    Proof: 
    $$
      F(n) = n^2 - F(n-1) 
             = n^2 - \frac{1}{2}n(n-1)
             = \frac{1}{2}n(n+1)
    $$
  