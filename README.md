# Quantum-Train Long Short-Term Memory (QT-LSTM) for Wave Prediction (PennyLane Public Demo)

### Adapted from Second Place project in Deloitte’s Quantum Climate Challenge 2024 (see details on [arXiv:2407.08617](https://arxiv.org/abs/2407.08617))

### Created by Chu-Hsuan Abraham Lin (al2823@ic.ac.uk), Chen-Yu Liu (d10245003@g.ntu.edu.tw)
This tutorial features the Quantum Train architecture proposed by Chen-Yu Liu et al. You can find more details on [arXiv:2405.11304](https://arxiv.org/abs/2405.11304) and [arXiv:2402.16465](https://arxiv.org/abs/2402.16465). Originally, in Deloitte’s Quantum Climate Challenge 2024, we implemented QT-LSTM to predict flood events along the Wupper River. However, due to the confidentiality of the data, we can only demonstrate QT-LSTM with fabricated data for simplicity while showcasing the power of this framework.
In this tutorial, we implemented a classical LSTM model to learn the time-series wave data. We then explore the components of the LSTM model and finally implement the QT-LSTM.
