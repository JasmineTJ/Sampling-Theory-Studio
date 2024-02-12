# Project Title: Signal Sampling and Recovery

## Description
A desktop application that illustrates the signal sampling and recovery process, showing the importance and validation of the Nyquist rate.

## Features
### Sample & Recover
The application allows the user to load a mid-length signal (around 1000 points length), visualize and sample it via different frequencies, then use the sampled points to recover the original signal using Whittaker–Shannon interpolation formula. Sampling frequency is shown in either actual frequency or normalized one (with respect to the maximum frequency). Three graphs are used, one for displaying the original signal along with the markers for the sampled points, another one displays the reconstructed signal, and lastly, the third one displays the difference between the original signal and the reconstructed one.

### Load & Compose
The loaded signal can come from a file or a signal mixer/composer in the application. In the signal mixer, the user can add multiple sinusoidal signals of different frequencies and magnitudes. The user can also remove any of the components during preparing the mixed signal.

### Additive Noise
The user can add noise to the loaded signal with custom/controllable SNR level. The application shows the dependency of the noise effect on the signal frequency.

### Real-time
Sampling and recovery is done in real time upon user changes.

### Resize
The application can be resized easily without messing up the UI.

### Preview
<img src = 'Preview 1.png'>
<img src = 'Preview 2.png'>