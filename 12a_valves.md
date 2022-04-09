# 12. Valves (or tubes)

## Definitions
- **Cathode** = positive, **Anode** = negative
- **Diode Valve** is a valve having two electrodes (Cathode and anode)
- **Triode Valve** is a valve having three electrodes (Cathode, anode and control grid)
- **Tetrode Valve** is a valve having four electrodes (Cathode, anode, control grid and screen grid)
- **Pentode** is a valve with five electrodes (Cathode, anode, control grid, screen grid and suppressor grid)


## Diagrams

- Actual valve amplifier (audio)

  ![](img/tube_amp_irl.jpg)

- Triode

  ![](img/triode.png)
  
- Tetrode

  ![](img/tetrode.jpg)
  
- Pentode

  ![](img/pentode.png)

## Graphs

- Grid voltage

  ![](img/grid-voltage.png)

## Notes

### Diodes

- By heating a metal, electrons on the surface of the metal become very agitated and electrons will escape from its surface.
- A diode is constructed with two electrodes: anode and cathode (heater not included)
- Cathode is tied to ground.
- High voltage is applied to the anode of the tube (also called plate)
- Cathode is coated with Barium Oxide
- Cathode is heated by a filament (made of heating wire)
- Liberated negative electrons are attracted to the anode because it is at a positive potential
- Like a semiconductor diode, reversing the polarity of the diode blocks current flow since electrons will not escape from a positive cathode

### Triodes 

- To amplifiy, there has to be a means of controlling the flow of electrons from the cathode to the anode.
- This is achieved by adding a wire mesh (grid) between the cathode and the anode
- The grid is widely spaced so it does not "physically" impede the electron stream
- When a negative signal is applied to the grid, it will repel some of the negative electrons and therefore reducing electron flow from cathode to anode.
- Conversely, applying a positive signal to the gride causes more electrons to be attracted, and thus, more electrons reach the anode
- Thus, since applying a small current can control a larger current flow, the valve can thus amplify the signal.
- Such a tube with an anode, cathode and grid is called a triode.

### Tetrodes

##### Issues with triodes
- The space between the cathode, anode and grid of a triode gives rise to interelectrode capacitance.
  - This makes it **not suitable** for high frequency applications
  - This also gives rises to feedback, which could lead to instability

- Triode interelectrode capacitance:

  ![](img/triode_inter_capacitance.jpg)
  
##### The solution:
- Placing another grid in between the anode and cathode helps reduce the interelectrode capacitance (series capacitance)
  - This grid is called the screen grid.
  - Usually tied to a high voltage in respect to the cathode.
    - This enhances the attraction of electrons from the cathode to the anode as well.
    - Leads to a higher gain.
  
- Tetrode configuration:

![](img/tetrode_amp_cir.png)

### Pentodes
- You may be asking: "Why do we need so many different kinds of tubes?"

##### Issues with tetrodes:
- Remember how the screen grid helps enhance the attraction of electrons to the anode?
- At times, the electrons can have so much energy that when it hits the anode, that they dislodge electrons from its surface.
   - This is called "secondary emission"
   - Has a detrimental effect to gain.
   - Impedes flow of current in the tube
   

##### The solution:
- Add another grid in between the cathode and anode =P
  - Tied to cathode.
  - Since cathode is more negative in respect to the anode, secondary emission of electrons is reduced.
  
- Part of amplifier circuit, using a pentode:

![](img/pentode_amp_cir.jpg)


### Example circuit (TODO: re-write or remove)


Advantages:

- A valve will withstand a certain amount of 'mistreatment' during tuning
- A valve is more easily matched to the aerial circuit
- A poor SWR will tolerated by a valve

Disadvantages:

- Requires a high voltage power supply
- Fragile; requires care when handling!
- Precautions necessary to avoid electric shock
- Valves wear out and require replacement which is likely to be expensive
- Less convenient for 'mobile' operation
