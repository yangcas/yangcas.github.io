
### PAMT: Phase-based Acoustic Ranging and Motion Tracking in Multipath Fading Environments (IEEE INFOCOM) [<font color="blue">[paper]</font>](https://ieeexplore.ieee.org/document/8737366)

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




