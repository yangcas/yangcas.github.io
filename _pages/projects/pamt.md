
### PAMT: Phase-based Acoustic Ranging and Motion Tracking in Multipath Fading Environments (IEEE INFOCOM) [<font color="blue">[paper]</font>](https://ieeexplore.ieee.org/document/8737366)

Accurate and low-cost motion tracking is essential for mobile interaction, VR/AR applications, and human–computer interfaces. Traditional systems often rely on specialized hardware such as cameras or IMUs, which are sensitive to occlusion or require line-of-sight. To overcome these limitations, I explored acoustic phase sensing as a new modality for precise ranging and motion tracking using only built-in microphones and speakers on commercial mobile devices.

- I proposed and implemented a fine-grained ranging system on commercial mobile devices (e.g., smartphones).
The key idea is that the acoustic phase is used to achieve accurate distance measurement.
A prototype system of ranging is implemented on a standard Android smartphone, which could monitor human breathing, as shown in the figures below. 

<table style="text-align:center; margin:auto;">
<tr>

<td>
<a href="/assets/paper_img/MM2018/phase-based-ranging.gif">
    <img src="/assets/paper_img/MM2018/phase-based-ranging.gif" style="width:55vw; border-radius:8px;"/>
</a>
<div><b>Phase-based Ranging</b><br><small>Demonstration of distance estimation through phase difference analysis of acoustic signals.</small></div>
</td>

<td>
<a href="/assets/paper_img/MM2018/breathing.png">
    <img src="/assets/paper_img/MM2018/breathing.png" style="width:47vw; border-radius:8px;"/>
</a>
<div><b>Breath Monitoring via Acoustics</b><br><small>Tracking human respiration using phase variations in reflected sound waves.</small></div>
</td>

</tr>
</table>


- Based on the ranging method above, I proposed and implemented a fine-grained and low-cost acoustic motion-tracking method called PAMT for mobile interaction. The proposed method allows mobile users to interact with a computer by using a gesture interface in practical indoor environments. The system could provide economical and flexible navigation and gesture recognition for VR/AR users.
 
- In practical indoor environments, it's challenging to obtain accurate moving distance change based on the phase change due to the attenuation and reflection of acoustic signals. To address this challenge, I proposed a metric to identify the impact of multipath fading in real time. Based on the metric, I proposed a multipath interference mitigation method through the diversity of acoustic frequencies, in which the actual moving distance is calculated by combining the moving distances measured at different frequencies, as shown in the figures below. Experiment results show the measurement errors are less than 2 mm and 4 mm in one-dimensional and two-dimensional scenarios, respectively.



<table style="text-align:center; margin:auto;">
<tr>

<td>
<img src="/assets/paper_img/IoT2019/MDV.gif" style="width:15vw; border-radius:8px;"/>
<div><b>Real-time Multipath Fading Feature</b><br><small>Visualization of a newly proposed feature that reflects dynamic multipath fading conditions.</small></div>
</td>

<td>
<img src="/assets/paper_img/IoT2019/Multipath_fading.png" style="width:30vw; border-radius:8px;"/>
<div><b>Distance Measurement Across Frequencies</b><br><small>Demonstration of motion tracking based on frequency-dependent phase variations.</small></div>
</td>

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




