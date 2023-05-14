

# WEEK 14











## Section 16.3，#11,16,19,29,33

### 16.3，11

Which fields in Exercises 1–6 are conservative, and which are not ?

$$
\mathbf{F}=\left(\ln x+\sec ^2(x+y)\right) \mathbf{i}+\left(\sec ^2(x+y)+\frac{y}{y^2+z^2}\right) \mathbf{j}+\frac{z}{y^2+z^2} \mathbf{k}
$$

**Solution**

$$
\frac{\partial f}{\partial z}=\frac{z}{y^{2}+z^{2}} \Rightarrow f(x, y, z)=\frac{1}{2} \ln \left(y^{2}+z^{2}\right)+g(x, y) \\\Rightarrow \frac{\partial f}{\partial x}=\frac{\partial g}{\partial x}=\ln x+\sec ^{2}(x+y) \\\Rightarrow g(x, y)=(x \ln x-x)+\tan (x+y)+h(y) \\\Rightarrow f(x, y, z)=\frac{1}{2} \ln \left(y^{2}+z^{2}\right)+(x \ln x-x)+\tan (x+y)+h(y)\\\Rightarrow \frac{\partial f}{\partial y}=\frac{y}{y^{2}+z^{2}}+\sec ^{2}(x+y)+h^{\prime}(y)=\sec ^{2}(x+y)+\frac{y}{y^{2}+z^{2}} \Rightarrow h^{\prime}(y)=0 \\\Rightarrow h(y)=C \Rightarrow f(x, y, z)=\frac{1}{2} \ln \left(y^{2}+z^{2}\right)+(x \ln x-x)+\tan (x+y)+C.
$$


### 16.3，16
In Exercises 13–17, show that the differential forms in the integrals are exact. Then evaluate the integrals.
$$\int_{(0,0,0)}^{(3,3,1)} 2 x d x-y^2 d y-\frac{4}{1+z^2} d z$$

**Solution**

Let $$\mathbf{F}(x, y, z)=2 x \mathbf{i}-y^{2} \mathbf{j}-\left(\frac{4}{1+z^{2}}\right) \mathbf{k}\\ \Rightarrow \frac{\partial P}{\partial y}=0=\frac{\partial N}{\partial z}, \frac{\partial M}{\partial z}=0=\frac{\partial P}{\partial x}, \frac{\partial N}{\partial x}=0=\frac{\partial M}{\partial y}$$ 

$$
\Rightarrow M d x+N d y+P d z \text{ is exact. } $$ 

$$
\frac{\partial f}{\partial x}=2 x \Rightarrow f(x, y, z)=x^{2}+g(y, z) \\\Rightarrow \frac{\partial f}{\partial y}=\frac{\partial g}{\partial y}=-y^{2} \\\Rightarrow g(y, z)=-\frac{y^{3}}{3}+h(z)\\\Rightarrow f(x, y, z)=x^{2}-\frac{y^{3}}{3}+h(z) \\\Rightarrow \frac{\partial f}{\partial z}=h^{\prime}(z)=-\frac{4}{1+z^{2}} \Rightarrow h(z)=-4 \tan ^{-1} z+C.
\\\Rightarrow f(x, y, z)=x^2-\frac{y^3}{3}-4 \tan ^{-1} z+C \\\Rightarrow \int_{(0,0,0)}^{(3,3,1)} 2 x d x-y^2 d y-\frac{4}{1+z^2} d z=f(3,3,1)-f(0,0,0) \\
\\=\left(9-\frac{27}{3}-4 \cdot \frac{\pi}{4}\right)-(0-0-0)=-\pi.
$$

### 16.3，19

Although they are not defined on all of space R3, the fields associated with Exercises 18–22 are conservative. Find a potential function for each field and evaluate the integrals as in Example 6.
$$
\int_{(1,1,1)}^{(1,2,3)} 3 x^2 d x+\frac{z^2}{y} d y+2 z \ln y d z
$$

**Solution**

 Let 
$$
\mathbf{F}(x, y, z)=3 x^{2} \mathbf{i}+\left(\frac{z^{2}}{y}\right) \mathbf{j}+(2 z \ln y) \mathbf{k} \Rightarrow \frac{\partial P}{\partial y}=\frac{2 z}{y}=\frac{\partial N}{\partial z}, \frac{\partial M}{\partial z}=0=\frac{\partial P}{\partial x}, \frac{\partial N}{\partial x}=0=\frac{\partial M}{\partial y}$$

$$
\Rightarrow M d x+N d y+P d z \text{ is exact. } $$  

$$
\frac{\partial f}{\partial x}=3 x^{2} \Rightarrow f(x, y, z)=x^{3}+g(y, z) \Rightarrow \frac{\partial f}{\partial y}=\frac{\partial g}{\partial y}=\frac{z^{2}}{y} \Rightarrow g(y, z)=z^{2} \ln y+h(z)\\\Rightarrow f(x, y, z)=x^{3}+z^{2} \ln y+h(z) \Rightarrow \frac{\partial f}{\partial z}=2 z \ln y+h^{\prime}(z)=2 z \ln y \\ \Rightarrow h^{\prime}(z)=0 \Rightarrow h(z)=C\Rightarrow f(x, y, z)=x^{3}+z^{2} \ln y+C \\\Rightarrow \int_{(1,1,1)}^{(1,2,3)} 3 x^{2} d x+\frac{z^{2}}{y} d y+2 z \ln y d z=f(1,2,3)-f(1,1,1)=(1+9 \ln 2+C)-(1C)=9 \ln 2.
$$


### 16.3，29

**Work along different paths**

 Find the work done by $\mathbf{F}=$ $\left(x^2+y\right) \mathbf{i}+\left(y^2+x\right) \mathbf{j}+z e^z \mathbf{k}$ over the following paths from $(1,0,0)$ to $(1,0,1)$

a. The line segment $x=1, y=0,0 \leq z \leq 1$

b. The helix $\mathbf{r}(t)=(\cos t) \mathbf{i}+(\sin t) \mathbf{j}+(t / 2 \pi) \mathbf{k}, 0 \leq t \leq 2 \pi$

c. The $x$-axis from $(1,0,0)$ to $(0,0,0)$ followed by the parabola $z=x^2, y=0$ from $(0,0,0)$ to $(1,0,1)$

![40%](${currentFileDir}/images/20230512022926.png)

**Solution**

$\frac{\partial P}{\partial y}=0=\frac{\partial N}{\partial z}, \frac{\partial M}{\partial y}=0=\frac{\partial P}{\partial x}, \frac{\partial N}{\partial x}=1=\frac{\partial M}{\partial y} \Rightarrow \mathbf{F}$ is conservative 

$\Rightarrow$ there exists an $f$ so that $\mathbf{F}=\nabla f$; $\frac{\partial f}{\partial x}=x^{2}+y$

$ \Rightarrow f(x, y, z)=\frac{1}{3} x^{3}+x y+g(y, z) \Rightarrow \frac{\partial f}{\partial y}=x+\frac{\partial g}{\partial y}=y^{2}+x \Rightarrow \frac{\partial g}{\partial y}=y^{2} \Rightarrow g(y, z)=\frac{1}{3} y^{3}+h(z)$ 

$\Rightarrow f(x, y, z)=\frac{1}{3} x^{3}+x y+\frac{1}{3} y^{3}+h(z) \Rightarrow \frac{\partial f}{\partial z}=h^{\prime}(z)=z e^{z} \Rightarrow h(z)=z e^{z}-e^{z}+C$ 

$\Rightarrow f(x, y, z)=\frac{1}{3} x^{3}+x y+\frac{1}{3} y^{3}+z e^{z}-e^{z}+C \Rightarrow \mathbf{F}=\nabla\left(\frac{1}{3} x^{3}+x y+\frac{1}{3} y^{3}+z e^{z}-e^{z}\right).$

(a) 
work $\displaystyle=\int_A^B \mathbf{F} \cdot \frac{d \mathbf{r}}{d t} d t=\int_A^B \mathbf{F} \cdot d \mathbf{r}=\left[\frac{1}{3} x^3+x y+\frac{1}{3} y^3+z e^z-e^z\right]_{(1,0,0)}^{(1,0,1)}=1;$

(b) 
work $\displaystyle=\int_A^B \mathbf{F} \cdot d \mathbf{r}=\left[\frac{1}{3} x^3+x y+\frac{1}{3} y^3+z e^z-e^z\right]_{(1,0,0)}^{(1,0,1)}=1;$
 
(c) 
work $ \displaystyle =\int_A^B \mathbf{F} \cdot d \mathbf{r}=\left[\frac{1}{3} x^3+x y+\frac{1}{3} y^3+z e^z-e^z\right]_{(1,0,0)}^{(1,0,1)}=1.$


### Supplement: P49: 5, 27, 30, 33; P116: 10; P118: 2 (5)

### 5. 
Let $f(t)=\int_{1}^{t^{2}} \mathrm{e}^{-x^{2}} \mathrm{~d} x$, then $\int_{0}^{1} t f(t) \mathrm{d} t=(\quad)$.


**Solution**




### 27. 
Compute 

$$
\iint_{D}\left(x^{3}+y^{3}\right) \mathrm{d} A
$$

Where D is bounded by $x^2 = 2y, x^2 = 3y, x = y^2$ and $x = 2y^2$.

**Solution_1**

Let 
$$
u = \frac{x}{y^2}, \ v = \frac{x^2}{y},
$$

then the region will be
$$
1 \le u \le 2 , \ 2 \le v \le 3. 
$$

We have

$$
x =v^{\frac{2}{3}}u^{-\frac{1}{3}},\ 
y =u^{-\frac{2}{3}}v^{\frac{1}{3}},
$$

so the Jacobi matrix is

$$
\begin{vmatrix}  
  \dfrac{\partial x}{\partial u}& \dfrac{\partial y}{\partial u} \\[1em]
  \dfrac{\partial x}{\partial v}& \dfrac{\partial y}{\partial v} \\  
\end{vmatrix} = 
\begin{vmatrix}  
  -\dfrac{v^{\frac{2}{3}}}{3 u^{\frac{4}{3}}} & - \dfrac{2 {v}^{\frac{1}{3}}}{3 u^{\frac{5}{3}}} \\[1em]
  \dfrac{2}{3 {u}^{\frac{1}{3}} {v}^{\frac{1}{3}}}& \dfrac{1}{3 u^{\frac{2}{3}} v^{\frac{2}{3}}} \\  
\end{vmatrix}  = \dfrac{1}{3 u^{2}}.
$$

So 

$$
\iint_{D}\left(x^{3}+y^{3}\right) \mathrm{d} A 
= \int^{3}_{2} \int^{2}_{1} \left( u^{-1}v^{2} + u^{-2}v \right) \dfrac{1}{3 u^{2}} du dv 
\\ =  \int^{2}_{1} \int^{3}_{2} \left( u^{-1}v^{2} + u^{-2}v \right) \dfrac{1}{3 u^{2}} dv du 
\\ =  \int^{2}_{1} \dfrac{1}{3 u^{2}} \dfrac{38 u + 15}{6 u^{2}} du
\\ =  \dfrac{149}{144}. 
$$


### 30. 
Find the centroid of of the region bounded by $r=2 \sin \theta$ and $r=4 \sin \theta$.


**Solution**



### 31. 
Compute that

$$
\int_{0}^{1} \mathrm{~d} x \int_{0}^{x} \mathrm{~d} y \int_{0}^{y} \frac{\sin z}{(1-z)^{2}} \mathrm{~d} z
$$


**Solution**



### 10. 
 Calculate the line integral $\int_{L} \sin 2 x d x+2\left(x^{2}-1\right) y d y$, here $L$ is the curve $y=\sin x$, from $(0,0)$ to $(\pi, 0)$.


**Solution**



### (5) 
Let $C$ be the curve $x^{2}+y^{2}=a^{2}(a>0)$, then $\int_{C} x^{2} d s=$


**Solution**





### 16.3，33

**a. Exact differential form** 
How are the constants $a, b$, and $c$ related if the following differential form is exact?
$$
\left(a y^2+2 c z x\right) d x+y(b x+c z) d y+\left(a y^2+c x^2\right) d z
$$

**b. Gradient field** 
For what values of $b$ and $c$ will
$$
\mathbf{F}=\left(y^2+2 c z x\right) \mathbf{i}+y(b x+c z) \mathbf{j}+\left(y^2+c x^2\right) \mathbf{k}
$$

be a gradient field?

**Solution**

(a) 
If the differential form is exact, then $\frac{\partial P}{\partial y}=\frac{\partial N}{\partial z} \Rightarrow 2 a y=c y$ for all $y \Rightarrow 2 a=c, \frac{\partial M}{\partial z}=\frac{\partial P}{\partial x} \Rightarrow 2 c x=2 c x$ for all $x$, and $\frac{\partial N}{\partial x}=\frac{\partial M}{\partial y} \Rightarrow b y=2 a y$ for all $y \Rightarrow b=2 a$ and $c=2 a$.

(b) 
$\mathbf{F}=\nabla f \Rightarrow$ the differential form with $a=1$ in part (a) is exact $\Rightarrow b=2$ and $c=2$.








## Section 16.4，#9,17,19,23,27,35

### 16.4，9

Use Green’s Theorem to find the counterclockwise circulation and outward flux for the field F and curve C.
$$\textbf{F}=\bigl(xy+y^2\bigr)\mathbf{i}+(x-y)\mathbf{j}$$

**Solution**

$M=x y+y^{2}, N=x-y \Rightarrow \frac{\partial M}{\partial x}=y, \frac{\partial M}{\partial y}=x+2 y, \frac{\partial N}{d x}=1, \frac{\partial N}{\partial y}=-1 \Rightarrow$
 Flux $=\iint_{R}(y+(-1)) d y d x$ $=\int_{0}^{1} \int_{x^{2}}^{\sqrt{x}}(y-1) d y d x=\int_{0}^{1}\left(\frac{1}{2} x-\sqrt{x}-\frac{1}{2} x^{4}+x^{2}\right) d x=-\frac{11}{60} ; \operatorname{Circ}=\iint_{R}(1-(x+2 y)) d y d x$ $=\int_{0}^{1} \int_{x^{2}}^{\sqrt{x}}(1-x-2 y) d y d x=\int_{0}^{1}\left(\sqrt{x}-x^{3 / 2}-x-x^{2}+x^{3}+x^{4}\right) d x=-\frac{7}{60}.$




### 16.4，17

Find the outward flux of the field

$$
\mathbf{F}=\left(3 x y-\frac{x}{1+y^2}\right) \mathbf{i}+\left(e^x+\tan ^{-1} y\right) \mathbf{j}
$$

across the cardioid $r=a(1+\cos \theta), a>0$.


**Solution**

$M=3 x y-\frac{x}{1+y^{2}}, N=e^{x}+\tan ^{-1} y \Rightarrow \frac{\partial M}{\partial x}=3 y-\frac{1}{1+y^{2}}, \frac{\partial N}{\partial y}=\frac{1}{1+y^{2}}$

$\Rightarrow$ Flux $=\iint_{R}\left(3 y-\frac{1}{1+y^{2}}+\frac{1}{1+y^{2}}\right) d x d y=\iint_{R} 3 y d x d y=\int_{0}^{2 \pi} \int_{0}^{a(1+\cos \theta)}(3 r \sin \theta) r d r d \theta$ $=\int_{0}^{2 \pi} a^{3}(1+\cos \theta)^{3}(\sin \theta) d \theta=\left[-\frac{a^{3}}{4}(1+\cos \theta)^{4}\right]_{0}^{2 \pi}=-4 a^{3}-\left(-4 a^{3}\right)=0$.

### 16.4，19

In Exercises 19, find the work done by $\mathbf{F}$ in moving a particle once counterclockwise around the given curve.

$$\mathbf{F}=2 x y^3 \mathbf{i}+4 x^2 y^2 \mathbf{j}$$

$C$ : The boundary of the "triangular" region in the first quadrant enclosed by the $x$-axis, the line $x=1$, and the curve $y=x^3$

**Solution**

$M=2 x y^{3}, N=4 x^{2} y^{2} \Rightarrow \frac{\partial M}{\partial y}=6 x y^{2}, \frac{\partial N}{\partial x}=8 x y^{2} \Rightarrow$ work $=\oint_{C} 2 x y^{3} d x+4 x^{2} y^{2} d y=\iint_{R}\left(8 x y^{2}-6 x y^{2}\right) d x d y$ $=\int_{0}^{1} \int_{0}^{x^{3}} 2 x y^{2} d y d x=\int_{0}^{1} \frac{2}{3} x^{10} d x=\frac{2}{33}$.

### 16.4，23

Apply Green’s Theorem to evaluate the integrals in Exercises 23.

$$
\oint_C(3 y d x+2 x d y)
$$

$C$ : The boundary of $0 \leq x \leq \pi, 0 \leq y \leq \sin x$

**Solution**

$M=6 y+x, N=y+2 x \Rightarrow \frac{\partial M}{\partial y}=6, \frac{\partial N}{\partial x}=2 \Rightarrow \oint_{C}(6 y+x) d x+(y+2 x) d y=\iint_{R}(2-6) d y d x$ 
$=-4($ Area of the circle $)=-16 \pi$

### 16.4，27

Use the Green’s Theorem area formula given above to find the areas 
of the regions enclosed by the curves

$$
\text { The astroid } \mathbf{r}(t)=\left(\cos ^3 t\right) \mathbf{i}+\left(\sin ^3 t\right) \mathbf{j}, \quad 0 \leq t \leq 2 \pi
$$

**Solution**

 $M=x=\cos ^{3} t, N=y=\sin ^{3} t \Rightarrow d x=-3 \cos ^{2} t \sin t d t, d y=3 \sin ^{2} t \cos t d t \Rightarrow$ 
 Area $=\frac{1}{2} \oint_{C} x d y-y d x$ $=\frac{1}{2} \int_{0}^{2 \pi}\left(3 \sin ^{2} t \cos ^{2} t\right)\left(\cos ^{2} t+\sin ^{2} t\right) d t=\frac{1}{2} \int_{0}^{2 \pi}\left(3 \sin ^{2} t \cos ^{2} t\right) d t=\frac{3}{8} \int_{0}^{2 \pi} \sin ^{2} 2 t d t=\frac{3}{16} \int_{0}^{4 \pi} \sin ^{2} u d u$ $=\frac{3}{16}\left[\frac{u}{2}-\frac{\sin 2 u}{4}\right]_{0}^{4 \pi}=\frac{3}{8} \pi$.

### 16.4，35

**Area and the centroid** 
Let $A$ be the area and $\bar{x}$ the $x$-coordinate of the centroid of a region $R$ that is bounded by a piecewise smooth, simple closed curve $C$ in the $x y$-plane. Show that
$$
\frac{1}{2} \oint_C x^2 d y=-\oint_C x y d x=\frac{1}{3} \oint_C x^2 d y-x y d x=A \bar{x}.
$$


**Solution**

Let $\delta(x, y)=1$, then

$$ 
\bar{x}=\frac{M_{y}}{M}=\frac{\iint_{R} x \delta(x, y) d A}{\iint_{R} \delta(x, y) d A}=\frac{\iint_{R} x d A}{\iint_{R} d A}=\frac{\iint_{R} x d A}{A} \\ \Rightarrow A \bar{x}=\iint_{R} x d A=\iint_{R}(x+0) d x d y=\oint_{C} \frac{x^{2}}{2} d y, \\ A \bar{x}=\iint_{R} x d A=\iint_{R}(0+x) d x d y=-\oint_{C} x y d x,
\\ A \bar{x}=\iint_{R} x d A=\iiint_{R}\left(\frac{2}{3} x+\frac{1}{3} x\right) d x d y=\oint_{C} \frac{1}{3} x^{2} d y-\frac{1}{3} x y d x.$$



## Section 16.5，#15,23,27,33,41

### 16.5，15

In Exercises 1–16, find a parametrization of the surface. (There are 
many correct ways to do these, so your answers may not be the same 
as those in the back of the book.)


**Solution**


### 16.5，23



**Solution**


### 16.5, 33



**Solution**


### 16.5，41



**Solution**






15. Let $x=w \cos v$ and $z=w \sin v$. Then $(x-2)^{2}+z^{2}=4 \Rightarrow x^{2}-4 x+z^{2}=0$ $\Rightarrow w^{2} \cos ^{2} v-4 w \cos v+w^{2} \sin ^{2} v=0 \Rightarrow w^{2}-4 w \cos v=0 \Rightarrow w=0$ or $w-4 \cos v=0 \Rightarrow w=0$ or $w=4 \cos v$. Now $w=0 \Rightarrow x=0$ and $y=0$, which is a line not a cylinder. Therefore, let $w=4 \cos v \Rightarrow x=(4 \cos v)(\cos v)=4 \cos ^{2} v$ and $z=4 \cos v \sin v$. Finally, let $y=u$. Then $\mathbf{r}(u, v)=\left(4 \cos ^{2} v\right) \mathbf{i}+u \mathbf{j}+(4 \cos v \sin v) \mathbf{k},-\frac{\pi}{2} \leq v \leq \frac{\pi}{2}$ and $0 \leq u \leq 3$.

23. $z=2-x^{2}-y^{2}$ and $z=\sqrt{x^{2}+y^{2}} \Rightarrow z=2-z^{2} \Rightarrow z^{2}+z-2=0 \Rightarrow z=-2$ or $z=1$. Since $z=\sqrt{x^{2}+y^{2}} \geq 0$, we get $z=1$ where the cone intersects the paraboloid. When $x=0$ and $y=0, z=2 \Rightarrow$ the vertex of the paraboloid is $(0,0,2)$. Therefore, $z$ ranges from 1 to 2 on the "cap" $\Rightarrow r$ ranges from 1 (when $x^{2}+y^{2}=1$ ) to 0 (when $x=0$ and $y=0$ at the vertex). Let $x=r \cos \theta, y=r \sin \theta$, and $z=2-r^{2}$. Then $\mathbf{r}(r, \theta)=(r \cos \theta) \mathbf{i}+(r \sin \theta) \mathbf{j}+\left(2-r^{2}\right) \mathbf{k}, 0 \leq r \leq 1,0 \leq \theta \leq 2 \pi \Rightarrow \mathbf{r}_{r}=(\cos \theta) \mathbf{i}+(\sin \theta) \mathbf{j}-2 r \mathbf{k}$ and

27. The parametrization $\mathbf{r}(r, \theta)=(r \cos \theta) \mathbf{i}+(r \sin \theta) \mathbf{j}+r \mathbf{k}$ at $P_{0}=(\sqrt{2}, \sqrt{2}, 2) \Rightarrow \theta=\frac{\pi}{4}, r=2$, $\mathbf{r}_{r}=(\cos \theta) \mathbf{i}+(\sin \theta) \mathbf{j}+\mathbf{k}=\frac{\sqrt{2}}{2} \mathbf{i}+\frac{\sqrt{2}}{2} \mathbf{j}+\mathbf{k}$ and $\mathbf{r}_{\theta}=(-r \sin \theta) \mathbf{i}+(r \cos \theta) \mathbf{j}=-\sqrt{2} \mathbf{i}+\sqrt{2} \mathbf{j}$ $\Rightarrow \mathbf{r}_{r} \times \mathbf{r}_{\theta}=\left|\begin{array}{ccc}\mathbf{i} & \mathbf{j} & \mathbf{k} \\ \sqrt{2} / 2 & \sqrt{2} / 2 & 1 \\ -\sqrt{2} & \sqrt{2} & 0\end{array}\right|=-\sqrt{2} \mathbf{i}-\sqrt{2} \mathbf{j}+2 \mathbf{k}$


$\Rightarrow$ the tangent plane is $0=(-\sqrt{2} \mathbf{i}-\sqrt{2} \mathbf{j}+2 \mathbf{k}) \cdot[(x-\sqrt{2}) \mathbf{i}+(y-\sqrt{2}) \mathbf{j}+(z-2) \mathbf{k}] \Rightarrow \sqrt{2} x+\sqrt{2} y-2 z=0$, or $x+y-\sqrt{2} z=0$. The parametrization $\mathbf{r}(r, \theta) \Rightarrow x=r \cos \theta, y=r \sin \theta$ and $z=r \Rightarrow x^{2}+y^{2}=r^{2}=z^{2}$

$\Rightarrow$ the surface is $z=\sqrt{x^{2}+y^{2}}$

33. (a) Let $w^{2}+\frac{z^{2}}{c^{2}}=1$ where $w=\cos \phi$ and $\frac{z}{c}=\sin \phi \Rightarrow \frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=\cos ^{2} \phi \Rightarrow \frac{x}{a}=\cos \phi \cos \theta$ and $\frac{y}{b}=\cos \phi \sin \theta$ $\Rightarrow x=a \cos \theta \cos \phi, y=b \sin \theta \cos \phi$, and $z=c \sin \phi$ $\Rightarrow \mathbf{r}(\theta, \phi)=(a \cos \theta \cos \phi) \mathbf{i}+(b \sin \theta \cos \phi) \mathbf{j}+(c \sin \phi) \mathbf{k}$

(b) $\mathbf{r}_{\theta}=(-a \sin \theta \cos \phi) \mathbf{i}+(b \cos \theta \cos \phi) \mathbf{j}$ and $\mathbf{r}_{\phi}=(-a \cos \theta \sin \phi) \mathbf{i}-(b \sin \theta \sin \phi) \mathbf{j}+(c \cos \phi) \mathbf{k}$

$\Rightarrow \mathbf{r}_{\theta} \times \mathbf{r}_{\phi}=\left|\begin{array}{ccc}\mathbf{i} & \mathbf{j} & \mathbf{k} \\ -a \sin \theta \cos \phi & b \cos \theta \cos \phi & 0 \\ -a \cos \theta \sin \phi & -b \sin \theta \sin \phi & c \cos \phi\end{array}\right|$ $=\left(b c \cos \theta \cos ^{2} \phi\right) \mathbf{i}+\left(a c \sin \theta \cos ^{2} \phi\right) \mathbf{j}+(a b \sin \phi \cos \phi) \mathbf{k}$ $\Rightarrow\left|\mathbf{r}_{\theta} \times \mathbf{r}_{\phi}\right|^{2}=b^{2} c^{2} \cos ^{2} \theta \cos ^{4} \phi+a^{2} c^{2} \sin ^{2} \theta \cos ^{4} \phi+a^{2} b^{2} \sin ^{2} \phi \cos ^{2} \phi$, and the result follows. $A=\int_{0}^{2 \pi} \int_{0}^{2 \pi}\left|\mathbf{r}_{\theta} \times \mathbf{r}_{\phi}\right| d \phi d \theta=\int_{0}^{2 \pi} \int_{0}^{\pi}\left[a^{2} b^{2} \sin ^{2} \phi \cos ^{2} \phi+b^{2} c^{2} \cos ^{2} \theta \cos ^{4} \phi+a^{2} c^{2} \sin ^{2} \theta \cos ^{4} \phi\right]^{1 / 2} d \phi d \theta$

41. $\mathbf{p}=\mathbf{k}, \nabla f=2 x \mathbf{i}-2 \mathbf{j}-2 \mathbf{k} \Rightarrow|\nabla f|=\sqrt{(2 x)^{2}+(-2)^{2}+(-2)^{2}}=\sqrt{4 x^{2}+8}=2 \sqrt{x^{2}+2}$ and $|\nabla f \cdot \mathbf{p}|=2$ $\Rightarrow S=\iint_{R} \frac{|\nabla f|}{|\nabla f \cdot \mathbf{p}|} d A=\iint_{R} \frac{2 \sqrt{x^{2}+2}}{2} d x d y=\int_{0}^{2} \int_{0}^{3 x} \sqrt{x^{2}+2} d y d x=\int_{0}^{2} 3 x \sqrt{x^{2}+2} d x=\left[\left(x^{2}+2\right)^{3 / 2}\right]_{0}^{2}=6 \sqrt{6}-2 \sqrt{2}$


































## Section 16.6，#6,13,25,29,37,44

### 16.6，6



**Solution**


### 16.6，13



**Solution**

**Solution**



### 16.6，29



**Solution**


### 16.6，37



**Solution**


### 16.6，44



**Solution**



### 16.6，25



**Solution**



### 16.6，29



**Solution**


### 16.6，37



**Solution**


### 16.6，44






6. Let the parametrization be $\mathbf{r}(r, \theta)=(r \cos \theta) \mathbf{i}+(r \sin \theta) \mathbf{j}+r \mathbf{k}, 0 \leq r \leq 1$ (since $0 \leq z \leq 1$ ) and $0 \leq \theta \leq 2 \pi$ $\Rightarrow \mathbf{r}_{r}=(\cos \theta) \mathbf{i}+(\sin \theta) \mathbf{j}+\mathbf{k}$ and $\mathbf{r}_{\theta}=(-r \sin \theta) \mathbf{i}+(r \cos \theta) \mathbf{j} \Rightarrow \mathbf{r}_{r} \times \mathbf{r}_{\theta}=\left|\begin{array}{ccc}\mathbf{i} & \mathbf{j} & \mathbf{k} \\ \cos \theta & \sin \theta & 1 \\ -r \sin \theta & r \cos \theta & 0\end{array}\right|$ $=(-r \cos \theta) \mathbf{i}-(r \sin \theta) \mathbf{j}+r \mathbf{k} \Rightarrow\left|\mathbf{r}_{r} \times \mathbf{r}_{\theta}\right|=\sqrt{(-r \cos \theta)^{2}+(-r \sin \theta)^{2}+r^{2}}=r \sqrt{2} ; z=r$ and $x=r \cos \theta$ $\Rightarrow F(x, y z)=r-r \cos \theta \Rightarrow \iint_{S} F(x, y, z) d \sigma=\int_{0}^{2 \pi} \int_{0}^{1}(r-r \cos \theta)(r \sqrt{2}) d r d \theta$ $=\sqrt{2} \int_{0}^{2 \pi} \int_{0}^{1}(1-\cos \theta) r^{2} d r d \theta=\frac{2 \pi \sqrt{2}}{3}$

13. $f(x, y, z)=2 x+2 y+z=2 \Rightarrow \nabla f=2 \mathbf{i}+2 \mathbf{j}+\mathbf{k}$ and $G(x, y, z)=x+y+(2-2 x-2 y)=2-x-y \Rightarrow \mathbf{p}=\mathbf{k}$, $|\nabla f|=3$ and $|\nabla f \cdot \mathbf{p}|=1 \Rightarrow d \sigma=3 d y d x ; \quad z=0 \Rightarrow 2 x+2 y=2 \Rightarrow y=1-x \Rightarrow \iint_{S} G d \sigma=\iint_{S}(2-x-y) d \sigma$ $=3 \int_{0}^{1} \int_{0}^{1-x}(2-x-y) d y d x=3 \int_{0}^{1}\left[(2-x)(1-x)-\frac{1}{2}(1-x)^{2}\right] d x=3 \int_{0}^{1}\left(\frac{3}{2}-2 x+\frac{x^{2}}{2}\right) d x=2$

25. Let the parametrization be $\mathbf{r}(r, \theta)=(r \cos \theta) \mathbf{i}+(r \sin \theta) \mathbf{j}+r \mathbf{k}, 0 \leq r \leq 1$ (since $0 \leq z \leq 1)$ and $0 \leq \theta \leq 2 \pi$ $\Rightarrow \mathbf{r}_{r}=(\cos \theta) \mathbf{i}+(\sin \theta) \mathbf{j}+\mathbf{k}$ and $\mathbf{r}_{\theta}=(-r \sin \theta) \mathbf{i}+(r \cos \theta) \mathbf{j} \Rightarrow \mathbf{r}_{\theta} \times \mathbf{r}_{r}=\left|\begin{array}{ccc}\mathbf{i} & \mathbf{j} & \mathbf{k} \\ -r \sin \theta & r \cos \theta & 0 \\ \cos \theta & \sin \theta & 1\end{array}\right|$ $=(r \cos \theta) \mathbf{i}+(r \sin \theta) \mathbf{j}-\mathbf{r} \mathbf{k} \Rightarrow \mathbf{F} \cdot \mathbf{n} d \sigma=\mathbf{F} \cdot \frac{\mathbf{r}_{\theta} \times \mathbf{r}_{r}}{\left|\mathbf{r}_{\theta} \times \mathbf{r}_{r}\right|}\left|\mathbf{r}_{\theta} \times \mathbf{r}_{r}\right| d \theta d r=\left(r^{3} \sin \theta \cos ^{2} \theta+r^{2}\right) d \theta d r$ since $\mathbf{F}=\left(r^{2} \sin \theta \cos \theta\right) \mathbf{i}-r \mathbf{k} \Rightarrow \iint_{S} \mathbf{F} \cdot \mathbf{n} d \sigma=\int_{0}^{2 \pi} \int_{0}^{1}\left(r^{3} \sin \theta \cos ^{2} \theta+r^{2}\right) d r d \theta=\int_{0}^{2 \pi}\left(\frac{1}{4} \sin \theta \cos ^{2} \theta+\frac{1}{3}\right) d \theta$ $=\left[-\frac{1}{12} \cos ^{3} \theta+\frac{\theta}{3}\right]_{0}^{2 \pi}=\frac{2 \pi}{3}$

29. $g(x, y, z)=z, \mathbf{p}=\mathbf{k} \Rightarrow \nabla g=\mathbf{k} \Rightarrow|\nabla g|=1$ and $|\nabla g \cdot \mathbf{p}|=1 \Rightarrow$ Flux $=\iint_{S} \mathbf{F} \cdot \mathbf{n} d \sigma=\iint_{R}(\mathbf{F} \cdot \mathbf{k}) d A$ $=\int_{0}^{2} \int_{0}^{3} 3 d y d x=18$

37. $g(x, y, z)=y^{2}+z=4 \Rightarrow \nabla g=2 y \mathbf{j}+\mathbf{k} \Rightarrow|\nabla g|=\sqrt{4 y^{2}+1} \Rightarrow \mathbf{n}=\frac{2 y \mathbf{j}+\mathbf{k}}{\sqrt{4 y^{2}+1}} \Rightarrow \mathbf{F} \cdot \mathbf{n}=\frac{2 x y-3 z}{\sqrt{4 y^{2}+1}}$; $\mathbf{p}=\mathbf{k} \Rightarrow|\nabla g \cdot \mathbf{p}|=1 \Rightarrow d \sigma=\sqrt{4 y^{2}+1} d A \Rightarrow$ Flux $=\iint_{R}\left(\frac{2 x y-3 z}{\sqrt{4 y^{2}+1}}\right) \sqrt{4 y^{2}+1} d A=\iint_{R}(2 x y-3 z) d A ;$ $z=0$ and $z=4-y^{2} \Rightarrow y^{2}=4 \Rightarrow$ Flux $=\iint_{R}\left[2 x y-3\left(4-y^{2}\right)\right] d A=\int_{0}^{1} \int_{-2}^{2}\left(2 x y-12+3 y^{2}\right) d y d x$ $=\int_{0}^{1}\left[x y^{2}-12 y+y^{3}\right]_{-2}^{2} d x=\int_{0}^{1}(-32) d x=-32$ 44. $\nabla f=2 y \mathbf{j}+2 z \mathbf{k} \Rightarrow|\nabla f|=\sqrt{4 y^{2}+4 z^{2}}=\sqrt{4\left(y^{2}+z^{2}\right)}=6 ; \mathbf{p}=\mathbf{k} \Rightarrow|\nabla f \cdot \mathbf{k}|=2 z$ since $z \geq 0 \Rightarrow \mathrm{d} \sigma=\frac{6}{2 \mathrm{z}} d A$ $=\frac{3}{z} d A ; M=\iint_{S} 1 d \sigma=\int_{-3}^{3} \int_{0}^{3} \frac{3}{z} d x d y=\int_{-3}^{3} \int_{0}^{3} \frac{3}{\sqrt{9-y^{2}}} d x d y=9 \pi ; M_{x y}=\iint_{S} z d \sigma=\int_{-3}^{3} \int_{0}^{3} z\left(\frac{3}{z}\right) d x d y=54 ;$ $M_{x z}=\iint_{S} y d \sigma=\int_{-3}^{3} \int_{0}^{3} y\left(\frac{3}{z}\right) d x d y=\int_{-3}^{3} \int_{0}^{3} \frac{3 y}{\sqrt{9-y^{2}}} d x d y=0 ; M_{y z}=\iint_{S} x d \sigma=\int_{-3}^{3} \int_{0}^{3} \frac{3 x}{\sqrt{9-y^{2}}} d x d y=\frac{27}{2} \pi$

Therefore, $\bar{x}=\frac{\left(\frac{27}{2} \pi\right)}{9 \pi}=\frac{3}{2}, \bar{y}=0$, and $\bar{z}=\frac{54}{9 \pi}=\frac{6}{\pi}$





















**Solution**


## Section 16.7，#7,13,15,21,28


### 16.7，7



**Solution**


### 16.7，13



**Solution**


### 16.7，15



**Solution**



### 16.7，21



**Solution**


### 16.7，28



**Solution**








7. $x=3 \cos t$ and $y=2 \sin t \Rightarrow \mathbf{F}=(2 \sin t) \mathbf{i}+\left(9 \cos ^{2} t\right) \mathbf{j}+\left(9 \cos ^{2} t+16 \sin ^{4} t\right) \sin e^{\sqrt{(6 \sin t \cos t)(0)}} \mathbf{k}$ at the base of the shell; $\mathbf{r}=(3 \cos t) \mathbf{i}+(2 \sin t) \mathbf{j} \Rightarrow d \mathbf{r}=(-3 \sin t) \mathbf{i}+(2 \cos t) \mathbf{j} \Rightarrow \mathbf{F} \cdot \frac{d \mathbf{r}}{d t}=-6 \sin ^{2} t+18 \cos ^{3} t$ $\Rightarrow \iint_{S} \nabla \times \mathbf{F} \cdot \mathbf{n} d \sigma=\int_{0}^{2 \pi}\left(-6 \sin ^{2} t+18 \cos ^{3} t\right) d t=\left[-3 t+\frac{3}{2} \sin 2 t+6(\sin t)\left(\cos ^{2} t+2\right)\right]_{0}^{2 \pi}=-6 \pi$

13. $\nabla \times \mathbf{F}=\left|\begin{array}{ccc}\mathbf{i} & \mathbf{j} & \mathbf{k} \\ \frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\ 2 z & 3 x & 5 y\end{array}\right|=5 \mathbf{i}+2 \mathbf{j}+3 \mathbf{k} ; \mathbf{r}_{r}=(\cos \theta) \mathbf{i}+(\sin \theta) \mathbf{j}-2 r \mathbf{k}$ and $\mathbf{r}_{\theta}=(-r \sin \theta) \mathbf{i}+(r \cos \theta) \mathbf{j}$ $\Rightarrow \mathbf{r}_{r} \times \mathbf{r}_{\theta}=\left|\begin{array}{ccc}\mathbf{i} & \mathbf{j} & \mathbf{k} \\ \cos \theta & \sin \theta & -2 r \\ -r \sin \theta & r \cos \theta & 0\end{array}\right|=\left(2 r^{2} \cos \theta\right) \mathbf{i}+\left(2 r^{2} \sin \theta\right) \mathbf{j}+r \mathbf{k} ; \mathbf{n}=\frac{\mathbf{r}_{r} \times \mathbf{r}_{\theta}}{\left|\mathbf{r}_{r} \times \mathbf{r}_{\theta}\right|}$ and $d \sigma=\left|\mathbf{r}_{r} \times \mathbf{r}_{\theta}\right| d r d \theta$

15. $\nabla \times \mathbf{F}=\left|\begin{array}{ccc}\mathbf{i} & \mathbf{j} & \mathbf{k} \\ \frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\ x^{2} y & 2 y^{3} z & 3 z\end{array}\right|=-2 y^{3} \mathbf{i}+0 \mathbf{j}-x^{2} \mathbf{k} ; \mathbf{r}_{r} \times \mathbf{r}_{\theta}=\left|\begin{array}{ccc}\mathbf{i} & \mathbf{j} & \mathbf{k} \\ \cos \theta & \sin \theta & 1 \\ -r \sin \theta & r \cos \theta & 0\end{array}\right|=(-r \cos \theta) \mathbf{i}-(r \sin \theta) \mathbf{j}+r \mathbf{k}$ and $\nabla \times \mathbf{F} \cdot \mathbf{n} d \sigma=(\nabla \times \mathbf{F}) \cdot\left(\mathbf{r}_{r} \times \mathbf{r}_{\theta}\right) d r d \theta($ see Exercise 13 above $) \Rightarrow \iint_{S} \nabla \times \mathbf{F} \cdot \mathbf{n} d \sigma=\iint_{R}\left(2 r y^{3} \cos \theta-r x^{2}\right) d r d \theta$ $=\int_{0}^{2 \pi} \int_{0}^{1}\left(2 r^{4} \sin ^{3} \theta \cos \theta-r^{3} \cos ^{2} \theta\right) d r d \theta=\int_{0}^{2 \pi}\left(\frac{2}{5} \sin ^{3} \theta \cos \theta-\frac{1}{4} \cos ^{2} \theta\right) d \theta=\left[\frac{1}{10} \sin ^{4} \theta-\frac{1}{4}\left(\frac{\theta}{2}+\frac{\sin 2 \theta}{4}\right)\right]_{0}^{2 \pi}$ $=-\frac{\pi}{4}$

21. (a) $\mathbf{F}=2 x \mathbf{i}+2 y \mathbf{j}+2 z \mathbf{k} \Rightarrow \operatorname{curl} \mathbf{F}=\mathbf{0} \Rightarrow \oint_{C} \mathbf{F} \cdot d \mathbf{r}=\iint_{S} \nabla \times \mathbf{F} \cdot \mathbf{n} d \sigma=\iint_{S} 0 d \sigma=0$

(b) Let $f(x, y, z)=x^{2} y^{2} z^{3} \Rightarrow \nabla \times \mathbf{F}=\nabla \times \nabla f=\mathbf{0} \Rightarrow \operatorname{curl} \mathbf{F}=\mathbf{0} \Rightarrow \oint_{C} \mathbf{F} \cdot d \mathbf{r}=\iint_{S} \nabla \times \mathbf{F} \cdot \mathbf{n} d \sigma=\iint_{S} 0 d \sigma=0$

(c) $\mathbf{F}=\nabla \times(x \mathbf{i}+y \mathbf{j}+z \mathbf{k})=\mathbf{0} \Rightarrow \nabla \times \mathbf{F}=\mathbf{0} \Rightarrow \oint_{C} \mathbf{F} \cdot d \mathbf{r}=\iint_{S} \nabla \times \mathbf{F} \cdot \mathbf{n} d \sigma=\iint_{S} 0 d \sigma=0$

(d) $\mathbf{F}=\nabla f \Rightarrow \nabla \times \mathbf{F}=\nabla \times \nabla f=\mathbf{0} \Rightarrow \oint_{C} \mathbf{F} \cdot d \mathbf{r}=\iint_{S} \nabla \times \mathbf{F} \cdot \mathbf{n} d \sigma=\iint_{S} 0 d \sigma=0$

28. $\frac{\partial P}{\partial y}=0, \frac{\partial N}{\partial z}=0, \frac{\partial M}{\partial z}=0, \frac{\partial P}{\partial x}=0, \frac{\partial N}{\partial x}=\frac{y^{2}-x^{2}}{\left(x^{2}+y^{2}\right)^{2}}, \frac{\partial M}{\partial y}=\frac{y^{2}-x^{2}}{\left(x^{2}+y^{2}\right)^{2}} \Rightarrow \operatorname{curl} \mathbf{F}=\left[\frac{y^{2}-x^{2}}{\left(x^{2}+y^{2}\right)^{2}}-\frac{y^{2}-x^{2}}{\left(x^{2}+y^{2}\right)^{2}}\right] \mathbf{k}=\mathbf{0}$. However, $x^{2}+y^{2}=1 \Rightarrow \mathbf{r}=(\cos t) \mathbf{i}+(\sin t) \mathbf{j} \Rightarrow \frac{d \mathbf{r}}{d t}=(-\sin t) \mathbf{i}+(\cos t) \mathbf{j}$

$\Rightarrow \mathbf{F}=(-\sin t) \mathbf{i}+(\cos t) \mathbf{j} \Rightarrow \mathbf{F} \cdot \frac{d \mathbf{r}}{d t}=\sin ^{2} t+\cos ^{2} t=1 \Rightarrow \oint_{C} \mathbf{F} \cdot d \mathbf{r}=\oint_{0}^{2 \pi} 1 d t=2 \pi$ which is not zero.































## Section 16.8，#9,13,19,23,27


### 16.8，9



**Solution**


### 16.8，13



**Solution**


### 16.8，19



**Solution**



### 16.8，23



**Solution**


### 16.8，27



**Solution**

9. $\frac{\partial}{\partial x}\left(x^{2}\right)=2 x, \frac{\partial}{\partial y}(-2 x y)=-2 x, \frac{\partial}{\partial z}(3 x z)=3 x \Rightarrow$ Flux $=\iiint_{D} 3 x d x d y d z$

$$
=\int_{0}^{\pi / 2} \int_{0}^{\pi / 2} \int_{0}^{2}(3 \rho \sin \phi \cos \theta)\left(\rho^{2} \sin \phi\right) d \rho d \phi d \theta=\int_{0}^{\pi / 2} \int_{0}^{\pi / 2} 12 \sin ^{2} \phi \cos \theta d \phi d \theta=\int_{0}^{\pi / 2} 3 \pi \cos \theta d \theta=3 \pi
$$

13. Let $\rho=\sqrt{x^{2}+y^{2}+z^{2}}$. Then $\frac{\partial p}{\partial x}=\frac{x}{\rho}, \frac{\partial \rho}{\partial y}=\frac{y}{\rho}, \frac{\partial p}{\partial z}=\frac{z}{\rho} \Rightarrow \frac{\partial}{\partial x}(\rho x)=\left(\frac{\partial \rho}{\partial x}\right) x+\rho=\frac{x^{2}}{\rho}+\rho$,

$$
\begin{aligned}
& \frac{\partial}{\partial y}(\rho y)=\left(\frac{\partial \rho}{\partial y}\right) y+\rho=\frac{y^{2}}{\rho}+\rho, \frac{\partial}{\partial z}(\rho z)=\left(\frac{\partial \rho}{\partial z}\right) z+\rho=\frac{z^{2}}{\rho}+\rho \Rightarrow \nabla \cdot \mathbf{F}=\frac{x^{2}+y^{2}+z^{2}}{\rho}+3 \rho=4 \rho, \text { since } \\
& \rho=\sqrt{x^{2}+y^{2}+z^{2}} \Rightarrow \text { Flux }=\iiint_{D} 4 \rho d V=\int_{0}^{2 \pi} \int_{0}^{\pi} \int_{1}^{\sqrt{2}}(4 \rho)\left(\rho^{2} \sin \phi\right) d \rho d \phi d \theta=\int_{0}^{2 \pi} \int_{0}^{\pi} 3 \sin \phi d \phi d \theta \\
& =\int_{0}^{2 \pi} 6 d \theta=12 \pi
\end{aligned}
$$

19. For the field $\mathbf{F}=(y \cos 2 x) \mathbf{i}+\left(y^{2} \sin 2 x\right) \mathbf{j}+\left(x^{2} y+x\right) \mathbf{k}, \nabla \cdot \mathbf{F}=-2 y \sin 2 x+2 y \sin 2 x+1=1$. If $\mathbf{F}$ were the curl of a field $\mathbf{A}$ whose component functions have continuous second partial derivatives, then we would have $\operatorname{div} \mathbf{F}=\operatorname{div}(\operatorname{curl} \mathbf{A})=\nabla \cdot(\nabla \times \mathbf{A})=0$. Since $\operatorname{div} \mathbf{F}=1, \mathbf{F}$ is not the curl of such a field.

23. By the Divergence Theorem, the net outward flux of the field $\mathbf{F}=x y \mathbf{i}+\left(\sin x z+y^{2}\right) \mathbf{j}+\left(e^{x y^{2}}+x\right) \mathbf{k}$ over the surface $S$ will be equal to the integral of $\nabla \cdot \mathbf{F}=y+2 y=3 y$ over the region $D$ bounded by $S$. We will integrate using the area in the $z x$-plane bounded by $z=0$ and $z=1-x^{2}$ as the base. The $y$ height at any point $(x, z)$ will be $2-z$. Thus the integral of $\operatorname{div} \mathbf{F}$ over $D$ is

$$
\begin{aligned}
& \left.\int_{-1}^{1} \int_{0}^{1-x^{2}} \int_{0}^{2-z} 3 y d y d z d x=\int_{-1}^{1} \int_{0}^{1-x^{2}} \frac{3}{2} y^{2}\right]_{0}^{2-z} d z d x=\int_{-1}^{1} \int_{0}^{1-x^{2}} \frac{3}{2}(2-z)^{2} d z d x \\
& \left.\left.\quad=\int_{-1}^{1}-\frac{1}{2}(2-z)^{3}\right]_{0}^{1-x^{2}} d x=\int_{-1}^{1} 4-\frac{1}{2}\left(x^{2}+1\right)^{3} d x=\left(\frac{7}{2} x-\frac{1}{3} x^{3}-\frac{3}{10} x^{5}-\frac{1}{14} x^{7}\right)\right]_{-1}^{1}=\frac{184}{35}
\end{aligned}
$$

27. Let $\mathbf{F}_{1}=M_{1} \mathbf{i}+N_{1} \mathbf{j}+P_{1} \mathbf{k}$ and $\mathbf{F}_{2}=M_{2} \mathbf{i}+N_{2} \mathbf{j}+P_{2} \mathbf{k}$

(a) $\mathbf{F}_{1} \times \mathbf{F}_{2}=\left(N_{1} P_{2}-P_{1} N_{2}\right) \mathbf{i}+\left(P_{1} M_{2}-M_{1} P_{2}\right) \mathbf{j}+\left(M_{1} N_{2}-N_{1} M_{2}\right) \mathbf{k}$

$$
\begin{gathered}
\Rightarrow \nabla \times\left(\mathbf{F}_{1} \times \mathbf{F}_{2}\right)=\left[\frac{\partial}{\partial y}\left(M_{1} N_{2}-N_{1} M_{2}\right)-\frac{\partial}{\partial z}\left(P_{1} M_{2}-M_{1} P_{2}\right)\right] \mathbf{i}+\left[\frac{\partial}{\partial z}\left(N_{1} P_{2}-P_{1} N_{2}\right)-\frac{\partial}{\partial x}\left(M_{1} N_{2}-N_{1} M_{2}\right)\right] \mathbf{j} \\
+\left[\frac{\partial}{\partial x}\left(P_{1} M_{2}-M_{1} P_{2}\right)-\frac{\partial}{\partial y}\left(N_{1} P_{2}-P_{1} N_{2}\right)\right] \mathbf{k}
\end{gathered}
$$

consider the i-component only: $\frac{\partial}{\partial y}\left(M_{1} N_{2}-N_{1} M_{2}\right)-\frac{\partial}{\partial z}\left(P_{1} M_{2}-M_{1} P_{2}\right)$

$=N_{2} \frac{\partial M_{1}}{\partial y}+M_{1} \frac{\partial N_{2}}{\partial y}-M_{2} \frac{\partial N_{1}}{\partial y}-N_{1} \frac{\partial M_{2}}{\partial y}-M_{2} \frac{\partial P_{1}}{\partial z}-P_{1} \frac{\partial M_{2}}{\partial z}+P_{2} \frac{\partial M_{1}}{\partial z}+M_{1} \frac{\partial P_{2}}{\partial z}$

$=\left(N_{2} \frac{\partial M_{1}}{\partial y}+P_{2} \frac{\partial M_{1}}{\partial z}\right)-\left(N_{1} \frac{\partial M_{2}}{\partial y}+P_{1} \frac{\partial M_{2}}{\partial z}\right)+\left(\frac{\partial N_{2}}{\partial y}+\frac{\partial P_{2}}{\partial z}\right) M_{1}-\left(\frac{\partial N_{1}}{\partial y}+\frac{\partial P_{1}}{\partial z}\right) M_{2}$ $=\left(M_{2} \frac{\partial M_{1}}{\partial x}+N_{2} \frac{\partial M_{1}}{\partial y}+P_{2} \frac{\partial M_{1}}{\partial z}\right)-\left(M_{1} \frac{\partial M_{2}}{\partial x}+N_{1} \frac{\partial M_{2}}{\partial y}+P_{1} \frac{\partial M_{2}}{\partial z}\right)+\left(\frac{\partial M_{2}}{\partial x}+\frac{\partial N_{2}}{\partial y}+\frac{\partial P_{2}}{\partial z}\right) M_{1}-\left(\frac{\partial M_{1}}{\partial x}+\frac{\partial N_{1}}{\partial y}+\frac{\partial P_{1}}{\partial z}\right) M_{2}$

Now, i-comp of $\left(\mathbf{F}_{2} \cdot \nabla\right) \mathbf{F}_{1}=\left(M_{2} \frac{\partial}{\partial x}+N_{2} \frac{\partial}{\partial y}+P_{2} \frac{\partial}{\partial z}\right) M_{1}=\left(M_{2} \frac{\partial M_{1}}{\partial x}+N_{2} \frac{\partial M_{1}}{\partial y}+P_{2} \frac{\partial M_{1}}{\partial z}\right)$;

likewise, i-comp of $\left(\mathbf{F}_{1} \cdot \nabla\right) \mathbf{F}_{2}=\left(M_{1} \frac{\partial M_{2}}{\partial x}+N_{1} \frac{\partial M_{2}}{\partial y}+P_{1} \frac{\partial M_{2}}{\partial z}\right)$;

$\mathbf{i}$ comp of $\left(\nabla \cdot \mathbf{F}_{2}\right) \mathbf{F}_{1}=\left(\frac{\partial M_{2}}{\partial x}+\frac{\partial N_{2}}{\partial y}+\frac{\partial P_{2}}{\partial z}\right) M_{1}$ and $\mathbf{i}-\operatorname{comp}$ of $\left(\nabla \cdot \mathbf{F}_{1}\right) \mathbf{F}_{2}=\left(\frac{\partial M_{1}}{\partial x}+\frac{\partial N_{1}}{\partial y}+\frac{\partial P_{1}}{\partial z}\right) M_{2}$.

Similar results hold for the $\mathbf{j}$ and $\mathbf{k}$ components of $\nabla \times\left(\mathbf{F}_{1} \times \mathbf{F}_{2}\right)$. In summary, since the corresponding

components are equal, we have the result $\nabla \times\left(\mathbf{F}_{1} \times \mathbf{F}_{2}\right)=\left(\mathbf{F}_{2} \cdot \nabla\right) \mathbf{F}_{1}-\left(\mathbf{F}_{1} \cdot \nabla\right) \mathbf{F}_{2}+\left(\nabla \cdot \mathbf{F}_{2}\right) \mathbf{F}_{1}-\left(\nabla \cdot \mathbf{F}_{1}\right) \mathbf{F}_{2}$

(b) Here again we consider only the $\mathbf{i}$-component of each expression. Thus, the $\mathbf{i}$-comp of $\nabla\left(\mathbf{F}_{1} \cdot \mathbf{F}_{2}\right)$

$=\frac{\partial}{\partial x}\left(M_{1} M_{2}+N_{1} N_{2}+P_{1} P_{2}\right)=\left(M_{1} \frac{\partial M_{2}}{\partial x}+M_{2} \frac{\partial M_{1}}{\partial x}+N_{1} \frac{\partial N_{2}}{\partial x}+N_{2} \frac{\partial N_{1}}{\partial x}+P_{1} \frac{\partial P_{2}}{\partial x}+P_{2} \frac{\partial P_{1}}{\partial x}\right)$

i-comp of $\left(\mathbf{F}_{1} \cdot \nabla\right) \mathbf{F}_{2}=\left(M_{1} \frac{\partial M_{2}}{\partial x}+N_{1} \frac{\partial M_{2}}{\partial y}+P_{1} \frac{\partial M_{2}}{\partial z}\right)$,

$\mathbf{i}$-comp of $\left(\mathbf{F}_{2} \cdot \nabla\right) \mathbf{F}_{1}=\left(M_{2} \frac{\partial M_{1}}{\partial x}+N_{2} \frac{\partial M_{1}}{\partial y}+P_{2} \frac{\partial M_{1}}{\partial z}\right)$,

i-comp of $\mathbf{F}_{1} \times\left(\nabla \times \mathbf{F}_{2}\right)=N_{1}\left(\frac{\partial N_{2}}{\partial x}-\frac{\partial M_{2}}{\partial y}\right)-P_{1}\left(\frac{\partial M_{2}}{\partial z}-\frac{\partial P_{2}}{\partial x}\right)$, and

i-comp of $\mathbf{F}_{2} \times\left(\nabla \times \mathbf{F}_{1}\right)=N_{2}\left(\frac{\partial N_{1}}{\partial x}-\frac{\partial M_{1}}{\partial y}\right)-P_{2}\left(\frac{\partial M_{1}}{\partial z}-\frac{\partial P_{1}}{\partial x}\right)$.

Since corresponding components are equal, we see that

$\nabla\left(\mathbf{F}_{1} \cdot \mathbf{F}_{2}\right)=\left(\mathbf{F}_{1} \cdot \nabla\right) \mathbf{F}_{2}+\left(\mathbf{F}_{2} \cdot \nabla\right) \mathbf{F}_{1}+\mathbf{F}_{1} \times\left(\nabla \times \mathbf{F}_{2}\right)+\mathbf{F}_{2} \times\left(\nabla \times \mathbf{F}_{1}\right)$, as claimed.