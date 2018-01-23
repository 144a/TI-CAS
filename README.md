# TI-CAS

This is it. One of the Holy Grails of my work. Its not the best, and its certainly not complete, but I think this has brought together some of the best things I've programmed, and put it together. I mean, I think you can kinda guess by the name. It is a basic computer algebra system, meaning it can solve algebraic problems symbolically (kinda like how we do algebra). This allows for complex math to be done, such as polynomial indefinite integration and factorization, while still keeping the variables in a readable format. The input works as follows: only one argument can be passed at a time, with each entry encased in brackets, and the operator either in the middle or the beginning of the statement (depending on the operator). There will be a table of accepted arguments below. There also is an ans function, so now you can reuse the answer from a previous function in later problems just by using the "ans" token instead of a polynomial inside the parentheses.

Accepted Arguments:

(Poly)+(Poly)-----Polynomial Addition

(Poly)-(Poly)------Polynomial Subtraction

(Poly)*(Poly)-----Polynomial Multiplication

(Poly)/(Poly)------Polynomial Division***

(Poly)^(Num)----Polynomial Power

F(Poly)-------------Polynomial Factorization**

D(Poly)------------Polynomial Derivation

I(Poly)-------------Polynomial Indefinite Integration**

**(cannot return ans)
***(will return quotient as ans)
