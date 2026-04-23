### Hi there 👋
Side Projects by Mevlüt Can Gündoğan
- Optics and Photonics
    - Ray Tracer
    - Wave propagation simulations
    - Aberration Correction
    - Experimentally Measuring Point Spread Functions
    - Camera Objective (Petzval’s Lens)
    - Fiber-Optic coupler
- Electronics
    - AZ (Noise Blocking) OpAmp
    - PSP Flip Flop
    - AM Radio
    - Guitar Pedal
    - Temperature Monitoring Device
- Machine Learning
    - Private LLM Server
    - Flappy Bird AI
    - MLP Image Classifier (cs231n)
    - CNN Image Classifier (cs231n)
- Miscellaneous
    - Autonomous Drone
    - Rigid Body Numerical Analysis in Python
    - SpacePong Game and Bot
# Optics and Photonics

## Ray Tracing
Renders 3D pictures by physically calculating the paths of light rays.

(C++)
<img src="https://user-images.githubusercontent.com/72755125/236655425-e1d31eb9-d25d-49fb-8bba-a18de69ecf40.png" width="400" height="225"><img src="https://user-images.githubusercontent.com/72755125/236655508-17a7ff00-d34a-415f-83f7-5160caab111d.png" width="337" height="225">

## Wave Propagation Simulations

Numerical solutions of the Nonlinear Schrödinger Equation for a Gaussian Beam.

(Python)

<img src="https://github.com/user-attachments/assets/17c05ab5-f0e1-4124-8d2f-97888d846e9c" alt="propagation_grating" width="300">
<img src="https://github.com/user-attachments/assets/550e3c33-586a-443d-8580-b2da98e8a7d8" alt="propagation_lens" width="300">
<img src="https://github.com/user-attachments/assets/101ee926-8372-4991-a037-3e0b0f9e352d" alt="propagation_free_space" width="300">

## ML Model for Aberration Correction 

<img width="284" height="110" alt="image" src="https://github.com/user-attachments/assets/ebea3fd0-7fad-48c8-a7fb-5bcd375c4dae" />
This physically informed neural network reduces aberration and noise in microscopical images.

(Python)

<img src="https://github.com/mgundogan20/mgundogan20/assets/72755125/f5e0c1b7-84f2-4393-863a-5afe6b09f535" width="600">

## Experimental PSF Measurements

Imaging fluorescent beads and processing the data to experimentally determine the point spread functions of microscopes.
![image](https://github.com/user-attachments/assets/9c3f4123-f220-4cf2-a094-6188f50f082d)

## Petzval’s Lens
Zemax project to create an objective lens, the image produced by this objective can be seen below.

<img src="Images/4eE-screenshot-computer-description-automatically.jpeg" width="600">
<img src="https://github.com/mgundogan20/mgundogan20/assets/72755125/d0b2bb7c-d1bb-4eee-a5c0-3f6b6fb7fbc0" height="300">
<img src="https://github.com/mgundogan20/mgundogan20/assets/72755125/a1b3753a-8a94-4eaf-b4f6-aa5faba11986" height="300">

## Fiber Coupler
Zemax project to couple 2 fiber-optics. Achieves near perfect coupling efficiencies.

<img src="https://github.com/mgundogan20/mgundogan20/assets/72755125/798803f4-4f1e-4d33-b7f6-d4bf025ea2d1" width="600" >
<img src="Images/Dcj-screenshot-computer-description-automatically.png" width="600">

# Electronics

## AZ Amplifier (Suppress Low Frequency Noise) 
OpAmp that samples low frequency noise and compensates for it.

(Cadence)

<img width="500" height="301" alt="circ" src="https://github.com/user-attachments/assets/af38d39c-f24c-4d1b-8a1f-832142b214a5" />
<img width="400" height="240" alt="Figure_1" src="https://github.com/user-attachments/assets/59c18cd9-bef9-4074-a8a3-0793324219a8" />

## Pseudo Single Phase Flip-Flop
Uses a delayed clock to sample input at the rising edge.

(Cadence)

<img width="1479" height="601" alt="6eeef31d-0a10-4b3e-ad86-be872454c7be" src="https://github.com/user-attachments/assets/339fe476-5a86-4a2f-b933-e0e982b57264" />
<img width="1600" height="800" alt="99f68cab-6928-4758-82e3-156d532bc11e" src="https://github.com/user-attachments/assets/516fd171-d0f5-4f3f-aad5-595f40d002c2" />

## Parallel Temperature Monitoring IOT Device
Gathers temperature readings from up to 6 different sources and reports them to a static IP.

<img src="Images/zah_Image_2.png" width="400">

## AM Radio Transmitter

Tunable radio transmitter using a 9V battery. Uses a BJT as an amplifier. Can broadcast around 1 to 2 MHz.

<img src="Images/ty4-diagram-circuit-description-automatically.jpeg" width="600">

Oscilloscope readings:
<img src="https://github.com/mgundogan20/mgundogan20/assets/72755125/83b94a65-17b8-49d8-b32e-064e5e3bf5a1" width="300"><img src="https://github.com/mgundogan20/mgundogan
                                                                                                                           
## DIY Guitar Pedal
Tunable pedal to add sound effects to electronic guitars.

<img src="Images/Fmn_Image_1.png" width="400">
20/assets/72755125/566b4115-a24f-4b16-9619-adc934621e18" width="300">

# Machine Learning

## Private LLM Server
Locally runs an LLM on an ORIN. Serves the model using NGROK.
<img width="487" height="316" alt="image" src="https://github.com/user-attachments/assets/4f274355-5c8a-4288-9b8b-176f48e7f753" />

## Genetic Algorithm

Genetic algorithm that mutates the weights of a neural network to play the popular mobile game “Flappy Bird”.

<img src="Images/ZX5_Image_12.png" width="600">

<img src="Images/W59_Image_13.gif">

## MLP Image Classification

Done as a part of CS231n machine learning class.

<img src="Images/wYO-collage-different-colored-squares-description.png" height="300"><img src="Images/t5X-collage-many-squares-description-automatically.png" width="300">

<img src="Images/2e7-graph-graph-graph-graph-description.png" width="400"><img src="Images/Pfp_Image_16.png" width="400">


## CNN Image Classification

Done as a part of CS231n machine learning class using PyTorch.

### Architecture:
((CONV -> PReLU -> NORM)^2 POOL)^2 -> FNN -> FNN -> FNN

Update function: Adam

The final training weights of the first layer after 10 epochs over CIFAR-10:
(Raw - Upsampled - Upsampled & Contrast Enhanced)

<img width="200" alt="Ekran görüntüsü 2024-02-29 003240" src="https://github.com/mgundogan20/mgundogan20/assets/72755125/fc5161bc-ffd8-473e-997b-82a1385f0f31">
<img width="200" alt="Ekran görüntüsü 2024-02-29 003742" src="https://github.com/mgundogan20/mgundogan20/assets/72755125/74d6c1b5-d3ed-411c-a060-88b9451af951">
<img width="200" alt="Ekran görüntüsü 2024-02-29 003541" src="https://github.com/mgundogan20/mgundogan20/assets/72755125/8ea9328a-c871-4601-a664-2ed335c2a318">

<img width="452" alt="Ekran görüntüsü 2024-02-29 003434" src="https://github.com/mgundogan20/mgundogan20/assets/72755125/d10bbabb-2bda-43a7-8ca6-dc17620c4d4e">
<img width="191" alt="Ekran görüntüsü 2024-02-29 003847" src="https://github.com/mgundogan20/mgundogan20/assets/72755125/366f3fc5-92cb-4f6c-9412-1f2d558338b4">

# Miscellaneous

## Autonomous Drone
Custom drone controlled autonomously by our server to find available parking spots in Koç University.

Server uses Spring Boot handle communication between user-server-ground control-drone.
Flutter app serves results to the client side.
QGC generates mission commands.
Fine-tuned YOLO model detects and locates empty spots.
PSQL database holds images, locations and missions.

<img width="1161" height="1597" alt="Picture1" src="https://github.com/user-attachments/assets/2162e0d1-d703-4933-9564-eb3acbe4f2fb" />

## Numerical Analysis in Python

Using 4th order Runge-Kutta method to model the complex behaviors of rigid body rotations in free space. This project was used to demonstrate the tennis racket theorem.

<img src="Images/1q6_Image_18.png" width="300"><img src="Images/nbB_Image_19.png" width="300"><img src="Images/fYV_Image_20.png" width="300">


## SpacePong Game and Bot

This was a Java aws application for the freshman year comp-sci project. The gif below shows the bot playing it.

![[video-to-gif output image]](Images/gfn-video-to-gif-output-image.gif)

