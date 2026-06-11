# GRATS: A Natural Multi-Speed Mandarin Dataset for Speech Time-Scale Modification Benchmarking

This repository hosts the official project page for **GRATS** (Granular Rate Adaptation for Temporal Scaling), a naturally recorded parallel multi-speaker Mandarin dataset for benchmarking Speech Time-Scale Modification (STSM) systems.

**Project page:** https://grats-dataset.github.io/

---

## Overview

GRATS provides independently recorded target-rate utterances from the same speaker and sentence across multiple speaking rates. This enables evaluation of STSM systems against authentic target-rate recordings rather than artificially time-scaled references.

---

## Dataset Summary

<table>
  <tr>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td>Language</td>
    <td>Mandarin Chinese</td>
  </tr>
  <tr>
    <td>Speakers</td>
    <td>25</td>
  </tr>
  <tr>
    <td>Gender</td>
    <td>13 female / 12 male</td>
  </tr>
  <tr>
    <td>Speaking rates</td>
    <td>0.5×, 0.75×, 1.0×, 1.25×, 1.5×</td>
  </tr>
  <tr>
    <td>Unique prompts</td>
    <td>60</td>
  </tr>
  <tr>
    <td>Total utterances</td>
    <td>7,500</td>
  </tr>
  <tr>
    <td>Total duration</td>
    <td>8.10 hours</td>
  </tr>
  <tr>
    <td>Sampling rate</td>
    <td>44.1 kHz</td>
  </tr>
  <tr>
    <td>Audio format</td>
    <td>16-bit PCM WAV, mono</td>
  </tr>
  <tr>
    <td>Sentence length</td>
    <td>10 Chinese characters</td>
  </tr>
</table>

---

## Paper

**GRATS: A Natural Multi-Speed Mandarin Dataset for Speech Time-Scale Modification Benchmarking**

Ghaida Fathin Aghniya, Dyah A. M. G. Wisnu, Yu Tsao, Stefano Rini

Accepted to **Interspeech 2026**.

Paper link: Coming soon.

---

## Benchmark

The benchmark evaluates representative classical and neural STSM systems using complementary metrics:

<ul>
  <li>Character Error Rate (CER)</li>
  <li>PESQ</li>
  <li>STOI</li>
  <li>DNSMOS</li>
  <li>Syllable-level duration MAE</li>
  <li>F0 correlation</li>
</ul>

Benchmark scripts, metadata format, and evaluation instructions will be made available on the project page.

---

## Dataset Access

The GRATS dataset will be released for research use through a controlled-access request process.

To request access, please contact:

**Ghaida Fathin Aghniya**  
Email: ghaidafthn.ee13@nycu.edu.tw

Please include your name, affiliation, research purpose, and intended use of the dataset.

---

## Citation

If you use GRATS, please cite:

<pre>
@inproceedings{aghniya2026grats,
  title     = {{GRATS}: A Natural Multi-Speed Mandarin Dataset for Speech Time-Scale Modification Benchmarking},
  author    = {Aghniya, Ghaida Fathin and Wisnu, Dyah A. M. G. and Tsao, Yu and Rini, Stefano},
  booktitle = {Proc. Interspeech},
  year      = {2026}
}
</pre>

---

## License

The dataset is intended for non-commercial research use under controlled access. Detailed terms will be provided with the dataset access agreement.
