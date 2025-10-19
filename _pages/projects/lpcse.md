<h3 id="lpcse" short-label = "LPCSE: Neural Speech Enhancement"> LPCSE: Neural Speech Enhancement through Linear Predictive Coding 
<a href="https://ieeexplore.ieee.org/document/10001278" style="color: blue; font-size: 0.9em;">[paper]</a>
</h3>

I proposed a new speech enhancement (SE) architecture called LPCSE that combines classic signal processing technologies, i.e., Linear Predictive Coding (LPC), with neural networks in the auto-differentiable machine learning frameworks, as shown in the figures below. The proposed architecture could leverage the strong inductive biases in the classic speech models in conjunction with the expressive power of neural networks. To achieve this work, I also studied the speech synthesis and enhancement technologies, such as speech vocoders (WaveNet WaveRNN, MelGAN HiFi-GAN, etc.), denoising (SEGAN, U-net, etc.), voice conversion (AutoVC, StarGAN-VC, etc.), and expert-rule inspired speech and audio synthesis (LPCNet, DDSP, etc.).


<table style="text-align:center; margin:auto;">
<tr>

<td>
<a href="/assets/paper_img/LPCSE/GC2022-1.jpg">
    <img src="/assets/paper_img/LPCSE/GC2022-1.jpg" style="width:25vw; border-radius:8px;"/>
</a>
<div><b>LPC Model and Application Scenario</b><br><small>Illustration of the LPC model and its deployment in real-world audio enhancement.</small></div>
</td>

<td>
<a href="/assets/paper_img/LPCSE/GC2022-2.jpg">
    <img src="/assets/paper_img/LPCSE/GC2022-2.jpg" style="width:25vw; border-radius:8px;"/>
</a>
<div><b>LPCSE Architecture</b><br><small>System design showing the integration of rule-driven and data-driven models for SE.</small></div>
</td>

</tr>
<tr>

<td>
<a href="/assets/paper_img/LPCSE/GC2022-3.png">
    <img src="/assets/paper_img/LPCSE/GC2022-3.png" style="width:25vw; border-radius:8px;"/>
</a>
<div><b>LPCSE Architecture (Detailed Module Design)</b><br><small>Architecture of the rule-driven and data-driven components for LPC-based SE.</small></div>
</td>

<td>
<a href="/assets/paper_img/LPCSE/GC2022-4.jpg">
    <img src="/assets/paper_img/LPCSE/GC2022-4.jpg" style="width:25vw; border-radius:8px;"/>
</a>
<div><b>Visualization of LPCSE Results</b><br><small>Comparison between noisy, distorted, and LPCSE-enhanced Mel-spectrograms.</small></div>
</td>

</tr>
</table>



A brief introduction to this project is shown in the video below.

<div class="video-container">
<iframe class="fitvidsignore" src="https://www.youtube.com/embed/1dW7MAzoys8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>  

---

