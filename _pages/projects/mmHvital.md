<h3 id="mmhvital" short-label = "mmHvital: mmWave - Vital Sign"> mmHvital: A Study on Head-Mounted mmWave Radar for Vital Sign Monitoring 
<a href="https://dl.acm.org/doi/10.1145/3722570.3726889" style="color: blue; font-size: 0.9em;">[paper]</a>
</h3>

As wearable sensing evolves toward non-contact and mobility-friendly designs, mmHvital explores how head-mounted mmWave radar can monitor vital signs such as heart rate (HR) and respiration rate (RR) without chest-level placement. The motivation stems from the limitations of traditional radar setups, which require fixed, front-facing positioning and make them unsuitable for natural, mobile usage in daily scenarios.

In this work, I designed and built the first head-mounted mmWave sensing prototype for vital sign monitoring, integrating a TI IWR6843AOP radar into a helmet alongside OmniBuds and Polar H10 sensors for benchmarking.  
The system investigates how sensor position, user posture, and chest motion visibility affect radar-based HR and RR estimation. To move beyond accuracy-only metrics, I introduced VITAL-KL, a new waveform-similarity metric that quantifies differences in respiratory and cardiac signal morphology between modalities.
Results show that front-facing placements achieve high similarity and up to 97% HR accuracy, while rear placements degrade performance due to motion obstruction, which provide design insights for future wearable radar systems, highlighting the feasibility of embedding mmWave sensing into natural form factors such as helmets, glasses, and AR headsets.

<table style="text-align:center; margin:auto;">
<tr>
  <td>
    <a href="/assets/paper_img/mmHvital/mmHvital_setup.png">
      <img src="/assets/paper_img/mmHvital/mmHvital_setup.png" style="width:30vw; border-radius:8px;"/>
    </a>
    <div><b>Head-Mounted Prototype</b><br><small>Helmet-integrated mmWave radar with OmniBuds and Polar H10 sensors for multimodal validation.</small></div>
  </td>
  <td>
    <a href="/assets/paper_img/mmHvital/mmHvital_sys.png">
      <img src="/assets/paper_img/mmHvital/mmHvital_sys.png" style="width:25vw; border-radius:8px;"/>
    </a>
    <div><b>System Architecture</b><br><small>mmWave-based HR/BR estimation pipeline with VITAL-KL comparison across sensing modalities.</small></div>
  </td>
</tr>
</table>
