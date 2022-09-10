# Stuff

First, there are 4 main kinematic equations that you should know.  The equations are:

- $v = v_0 + at$
- $\Delta x = \left(\frac{v + v_0}{2}\right) t$
  - **Note**: $x$ is typically used when discussing horizontal displacement and $y$ is typically used when discussing vertical displacement.
- $\Delta x = v_0 t + \frac{1}{2} a t^2$
- $v^2 = v_0^2 + 2 a \Delta x$

Hopefully, these equations align with your textbook.  Each formula is missing one of the five kinematic variables, which are:

- $\Delta y$  - vertical displacement (which is equal to $y_2 - y_1$, where $y_1$ is equal to the initial vertical position and $y_2$ is equal to the final vertical position).
- $t$ - time
- $v_0$ - initial velocity
- $v$ - final velocity
- $a$ = constant acceleration (due to gravity)

---

## Question: You toss a ball straight up with an initial speed of 20 m/s.  How high does it go?

Out of the 5 variables noted above, which ones do you know, based on the question asked?

- **Initial velocity**, $v_0$, is equal to $20 \frac{m}{s}$ (this is given).
- **Acceleration**, $a$, is a constant due to gravity and is equal to $-9.8 \frac{m}{s^2}$ (since it is acting in the opposite direction of the flight of the ball, it is noted as being negative.)
- **Final velocity**, $v$, is equal to 0.  This can be a little tricky.  Note that the ball has an instantaneous velocity of zero at the very top of its upward flight, before it starts falling back towards the ground.
- **Starting position**, $y_0$, is equal to 0 meters.  This can be tricky, too.  Assume that the starting position (when the ball is in your hand) is equal to 0 meters.

Looking back at the 4 kinematic equations, you need to find one that involves the known variable highlighted above.  Given this, we  should choose the following equation:

$$v^2 = v_0^2 + 2 a \Delta y$$

But first, we need to get $y_2$ alone on the left side of the equation as follows:

$$\begin{align*}
v^2 &= v_0^2 + 2a \Delta y \\
v^2 &= v_0^2 + 2a (y_2 - y_1) \\
v^2 - v_0^2 &= 2a (y_2 - y_1) \\
\frac{v^2 - v_0^2}{2a} &= y_2 - y_1 \\
\frac{v^2 - v_0^2}{2a} + y_1 &= y_2 \\
y_2 &= \frac{v^2 - v_0^2}{2a} + y_1 \\
\end{align*}$$

Now, plug-n-chug (and make sure that units cancel correctly!):

$$\begin{align*}
  y_2 &= \frac{0^2 - (20 \frac{m}{s})^2}{2 (-9.8 \frac{m}{s^2})} + 0 \\
  y_2 &= \frac{(- 400 \frac{m^2}{s^2})}{2 (-9.8 \frac{m}{s^2})} \\
  y_2 &= 20.41 m
\end{align*}$$

## Question: How long is it in their air, neglecting air resistance?

Again, think about what you know:

- $\Delta y = 20.41 m$ (from first question)
- $v_0 = 20 \frac{m}{s}$
- $v_1 = 0 \frac{m}{s}$
- $a = -9.8 \frac{m}{s}$

Now, go check out the kinematic equations and pick one that involves the values noted above and $t$ (since that is what the question is asking us to find).  I would pick the following equation, since it is easy to manipulate:

$v = v_0 + at$

Now, get $t$ alone on the left side of the equation:

$$\begin{align*}
  v &= v_0 + at \\
  v - v_0 &= at \\
  t &= \frac{v - v_0}{a}
\end{align*}$$

Now, plug-n-chug (and make sure the units cancel correctly!):

$$\begin{align*}
  t &= \frac{v - v_0}{a} \\
  t &= \frac{0 \frac{m}{s} - 20 \frac{m}{s}}{-9.8 \frac{m}{s^2}} \\
  t &= \frac{-20 \frac{m}{s}}{-9.8 \frac{m}{s^2}} \\
  t &= 2.04 s
\end{align*}$$
