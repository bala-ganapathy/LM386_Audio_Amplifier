# LM386_Audio_Amplifier
It is a PCB design made by using KiCad software 
# LM386 Audio Amplifier

This repository contains the KiCad project files for a simple audio amplifier based on the LM386 IC. This amplifier is designed for low-power audio applications and is suitable for use with small speakers or headphones.

## Project Files

- **Schematic Diagram**: See `Project-LM386_Amp.kicad_sch`
- **PCB Layout**: See `Project-LM386_Amp.kicad_pcb`
- **Images**: See
  Schematic Diagram : 'Project-LM386_Amp-Schematic_Diag.png'
  PCB Diagram : 'Project-LM386_Amp_PCB-Diag.png'
  #d View : 'Project-LM386_Amp_3d-view.png'

## Design Overview

This audio amplifier uses the LM386 IC to amplify low audio signals. The PCB layout is optimized to reduce noise and improve signal integrity.

## Components

| Component | Value   | Purpose                       |
|-----------|---------|-------------------------------|
| LM386     | -       | Amplifier IC                  |
| C_in1     | 10 µF   | Input Coupling Capacitor      |
| C_out1    | 220 µF  | Output Coupling Capacitor     |
| C_power1  | 100 µF  | Power Supply Bypass Capacitor |
| J_audio1  | -       | Audio Input Connector         |
| J_power1  | -       | Power Connector               |
| J_speaker1| -       | Speaker Output Connector      |

