# test

## 01.10.02 : Difference Equation

* In many fields, a dynamic system that changes over a time should be **mathematically** modeled. 
* Several features of the system are each measured at **discrete time intervals**, producing a sequence of vectors, 

$$ \textbf{x}\_0, \textbf{x}\_1, \textbf{x}\_2, \cdots, $$. 

The entries in $$\textbf{x}\_k$$ provide information about the state of system at the time of the $k$th measurement.

* If there is a matrix $A$ such that $\textbf{x}\_1=A\textbf{x}\_0, \textbf{x}\_2=A\textbf{x}\_1$, and , in general $$\textbf{x}\_{k+1}=A\textbf{x}\_k \text{  for }k=0,1,2,\cdots$
* then it is called a **linear difference equation** \(or **recurrence relation**\)

