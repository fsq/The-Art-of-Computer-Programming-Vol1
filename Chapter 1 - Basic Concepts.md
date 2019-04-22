


# Chapter1 Basic Concepts

[TOC]

# 1.1 Algorithms

​ Five features of algorithms:

- Finiteness
- Definiteness
- Input
- Output
- Effectiveness



# 1.2 Mathematical Preliminaries

## 1.2.1 Mathematical Induction

Upper bound of Fibonacci: 0, 1, 1, 2... (starting from $F_0$)
$$
  F_n \le \phi^{n-1}
$$
Where $\phi=(1+\sqrt{5})/2$, notice $\phi^2=1+\phi$.

## 1.2.2 Numbers, Powers and Logarithms

## 1.2.3 Sums and Products

1. The distribution law
$$
  \left( \sum_{R(i)} a_i \right) \left( \sum_{S(j)} b_j \right) = 
  \sum_{R(i)}\sum_{S(j)} a_i b_j
$$

2. Change of variable
$$
  \sum_{R(i)} a_i = \sum_{R(j)} a_j = \sum_{R(p(j))} a_{p(j)}
$$

$p(j)$ is a function of $j$ that represents a bijection between i and $p(j)$.
    
3. Interchanging order of summation:
$$
  \sum_{R(i)}\sum_{S(j)} a_{ij} = \sum_{S(j)}\sum_{R(i)} a_{ij}
$$

$$
  \sum_{R(i)}\sum_{S(i,j)} a_{ij} = \sum_{S'(j)}\sum_{R'(i,j)} a_{ij}
$$

4. Manipulating the domain
$$
  \sum_{R(j)}a_j + \sum_{S(j)}a_j = \sum_{R(j)\ or\ S(j)}a_j + 
                                    \sum_{R(j)\ and \ S(j)} a_j
$$

