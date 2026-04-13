# 🌌 Planet-Orbit-Around-the-Sun-Simulation
A simulation of planets orbiting around the Sun

## 📌 Introduction
This project showcases planetary motion around the sun using **Newtonian mechanics** and **Python visualization tools**.  
The goal is to demonstrate how gravitational forces govern planetary orbits and to create an interactive, visual model of the solar system.

---

## ⚙️ Project Workflow
1. **Physics Setup**  
   - Applied Newton’s law of gravitation to calculate forces between planets and the Sun.
   - Used **F = G(Mm/r²)** to calculate the gravational force between the planets and the sun.
  
2. **Constants Used**
   - AU is Astronomical unit. It is multiplied by 1000 to convert it into meters.
   - G denotes gravity.
   - Scale is the zoom of the view of your simulation.
   - TIMESTEP displays the timeframe of 1 day.

4. **Simulation**  
   - Initialized planets with approximate masses, radius, velocities in the x and y direction denoted by x_vel and y_vel respectively.
   - Simulated orbital paths step by step.  

5. **Visualization**  
   - Plotted orbits using `pygame`.  
   - Added the distance of the planets from the sun to show elpitical motion of the planets.  

---

## 🛠️ Technologies Used
- Python 3.12 
- Jupyter Notebook  
- Libraries: 'math', 'pygame'  

---

## 📊 Results
- Generated plots showing elliptical orbits around the Sun.  
- Animated simulation of multiple planets moving simultaneously.

---

## Future Work:
- Add more planets (the current model only includes mercury, venus, earth, and mars)
- Make better visualization by adding better graphics.

--- 

**Example Screenshot:**

<img width="683" height="679" alt="image" src="https://github.com/user-attachments/assets/16575091-8736-40ca-ac6a-23a90c87e08f" />

---

## Medium Article:
I wrote a Medium article explaining the steps in details. Here's the link
https://medium.com/@manumfatima2000/simulation-of-planetary-motion-70cf99e84ad2

--- 

## Work Inspired by:
- TechWithTim: https://www.youtube.com/watch?v=WTLPmUHTPqo

