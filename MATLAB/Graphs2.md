### Impulse signals

---

```matlab
n=-10:10;
u=[zeros(1,10) 1 zeros(1,10)];
stem(n,u)
```

Stem - Discrete values
Plot - Continous values

#### Straight Line

```matlab
x=1:100
a=5
c=20
y=a*x+c
plot(y)
```

#### Sawtooth wave

```matlab
T=10*(1/50);
fs=1000;
dt=1/fs;
t=0:dt:T-dt;
x=sawtooth(2*pi*50*t);
plot(t,x);
grid on; --> enable the grid
```

---
