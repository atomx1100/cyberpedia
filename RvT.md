# RvT

**Goal**

to understand RvT, i need to understand the AC resistance bridge and the type of measurement performed
think about what i can add in my masters report

1. northon+find basic patterns
2. apply to what im doing
3. memorize rvt system

should i do exercises?

todo:
- look in white notebook for questions to answer
- map out RvT system
- understand how the scanner work, what pins need to be provided current and voltage
- finding the basic concepts from which everything follows and building mental constructions of these concepts
- memorize the functioning of the ac resistance bridge 370

tentative plan:
1. thenevin+northon thm
2. source transformation
3. summarize notes so far, write about it, mental constructions, what to memorize (loop-back method, calculations of thenevin emf and resistance)
4. two-terminal networks  application is for voltage divider, first-order filters, IV characteristics, wire resistance measurement 
5. ac current features
6. impedance, input/output impedance
7. lock-in amplifier

later:
- for practical considerations of RvT, see "measurement, instrumentation and sensors" book

**Questions**
- whats the difference between the amplification in a lock-in amplifier and an amplifier?
- whats a linear network?

- what does thenevin thm says?
- whats its physical meaning 
- how does it apply to circuits in the lab and measurement?
- look up measurement of input and output impedance using resistors
- i need better intuition of electrical circuits-->solve problems everyday
- 



### ac current and voltage
introduce time dep current and voltage, periodic in time (sinuosidal)
important quantities:
- amplitude
- frequency/period (characterize the length of the repeated pattern in time)
- phase (time indep)

sinuosidal waveform-->oscillates about 0, current changes direction

when you have mutliple currents and voltages simultaneously with the same frequency, then you have the concept of phase difference becomes important (there can also be a phase difference between a current and its voltage because of inductors or capacitors)
-->phase difference is only meaningful when refering to waveform with the same frequency

Power (energy per time)-->why is it an important quantity in electrical circuit?
power becomes time dependent so you have 
- instantaneous power
- average power in time per cycle 

RMS (root mean squared) current and voltage, since we are concerned with sinuosidal currents adn voltages, their mean is 0, so to get an average value associated with the current over one cycle, we look at the sqrt of the mean of current square, sqrt(<I^2>)
the usefulness of the RMS values is that dc power formula applies for the average power of resistive loads

#### complex representation
can use complex representation because of relationship between sin/cos and euler formula
whats the relation between sin/cos function and complex numbers?


### steady state vs transient
the steady state is the transient state when t-->infty or when t>>tau (the decay transient time)
transient circuit usually have a switch


### resistance and impedance
understand resistance microscopically vs understanding resistance at a behavior level

what does it mean that capacitor and inductor leads to a phase difference between the current and voltage while no phase difference for a resistor?
what does it mean that the voltage and current have a phase difference, what are the physical consequences?

power is dissipated in a resistor, capacitor and inductor stores the energy in E-field and B-field, respectively

### practical application of electrical circuits theory
identify the components
first draw the circuit
analyze the circuit
run experiments if the analysis predicts the behavior the circuits

**what type of intuition to develop about electrical circuits?**
- what behaviors to expect from circuit X
- numerical estimation
- 

### types of circuits
make a list of all the most basic types of circuits with their associated behavior and their function/use
eg. dc in series and parallel of one resistor and one capacitor
eg. ac in series of resistor and inductor
