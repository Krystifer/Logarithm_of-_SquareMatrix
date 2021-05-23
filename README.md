# <center>Calculate the Logarithm of a square matrix</center>

Using Taylor series we can approximate an analitic function to a polinomial, for example, is well known that

<img src="https://latex.codecogs.com/gif.latex?e^x&space;=&space;\sum_{n=0}^{\infty}&space;\frac{x^n}{n!}&space;\quad&space;for&space;~|x|<1" title="e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!} \quad for ~|x|<1" />

and

<img src="https://latex.codecogs.com/gif.latex?\ln(x)&space;=&space;\sum_{n=1}^{\infty}&space;(-1)^{n&plus;1}\frac{(x-1)^n}{n}\quad&space;for~&space;|x|<1" title="\ln(x) = \sum_{n=1}^{\infty} (-1)^{n+1}\frac{(x-1)^n}{n}\quad for~ |x|<1" />

Also, matrix multiplication allows us to define de exponential matrix

<img src="https://latex.codecogs.com/gif.latex?e^A&space;=&space;\sum_{n=0}^{\infty}&space;\frac{A^n}{n!}&space;\quad&space;for~&space;||A||<1" title="e^A = \sum_{n=0}^{\infty} \frac{A^n}{n!} \quad for~ ||A||<1" />

and the natural logarithm of a matrix

<img src="https://latex.codecogs.com/gif.latex?\ln(A)&space;=&space;\sum_{n=1}^{\infty}&space;(-1)^{n&plus;1}\frac{(A-I)^n}{n}\quad&space;for&space;~&space;||x||<1" title="\ln(A) = \sum_{n=1}^{\infty} (-1)^{n+1}\frac{(A-I)^n}{n}\quad for ~ ||x||<1" />

Where A is a square matrix. Since has been proved that these series indeed exist (converges), one might want to know how the matrix   <img src="https://latex.codecogs.com/gif.latex?e^A" title="e^A" /> or <img src="https://latex.codecogs.com/gif.latex?\ln(A)" title="\ln(A)" /> looks like for a given <img src="https://latex.codecogs.com/gif.latex?A\in&space;M_{k\times&space;k}" title="A\in M_{n\times n}" />.
This code allows to compute such matrices for a given number of addends in the last series.
