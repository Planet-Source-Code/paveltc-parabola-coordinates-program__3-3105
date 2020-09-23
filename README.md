<div align="center">

## Parabola Coordinates Program


</div>

### Description

A program that finds coordinates to a parabola.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Paveltc](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/paveltc.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |C
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__3-7.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/paveltc-parabola-coordinates-program__3-3105/archive/master.zip)





### Source Code

```
#include <stdio.h>
#include <iostream.h>
#include <math.h>
int main()
{
 double a, b, c, x1, x2, vp, z;
 printf("Please enter a, b, and c of your quadratic equation (in that order): ");
 cin >> a;
 cin >> b;
 cin >> c;
 x1 = (-b + sqrt(b*b - 4*a*c))/(2*a); //First x-intercept
 x2 = (-b - sqrt(b*b - 4*a*c))/(2*a); //Second x-intercept
 z = -b/(2*a);
 vp = (a*z)*(a*z) + (b*z) + c;     //Vertex point
 printf("The x-intercepts are %lg and %lg\n", x1, x2);
 printf("The y-intercept is %lg\n", c);
 printf("The vertex point is %lg , %lg\n", z, vp);
 return 0;
}
```

