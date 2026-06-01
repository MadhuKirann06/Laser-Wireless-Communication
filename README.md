# Laser-Wireless-Communication
A hardware project exploring point-to-point wireless audio data transmission using targeted laser modules.
# Laser Wireless Optical Audio Communication System 🔦



## Project Demo
▶️ [**Click here to watch the Laser Communication Hardware Demo Video (Google Drive)**](https://drive.google.com/file/d/17tIpdZwa91XO_U8ItGNJpnWbi02V3ZD2/view?usp=sharing)

## Project Description
This project is a 100% hardware-based, analog Wireless Optical Communication (WOC) system designed to transmit raw audio signals wirelessly using a laser beam. The system bypasses digital processing entirely, instead utilizing analog circuit design principles to modulate a laser beam's intensity at the transmitter stage and demodulate it at the receiver stage to achieve real-time audio playback over a line-of-sight optical link.

## Circuit Architecture & Implementation Details

### 1. Analog Transmitter Stage
* **Audio Input:** A standard 3.5mm earphone audio cable is connected directly to a smartphone to source the live raw audio signal.
* **Biasing Network:** Uses an Operational Amplifier (Op-Amp) configured with a stable voltage divider bias circuit.
* **Modulation Control:** Integrated a manual rotatable resistor (potentiometer) to vary the circuit resistance, allowing precise calibration of the input signal levels.
* **Optical Source:** The combined bias voltage and fluctuating analog audio signal drive a laser module powered by a battery pack, modulating the laser's brightness in sync with the audio waveforms.

### 2. Receiver & Playback Stage
* **Optical Sensor:** An LDR (Light Dependent Resistor) captures the incoming modulated laser beam, translating the changing light intensity back into a fluctuating electrical resistance.
* **Demodulation Network:** The LDR is paired with an identical Op-Amp circuit utilizing a voltage divider bias network.
* **Signal Calibration:** Uses a second rotatable resistor (potentiometer) to tune the circuit's sensitivity and filter out ambient environmental light noise.
* **Audio Output:** The recovered and amplified analog electrical signal is routed directly to a small portable speaker for real-time audio playback.

## Hardware Components List
* **Transmitter Side:** Battery Source, Laser Diode Module, Op-Amp IC, Rotatable Resistor (Potentiometer), Fixed Resistors (Voltage Divider Network), 3.5mm Earphone Audio Cable.
* **Receiver Side:** LDR Sensor (Light Dependent Resistor), Op-Amp IC, Rotatable Resistor (Potentiometer), Fixed Resistors (Voltage Divider Network), Portable Speaker.
