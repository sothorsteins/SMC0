# SMC0

# Introduction
The purpose of this project was to reverse-engineer a product related to subjects of Sound and Music Computing. We chose to reverse-engineer **Polytune 3**, a guitar tuner pedal from the Danish company TC Electronic.
### Polytune 3
The most interesting feature of the Polytune pedals from TC Electronic is their polyphonic pitch detection, which allows tuning of all strings of the guitar (or other electric string instrument) at once. This feature makes the tuning process a bit faster, and can especially be useful while tuning live on stage between songs.

Link to product: https://www.tcelectronic.com/product.html?modelCode=P0CM0

Link to product video presentation: https://www.youtube.com/watch?v=NUtpFd3377Y

# Requirements

The following is a list of non-function and functional requirements the product should meet. The requirement were made based on the functionality, size and price of the Polytuner.  

**Non-functional requirements:**

1. Shoud detect if one string or several strings are playing
2. Should have quick polyphonic pitch detection
3. Should have different interfaces
4. Should be usable with multiple instruments
5. Should be affordable for end-consumer
6. Should have fit in small enclosure
7. Should have precise accuracy
8. Should keep the strength of the signal effectively
9. Should be able t o work with standard jack-cables for guitar/bass
10. Should work hands-free
11. User should be able to visually and quickly see tuning of instrument


**Functional requirements:**

1. 
    - Should do spectral analysis to identify single mode or Polyphonic mode
    - Should have different tunings (D/G) for single  mode
2. Should have real time low-latency sound processing (less than 0.5 s.)
3. Should have classic tuner in simple mode (needle, horizontal), polyphonic in vertical position 
4. Should show 4 verticals for bass, and 6 verticals for guitar
5. Should use affordable materials
6. 
    - The microchip should be small
    - Should Ffit 2 jack inputs in a smaller space + other hardware stuff
7. 
    - Input signal needs to be quite clean (so through jack, not microphone for example)
    - Should have high accuracy of 0.5 cent, although less accurate for polyphonic tuning
8. Should have bonafide buffering
9. Should have quarter inch jack for input/output and power supply input
10. Should have footswitch
11. Should have color display / green and red diodes

# Tasks and milestones

The following is a list of milestones and tasks based on the requirements.  

1. Background research completed
    - a. Research materials 
    - b. Research polyphonic pitch detection
        - How advanced is it? 
        - How much processing power does it take?
    - c. Research other state of the art products / software
        - What was their challanges? 
        - How are the products designed? 
2. Project plan completed  
    - a. Create tasks to be done
    - b. Create milestones / deadlines / time estimates on tasks 
    - c. Put these tasks into Jira 
    - d. Assign tasks to different teams 
3. Low-fi prototype tested
    - a. Make a design for the pedal and the interface
    - b. Test the design 
    - c. Focus group test
4. Polyphonic pitch estimation algorithm implemented
    - a. Develop polyphonic detection algorithm based on research
    - b. Test the effectiveness of the code / is it accurate enough
        - Build automatic tests for development
    - c. Evaluate, debug
5. Algorithm ported to microchip
    - a. Test different microchips (e.g. bela) for lowest latency 
    - b. Evaluate, debug and optimize code if latency is too high 
        - Goal is for latency to be less than 0.5 s.
6. User-interface designed (UI/UX-designers) 
    - a. Make initial design with Figma
        - One-string mode design
        - 6-string mode design
    - b. Evaluate interface on guitar players 
        - Are they able to understand the information? 
    - c. Create and implement final design
7. Design of circuit board and enclousure done
    - a. Develop 3D model in AutoCAD of product based on low-fi prototype results 
    - b. Decide on materials for product (should be low-cost) and estimate production cost 
    - c. Design circuit board
    - d. Make final design
    - e. Evaluate, debug 
8. Final product evaluation finished
    - a. Evaluate if requirements are met or are close to being met
    - b. Plan evaluation
    - c. Define beta tester group
    - d. Give product to selected beta testers
    - e. Evaluate if all requirements have actually been met
    - f. Fix bugs that beta testers encounter

# Project plan / Gantt Chart
