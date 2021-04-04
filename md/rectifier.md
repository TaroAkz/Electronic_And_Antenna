## Rectifiers
Now we come to the most popular application of the diode: _rectification_. Simply defined, rectification is the conversion of alternating current(AC) to direct current (DC). This involves a device that only allows one-way flow of electric charge. As we have seen, this is exactly what a semiconductor diode does. The simplest kind of rectifier circuit is the _half-wave_ rectifier. It only allows one half of an AC waveform to pass through to the load.
![Rectifier](/image/rectifier-circuit.jpg)

### Half-Wave Rectifiers
half-wave rectification is insufficient for the task. The harmonic content of the rectifier’s output waveform is very large and consequently difficult to filter. Furthermore, the AC power source only supplies power to the load one half every full cycle, meaning that half of its capacity is unused. Half-wave rectification is, however, a very simple way to reduce power to a resistive load. Some two-position lamp dimmer switches apply full AC power to the lamp filament for “full” brightness and then half-wave rectify it for a lesser light output.
![Half-Wave-Rectifier](/image/half-wave-rectifier-circuit.jpg)

### Full-wave rectifier
If we need to rectify AC power to obtain the full use of _both_ half-cycles of the sine wave, a different rectifier circuit configuration must be used. Such a circuit is called a _full-wave_ rectifier. One kind of full-wave rectifier, called the _center-tap_ design, uses a transformer with a center-tapped secondary winding and two diodes, as in the figure below.
![Full-Wave-Rectifier](/image/full-wave-rectifier-center-tapped-design.jpg)

### Positive Half-Cycle
This circuit’s operation is easily understood one half-cycle at a time. Consider the first half-cycle, when the source voltage polarity is positive (+) on top and negative (-) on bottom. At this time, only the top diode is conducting; the bottom diode is blocking current, and the load “sees” the first half of the sine wave, positive on top and negative on bottom. Only the top half of the transformer’s secondary winding carries current during this half-cycle as in the figure below.
![Half-Wave-Rectifier+](/image/full-wave-center-tap-rectifier-positive-half-cycle.jpg)

### Negative Half-Cycle
During the next half-cycle, the AC polarity reverses. Now, the other diode and the other half of the transformer’s secondary winding carry current while the portions of the circuit formerly carrying current during the last half-cycle sit idle. The load still “sees” half of a sine wave, of the same polarity as before: positive on top and negative on bottom.
![Half-Wave-Rectifier-](/image/full-wave-center-tap-rectifier-negative-half-cycle.jpg)