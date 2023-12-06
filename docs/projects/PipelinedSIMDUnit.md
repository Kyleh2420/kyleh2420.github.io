---
title: Pipelined SIMD Unit with Custom Instruction Set
layout: default
parent: Projects
nav_order: 2023-12-05
#has_children: true
---

# Table of Contents 
{: .no_toc}

1. TOC
{:toc}

# About

For ESE 345: Computer Architecture, we were tasked with designing a four-stage Single Instruction Multiple Data (SIMD) multimedia unit capable of executing a custom instruction set in VHDL. The four stages and their integrated entities are the following:
1. Instruction Decode (Program Counter and an Instruction buffer that acts as an EEPROM)
2. Instruction Fetch (A Register file that fetches data based on the given addresses)
3. Execute Stage (Including a forwarding unit and an ALU)
4. Write Back (A write back unit that would control the write enable line that connects to the register file.)

# The Assignment
The original assignment can be fonud in the [following PDF.](https://kyleh2420.github.io/assets/pdf/ESE345_Instructions.pdf)
<object data="https://kyleh2420.github.io/assets/pdf/ESE345_Instructions.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://kyleh2420.github.io/assets/pdf/ESE345_Instructions.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://kyleh2420.github.io/assets/pdf/ESE345_Instructions.pdf">Download PDF</a>.</p>
    </embed>
</object>

# Design
Following the 4 stage design laid out above, I constructed 8 entities in mostly behavioral VHDL according to the following block diagram. Each of the entities besides the register buffers has been testbenched before assembling them into an overarching structural architecture.

![A hand drawn block diagram of the 4 stage pipelined SIMD unit.]({{ site.baseurl }}/assets/images/SBU/ESe345BlockDiagram.jpg)

# Final Report

The final project report can be found in the [following PDF.](https://kyleh2420.github.io/assets/pdf/ESE345FinalSubmission.pdf)
<object data="https://kyleh2420.github.io/assets/pdf/ESE345FinalSubmission.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://kyleh2420.github.io/assets/pdf/ESE345FinalSubmission.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://kyleh2420.github.io/assets/pdf/ESE345FinalSubmission.pdf">Download PDF</a>.</p>
    </embed>
</object>

You can find more about the SIMD unit by visiting the [Github Repo here](https://github.com/Kyleh2420/Pipelined-SIMD-Multimedia-Unit).