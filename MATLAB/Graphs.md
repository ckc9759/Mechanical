### Sinosoidal

---

```matlab
t=-1:1/100:1;
f=1;
x=sin(2*pi*f*t);
plot(x) --> Graph will be plotted

plot(t,x) --> Specified both the axis
xlabel('X')
ylabel('Y')
title('Hello')
```

#### Scripts

---

```matlab
plotting graphs

x=1:10
y=x
plot(x,y)
title('plot')
```

Plotting multiple graphs

```matlab
subplot(1,2,1)
plot(x,y)
subplot(1,2,2)
plot(x,y2)
// subplot(rows,columns,position)
```

#### Plotting two signals on one graph

```matlab
t=0:0.01:1;
f=1;
x1=sin(2*pi*f*t)
x2=cos(2*pi*f*t)

plot(t,x1);
plot(t,x2);
plot(t,x1,t,x2) --> two graphs together
```

- We can use subplot with multiple plots as well !!

---

#### Linestyle and color

```matlab
plot(x,y,'*') --> printed in star form
plot(x,y,'r') --> red colour
'g' --> green color
`g*` --> green color with * mark

```

---




