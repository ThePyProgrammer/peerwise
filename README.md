# Peerwise
My questions on Peerwise.

## InfiniteStream (Magnetostatic)
<p align="center">
  <img src="Y4S1/Magnetostatic/InfiniteStream/infiniteStream.png" align="center" height="360" />
</p>

### Question
Let's say you have an infinite stream of electrons spaced s = 1mm apart. These electrons are initially charged with an initial kinetic energy of E<sub>k</sub> = 20keV. These electrons enter a changing magnetic field ![formula](https://render.githubusercontent.com/render/math?math=B_1%20=%20B_o\sqrt{e^{t^2-1}%2B5}), where B<sub>o</sub> = 2.3232323232...T facing out of the page. Certainly, we can therefore gather that the stream tilts upwards, but let's just assume the radius r is constant.

After a time T = 5s, this stream exits the magnetic field to move an arbitrary distance upwards to enter a wire loop of mass M = 16kg and diameter d = 3cm. After exiting the loop, the electrons just leave to an electron storage, never to be seen again. Now, once there is assured to be absolutely no change in the current of the loop, a uniform magnetic field B<sub>2</sub> = 2.1111111...T facing downwards perpendicular to the electrons' motion before entering the loop is placed on the loop, and a torque is therefore exerted. Find the angular velocity of the loop when it rotates exactly ![formula](https://render.githubusercontent.com/render/math?math=\frac{\pi}{2}) radians.


The moment of inertia of a hoop about any diameter, ![formula](https://render.githubusercontent.com/render/math?math=I_{loop}%20=%20\frac{1}{2}MR^2).

The mass of an electron, ![formula](https://render.githubusercontent.com/render/math?math=m_e%20=%209.109383701528%20\times%2010^{-31}%20kg).

The elementary charge, ![formula](https://render.githubusercontent.com/render/math?math=q_e%20=%201.602176634%20\times%2010^{-19}%20C).


## Inator (Electrostatic)

### Question
<p>Let's say you have devised a system called the "Stop-Time-inator" that has allowed you to momentarily stop time. In that moment, no effect of force is seen but the force you yourself apply, and your physical body does not age. You thus stop time and open up a dimension, let's just call this the Cartesian Dimension, where it's just a single infinite plane with no gravitational force present. You enter it, starting at a certain origin which is assumed to be the centre of this dimension. From here, you can also see four paths around you, representing the positive and negative x-axis and positive and negative y-axis of the Cartesian Coordinate plane. Now, in stopped time, you get to work.</p>
<p>You bring along a device called the "Charged-Particle-inator" which releases a charged particle of charge q, set by the user. Now, you place your hand on the knob and cover the dial so that you cannot see the charge q that you set. You turn the knob and release it. Let's say this charge is denoted as a value q<sub>o</sub>.</p>
<p>Now, you decide to do very interesting thing: you use the python random module to generate a random integer between 2 and a super large number. You label this value as k in the interpreter, but do not check what k is. Now you load this values of k into a "Move-inator", which allows you to go to a specific x and y with respect to the assumed origin. What this "Move-inator" now does is it sends the&nbsp;"Charged-Particle-inator" to points (k<sup>n</sup>, k<sup>n</sup>) for all n from 0 to infinity (let's just assume that the "Move-inator" is able to do this within the stopped time) and releases one charge there.</p>
<p>Now it returns, and you haven't died (consider yourself lucky). Now you have set the Move-inator to go to the points&nbsp;(-k<sup>n</sup>,- k<sup>n</sup>) for all n from 0 to infinity (again, let's just assume that the "Move-inator" is able to do this within the stopped time), and to each n, it swaps another charge knob that toggles the charge between positive and negative while keeping the magnitude intact (i.e. at (-k<sup>0</sup>, -k<sup>0</sup>), a negative charge of q<sub>o</sub> is released, while at (-k, -k), a positive charge of q<sub>o</sub> is released and so on).&nbsp;</p>
<p>Now you use another device you have created called the "Uncharge-inator" and use it to completely discharge yourself, and then another called the "Charge-inator" to charge yourself to the same q<sub>o</sub> which you still do not know. Now you relocate to the assumed origin and stop the the "Stop-Time-inator". What is the acceleration that you, a 60-year old esteemed physicist who has spent years devising this complex system and has a mass of m, experience?</p>

### Answer
<p>To calculate this, you must use the formula F = (1/4&pi;&epsilon;0) * (Qq/r<sup>2</sup>).</p>
<p>Here, we know that Q and q are both equal to q<sub>o</sub>, which you already know as a constant, but the direction may change based on the charge of the charges dropped by the "Charged-Particle-inator".</p>
<p>Thus, you extract it as F = (q<sub>o</sub>/4&pi;&epsilon;0) * 1/r<sup>2</sup>.</p>
<p>To calculate r<sup>2</sup>, what you do is you calculate based on the points as given. From this we have r<sup>2</sup> = k<sup>2n</sup> + k<sup>2n</sup> = 2k<sup>2n</sup>.<sup><br /></sup></p>
<p>We thus derive a series representing the force exhibited for the positive direction (i.e. x and y are both positive) F<sub>1</sub> =&nbsp;(q<sub>o</sub>/4&pi;&epsilon;<sub>0</sub>) * (1/2k<sup>0</sup>&nbsp;+ 1/2k<sup>2</sup> + 1/2k<sup>4</sup> + ....), which faces south-west.</p>
<p>Meanwhile, we can also derive a similar&nbsp;series representing the force exhibited for the positive direction (i.e. x and y are both positive) F<sub>2</sub> = (q<sub>o</sub>/4&pi;&epsilon;<sub>0</sub>) * (1/2k<sup>0</sup>&nbsp;- 1/2k<sup>2</sup> + 1/2k<sup>4</sup>&nbsp;- ....), which faces south-west as well.</p>

<p>We add these two forces up and we get F<sub>net</sub> =&nbsp;(q<sub>o</sub>/4&pi;&epsilon;<sub>0</sub>) *&nbsp;(1/k<sup>0</sup>&nbsp;+ 1/k<sup>4</sup>&nbsp;+ 1/k<sup>8</sup>&nbsp;+ ....), which faces south-west.</p>

<p>Now, I would like to divert to derive an expression for S = 1/k<sup>0</sup> + 1/k<sup>4</sup> + 1/k<sup>8</sup> + ...</p>
<p>To do this, we derive k<sup>4</sup>S = k<sup>4</sup> + 1/k<sup>0</sup> + 1/k<sup>4</sup> + .... = k<sup>4</sup> + S</p>
<p>From this, we get S = k<sup>4</sup>/(k<sup>4</sup> - 1)</p>

<p>Now substituting back in, we get F<sub>net</sub> =&nbsp;(q<sub>o</sub>/4&pi;&epsilon;<sub>0</sub>) * (k<sub>4</sub>/(k<sub>4</sub> - 1)) = ma</p>
<p>:. a =&nbsp;(q<sub>o</sub>/4&pi;&epsilon;<sub>0</sub>) * (k<sup>4</sup>/m(k<sup>4</sup> - 1)), facing south-west</p>
