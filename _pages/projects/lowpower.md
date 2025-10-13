###  Low-Cost Real-Time Power Measurement and Abnormal Diagnosis [<font color="blue">[paper]</font>](https://onlinelibrary.wiley.com/doi/10.1155/2017/8713873)
Engineers engaged in the development of battery power-supply devices are facing huge pressure to reduce the consumption of power.
During the development, engineers require a flexible and low-cost way to know the real-time power computation of multiple Devices Under Tests (DUTs).

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