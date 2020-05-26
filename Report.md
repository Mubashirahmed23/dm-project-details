## DM 103348: RSA Implementation
### PROJECT MEMBERS ###
StdId | Name
62640 | Mubashir Ahmed 
54321 | Areeb Aftab
67890 | Usman siddiqui

## Project Description ##
RSA (Rivest–Shamir–Adleman) is a calculation utilized by present day PCs to scramble and decode messages. It is an awry cryptographic calculation. Lopsided implies that there are two distinct keys. This is additionally called open key cryptography, since one of the keys can be given to anybody.
## Discrete Math Concepts Used ##
We have used different Discrete Mathematics concepts in our program, amongst them some of the most important ones are:
Multiplicative Inverse, Euler's Totient, Euclid's Algorithm and GCD for checking prime numbers. As We all know RSA algorithm purely works on Prime numbers to generate keys. So all the mentioned concepts are used to make program workable.
### Example: encryption key
```C language
void encryption_key()
{
  int k;
  k = 0;
  for(i = 2; i < t; i++)
  {
    if(t % i == 0)
     continue;
    flag = prime(i);
    if(flag == 1 && i != x && i != y)
    {
     e[k] = i;
     flag = cd(e[k]);
    if(flag > 0)
    {
     d[k] = flag;
     k++;
    }
   if(k == 99)
    break;
   }
 }
}
long int cd(long int a)
{
  long int k = 1;
  while(1)
  {
    k = k + t;
    if(k % a == 0)
     return(k / a);
  }
}}
```
## Problems Faced
All the concepts used in our project were well explained by our lecturer so we didn't face much problem but combining multiple algorithms together was a bit difficult for us.
## References##
Youtube.com 
*[links] https://www.youtube.com/watch?v=sYGS80-Joi8
* Geeks for geeks
