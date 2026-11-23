# Peter Yazdi

I build hardware for medical imaging: high-voltage ultrasound electronics, multilayer PCBs and embedded firmware, with some imaging simulation and machine learning on the software side. Honours Physics at UBC.

## Projects

**[Multi-channel ultrasound system](https://github.com/peteryazdi/Ultrasound-Imaging-System)**

Ultrasound imaging system built from scratch on my own budget. Rev 0 is a 4-layer, 2-channel high-voltage transmit board, designed for ±100 V and tested in a water tank with 5 MHz transducers. Rev 1, a 4-channel 5 MHz transmit and receive system with FPGA pulse timing, is in design, with FPGA beamforming to follow.

**[EMG Band](https://github.com/peteryazdi/EMG-Band)**

Multi-channel EMG armband being built to control BioTron's bionic arm. One control board in the band, with an 8-channel ADS1299 front end and an STM32WB55 that streams over USB or Bluetooth, running from USB-C or a rechargeable battery with on-board charging and protection. Control board in design.

**[PyTheraTwin](https://github.com/qurit/PyTheraTwin)**

Open-source pipeline that turns patient CT scans into virtual patients with ground-truth SPECT images and absorbed-dose maps, using Monte Carlo simulation. Built at BC Cancer. Presented at EANM and AAPM.

**[AI platform for radiologists](https://github.com/peteryazdi/Frozen-Pillar-0)**

Started by benchmarking frozen CT foundation models for pulmonary embolism detection: Pillar-0 embeddings with small classifiers, compared against Google's CT Foundation model on the same scans. Now being built into an accessible AI platform for radiologists with Dr. Philip Edgcumbe and Armin Saghafian, continuing earlier work by Dr. Sara Hosseinirad. In progress.

**[UBC Rocket](https://github.com/UBC-Rocket)**

Redesigned the avionics into a modular four-board stack in Altium: STM32 flight controller, GPS/radio, pyro, and a battery-managed backplane over SPI, vacuum-chamber tested across flight pressures. Led over 100 members on a rocket that reached 31,000 ft at IREC 2026, a UBC record.

**[Solid-state Tesla coil](https://github.com/peteryazdi/Solid-State-Tesla-Coil)**

Half-bridge IGBT coil that self-tunes to its ~380 kHz resonance, built for a UBC physics course (PHYS 420) from the LabCoatz design. Built the driver and designed the coil, top load and enclosure.

## Contact

peteryazdi@gmail.com
