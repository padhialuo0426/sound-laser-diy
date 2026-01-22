<div align="center">

[**简体中文**](./HowToMake.md) | [**English**](./HowToMake_EN.md)

</div>

---

# How to Make
This document describes how to make a SoundLaserDIY sound beam emitter, including the required materials, tools, and steps.

# Required Materials
- Ultrasonic transducer (it is recommended to use a **40kHz** transducer, detailed parameters can be found in the image **Ultrasonic Transducer Parameters.png**), the quantity depends on the design requirements. The sample I made used 100 transducers arranged in a 10x10 matrix;
- Perforated board for mounting and connecting ultrasonic transducers;
- Power adapter (using a **12V** DC power supply, there is a DC jack on the PCB for connecting the power adapter);
- Male-to-male 3.5mm audio cable for connecting the audio source device to the audio input jack on the PCB board;
- Audio source device with a 3.5mm audio jack (such as MP3, computer, etc.);
- Other electronic components and PCB design are detailed in the folder **PCB Design**; 

# Required Tools
- Soldering iron and solder wire for soldering electronic components;
- That's all

# Making Steps
- Refer to the circuit schematic and PCB layout design in the **Driver Board PCB Design** folder, prepare all electronic components and PCB board;
- Solder the electronic components onto the PCB board according to the circuit schematic, ensuring that the soldering is firm and there are no short circuits;
- Solder the ultrasonic transducers onto the perforated board. You can refer to the sample photos I provided for arrangement and connection. Do not reverse the polarity of the ultrasonic transducers;
- I used a 10x10 matrix arrangement, evenly distributing 100 transducers on the perforated board. Since the designed PCB has 20 outputs, each output connects 5 transducers in parallel. The specific connection method can be referred to in the sample photos;
- Then connect all the transducers to the GND pin of the PCB board. There is a pad labeled GND on the PCB board;
- Connect the power adapter to the DC jack on the PCB board, ensuring that the power adapter outputs 12V DC voltage;
- Use the male-to-male 3.5mm audio cable to connect the audio source device to the audio input jack on the PCB board;
- Turn on the audio source device, play music or other audio content, and adjust the volume to an appropriate level;
- Observe and test the sound beam emission effect. You can hear directional sound effects at specific locations.

# Precautions
- Ensure that all solder joints are firm and there are no short circuits to avoid circuit failure;
- Use a suitable power adapter to avoid excessively high or low voltage;
- During the testing process, pay attention to protecting your hearing and avoid prolonged exposure to high-volume environments;
- Never use it with headphones or hearing aids that have noise-canceling functions to avoid damaging the equipment or harming your hearing.