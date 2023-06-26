# t1t2
```
module skill_2 (a, b, c, T1, T2);
input a,b,c;
output T1, T2;
wire adash, bdash, cdash, x, y, z;
not (adash, a); not (bdash, b);
not (cdash, c);
and (x, adash,bdash);
and (y, adash, cdash); or (T1,x,y);
and (z,b,c);
or (T2, a, z);
endmodule
```
