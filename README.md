<!-- ===================================================== -->
<!--                     HEADER                            -->
<!-- ===================================================== -->

<h1 align="center">IRIS Benchmarks</h1>

<p align="center">
  <strong>Standardized Comparisons. Real-World Conditions.</strong>
</p>

<p align="center">
  Controlled evaluation of computer vision models under consistent, real-world scenarios.
</p>

<p align="center">
  <a href="#featured-benchmarks">Explore Benchmarks</a> •
  <a href="#methodology">Methodology</a> •
  <a href="#related-repositories">Ecosystem</a>
</p>

---

<p align="center">
  <img src="assets/iris-benchmark-hero.png" width="100%" />
</p>

---

<!-- ===================================================== -->
<!--                     BADGES                            -->
<!-- ===================================================== -->

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Real--World%20Evaluation-black" />
  <img src="https://img.shields.io/badge/Comparison-Standardized-blue" />
  <img src="https://img.shields.io/badge/Architectures-YOLO%20%7C%20RT--DETR%20%7C%20Faster%20R--CNN%20%7C%20SSD%20%7C%20RetinaNet-green" />
  <img src="https://img.shields.io/badge/Status-Active%20Development-orange" />
</p>

---

<!-- ===================================================== -->
<!--                 WHAT THIS IS                          -->
<!-- ===================================================== -->

## What This Repository Is

IRIS Benchmark is the **comparison layer** of the IRIS ecosystem.

It exists to evaluate how computer vision models behave under:
- consistent training and validation conditions  
- real-world environmental variability  
- operationally relevant constraints  

This is not a collection of isolated results.

It is a structured system for understanding **model behavior across conditions**.

---

<!-- ===================================================== -->
<!--                 WHY IT EXISTS                         -->
<!-- ===================================================== -->

## Why This Exists

Most model evaluations optimize for a score.

They do not answer:
- how models behave under distance and scale
- how performance shifts in cluttered environments
- where failure modes actually emerge

IRIS Benchmark focuses on:
- **behavior, not just metrics**
- **consistency, not just peak performance**
- **comparability across architectures**

---

<!-- ===================================================== -->
<!--               FEATURED BENCHMARKS                     -->
<!-- ===================================================== -->

## Featured Benchmarks

<table>
  <tr>
    <th>Benchmark</th>
    <th>Domain</th>
    <th>Focus</th>
    <th>Architectures</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>Anti-UAV EO</strong></td>
    <td>Drone Detection</td>
    <td>Small / distant object detection</td>
    <td>YOLO, RT-DETR, Faster R-CNN</td>
    <td><a href="#">View</a></td>
  </tr>
</table>

---

<!-- ===================================================== -->
<!--                VISUAL COMPARISON                      -->
<!-- ===================================================== -->

## What These Benchmarks Show

<p align="center">
  <img src="assets/iris-benchmark-comparison.png" width="90%" />
</p>

These comparisons highlight:
- detection confidence differences  
- localization consistency  
- failure cases under real-world conditions  

---

<!-- ===================================================== -->
<!--                 METHODOLOGY                           -->
<!-- ===================================================== -->

## Methodology

All benchmarks are designed around **controlled comparability**.

### Standardization

- consistent dataset splits  
- aligned preprocessing pipelines  
- controlled training conditions where applicable  

### Evaluation

- mAP, mAR, IoU  
- qualitative inspection of outputs  
- failure mode analysis  

### What Matters

- consistency across frames  
- performance under environmental variation  
- behavior at operational limits  

---

<details>
<summary><strong>Why Metrics Alone Are Not Enough</strong></summary>

Traditional metrics provide frame-level evaluation.

They do not capture:
- persistence across sequences  
- sensitivity to environmental change  
- real-world failure behavior  

IRIS Benchmark pairs quantitative metrics with qualitative evaluation to provide a more complete picture of model performance.

</details>

---

## How This Fits Into IRIS

**Flow:**

- Benchmarks → structured comparisons  
- Experiments → how models were developed  
- Model Zoo → deployable outputs  

---

## Related Repositories

- **IRIS Model Zoo**  
  Released models with weights and deployment profiles  
  → [Link]

- **IRIS Experiments**  
  Experiment lineage and model evolution  
  → [Link]

---

## External Resources

[IRIS](https://iriscomputervision.ai/)
- Hugging Face Models → [Link]  
- IRIS Platform → [Link]  
- Case Studies → [Link]

---

<p align="center">
  <strong>IRIS is built for lifecycle-driven computer vision.</strong>
</p>
