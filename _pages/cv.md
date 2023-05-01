---
permalink: /
title: "About me"
toc: true
---

My name is Yang Liu, a Marie Curie Research Fellow in the Department of Electronic and Electrical Engineering at the University of Sheffield, UK. My advisor is Professor 
[<font color="blue">[Xiaoli Chu]</font>](https://www.sheffield.ac.uk/eee/people/academic-staff/xiaoli-chu). I'm leading a project of battery-free backscatter communications funded by the EU Horizon 2020 programme. Currently, my work focuses on the research of a battery-free backscatter communication system to embed acoustic signals into RFID signals, including RF energy harvesting and PCB design (Keysight ADS), software-defined radio (Ettus USRP), ultra-low power microcontroller development (TI MSP430), and acoustic signal processing with machine learning (Pytorch). 

My projects involve the development of hardware and software systems and the evaluation of the systems in real-world deployments.
I am always looking for new opportunities and challenges to explore various types of wireless signals, e.g., radio, acoustics, and visible light, to enable novel technologies, such as acoustic motion tracking, breathing motoring, indoor localization, and battery-free communications.
I received a Ph.D. degree in Communication and Information Systems from the University of Chinese Academy of Sciences (UCAS), China, in July 2019. My Ph.D. supervisor is Professor [<font color="blue">[Yang Yang]</font>](https://faculty.sist.shanghaitech.edu.cn/faculty/yangyang/). I received a Master of Engineering (M.Eng.) degree in Software Engineering from Beihang University, China, in 2016, and a Bachelor of Engineering (B.Eng.) degree in Microelectronics from Anhui University, China, in 2012. 


<h2 id="projects"><i class="ion-ios-lightbulb"></i> Projects</h2>

### Battery-free wireless sensor nodes for backscatter communications
#### My contributions and methodologies:
Currently, I'm working on battery-free wireless sensor nodes for backscatter communications. The proposed node harvests energy from RF signals at RFID frequency bands, and then reflects the RF signals embedded with the raw signals from analog sensors, e.g., nanogenerators, microphones and piezo sensors. The node enables microwatt-level uplink and downlink communications to an RFID Reader at a distance of a couple of meters.

As an example of application scenarios, the battery-free nodes are deployed in hazardous environments, .e.g, caves, forests and oceans. A low-altitude drone equipped with an RFID Reader collects the data from the nodes by flying along the nodes one by one. The battery-free design in wireless sensor networks improves the scalability and lifetime of wireless sensor nodes by removing the cost of battery maintenance.

The figures below show the PCB and node design, S11 and the received spectrums of the 2-FSK signals in backscatter communications.
The reflection coefficient from the proposed circuit (S11) in the first figure is measured by a Rohde & Schwarz network analyzer, which indicates the circuit has good impedance matching at the target frequency (915 MHz). In this project, Keysight ADS is used for impedance matching, schematic and PCB design, and the Large-Signal S-Parameters (LSSP) and harmonic balance simulation. Ettus USRP is used to evaluate the system's performance. An ultra-low power chip (TI MSP430) supports power management in energy harvesting and wireless modulation and demodulation in backscatter communications.

<table style="text-align:center" class="center">
<tr>
<th><a href="/assets/paper_img/EH/EH-4.png"><img src="/assets/paper_img/EH/EH-4.png" style="width:62vw"/></a></th>
<th><a href="/assets/paper_img/EH/EH-1.gif"><img src="/assets/paper_img/EH/EH-1.gif" style="width:38vw"/></a></th>
</tr>
<tr>
<td><Figurenum>The proposed battery-free wireless sensor node (click the figures to zoom in)</Figurenum></td>
<td><Figurenum>PCB design and soldering</Figurenum></td>
</tr>
</table>


### LPCSE: Neural Speech Enhancement through Linear Predictive Coding (IEEE GLOBECOM'22)
#### My contributions and methodologies:
I proposed a new speech enhancement architecture called LPCSE that combines classic signal processing technologies, i.e., Linear Predictive Coding (LPC), with neural networks in the auto-differentiable machine learning frameworks, as shown in the figures below. The proposed architecture could leverage the strong inductive biases in the classic speech models in conjunction with the expressive power of neural networks. To achieve this work, I also studied the speech synthesis and enhancement technologies, such as speech vocoders (WaveNet WaveRNN, MelGAN HiFi-GAN, etc.), denoising (SEGAN, U-net, etc.), voice conversion (AutoVC, StarGAN-VC, etc.), and expert-rule inspired speech and audio synthesis (LPCNet, DDSP, etc.).

<table style="text-align:center" class="center">
<tr>
<th> <a href="/assets/paper_img/LPCSE/GC2022-1.jpg"><img src="/assets/paper_img/LPCSE/GC2022-1.jpg" style="width:33vw"/></a></th>
<th> <a href="/assets/paper_img/LPCSE/GC2022-2.jpg"><img src="/assets/paper_img/LPCSE/GC2022-2.jpg" style="width:33vw"/></a></th>
<th> <a href="/assets/paper_img/LPCSE/GC2022-3.jpg"><img src="/assets/paper_img/LPCSE/GC2022-3.jpg" style="width:33vw"/></a></th>
</tr>
<tr>
<td><Figurenum>The LPC model and an application scenario</Figurenum></td>
<td><Figurenum>LPCSE architecture</Figurenum></td>
<td><Figurenum>The visualizations of LPCSE based speech enhancement</Figurenum></td>
</tr>
</table>

A brief introduction to this project is shown in the video below.

<div class="video-container">
<iframe src="https://www.youtube.com/embed/1dW7MAzoys8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>  



### PAMT: Phase-based Acoustic Ranging and Motion Tracking in Multipath Fading Environments (IEEE INFOCOM'19 and ACM MM'18)
#### My contributions:
- I proposed and implemented a fine-grained ranging system on commercial mobile devices (e.g., smartphones).
The key idea is that the acoustic phase is used to achieve accurate distance measurement.
A prototype system of ranging is implemented on a standard Android smartphone, which could monitor human breathing, as shown in the figures below. 

<table style="text-align:center" class="center">
<tr>
<th><a href="/assets/paper_img/MM2018/phase-based-ranging.gif"><img src="/assets/paper_img/MM2018/phase-based-ranging.gif" style="width:55vw"/></a></th>
<th><a href="/assets/paper_img/MM2018/breathing.png"><img src="/assets/paper_img/MM2018/breathing.png" style="width:47vw"/> </a></th>
</tr>
<tr>
<td><Figurenum>Phase based ranging</Figurenum></td>
<td><Figurenum>Breath monitoring using acoustic signals</Figurenum></td>
</tr>
</table>

- Based on the ranging method above, I proposed and implemented a fine-grained and low-cost acoustic motion-tracking method called PAMT for mobile interaction. The proposed method allows mobile users to interact with a computer by using a gesture interface in practical indoor environments. The system could provide economical and flexible navigation and gesture recognition for VR/AR users.
 
- In practical indoor environments, it's challenging to obtain accurate moving distance change based on the phase change due to the attenuation and reflection of acoustic signals. To address this challenge, I proposed a metric to identify the impact of multipath fading in real time. Based on the metric, I proposed a multipath interference mitigation method through the diversity of acoustic frequencies, in which the actual moving distance is calculated by combining the moving distances measured at different frequencies, as shown in the figures below. Experiment results show the measurement errors are less than 2 mm and 4 mm in one-dimensional and two-dimensional scenarios, respectively.



<table style="text-align:center" class="center">
<tr>
<th><img src="/assets/paper_img/IoT2019/MDV.gif" style="width:15vw"/></th>
<th>  <img src="/assets/paper_img/IoT2019/Multipath_fading.png" style="width:30vw" /> </th>
</tr>
<tr>
<td><Figurenum>A new feature indicating multipath fading in real time</Figurenum></td>
<td><Figurenum> Moving distance measured at different
frequencies</Figurenum></td>
</tr>
</table>

A demonstration is shown in the video below.

<div class="video-container">
<iframe src="https://www.youtube.com/embed/XJROYu_67ug" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>  

A brief introduction to this project is shown in the video below.

<div class="video-container">
<iframe src="https://www.youtube.com/embed/Hrjy5ulx6NY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>  




###  Low-Cost Real-Time Power Measurement and Abnormal Diagnosis
#### Motivations:
Engineers engaged in the development of battery power-supply devices are facing huge pressure to reduce the consumption of power.
During the development, engineers require a flexible and low-cost way to know the real-time power computation of multiple Devices Under Tests (DUTs).

#### My contributions:
In this work, a low-cost and real-time power measurement platform called PTone is proposed to provide a more flexible way for low-power device development than cumbersome equipment, e.g., Keysight 34465A.
Compared with traditional measuring equipment, such as Keysight 34465A (>$1500 on Amazon), our system is low-cost (<$20) and could be widely deployed.
The median error of PTone is less than 0.37% of the benchmark, as shown in the figures below.
Based on the real-time power consumption measured by the system, we propose an SVM-based method to diagnose the abnormal status of DUTs.
Our key insight is that the real-time power consumption of low-power devices changes with the periodic system process, such as data collecting, simple signal processing, signal transmission, and sleep, and we used the features of the power consumption to identify whether the microcontroller in the DUT works as expected. 

<table style="text-align:center" class="center">
<tr>
<th><img src="/assets/paper_img/PTone/hardware.png" style="width:22vw"/></th>
<th>  <img src="/assets/paper_img/PTone/wave.png" style="width:18vw"/> </th>
</tr>
<tr>
<td><Figurenum>Real-time power measurement system</Figurenum></td>
<td><Figurenum>Power consumption measured by our system and Keysight 34465A</Figurenum></td>
</tr>
</table>

<h2 id="publications"><i class="ion-ios-book"></i> Publications</h2>

1. **Yang Liu**, Na Tang, Xiaoli Chu, Yang Yang, and Jun Wang, "LPCSE: Neural Speech Enhancement through Linear Predictive Coding," arXiv preprint arXiv:2206.06908, 2022. [<font color="blue">[PDF]</font>](https://arxiv.org/abs/2206.06908)
2. **Yang Liu**, Wuxiong Zhang, Yang Yang, Weidong Fang, Fei Qin, and Xuewu Dai. RAMTEL: Robust Acoustic Motion Tracking using Extreme Learning Machine for Smart Cities. *IEEE Internet of Things Journal*, 2019. (IF: 5.863) [<font color="blue">[PDF]</font>](/_pdf/RAMTEL.pdf)
3.	**Yang Liu**, Wuxiong Zhang, Yang Yang, Weidong Fang, Fei Qin, and Xuewu Dai. PAMT: Phase-based Acoustic Motion Tracking in Multipath Fading Environments. *IEEE Conference on Computer Communications* 2019(INFOCOM’19). (Rank A, acceptance rate: 19.7%). [<font color="blue">[PDF]</font>](/_pdf/PAMT.pdf)
4.	**Yang Liu**, Yang Yang, Weidong Fang, and Wuxiong Zhang. Demo: Phase-based Acoustic Localization and Motion Tracking for Mobile Interaction. *ACM Multimedia conference* (ACM MM’18). [<font color="blue">[PDF]</font>](/_pdf/Demo2018.pdf)
5.	**Yang Liu**, Wuxiong Zhang and Weidong Fang, IoT sensing technology based on acoustic phase. *Chinese Journal on Internet of Things*, 2018. (A Chinese journal)
6.	**Yang Liu**, Yubing Wang, Weiwei Gao, Wuxiong Zhang, and Yang Yang. A Novel Low-Cost Real-Time Power Measurement Platform for LoWPAN IoT Devices. *Mobile Information Systems*, 2017. [<font color="blue">[PDF]</font>](/_pdf/PTone.pdf)
7. Weidong Fang, Wuxiong Zhang, Wei Chen, **Yang Liu**, and Chaogang Tang. TMSRS: Trust Management-based Secure Routing Scheme in Industrial Wireless Sensor Network with Fog Computing. *Wireless Networks*, 2019. [<font color="blue">[PDF]</font>](/_pdf/TMSRS.pdf)
8.	Weidong Fang, Wuxiong Zhang, Yang Yang, **Yang Liu**, and Wei Chen. A resilient trust management scheme for defending against reputation time-varying attacks based on BETA distribution. *Science China Information Sciences*, 2017. [<font color="blue">[PDF]</font>](/_pdf/trust_management.pdf)



<h2 id="skills"><i class="ion-ios-gear"></i> Skills</h2>


* Digital signal processing
  * Speech signal processing.
  * Sonar, radio radar.
  * Wireless modulation and demodulation.
  * Wireless indoor localization.
  * Wireless channel estimation and equalization.
  * Array signal processing and Spectral density estimation.
* Embedded system development
  * IoT microcontroller development, e.g., STM32, TI MSP430.
  * Linux-based system development, such as Ubuntu, Betaflight, and OpenWrt.
* Applications of machine learning technologies.
  * Neural speech enhancement.
  * Multipath fading mitigation in wireless communications.
* Hardware skills for wireless communications
  * RF circuit design, e.g.,  the circuit for RF energy harvesting and backscatter communications.
  * Hand soldering for SMD Components on PCBs, e.g., 0603 capacitors and inductors.
  * Common experimental equipment, such as Vector Network Analyzers, Spectrum Analyzers, Programmable Signal Generators, and Oscilloscopes.

<h2 id="work-experience"><i class="ion-ios-filing"></i> Experience</h2>

* Marie Curie Research Fellow at The University of Sheffield (Mar. 2021 - present)

* Research Associate at ShanghaiTech University, Shanghai, China. (Aug. 2019 - Jan. 2021)
  
* Visiting Ph.D. Student at Shanghai Institute of Fog Computing Technology (SHIFT), Shanghai, China. (Apr. 2018 - July 2019)

* Visiting Ph.D. Student at Shanghai Institute of Microsystem and Information Technology (SIMIT), Chinese Academy of Sciences (CAS), China. (Sept. 2016 - Apr. 2018)
 
* Student Internship at Shanghai Research Center for Wireless Communications, Shanghai, China. (Oct. 2014 - Sep. 2016)

* Research and Teaching Assistant at Beihang University, Beijing, China. (Sept. 2013 - Aug. 2014)

* Intern at EDA Laboratory of Beihang University, Beijing, China. (June 2013 - Aug. 2013)

* Summer student at the school’s innovation Laboratory of Anhui University. (July 2009 - Aug. 2009)




