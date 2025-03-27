# Optimizing the Output from the Generalized Cobb-Douglas Production Function with Cost Constraints

## Contents

1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Objectives](#objectives)
4. [Methodology](#Methodology)
5. [Results](#results)
6. [Conclusion and Recommendations](#conclusion-and-recommendations)

---

## Introduction

In economics, a production function relates physical output of a production process to physical inputs or factors of production. It is a mathematical function that relates the maximum amount of output that can be obtained from a given number of inputs. Different inputs include generally the capital and labor  
 
The production function could be expressed in a general form such as $Q=f(x_1, x_2, \cdots, x_n)$, where $Q$ denotes the output of the firm, and $x_1, x_2, \cdots, x_n$ are the number of inputs of the firm such as factor inputs such as capital, labor, land or raw materials, etc {\color{blue}\cite{Mankiw}}. If $x_1=x_2=\cdots=x_n=0$ then $Q=0$ since we cannot produce anything without inputs.  The function  $f(x_1, x_2, \cdot, x_n)$ represents how inputs  $x_1,x_2, \cdots, x_n$  are used in the production process to create output from inputs. 

Some examples of the production functions in Economics are the following :
Linear production functions, Diminishing Returns Production Function, Fixed proportions, Perfect Substitutes Production Function and the  Cobb Douglas Production Functions.

Apart from production function, another important concept in economics is the economic cost. If a firm is producing output $Q$ based on $n$ inputs $x_1, x_2, \cdots, x_n$, where the prices of inputs are $r_1, r_2, \cdots, r_n$ then the total cost of the firm is given by $C=r_1x_1+r_2x_2+\cdots +r_nx_n$.  If the price for each unit in the output $Q$ is $Z$ then the total revenue will be given by $QZ$ and the profit will be given by $QZ-C$. To maximize the profit, the firm must minimize the cost of inputs, or must maximize the output.


### Why production functions?

- The production function is the central part of productiontheory, and there is theoretical interest in its estimates.
- Economists are often involved in describing activity at the level of a firm, an industry, or the economy as a whole through the production function approach
- he production function also gives information about increasing or decreasing returns to scale and the marginal products of labor and capital.


## Problem Statement

 A most familiar empirical production function found out by statistical methods is the Cobb-Douglas production function. In the Cobb-Douglas production function, there are two inputs, labour and capital, Cobb-Douglas production function takes the following mathematical form :
$Q=AL^{\alpha}K^{\beta}$, where where $Q$ is the manufacturing output, $L$ is the quantity of labour employed, $K$ is the quantity of capital employed, and $A, \alpha$ and $\beta$ are positive constants. One can observe that the form of Cobb-Douglas production function that it is a multiplicative production function which implies that both the factors are required to produce an output. That is, if amount of one factor is zero, no output can be produced.

In its general form, where more than two inputs are needed for the outputs, the Cobb-Douglass production is written as 

$$Q=A \prod_{i=1}^n L_{i}^{\alpha_i}, \quad L=\left(L_1, L_2, \cdots,  L_n\right)$$

where  $A$ is  an efficiency parameter which measures how efficiently inputs are transformed into output, given the current state of technology and management practices., $n$ is the total number of input variables (goods), $L_1, \cdots, L_n$ are the (non-negative) quantities of good consumed, produced, and $\alpha_{i}$ is an elasticity parameter for good $i$.

In this project, we consider  a firm that buys four inputs $K, L, R$, and $M$, for its production output $Q$ over a given period. The set data representing these variables is available. The Cobb-Douglass production of this firm is given by :

$$Q(K,L,R,M) = AK^{\alpha}L^{\beta}R^{\gamma}M^{\eta}$$

where $A$ is an efficient constant, and $\alpha, \beta,\gamma$ and $\eta$ are parameters between zero and one.

The first problem considered is to estimate the parameters  $\alpha, \beta, \gamma$ and $\eta$ by using the given data. The above equation can be written in the form 

$$\ln Q=\ln A+\alpha \ln K+\beta \ln L+\gamma \ln R +\eta \ln M$$

Hence the estimation of these parameters can be done with the least squares method.

The price of each unit of these inputs are $r_1, r_2, r_3$ and $r_4$, Rwandan francs respectively. The total cost to use in buying the inputs is given by $r_1K+r_2L+r_3R+r_4M$. Assuming that the firm has the amount $C$, which maybe used to buy the four inputs, it follows that we must have the equality $r_1K+r_2L+r_3R+r_4M=C$. 

Using the estimated parameters $\hat{\alpha}, \hat{\beta}, \hat{\gamma}, \hat{\eta}$,  the second problem considered is to maximize the production under this constraint of available cost. Mathematically, we consider the problem:

$$
\begin{array}{ccc}
\text{Optimize} & Q(K,L,R,M) = A K^{\hat{\alpha}} L^{\hat{\beta}} R^{\hat{\gamma}} M^{\hat{\eta}} \\
\text{Subject to} & r_1 K + r_2 L + r_3 R + r_4 M = C.
\end{array}
$$

We will solve this problem by using the Lagrange multiplier method, since it is a nonlinear optimization problem. The obtained results will be then interpreted in terms of economics. 

Given a value of the production function $Q_0$, and the price of each unit of the outputs $K,L,R,M$ and the available amount $C$, we finally determine an optimal combination of these inputs, by solving the optimization problem:

$$
\begin{array}{ccc}
\text{Optimize} & r_1K + r_2L + r_3R + r_4M = C \\
\text{Subject to} & A K^{\hat{\alpha}} L^{\hat{\beta}} R^{\hat{\gamma}} M^{\hat{\eta}} = Q_0.
\end{array}
$$

The above problems can be extended by increasing the number of constrains, which can be linear or non-linear


## Objectives

 **The Primary Objective** of this research is to optimize the output from the generalized Cobb-Douglass production function in a given company, and to determine an optimal combination of inputs given a fixed amount of units in  the production function.
 **The specific objectives of this study are the following:**:
 - To estimate the parameters of the generalized Cobb-Douglass production function in a firm with more than two inputs.
 - To determine how much output to produce from the Cobb-Douglas production function for a given amount of inputs.
 - To know the optimal output from the Cobb-Douglass production function, and what combination of inputs to be used given the price of inputs.

## Methodology

In this final research project, we have used the following methodology in order to achieve the specified objectives:
 
 - **Problem formulation** We started by formulating the problem to be considered in this final research project. The formulation of the problem was done by taking into consideration the following questions:

 1. What are the methods used to estimate parameters of the Cobb-Douglass production function?
 2. In a given firm, how much output to produce from the Cobb-Douglas production function for a given amount of inputs?
 3. Given an amount of output from the Cobb-Douglass production function, what is the best combination inputs to be used given the price of each unit of inputs?
 
- **Theoretical review** We have started by reading  the theory related to optimization problems. Namely, different types of problems in optimization such as linear and non-linear, constrained and non-constrained, and different methods that are used to solve these types of problem. A particular attention, was paid to the Lagrange multiplier method, Karush-Kuhn Tucker conditions and the method of Least-squares. Different documents related to optimization methods were consulted.
- **Designing the research project** The primary goal of this final research project, is to optimize the output from the generalized Cobb-Douglass production function in a given company where more than two inputs are available while accounting for cost linear constraints. Different steps that are used to achieve this goal were discussed and the methods to be used. The topic was suggested by my supervisor and different steps to follows were fixed in a close collaboration with me.
- **Data collection and data analysis** The data used in this final project are the secondary data that we have taken from a book of statistics. In these data, we have taken the columns as the values of inputs, where a period of twelve months was considered. To estimate the parameters, the Python software was used.

**Example of a Cobb-Douglass production function**:

- Here's an example of a production function: $Q = K^{0.3} \cdot L^{0.7}$.
- Here, $Q$ represents the total output, $K$ represents the amount of capital used in production, and $L$ represents the amount of labor used in production. 
- The exponents $0.3$ and $0.7$ represent the elasticity of output with respect to capital and labor, respectively.
- If we have $10$ units of capital and $20$ units of labor, we can calculate the total output as follows:
  
$$Q =  10^{0.3} \cdot 20^{0.7}=16.245$$


## Results

### Formulation of the real life problem under consideration

The  Cobb-Douglas production function allows firms to determine the most efficient combination of inputs to produce a given level of output, while taking into account the constraint that the inputs used are limited by a fixed budget or other constraints.
 
Consider a a firm manufacturing products, where the vector $Q$ of outputs over a period of twelve months is given. The production units for each period is shown in the table. The production of this firm depends on four inputs, which are denoted by 
  $K, L, M$ and $N$. The data used here where taken from the book {\color{blue}\cite{Douglass}}.
 The units for each input in each month are also shown in the table. So, the data set is shown in the following table:

 | Months |   Q  |  K  |  L  |  M  |  N  |
|--------|----:|---:|---:|---:|---:|
| Jan    | 240 | 25 | 24 | 91 | 100 |
| Feb    | 236 | 31 | 21 | 90 |  95 |
| Mar    | 270 | 45 | 24 | 88 | 110 |
| Apr    | 274 | 60 | 25 | 87 |  88 |
| May    | 301 | 65 | 25 | 91 |  94 |
| Jun    | 316 | 72 | 26 | 94 |  99 |
| Jul    | 300 | 80 | 25 | 87 |  97 |
| Aug    | 296 | 84 | 25 | 86 |  96 |
| Sep    | 267 | 75 | 24 | 88 | 110 |
| Oct    | 276 | 60 | 25 | 91 | 105 |
| Nov    | 288 | 50 | 25 | 90 | 100 |
| Dec    | 261 | 38 | 23 | 89 |  98 |

Using this data, we want to estimate the coefficients of the Cobb-Douglass production function and then obtain the mathematical expression relating the output and the inputs for this firm.

### Estimating the parameters in the Cobb-Douglass production function

Consider the expression of the Cobb-Douglass production function with four inputs.

 $$Q(K,L,R,M) = AK^{\alpha}L^{\beta}M^{\gamma}N^{\eta}$$

In order to estimate the parameters  $\alpha, \beta, \gamma$ and $\eta$ by using the given data, The above equation  can be written in the form 

$$\ln Q=\ln A+\alpha \ln K+\beta \ln L+\gamma \ln M +\eta \ln N$$

Letting  $\ln Q = y,  \ln A = C,  \ln K = x_1,  \ln L = x_2,  \ln M = x_3$ and $\ln N = x_4$, the previous equation can be written as a multiple linear regression model:


$$y = C+\alpha x_1 + \beta x_2 +\gamma x_3 + \eta x_4$$

Computing the natural logarithm for each of the above inputs and output, we obtain the following table:

## Data Table

| \$ln(Q)$ | \$ln(K)$ | \$ln(L)$ | \$ln(M)$ | \$ln(N)$ |
|-----------|-----------|-----------|-----------|-----------|
| y         | x₁        | x₂        | x₃        | x₄        |
| 5.48      | 3.22      | 3.18      | 4.51      | 4.61      |
| 5.46      | 3.43      | 3.04      | 4.50      | 4.60      |
| 5.60      | 3.81      | 3.18      | 4.48      | 4.70      |
| 5.61      | 4.09      | 3.22      | 4.47      | 4.62      |
| 5.71      | 4.17      | 3.22      | 4.51      | 4.70      |
| 5.76      | 4.28      | 3.26      | 4.54      | 4.79      |
| 5.70      | 4.38      | 3.22      | 4.47      | 5.48      |
| 5.69      | 4.43      | 3.22      | 4.45      | 4.56      |
| 5.59      | 4.32      | 3.18      | 4.48      | 4.70      |
| 5.62      | 4.09      | 3.22      | 4.51      | 4.65      |
| 5.66      | 3.91      | 3.22      | 4.50      | 5.44      |
| 5.56      | 3.64      | 3.14      | 4.49      | 4.58      |


The  estimation of the parameters in Equation multiple linear regression model can be done with the least squares method. This can be done in Excel, Statistical Package for Social Sciences (SPSS) or any other statistical software. In our case we use the SPSS to estimate the parameters of Equation multiple linear regression model. The output tables should include Model summary  table that provides an overview of the regression model including the R-squared value which measures the proportion of variance in the dependent variable that is explained by the independent variables, ANOVA table that provides the results of the analysis of variance (ANOVA) for the regression model, including the F-test for the overall significance of the model and Coefficients   table that provides the estimates of the regression coefficients (i.e., the beta weights) for each independent variable, as well as their standard errors, t-values, and p-values.
Basing on our aim, only Model summary and Coefficients tables we shall leave with and they look like the following:

1. ![TABLE1](https://github.com/user-attachments/assets/408e2b62-02e2-4d68-b76f-8fab8510d36f)
2. ![TABLE2](https://github.com/user-attachments/assets/0f7f3f3b-e54d-4422-b2b2-cb854596ca39)

The $1^{\text{st}}$ table shows that since $R^2 = 0.884$. The value of $0.884$ indicates that $88.4 \%$ of the total outputs (or observed) variation in $\ln Q$  is attributable to, or explained by, the  regression function or the regressors inputs $(\ln K, \ln L, \ln M, \ln N)$ 

From the $2^{\text{nd}}$ table in column named $B$ we obtain the coefficients of the model which are given as follows:

$$
\begin{align*}
\text{Regression coefficients} & & \text{Cobb-douglass positive constants}\\
\begin{cases}
C = - 0.265 \\
\alpha = 0.147\\
\beta = 0.521\\
\gamma = 0.763\\
\eta = 0.044
\end{cases}
& \Longrightarrow & 
\begin{cases}
A = e^{- 0.265} = 0.768 \\
\alpha = 0.147\\
\beta = 0.521\\
\gamma = 0.763\\
\eta = 0.044
\end{cases}
\end{align*}
$$

Basing on the necessary information about the output and generalized analysis we have seen we can estimate the multiple linear regression model as

$$
\begin{equation}
y = -0.265 + 0.147x_1 + 0.521x_2 + 0.763x_3 + 0.044x_4
\end{equation}
$$

Finally the linear regression model has helped us to find the positive constants of Cobb-Douglass coefficients. That is, from Equation \ref{Cobb4}, we obtain the estimation of the Cobb-Douglass production function of the firm.

$$
\begin{equation}
Q = 0.768 \cdot K^{0.147} \cdot L^{0.521} \cdot M^{0.763} \cdot N^{0.044}
\end{equation}
$$

This estimated production function can be used to predict the output of the firm once the quantity for each inputs is known.

## Optimization of the production function under linear constraints

We now assume that the firm can buy the four inputs $K, L, M$, and $N$ at a per-
unit price of \$ $50$, \$ $30$, \$ $25$ and  \$ $20$, respectively, and operate with the estimated production function $Q = 0.768 \cdot K^{0.147} \cdot L^{0.521} \cdot M^{0.763} \cdot N^{0.044}$. The problem which is considered now, it to know the optimum value of outputs that can make a total cost of \$ $30,000$. This problem can mathematically written as follows:

$$
\begin{eqnarray}
\begin{array}{ccc}
\text{Optimize} & 0.768 \cdot K^{0.147} \cdot L^{0.521} \cdot M^{0.763} \cdot N^{0.044}\\
\text{Subject to } &  50K + 30L +25M + 20N)=30,000 
\end{array}
\end{eqnarray}
$$

The relevant Lagrange function is

$$\mathscr{L} = 0.768  K^{0.147}  L^{0.521}  M^{0.763}  N^{0.044} -\lambda (30,000 - 50K - 30L - 25M - 20N)$$

Differentiating to find stationary points, and setting equal to zero, we obtain the system of equations to solve:

$$\dfrac{\partial \mathscr{L}}{\partial K} = 0.112896K^{-0.853}L^{0.521}M^{0.763}N^{0.044} -50\lambda = 0  \hspace{1.5in}(1)$$

$$\dfrac{\partial \mathscr{L}}{\partial L} = 0.400128K^{0.147}L^{-0.479}M^{0.763}N^{0.044} -30\lambda = 0  \hspace{1.5in}(2)$$

$$\dfrac{\partial \mathscr{L}}{\partial M} = 0.585984K^{0.147}L^{0.521}M^{-0.237}N^{0.044} -25\lambda = 0  \hspace{1.47in}(3)$$

$$\dfrac{\partial \mathscr{L}}{\partial N} = 0.033792K^{0.147}L^{0.521}M^{0.763}N^{-0.956} -20\lambda = 0  \hspace{1.5in}(4)$$

$$\dfrac{\partial \mathscr{L}}{\partial \lambda} = 30,000 - 50K - 30L - 25M - 20N = 0  \hspace{1.8in}(5)$$

To solve the above non- linear simultaneous equations we can use some software such as Matlab, Python or others mathematical software. The following visual shows the python codes of our non linear equations and related output.

![python_output_2](https://github.com/user-attachments/assets/d3dc725b-eaa7-40ad-87e7-c2d2af813e83)

Now from the above output it shown that the value of our inputs should be the following stationary point.

$$
\begin{cases}
K = 59.7966102\\
L = 353.220339\\
M = 620.745763\\
N = 44.7457627\\
\lambda = 0.234078507
\end{cases}
$$

To test the nature of the stationary points, we need to find the bordered Hessian matrix. For  test of  stationary points, write the bordered Hessian matrix 

  $$\frac{\partial^2 G}{\partial K^2}  = \lambda \left(0.096630976K^{-1.853}L^{0.521}M^{0.763}N^{0.044}\right)$$
  
 $$\frac{\partial^2 G}{\partial K \partial L}  = \lambda \left(-0.056418048K^{-0.853}L^{-0.479}M^{0.763}N^{0.044}\right) $$
 
$$\frac{\partial^2 G}{\partial K \partial M}  = \lambda \left(-0.086139648K^{-0.853}L^{0.521}M^{-0.237}N^{0.044}\right)$$

 $$\frac{\partial^2 G}{\partial K \partial N}   = \lambda \left(-0.004967424K^{-0.853}L^{0.521}M^{0.763}N^{-0.956}\right)$$
 
$$\frac{\partial^2 G}{\partial L^2}   =  \lambda \left(0.191661312K^{0.147}L^{-1.479}M^{0.763}N^{0.044}\right)$$

$$\frac{\partial^2 G}{\partial L \partial M}   = \lambda \left(-0.305297664K^{0.147}L^{-0.479}M^{-0.237}N^{0.044}\right)$$

$$\frac{\partial^2 Q}{\partial L \partial N}   = \lambda \left(-0.017605632K^{0.147}L^{-0.479}M^{0.763}N^{-0.956}\right)$$

$$\frac{\partial^2 G}{\partial M^2}   =  \lambda \left(0.138878208K^{0.147}L^{0.521}M^{-1.237}N^{0.044}\right)$$

$$\frac{\partial^2 G}{\partial M \partial N}  = \lambda \left(-0.025783296K^{0.147}L^{0.521}M^{-0.237}N^{-0.956}\right)$$

$$\frac{\partial^2 G}{\partial N^2} = \lambda \left(0.032305152K^{0.147}L^{0.521}M^{0.763}N^{-1.956}\right)$$

Thus the matrix $\pmb{W}$ which is symmetric is given by

$$
W = \begin{bmatrix}
\dfrac{\partial^2 G}{\partial K^2} & \dfrac{\partial^2 G}{\partial K \partial L} & \dfrac{\partial^2 G}{\partial K \partial M} & \dfrac{\partial^2 G}{\partial K \partial N}\\\\
\dfrac{\partial^2 G}{\partial L \partial K} & \dfrac{\partial^2 G}{\partial L^2} & \dfrac{\partial^2 G}{\partial L \partial M} & \dfrac{\partial^2 G}{\partial L \partial N}\\\\
\dfrac{\partial^2 G}{\partial M \partial K} & \dfrac{\partial^2 G}{\partial M \partial L} &   \dfrac{\partial^2 G}{\partial M^2}  & \dfrac{\partial^2 G}{\partial M \partial N}\\\\
\dfrac{\partial^2 G}{\partial N \partial K} & \dfrac{\partial^2 G}{\partial N \partial L} & \dfrac{\partial^2 G}{\partial N \partial M} & \dfrac{\partial^2 G}{\partial N^2} 
\end{bmatrix}
$$

$$=\begin{bmatrix}                1.82179884	& -0.180066521	& -0.156440771 &	-0.00051321\\\\
-0.180066521 &	0.103557185	& -0.093864463	& -0.07509157\\\\
-0.156440771 &	-0.093864463 &	0.024296503	 & -0.062576309\\\\
-0.00051321 &	-0.07509157	& -0.062576309 &	1.087690018
\end{bmatrix}$$

and

$$
P= \begin{bmatrix}
50 & 30 & 25 & 20\\
\end{bmatrix}
$$

Therefore bordered Hessian matrix is given by :

 $$
 H^B = \begin{bmatrix}
0 & 50 & 30 & 25 & 20\\\\
50 & -0.167530077 & 0.016558666 &	0.014386075	& 1.85404E-05\\\\
30 & 0.016558666	& -0.009522974	& 0.008631645 & 0.006905316\\\\
25 & 0.014386075 & 0.008631645 &	-0.002234272 & 0.00575443\\\\
20 & 1.85404E-05 & 0.006905316 & 0.00575443 & -0.100022455
\end{bmatrix}
$$

In the optimization problem \ref{Cobb6}, we have  $n = 4, m = 1$ and $2m + 1 = 3$. Starting from the principal minor determinant of order $3$, we check $n-m = 3$ principal minor determinants.  Accordingly, we have:


  $$
  |\Delta_3| = \begin{vmatrix}
0 & 50 & 30\\\\
50 & -0.167530077 & 0.016558666\\\\
30 & 0.016558666 & -0.009522974
\end{vmatrix} = 224.260502
$$

$$
|\Delta_4| = \begin{vmatrix}
0 & 50 & 30	& 25\\\\
50 & -0.167530077 & 0.016558666	& 0.014386075\\\\
30 & 0.016558666 & -0.009522974	& 0.008631645\\\\
25 & 0.014386075 & 0.008631645	& -0.002234272
\end{vmatrix} = -4.553034416
$$

  $$
  |\Delta_5| = \begin{vmatrix}
0 & 50 & 30 & 25 & 20\\\\
50 & -0.167530077 & 0.016558666 &	0.014386075	& 1.85404E-05\\\\
30 & 0.016558666 & -0.009522974	& 0.008631645 & 0.006905316\\\\
25 & 0.014386075 & 0.008631645 & -0.002234272 & 0.00575443\\\\
20 & 1.85404E-05 & 0.006905316 & 0.00575443 & -0.100022455\\
\end{vmatrix} = 0.484104347
$$

It follows from the rule discussed in Section \ref{Lagrange}  that the obtained values of $K, L, M$ and $N$ gives the maximum output level of the firm. Hence the maximum  of the firm under the given constraint is given by:

$$
\begin{equation*}
Q_{max}(K,L,M,N) = 4,760.91877869938  \quad \text{units}
\end{equation*}
$$


###  Optimum combination of inputs for a determined output

We consider the same firm with the same production function, where four inputs are required, with the production function.

$$Q = 0.768 \cdot K^{0.147} \cdot L^{0.521} \cdot M^{0.763} \cdot N^{0.044}$$

The inputs prices per unit are the same as in the previous section. We assume that the company want an output of $1,200$ units, and the question is to find the optimum way of producing these units.


In this case the objective function to optimize is given by $TC = 50K + 30L +25M + 20N$, and the constraint is as follows: $Q = 0.768 \cdot K^{0.147} \cdot L^{0.521} \cdot M^{0.763} \cdot N^{0.044} = 1,200$

Accordingly, the mathematical formulation of this problem is then given as follows:

$$
\begin{eqnarray}
\begin{array}{ccc}
\text{Optimize} & 50K + 30L +25M + 20N\\
\text{Subject to } &  0.768 \cdot K^{0.147} \cdot L^{0.521} \cdot M^{0.763} \cdot N^{0.044} = 1,200 
\end{array}
\end{eqnarray}
$$


The corresponding Lagrange function is therefore

$$G = 50K + 30L +25M + 20N + \lambda (1,200 - 0.768  K^{0.147}  L^{0.521}  M^{0.763} N^{0.044})$$

Differentiating to get stationary points.

To find the partial derivatives of $G$ with respect to each of the variables $K$, $L$, $M$, $N$, and $\lambda$, we can differentiate each term in $G$ separately.

$$\frac{\partial G}{\partial K} = 50 + \lambda\left(-0.112896K^{-0.853}L^{0.521}M^{0.763}N^{0.044}\right) = 0 \hspace{1.5in}(1)$$

$$\frac{\partial G}{\partial L} = 30 + \lambda\left(-0.400128K^{0.147}L^{-0.479}M^{0.763}N^{0.044}\right) = 0 \hspace{1.5in}(2)$$

$$\frac{\partial G}{\partial M} = 25 + \lambda\left(-0.585984K^{0.147}L^{0.521}M^{-0.237}N^{0.044}\right) = 0 \hspace{1.47in}(3)$$

$$\frac{\partial G}{\partial N} = 20 + \lambda\left(-0.033792K^{0.147}L^{0.521}M^{0.763}N^{-0.956}\right) = 0 \hspace{1.5in}(4)$$

$$\frac{\partial G}{\partial \lambda} = 1,200 - 0.768K^{0.147}L^{0.521}M^{0.763}N^{0.044} = 0 \hspace{2in}(5)$$

Solving the above nonlinear system of equations we have to use python as the previous one.

![python_output_3](https://github.com/user-attachments/assets/75d763a2-d140-4f85-98f5-e3d015b85788)

Now from the above output, optimum values  should be the following:

$$
\begin{cases}
K = 23.49131857\\
L = 138.76391129\\
M = 243.86225946\\
N = 17.57853771\\
\lambda = 6.65853701
\end{cases}
$$

Checking that these values do give the required 1,200 units of output:

$$Q = 0.768 (23.49131857)^{0.147} (138.76391129)^{0.521} (243.86225946)^{0.763} (17.57853771)^{0.044} = 1,200$$

For  test of  stationary points, write the bordered Hessian matrix 


 $$\frac{\partial^2 G}{\partial K^2}  = \lambda \left(0.096630976K^{-1.853}L^{0.521}M^{0.763}N^{0.044}\right)$$ 
 
 $$\frac{\partial^2 G}{\partial K \partial L}  = \lambda \left(-0.056418048K^{-0.853}L^{-0.479}M^{0.763}N^{0.044}\right) $$
 
$$\frac{\partial^2 G}{\partial K \partial M}  = \lambda \left(-0.086139648K^{-0.853}L^{0.521}M^{-0.237}N^{0.044}\right)$$

 $$\frac{\partial^2 G}{\partial K \partial N}   = \lambda \left(-0.004967424K^{-0.853}L^{0.521}M^{0.763}N^{-0.956}\right)$$
 
$$\frac{\partial^2 G}{\partial L^2}   =  \lambda \left(0.191661312K^{0.147}L^{-1.479}M^{0.763}N^{0.044}\right)$$

$$\frac{\partial^2 G}{\partial L \partial M}   = \lambda \left(-0.305297664K^{0.147}L^{-0.479}M^{-0.237}N^{0.044}\right)$$

$$\frac{\partial^2 Q}{\partial L \partial N}   = \lambda \left(-0.017605632K^{0.147}L^{-0.479}M^{0.763}N^{-0.956}\right)$$

$$\frac{\partial^2 G}{\partial M^2}   =  \lambda \left(0.138878208K^{0.147}L^{0.521}M^{-1.237}N^{0.044}\right)$$

$$\frac{\partial^2 G}{\partial M \partial N}  = \lambda \left(-0.025783296K^{0.147}L^{0.521}M^{-0.237}N^{-0.956}\right)$$

$$\frac{\partial^2 G}{\partial N^2} = \lambda \left(0.032305152K^{0.147}L^{0.521}M^{0.763}N^{-1.956}\right)$$

Thus the matrix $W$ which is symmetric is given by

$$
W = \begin{bmatrix}
\dfrac{\partial^2 G}{\partial K^2} & \dfrac{\partial^2 G}{\partial K \partial L} & \dfrac{\partial^2 G}{\partial K \partial M} & \dfrac{\partial^2 G}{\partial K \partial N}\\\\
\dfrac{\partial^2 G}{\partial L \partial K} & \dfrac{\partial^2 G}{\partial L^2} & \dfrac{\partial^2 G}{\partial L \partial M} & \dfrac{\partial^2 G}{\partial L \partial N}\\\\
\dfrac{\partial^2 G}{\partial M \partial K} & \dfrac{\partial^2 G}{\partial M \partial L} &   \dfrac{\partial^2 G}{\partial M^2}  & \dfrac{\partial^2 G}{\partial M \partial N}\\\\
\dfrac{\partial^2 G}{\partial N \partial K} & \dfrac{\partial^2 G}{\partial N \partial L} & \dfrac{\partial^2 G}{\partial N \partial M} & \dfrac{\partial^2 G}{\partial N^2} 
\end{bmatrix}
$$

$$=\begin{bmatrix}                
1.82179884	& -0.180066521	& -0.156440771 &	-0.00051321\\\\
-0.180066521 &	0.103557185	& -0.093864463	& -0.07509157\\\\
-0.156440771 &	-0.093864463 &	0.024296503	 & -0.062576309\\\\
-0.00051321 &	-0.07509157	& -0.062576309 &	1.087690018
\end{bmatrix}$$


and 

$$P= \begin{bmatrix}
7.509157031 &	4.505494218	& 3.754578515 &	3.003662811\\
\end{bmatrix}
$$

Therefore bordered Hessian matrix is given by 

 $$
 H^B = \begin{bmatrix}
0 & 7.509157031	& 4.505494218 &	3.754578515 &	3.003662811\\\\
7.509157031 &	1.82179884	& -0.180066521 &	-0.156440771	& -0.00051321\\\\
4.505494218	& -0.180066521	& 0.103557185 &	-0.093864463	& -0.07509157\\\\
3.754578515 &	-0.156440771	& -0.093864463	& 0.024296503	& -0.062576309\\\\
3.003662811 &	-0.00051321	& -0.07509157	& -0.062576309	& 1.087690018
\end{bmatrix}
$$


Here $n = 4, m = 1, 2m + 1 = 3$. Starting from the principal minor determinant of order 3, we check $n-m = 3$ principal minor determinants. 
Note that

  $$
  |\Delta_3| = \begin{vmatrix}
0 &	7.509157031 &	4.505494218 \\\\
7.509157031	& 1.82179884	&-0.180066521\\\\
4.505494218	& -0.180066521	& 0.103557185
\end{vmatrix} =-55.00507821
$$

$$
|\Delta_4| = \begin{vmatrix}
0 &	7.509157031	& 4.505494218 &	3.754578515\\\\
7.509157031	& 1.82179884	& -0.180066521 &	-0.156440771\\\\
4.505494218 &	-0.180066521 &	0.103557185 &	-0.093864463\\\\
3.754578515	& -0.156440771	& -0.093864463 &	0.024296503
\end{vmatrix} = -12.14391062
$$

  $$
  |\Delta_5| = \begin{vmatrix}
0 &	7.509157031 &	4.505494218	& 3.754578515 & 3.003662811\\\\
7.509157031 &	1.82179884 &	-0.180066521 &	-0.156440771 &	-0.00051321\\\\
4.505494218 &	-0.180066521 &	0.103557185	& -0.093864463 &	-0.07509157\\\\
3.754578515 &	-0.156440771 &	-0.093864463 &	0.024296503	& -0.062576309\\\\
3.003662811 &	-0.00051321	& -0.07509157 &	-0.062576309 &	1.087690018
\end{vmatrix}=-14.04190435
$$


It is shown that all $|\Delta_3|, |\Delta_4|, \text{and } |\Delta_5|$ have sign of $(-1)^1$ Thus the values for $K, L, M, N$ determine the the minimum point. Accordingly, the cheapest cost level for producing this output will therefore be $TC=50(23.49131857)+ 30(138.76391129) +25(243.86225946) + 20(17.57853771) =$ \$ $11,785.6105079$

 ## Results interpretation
In this section we are proud to expound the results found. First of all basing on one of the above section  with our Cobb-Douglass production function $Q$ where $\alpha + \beta + \gamma + \eta$ is given by $0.147172253 + 0.520665159 + 0.762692634 + 0.044302849
= 1.474832894  > 1$, which means that we have increasing returns to scale (i.e 1\% increase in all inputs will lead to $(1.01^{0.147}\cdot1.01^{0.521}\cdot1.01^{0.763}\cdot1.01^{0.044} -1) \approx 1.478\%$  increase in output, assuming that all other factors remain constant).
 Again, since the efficient parameter $A = 0.768$ implies that the inputs used in the production process are being used with an efficiency of $76.8\%$ of their maximum potential.

According to the results from Section1 and Section2, we can have the following points related to the considered firm:

- The firm had \$ $30,000$ and wanted to optimize the out put $Q$ with the relevant inputs of $K, L, M$ and $N$ where the price of each was \$ $50$, \$ $30$, \$ $25$, \$ $20$ respectively. Based on the results found, the inputs should be 

$K = 59.7966102, L = 353.220339, M = 620.745763, N = 44.7457627$ 

Where  the maximum output $Q$ that a company should produce is $4,760.91877869938$ units.

- The firm  wanted to optimize the cost of similar inputs as above. So as to produce $1,200$  units. Then the inputs should be 
$K = 23.49131857, L = 138.76391129, M = 243.86225946, N = 17.57853771$ and the cheapest cost should be \$ $11,785.6105079$

We note the the same method works even if we have a firm with more than four inputs and any given number of linear and non-linear constraints.



## Conclusion and Recommendations

### Conclusion

In this work we have used the method of using Lagrange multipliers which is include among the best methods that act as  a useful tool for optimizing the production function. 

The main problem which was under consideration was to optimize the output from the generalized Cobb-Douglass production function with cost linear  constraints. We have considered a firm with four inputs that are used to get output. Namely,  we have had the data containing 1 kind of output and 4 kind of inputs in 12 months, we have first computed all relevant positive constants using different tools including SPSS in order to estimate the corresponding parameters of  the Cobb-Douglas production function. After knowing the cost of each input unit and related purchasing power for all inputs but aiming to maximize the output, and again after knowing the outputs units that a company wants to produce  aiming to minimize the cost, then by setting up the Lagrange function and solving for the optimal values of the inputs and the Lagrange multiplier, we have been able for  the firm to make production decisions that maximize efficiency  and minimize the cost with purpose of profitability as well.

In this study, we have also determined the possible optimal combination of inputs under the constraint of a given amount of output to produce.

This study has performed a great work where we have found that  output increases in a greater proportion than the increase in all inputs after obtaining that the sum of all parameters is $1.474832894$ which is greater than one.


### Recommendations

This section is dedicated to the recommendations to be taken into consideration for
improving future research-oriented in the same area.

- The current project focuses on optimizing output from the generalized Cobb-Douglass production function using four inputs and cost constraints. Future research could expand the scope to include more inputs and different types of constraints. This would provide a more comprehensive understanding of the production function and its constraints.

- The current project uses simulated data to illustrate the optimization process. Future research could use real-world data to validate the results and provide more practical insights.

- The current project focuses on the manufacturing industry. Future research could test the model in different industries such as agriculture, service, or healthcare to determine its generalizability. 

- Future research could compare the generalized Cobb-Douglass production function with other production functions such as the CES production function to determine the best fit for different industries and situations.  






