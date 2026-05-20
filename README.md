# Dispersion-Limited-Fiber-Length
Dispersion Limited Fiber Length
# Objective: 
 
Calculate the dispersion-limited fiber length for a fiber optic transport system that 
employs standard single-mode fiber and a directly-modulated single-mode laser diode 
transmitter. 
 
Simulate the resulting system and verify that it meets performance objective.  
 
# Theory: 
 
The maximum allowable dispersion (or pulse spread) <img width="76" height="52" alt="image" src="https://github.com/user-attachments/assets/52dff457-e7aa-4312-aef4-aa4e234afb47" /> is given in terms of the transmission rate R by the following engineering guideline <img width="192" height="124" alt="image" src="https://github.com/user-attachments/assets/4fcb3de9-6a4a-48db-ba5f-f020a6c85d8b" /> This guideline provides reasonable assurance that there will be no significant inter
symbol interference (ISI) due to pulse spread. 
 
For standard single-mode fiber driven by a directly-modulated laser diode transmitter, the 
pulse spread due to chromatic dispersion is given by
<img width="898" height="694" alt="image" src="https://github.com/user-attachments/assets/5499f4b0-2405-4a5f-b773-ce004a76e850" />
<img width="1300" height="974" alt="image" src="https://github.com/user-attachments/assets/bbd90891-43d6-4a5d-92d2-73ed3e4e57eb" />
# Layout: 
Open up the OptiPerformer file called “Dispersion Limited Fiber.osp”. This layout uses 
the Laser Rate Equations laser diode component with default parameters.  It models a 
directly modulated laser diode based using a standard rate equation model. One of the 
effects of this model is that it generates a signal with a spectral width of about 0.6 nm for 
the default parameters with 2.5 Gb/s, return to zero modulation. 
Within the layout, there are several “Visualizers.” The “Optical Time Domain 
Visualizers” allow the user to the view the simulated signal as a function of time. There is 
one at the output of the laser and one at the end of the fiber.  This allows the user to 
directly observe the changes in the pulses due fiber dispersion. The “Optical Spectrum 
Analyzer” allows the user to view the spectral content of the signal. It this lab it is used to 
verify that the spectral width is about 6 nm. The “BER analyzer” provides calculations of 
the Q factor, the bit error rate (BER) and provides a plot of the eye diagram. 
# Simulation:  
Set the laser power such to achieve a transmitter output power of 0 dBm. The transmitter 
power can be viewed by double clicking the “Output Power Meter Visualizer.” The 
power will read -100 dBm until the first run is made.  
Using the chromatic dispersion factor equation, determine the dispersion of the fiber at 
1550 nm and set the fiber dispersion parameter accordingly. 
Using the equations above, determine the dispersion-limited fiber length. 
<img width="1262" height="1044" alt="image" src="https://github.com/user-attachments/assets/e0b20ca6-42b4-4f1b-ac9a-e4f931a85001" />
<img width="1920" height="1080" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/7c5343b9-ffb9-45b8-905c-bbb628784aca" /> 
<img width="1920" height="1080" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/ef9f2618-f624-4006-af72-3f28a6c29a42" /> 
<img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/690aaa1b-281a-43e8-adb4-22fa6b024b3a" /> 
<img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/22c9db43-43df-4515-b421-c2951a4959f3" /> 
<img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/2f442f9c-4569-4b38-b685-660b9609ca22" />






# Calculation
<img width="1440" height="1161" alt="WhatsApp Image 2026-05-20 at 9 41 19 PM" src="https://github.com/user-attachments/assets/3b92e736-7fd4-421a-ab2e-8870a04abfb7" />
<img width="1191" height="1600" alt="WhatsApp Image 2026-05-20 at 9 41 07 PM" src="https://github.com/user-attachments/assets/bbc4ffd4-758a-47e5-8ae7-3d518ff3b0d4" />




# Result
Hence the dispersion-limited fiber length for a fiber optic transport system that 
employs standard single-mode fiber and a directly-modulated single-mode laser diode 
transmitter is calculated. 
