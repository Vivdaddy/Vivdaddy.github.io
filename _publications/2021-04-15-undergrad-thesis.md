---
title: "Generating Certifiably Robust Deep Neural Networks with Minimal Prediction Overhead."
collection: publications
permalink: /publication/undergrad_thesis
excerpt: 'My undergraduate honors thesis. In this work, I present a prediction mechanism with a 9xs speedup compared to the one presented in PixelDP'
date: 2021-04-15
venue: 'Electronics Theses for Schreyer Honors College'
paperurl: 'https://honors.libraries.psu.edu/files/final_submissions/7212'
citation: 'Vivek Anand (2021). &quot;Generating Certifiably Robust Deep Neural Networks with Minimal Prediction Overhead.&quot; <i>Electronic Theses for Schreyer Honors College</i>.'
---
My undergraduate honors thesis. In this work, I present a prediction mechanism with a 9xs speedup compared to the one presented in [PixelDP](http://www.cs.columbia.edu/~suman/docs/pixeldp.pdf).

## Abstract
Over the past decade, Deep Neural Networks (DNNs) have become prevalent in several sensitive and security critical applications such as self-driving cars, facial recognition, anomaly detection, chatbots etc. In these applications, it is imperative that the DNN functions as intended and is robust to malicious adversaries and attacks. However, DNNs have been found to be systemically vulnerable to adversarial attacks. These adversarial attacks result from inputs being carefully manipulated resulting in incorrect outputs by the DNN. These attacks may even be imperceptible to a naked eye such that manual intervention may be insufficient or even infeasible. Till now, most defences to these adversarial attacks require significant computational overhead in both/either training and inference even on powerful graphics processing units (GPUs) resulting in considerable energy and time expended. In this work, to mitigate this overhead, we present a simple algorithm, FAST_DP_PREDICT to reduce computational costs during prediction. Specifically, we minimize the additional i.i.d. samples of the noise required to estimate the mean scoring function of the DNN during the certified prediction mechanism of the baseline PixelDP mechanism. We do this by leveraging the normal approximation to the binomial and adaptive sampling. In our extensive experiments on the CIFAR-10 dataset, we show that FAST_DP_PREDICT unequivocally outperforms the baseline PixelDP prediction mechanism across the board with at least a 9xs end to end speedup.


[Download paper here](https://honors.libraries.psu.edu/files/final_submissions/7212)

