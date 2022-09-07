# SMC0

# Introduction
The purpose of this project was to reverse-engineer a product related to subjects of Sound and Music Computing. We chose to reverse-engineer **Polytune 3**, a guitar tuner pedal from the Danish company TC Electronic.
### Polytune 3
The most interesting feature of the Polytune pedals from TC Electronic is their polyphonic pitch detection, which allows tuning of all strings of the guitar (or other electric string instrument) at once. This feature makes the tuning process a bit faster, and can especially be useful while tuning live on stage between songs.
# Requirements

The following is a list of non-function and functional requirements the product should meet. The requirement were made based on the functionality, size and price of he Polytuner.  

Non-functional requirements:

1. Detect if one string playing or many strings - automatically switch between interfaces
2. Very quick detection
3. Different interfaces
4. Multiple instruments
5. Affordable
6. Small size
7. Good accuracy
8. Keep the strength of the signal 
9. Should be able to work with standard jack-cables for guitar/bass
10. Working hands-free
11. Visually and quickly be able to see tuning accuracy



Functional requirements:

1. 
    - Do Spectrum analysis to identify Single mode or Polyphonic mode
    - Different tunings (D/G)  for single mode
2. Real time low-latency processing (less than 0.5 s.)
3. Classic tuner in simple mode (needle, horizontal), polyphonic in vertical position 
4. Show 4 verticals for bass, and 6 verticals for guitar
5. Use affordable materials
6. 
    - Small microchip 
    - Fit 2 jack inputs in a smaller space + other hardware stuff
7. 
    - Signal needs to be quite clean (so through jack, not microphone for example)
    - Accuracy of 0.5 cent, although less accurate for polyphonic tuning
8. Bonafide buffering
9. Quarter inch jack for input/output and power supply input
10. Footswitch
11. Color display / green and red diodes

# Tasks and milestones

Based on the requirements for the product a list of tasks and milestones was made. 

1. Research of state of the art - what have others done, what are their issues - learn from this
    - a. Research materials 
    - b. Research polyphonic pitch estimation
        - How advanced is it? 
        - How much processing power does it take?
    - c. Research other similar product / software 
2. Plan the project 
    - a. Create tasks to be done
    - b. Create milestones / deadlines / time estimates on tasks 
    - c. Put these tasks into Jira 
3. Create low-fi prototype (maybe paper prototype)
    - a. Make a design for the pedal and the interface
    - b. Test the design 
    - c. Focus group test
4. Create “prototype” in software based on research for polyphonic spectral analysis (this can be in matlab), proof-of-concept. 
    - a. Develop polyphonic detection algorithm based on research
        - Do FFT
        - Do filtering
    - b. Test the effectiveness of the code / is it accurate enough
        - Build automatic tests for development
5. Port the code to a microchip (DSP-chip) e.g. c++ 
    - a. Test different microchips for lowest latency 
    - b. Optimize code if latency too high 
    - c. Goal is for latency to be less than 0.5 s.
6. Create user-interface (UX-designers) 
    - a. Make initial design with Figma or other similar platform
        - One-string mode design
        - 6-string mode design
    - b. Test on guitar players - are they able to understand the information
    - c. Create and implement final design
7. Create circuit / design of physical product
    - a. Develop 3D model of product design based on low-fi prototype results
    - b. Decide on materials for product (low-cost) and estimate production cost 
    - c. Design circuit -board
    - d. Make final design
    - e. Evaluate, debug 
8. Final evaluation 
    - a. Evaluate if requirements are met or are close to being met
    - b. Plan evaluation
    - c. Define beta tester group
    - d. Give product to selected beta testers
    - e. Evaluate if all requirements have actually been met
    - f. Fix bugs that beta testers encounter






# Project plan / Gantt Chart
