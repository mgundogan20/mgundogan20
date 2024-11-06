### Hi there 👋
Side Projects by Mevlüt Can Gündoğan
- Optics and Photonics
    - Ray Tracer
    - Wave propagation simulations
    - Aberration Correction
    - Experimentally Measuring Point Spread Functions
    - Camera Objective (Petzval’s Lens)
    - Fiber-Optic coupler
- Machine Learning
    - Flappy Bird AI
    - MLP Image Classifier (cs231n)
    - CNN Image Classifier (cs231n)
- Electronics
    - AM Radio
    - Guitar Pedal
    - Temperature Monitoring Device
- Signal Processing
    - Analog Control (PID)
    - Digital signal transmission
    - Analog signal transmission
- Miscellaneous
    - Rigid Body Numerical Analysis in Python
    - SpacePong Game and Bot
# Optics and Photonics

## Ray Tracing

Renders 3D pictures by physically calculating the paths of light rays.

<img src="https://user-images.githubusercontent.com/72755125/236655425-e1d31eb9-d25d-49fb-8bba-a18de69ecf40.png" width="400" height="225"><img src="https://user-images.githubusercontent.com/72755125/236655508-17a7ff00-d34a-415f-83f7-5160caab111d.png" width="337" height="225">

## Wave Propagation Simulations

Numerical solutions of the Nonlinear Schrödinger Equation for a Gaussian Beam.

<img src="https://github.com/user-attachments/assets/17c05ab5-f0e1-4124-8d2f-97888d846e9c" alt="propagation_grating" width="300">
<img src="https://github.com/user-attachments/assets/550e3c33-586a-443d-8580-b2da98e8a7d8" alt="propagation_lens" width="300">
<img src="https://github.com/user-attachments/assets/101ee926-8372-4991-a037-3e0b0f9e352d" alt="propagation_free_space" width="300">

## Aberration Correction

This physically informed neural network reduces aberration and noise in microscopical images.

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

# Machine Learning

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
# Electronics

## DIY Guitar Pedal

Tunable pedal to add sound effects to electronic guitars.

<img src="Images/Fmn_Image_1.png" width="400">

## Parallel Temperature Monitoring IOT Device

Gathers temperature readings from up to 6 different sources and reports them to a static server.

<img src="Images/zah_Image_2.png" width="400">

## AM Radio Transmitter

Tunable radio transmitter using a 9V battery. Uses a BJT as an amplifier. Can broadcast around 1 to 2 MHz.

<img src="Images/ty4-diagram-circuit-description-automatically.jpeg" width="600">
<img src="https://github.com/mgundogan20/mgundogan20/assets/72755125/83b94a65-17b8-49d8-b32e-064e5e3bf5a1" width="300"><img src="https://github.com/mgundogan20/mgundogan20/assets/72755125/566b4115-a24f-4b16-9619-adc934621e18" width="300">




# Signal Processing

## Analog Controller

<img src="Images/lKj-screenshot-computer-description-automatically.png" width="800">

## 16QAM modulation and AD conversion

Experimenting with digital signal transmission and sequence retrieval.
<img src="Images/SEK-screenshot-computer-description-automatically.png" width="600">

## Signal Modulation/Demodulation

Experimenting with analog signal transmission and retrieval.

<img src="Images/4gz-screenshot-computer-description-automatically.png" width="600">



# Miscellaneous

## Numerical Analysis in Python

Using 4th order Runge-Kutta method to model the complex behaviors of rigid body rotations in free space. This project was used to demonstrate the tennis racket theorem.

<img src="Images/1q6_Image_18.png" width="300"><img src="Images/nbB_Image_19.png" width="300"><img src="Images/fYV_Image_20.png" width="300">


## SpacePong Game and Bot

This was a Java aws application for the freshman year comp-sci project. The gif below shows the bot playing it.

![[video-to-gif output image]](Images/gfn-video-to-gif-output-image.gif)

