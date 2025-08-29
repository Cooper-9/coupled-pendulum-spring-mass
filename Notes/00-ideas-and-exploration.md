# Exploraiton of interesting problems involving driven oscillators/pendulums
Summarize our exploration of interesting problems and simpler variants that we can use to orient our understanding. 

## Some interesting quesitons to explore
- How do we calculate the center of mass for a complicated object
  - ...and how do we approach this problem if it is not ridgid?
- Can we understand and predict the dynamics of the driven pendulum?
  - is there a closed-form solution?
- How do things change when the pendulum motion affects the driver's motion?

### Driven rigid pendulum
**What do we know about pendulum motion:**
- Make strong statements about forces, _torques_, potential/kinetic energy
  - need to remind ourselves about polar coordinates and angular motion
  - $\vec{F}_g = -mg\hat{y}$
  - $\omega = 2\pi f = 2\pi/T$
- What do we remember about a pendulum
  - simple harmonic motion (_when_?)
    - **guess:** between $\pm 90^{\circ}$?
  - we expect that simple harmonic motion breaks down for large starting displacements of the pendulum
- Driven pendulum
  - [Video of driven rigid pendulum]()
  - seems dependent on driving frequency

## Questions for the Assignment
- How do you expect the rigid pendulum will respond if the frequency of the drive is much higher or much lower than the natural frequency ( $\omega = \sqrt(g/L)$ of the pendulum (for small oscillations) and the amplitude is small compared to the size of the pendulum?
  - I would expect the pendulum to experience motion similar to that of the inverted driven pendulum example. (Where it had the tendency to return to a neutral position.) When driven much lower than the natural frequency, I guess that the motion would appear almost random and 'awkward' compared to that of the regular frequency.
- If the pendulum is slightly displaced from equilibrium and the pivot point moves down abruptly, what will happen to the pendulum's displacement angle?
    - If this happened I would expext the 'arm' of the pendulum to go up compared to the moment before, making the angle increase momentarily.
- If we start the pendulum oriented above its pivot point, at its unstable equilibrium angle, if the pivot point moves down as the pendulum begins to fall, what is your expectation of the behavior?
  - As I said in the previous example, driving the pivot down should momentarily increase the angle of the pendulum. So in this case I believe it would return to near unstable equilibrium where it began. 
