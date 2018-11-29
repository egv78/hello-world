# hello-world
Following the tutorial

I am not a robot.  How many times do I need to tell the internet that?

Also, I just read about Ackermann's function.  It is recursive, has a (theoretically) knowable answer for any given 
pair of positive integers entered.  However, given the recursive nature, the computations (and values) blow up quite fast.

Ackermann's function:

```
def ack(m,n):
    if m < 0 or n < 0:
        return Null  //I've added this bit.  It's usually just stated that m & n must be positive integers.
    elif m == 0:
        return n+1
    elif n == 0:
        ack((m-1), 1)
    else:
        ack((m-1), ack(m, (n-1))
```        
