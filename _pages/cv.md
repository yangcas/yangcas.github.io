---
permalink: /
title: "About me"
toc: true
---
<p>I am a Research Scientist at <a href="https://www.nokia.com/bell-labs/about/locations/cambridge-uk/" target="_blank">Nokia Bell Labs</a>, Cambridge, UK.</p>

<p>Previously, I was a Marie Curie Research Fellow at The University of Sheffield, UK, where I worked under the supervision of 
<a href="https://www.sheffield.ac.uk/eee/people/academic-staff/xiaoli-chu" target="_blank">Professor Xiaoli Chu</a>. 
During this time, I led a EU Horizon 2020-funded project on battery-free backscatter communications.</p>

<p>Currently, my research focuses on wearable devices, digital health, wireless sensing, and embedded machine learning. 
I am passionate about exploring diverse wireless signals—including acoustic, RF, UWB, mmWave and visible light—to enable novel technologies such as vital signs monitoring, indoor localization and motion tracking, and ultra-low power or battery-free systems.</p>

<p>My projects involve end-to-end development of hardware and software systems, with extensive real-world deployments. 
These experiences have equipped me with interdisciplinary, hands-on skills in:</p>
<ul>
  <li>Advanced signal processing and machine learning for wireless signals</li>
  <li>Wireless sensing and localization</li>
  <li>Low-power embedded system design</li>
  <li>Rapid hardware prototyping</li>
  <li>User study design for wearable sensing</li>
</ul>

<p>I received a Ph.D. in Communication and Information Systemsfrom the 
University of Chinese Academy of Sciences (UCAS), China, in July 2019, supervised by 
<a href="https://faculty.sist.shanghaitech.edu.cn/faculty/yangyang/" target="_blank">Professor Yang Yang</a>. 
I also earned a M.Eng. in Software Engineering from Beihang University in 2016, 
and a B.Eng. in Microelectronics from Anhui University in 2012.</p>

<p>I am always looking for <strong>new opportunities and challenges</strong> that allow me to explore and push the boundaries of wireless technologies. <strong>I warmly welcome collaborations</strong>.</p>


<h2 id="projects"><i class="ion-ios-lightbulb"></i> Projects</h2>

### OmniBuds: A Sensory Earable Platform for Advanced Bio-Sensing and On-Device Machine Learning
<p>
We proposed OmniBuds, which is an advanced earable research platform designed to enable multimodal bio-sensing and on-device machine learning, advancing real-time health perception. Unlike conventional wearables that rely on cloud-based processing, OmniBuds offers direct access to raw physiological data, supporting privacy-preserving, real-time analysis. It integrates a wide array of sensors, including PPG, temperature, IMUs, and multiple microphones, all within a compact True Wireless Stereo (TWS) earbud form factor. Equipped with an embedded machine learning accelerator, OmniBuds enables efficient on-device computation, optimized for low power consumption to support continuous operation. This platform is ideal for researchers aiming to explore health-aware wearable intelligence and real-time physiological monitoring.
</p>
<p>
Web: <a href="https://www.omnibuds.tech/">https://www.omnibuds.tech/</a><br>
Paper: <a href="https://arxiv.org/abs/2410.04775">https://arxiv.org/abs/2410.04775</a>
</p>


<table style="text-align:center" class="center">
<tr>
<th><a href="/assets/paper_img/OmniBuds/HW.png"><img src="/assets/paper_img/OmniBuds/HW.png" style="width:58vw"/></a></th>
<th><a href="/assets/paper_img/OmniBuds/System.jpg"><img src="/assets/paper_img/OmniBuds/System.jpg" style="width:42vw"/></a></th>
</tr>
<tr>
<td><Figurenum>OmniBuds Hardware Block Diagram.</Figurenum></td>
<td><Figurenum>Placement of the sensors in OmniBuds</Figurenum></td>
</tr>
</table>


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

1. **Yang Liu**, Alessandro Montanari, and Fahim Kawsar, "mmHvital: A Study on Head-Mounted mmWave Radar for Vital Sign Monitoring," submitted, (To appear).

2. **Yang Liu**, Alessandro Montanari, Ashok Thangarajan, Khaldoon Al-Naimi, Andrea Ferlini, Ananta Narayanan Balaji, and Fahim Kawsar, "Demo: Multimodal Bio-Sensing and On-Device Machine Learning: Advancing Health Perception with OmniBuds," ACM SenSys 2025, DOI: 10.1145/3715014.3724367 (To appear). 

3. Harshvardhan Takawale, **Yang Liu**, Khaldoon Al-Naimi, Fahim Kawsar, and Alessandro Montanari, "Towards Detecting Auditory Attention from in-Ear Muscle Contractions using Commodity Earbuds," in *ICASSP 2025 - IEEE International Conference on Acoustics, Speech and Signal Processing*, pp. 1-5, IEEE, 2025. [<font color="blue">[LINK]</font>](https://ieeexplore.ieee.org/abstract/document/10889668)

4. Jiatao Quan, Khaldoon Al-Naimi, Xijia Wei, **Yang Liu**, Fahim Kawsar, Alessandro Montanari, and Ting Dang, "Cognitive Load Monitoring via Earable Acoustic Sensing," in *ICASSP 2025 - IEEE International Conference on Acoustics, Speech and Signal Processing*, pp. 1-5, IEEE, 2025. [<font color="blue">[LINK]</font>](https://ieeexplore.ieee.org/abstract/document/10887838)

5. Irtaza Shahid, Khaldoon Al-Naimi, Ting Dang, **Yang Liu**, Fahim Kawsar, and Alessandro Montanari, "Towards Enabling DPOAE Estimation on Single-Speaker Earbuds," in *ICASSP 2024 - IEEE International Conference on Acoustics, Speech and Signal Processing*, pp. 246-250, IEEE, 2024. [<font color="blue">[LINK]</font>](https://ieeexplore.ieee.org/document/10446436)

6. Alessandro Montanari, Ashok Thangarajan, Khaldoon Al-Naimi, Andrea Ferlini, **Yang Liu**, Ananta Narayanan Balaji, and Fahim Kawsar, "OmniBuds: A Sensory Earable Platform for Advanced Bio-Sensing and On-Device Machine Learning," *arXiv preprint arXiv:2410.04775*, 2024. [<font color="blue">[LINK]</font>](https://arxiv.org/abs/2410.04775)

7. Na Tang, **Yang Liu**, Xiaoli Chu, Ian F. Akyildiz, "Design, Modeling and Analysis of Underwater Acoustic Backscatter Communications," IEEE *ICC (International Computer Communications)* Conf., Denver, Colorado, USA, June 2024. [<font color="blue">[LINK]</font>](https://ieeexplore.ieee.org/document/10623056)

8. Zhiyu Liu, **Yang Liu**, and Xiaoli Chu, "Reconfigurable-Intelligent-Surface-Assisted Indoor Millimeter-Wave Communications for Mobile Robots," *IEEE Internet of Things Journal*, vol. 11, no. 1, pp. 1548-1557, Jan. 1, 2024. [<font color="blue">[LINK]</font>](https://ieeexplore.ieee.org/document/10163913)

9. **Yang Liu**, Na Tang, Xiaoli Chu, Yang Yang, and Jun Wang, "LPCSE: Neural Speech Enhancement through Linear Predictive Coding," *GLOBECOM 2022 - 2022 IEEE Global Communications Conference*, Rio de Janeiro, Brazil, 2022, pp. 5335-5341, doi: 10.1109/GLOBECOM48099.2022.10001278. [<font color="blue">[PDF]</font>](https://ieeexplore.ieee.org/document/10001278)

10. **Yang Liu**, Wuxiong Zhang, Yang Yang, Weidong Fang, Fei Qin, and Xuewu Dai, "RAMTEL: Robust Acoustic Motion Tracking using Extreme Learning Machine for Smart Cities," *IEEE Internet of Things Journal*, 2019. [<font color="blue">[LINK]</font>](https://ieeexplore.ieee.org/document/8660446)

11. **Yang Liu**, Wuxiong Zhang, Yang Yang, Weidong Fang, Fei Qin, and Xuewu Dai, "PAMT: Phase-based Acoustic Motion Tracking in Multipath Fading Environments," *IEEE Conference on Computer Communications* 2019 (INFOCOM’19). (Rank A, acceptance rate: 19.7%). [<font color="blue">[LINK]</font>](https://ieeexplore.ieee.org/document/8737366)

12. **Yang Liu**, Yang Yang, Weidong Fang, and Wuxiong Zhang, "Demo: Phase-based Acoustic Localization and Motion Tracking for Mobile Interaction," *ACM Multimedia conference* (ACM MM’18). [<font color="blue">[LINK]</font>](https://dl.acm.org/doi/10.1145/3240508.3241385)


13. **Yang Liu**, Yubing Wang, Weiwei Gao, Wuxiong Zhang, and Yang Yang, "A Novel Low-Cost Real-Time Power Measurement Platform for LoWPAN IoT Devices," *Mobile Information Systems*, 2017.

14. Weidong Fang, Wuxiong Zhang, Wei Chen, **Yang Liu**, and Chaogang Tang, "TMSRS: Trust Management-based Secure Routing Scheme in Industrial Wireless Sensor Network with Fog Computing," *Wireless Networks*, 2019. [<font color="blue">[LINK]</font>](https://link.springer.com/article/10.1007/s11276-019-02129-w)

15. Weidong Fang, Wuxiong Zhang, Yang Yang, **Yang Liu**, and Wei Chen, "A resilient trust management scheme for defending against reputation time-varying attacks based on BETA distribution," *Science China Information Sciences*, 2017. [<font color="blue">[LINK]</font>](https://link.springer.com/article/10.1007/s11432-016-9028-0)








