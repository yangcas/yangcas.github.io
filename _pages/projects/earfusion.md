### EarFusion: Quality-Aware Fusion of In-Ear Audio and Photoplethysmography for Heart Rate Monitoring [<font color="blue">[paper]</font>](https://dl.acm.org/doi/10.1145/3737901.3768366)

EarFusion explores how in-ear audio and PPG, which includes two physiologically complementary modalities and can be dynamically fused for robust heart rate (HR) monitoring in real-world environments.  
While PPG is widely used in wearables, it is easily corrupted by motion and skin–sensor variability. In contrast, in-ear audio sensing captures cardio-mechanical vibrations that are resilient to motion but sensitive to acoustic noise. EarFusion bridges these limitations through signal quality–aware fusion that adapts in real time to the reliability of each modality.

Built on the OmniBuds earable platform, EarFusion integrates an in-ear microphone, optical PPG sensor, and reference ECG (Polar H10). The system computes modality-specific fine-grained meterics and Signal Quality Indices (SQIs) which capture SNR, morphology, and rhythm consistency and then are used to fuse HR estimates based on their reliability.
Experimental results across multiple participants and conditions show that EarFusion consistently outperforms single-modality baselines, achieving stable HR estimation under both motion and acoustic interference.

<table style="text-align:center; margin:auto;">
<tr>
  <td>
    <a href="/assets/paper_img/EarFusion/earFusion_system.png">
      <img src="/assets/paper_img/EarFusion/earFusion_system.png" style="width:28vw; border-radius:8px;"/>
    </a>
    <div><b>System Overview</b><br><small>Multimodal data collection setup integrating PPG, in-ear audio, and Polar H10 ECG for synchronized multimodal acquisition.</small></div>
  </td>
  <td>
    <a href="/assets/paper_img/EarFusion/earFusion_results.png">
      <img src="/assets/paper_img/EarFusion/earFusion_results.png" style="width:50vw; border-radius:8px;"/>
    </a>
    <div><b>Signal Quality and Fusion Results</b><br><small>Visualization of SQI-driven HR estimation under clean, motion, and audio-noise conditions.</small></div>
  </td>
</tr>
</table>
