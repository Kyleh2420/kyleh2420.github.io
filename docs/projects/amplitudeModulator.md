---
title: Amplitude Modulator and Demodulator
layout: default
parent: Projects
nav_order: 2022-08-18
#has_children: true
---

# ESE 342: Communication Systems
{: .no_toc}

1. TOC
{:toc}


## About
In the fall of 2022, I took ESE 342: Communication Systems, where I learned the basics of wireless communication. We were required to construct and simulate the following two systems using Commercial Off-The-Shelf resources.
1. Amplitude Modulator with a 15 dBm output power centered at 10GHz and a modulation depth of ± 5dB.
2. Envelope Detector given an modulation equation and an arbitrary music file.

## Amplitude Modulator

Design an amplitude modulator using a variable gain amplifier, such as the HMC694LPE. The baseband signal is given by

$$
    x(t) = 0.5cos(2 \pi f_0 t) + 0.5cos(4 \pi f_0t)\ V
$$


The carrier frequency is generated using a dielectric resonator oscillator with an output power of 15dBm at a frequency of 10GHz. The modulated signal should have a mean power of 15dBm with a modulation depth of ± 5 dB. Download the data sheets of the components from the manufacturer or distributor websites to design your modulator circuit to meet the specifications.

### Submission Paper

The original assignment can be fonud in the [following PDF.](https://kyleh2420.github.io/assets/pdf/ESE342_Amplitude_Modulator.pdf)
<object data="https://kyleh2420.github.io/assets/pdf/ESE342_Amplitude_Modulator.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://kyleh2420.github.io/assets/pdf/ESE342_Amplitude_Modulator.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://kyleh2420.github.io/assets/pdf/ESE342_Amplitude_Modulator.pdf">Download PDF</a>.</p>
    </embed>
</object>


## Envelope Detector
Design an envelope detector for demodulating an amplitude modulated signal arriving at the reciever. The signal arriving at the input of the demodulator is given by 

$$
    v_c(t) = 5.0[1+\mu x(t)]cos(2\pi f_ct+\phi_0) \ \ \ \mu V
$$

where the modulation index, $\mu$ = 0.3, $\phi_0$ is an arbitrary phase angle and $f_c$ = 98.6 MHz is the carrier frequency. Generate a music signal x(t) for testing and verification of your envelope detector.

You must model the various electrical components, such as the diode, and process the signal in the time domain. You should display the signal at various stages of processing. Input should be taken from a music file and the output file should be played using any audio player.

### Final Paper

The original assignment can be fonud in the [following PDF.](https://kyleh2420.github.io/assets/pdf/ESE342_Envelope_Detector.pdf)
<object data="https://kyleh2420.github.io/assets/pdf/ESE342_Envelope_Detector.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://kyleh2420.github.io/assets/pdf/ESE342_Envelope_Detector.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://kyleh2420.github.io/assets/pdf/ESE342_Envelope_Detector.pdf">Download PDF</a>.</p>
    </embed>
</object>