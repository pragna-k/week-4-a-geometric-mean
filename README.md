# week-4-a-geometric-mean
n<-c(scan())
l<-length(n)
p<-1
for(i in n)
{
p=p*i
}
gm=p^(1/l)
gm


OUTPUT:
> n<-c(scan())
1: 5
2: 6
3: 7
4: 8
5: 9
6: 
Read 5 items
> l<-length(n)
> p<-1
> for(i in n)
+ {
+   p=p*i
+ }
> gm=p^(1/l)
> gm
[1] 6.853468
> n<-c(scan())
1: 9
2: 5
3: 1
4: 6
5: 4
6: 
Read 5 items
> l<-length(n)
> p<-1
> for(i in n)
+ {
+   p=p*i
+ }
> gm=p^(1/l)
> gm
[1] 4.042823
> 
