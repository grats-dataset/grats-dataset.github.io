GRATS: A Natural Multi-Speed Mandarin Dataset for Speech Time-Scale Modification Benchmarking

This repository hosts the official project page for GRATS (Granular Rate Adaptation for Temporal Scaling), a naturally recorded parallel multi-speaker Mandarin dataset for benchmarking Speech Time-Scale Modification (STSM) systems.

Project page: https://grats-dataset.github.io/

Overview

GRATS provides independently recorded target-rate utterances from the same speaker and sentence across multiple speaking rates. This enables evaluation of STSM systems against authentic target-rate recordings rather than artificially time-scaled references.

Dataset Summary
Property	Value
Language	Mandarin Chinese
Speakers	25
Gender	13 female / 12 male
Speaking rates	0.5×, 0.75×, 1.0×, 1.25×, 1.5×
Unique prompts	60
Total utterances	7,500
Total duration	8.10 hours
Sampling rate	44.1 kHz
Audio format	16-bit PCM WAV, mono
Sentence length	10 Chinese characters
Paper

GRATS: A Natural Multi-Speed Mandarin Dataset for Speech Time-Scale Modification Benchmarking

Ghaida Fathin Aghniya, Dyah A. M. G. Wisnu, Yu Tsao, Stefano Rini

Accepted to Interspeech 2026.

Paper link: Coming soon.

Benchmark

The benchmark evaluates representative classical and neural STSM systems using complementary metrics:

Character Error Rate (CER)
PESQ
STOI
DNSMOS
Syllable-level duration MAE
F0 correlation

Benchmark scripts, metadata format, and evaluation instructions will be made available on the project page.

Dataset Access

The GRATS dataset will be released for research use through a controlled-access request process.

To request access, please contact:

Ghaida Fathin Aghniya
Email: ghaidafthn.ee13@nycu.edu.tw

Please include your name, affiliation, research purpose, and intended use of the dataset.

Citation

If you use GRATS, please cite:

@inproceedings{aghniya2026grats,
  title     = {{GRATS}: A Natural Multi-Speed Mandarin Dataset for Speech Time-Scale Modification Benchmarking},
  author    = {Aghniya, Ghaida Fathin and Wisnu, Dyah A. M. G. and Tsao, Yu and Rini, Stefano},
  booktitle = {Proc. Interspeech},
  year      = {2026}
}
License

The dataset is intended for non-commercial research use under controlled access. Detailed terms will be provided with the dataset access agreement.
