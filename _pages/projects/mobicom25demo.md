### OmniBuds Demo: Real-Time Multimodal Sensing and Closed-Loop Feedback 

[<font color="blue">[To be demonstrated at ACM MobiCom 2025, Hong Kong, China]</font>](https://www.sigmobile.org/mobicom/2025/)

This live demo showcases **OmniBuds**, a pair of sensor-rich true wireless earbuds that enable **real-time multimodal sensing and closed-loop feedback** for embodied interaction.  
Each earbud integrates dual 9-axis IMUs, optical PPG, and skin temperature sensors that stream synchronized data via BLE to a host computer. The system performs **on-device vital sign estimation** (HR, HRV, RR, SpO₂, temperature) and **lightweight ML-based motion recognition**, supporting dynamic interaction between physiological state and behavior.

In this demo, OmniBuds control the **Chrome T-Rex game** using head and body motion. The earbuds detect jumping and ducking through IMU data, while heart rate modulates the game speed. A real-time visualization dashboard displays raw IMU and PPG waveforms, derived vital signs, and gameplay feedback. Auditory cues—such as “Jump now!”—are delivered through the same earbuds, enabling **fully closed-loop human-in-the-loop interaction**.

<table style="text-align:center; margin:auto;">
<tr>

<td>
<a href="/assets/paper_img/T-REX/demo_setup.png">
    <img src="/assets/paper_img/T-REX/demo_setup.png" style="width:50vw; border-radius:8px;"/>
</a>
<div><b>Live Demo Setup</b><br><small>User interacts with the T-Rex game via head and body motion while real-time sensor data and vitals are visualized.</small></div>
</td>
<td>
<a href="/assets/paper_img/T-REX/demo_flow.png">
    <img src="/assets/paper_img/T-REX/demo_flow.png" style="width:50vw; border-radius:8px;"/>
</a>
<div><b>System Architecture</b><br><small>OmniBuds-based multimodal sensing and feedback framework integrating IMU, PPG, and physiological inference.</small></div>
</td>
</tr>
</table>
