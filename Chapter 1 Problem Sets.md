
# Chapter1
Skipped some trivial ones. 
## 1.2 Mathematical Preliminaries
### 1.2.1 Mathematical Induction
2.  The deduction is assuming $a^{(n-1)-1}=a^{n-2}=1$. So prove of $P(n+1)$ depends on $P(n)$ and $P(n-1)$. 
But $P(2)$ is false.

3. The proof should begin with $n=2$.  
Then: 

$$
\frac{1}{1\times2} \neq \frac{3}{2}-\frac{1}{2}
$$

7. $F(n) = \frac{1}{2}n(1+n)$   
    Proof: 
    $$
      F(n) = n^2 - F(n-1) 
             = n^2 - \frac{1}{2}n(n-1)
             = \frac{1}{2}n(n+1)
    $$


8. (a) When n is odd,
   $$
   n^3=\cdots+(n^2-2)+n^2+(n^2+2)+\cdots
   $$
   Sum n terms: $n^3=n*n^2$

   Similar for even n.

   (b) 
   $$
   1^3+2^3+\cdots+n^3=1+3+5+\cdots
   $$
   Right hand side has $\sum_{1}^n=n(n+1)/2$ terms, the last number is $n(n+1)-1$.
   $$
   \begin{align}
   1+3+5+\cdots+(n(n+1)-1) &=\frac{n(n+1) * (n(n+1)/2)}{2}=\frac{n^2(n+1)^2}{4} \\
   &=(1+2+\cdots+n)^2
   \end{align}
   $$
   

9.
$$
   (1-a)^{n+1}\ge(1-na)(1-a)=1-(n+1)a+na^2\ge1-(n+1)a
$$

11. 
$$
S(n) = (-1)^{n+1}\frac{n}{4n^2+1}
$$

### 1.2.3 Sums and Products

1. $-a_1$

3. Not a permutation mapping.

9. No

15/16. 
$$
  \sum_{j=0}^n jx^j = x\sum_{j=0}^n jx^{j-1} = x\sum_{j+1=0}^n (j+1)x^j = 
  x \sum_{j=0}^n (j+1)x^j
$$

17. $|S|$

20.
$$
  9\times\sum_{i=1}^n i10^{n-i}+n+1 = \sum_{i=0}^{n} 10^i
$$
$$
  (b-1)\times\sum_{i=0}^n (n-i)b^i+n+1 = \sum_{i=0}^n b^i
$$

25. Can't use an existing var name.

 