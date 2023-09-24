# Learning to Immunize Images for Tamper Localization and Self-Recovery (Imuge+), TPAMI 2023
Paper: https://arxiv.org/pdf/2210.15902 (not the final version)

## What is image immunization?
Digital images are vulnerable to nefarious tampering attacks such as content addition or removal that severely alter the original meaning. It is somehow like a person without protection that is open to various kinds of viruses. Image immunization (Imuge) is a technology of protecting the images by introducing trivial perturbation, so that the protected images are immune to the viruses in that the tampered contents can be auto-recovered. This paper presents Imuge+, an enhanced scheme for image immunization. By observing the invertible relationship between image immunization and the corresponding self-recovery, we employ an invertible neural network to jointly learn image immunization and recovery respectively in the forward and backward pass. We also introduce an efficient attack layer that involves both malicious tamper and benign image post-processing, where a novel distillation-based JPEG simulator is proposed for improved JPEG robustness.  Our method achieves promising results in real-world tests where experiments show accurate tamper localization as well as high-fidelity content recovery. Additionally, we show superior performance on tamper localization compared to state-of-the-art schemes based on passive forensics.

## to-do lists

- [ ] release code (scheduled late October, 2023)

- [ ] release pretrained models (scheduled late October, 2023)

- [ ] release hand-crafted manipulated images (scheduled late October, 2023)

(the first author is currently busy with graduation and job seeking, and therefore wish to postpone release of code subject to some mandatory code cleaning.)

Please kindly star the repo to get updated :)
