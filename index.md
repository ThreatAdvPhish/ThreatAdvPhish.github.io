---
layout: page
title: ThreatAdvPhish
tagline: Description and Resources
# description: Website for threatAdvPhish
---


Welcome to the website related to the paper _"Are Adversarial Phishing Webpages a Threat in Reality?” Understanding the Users' Perception of Adversarial Webpages_ accepted to [WWW'24](https://www2024.thewebconf.org/).

We will [present the paper](https://www2024.thewebconf.org/program/full-schedule/) in Singapore on Thursday, May 16th, 2024 (@15:00)!

---

### Summary: 
**What did we do?** In this work, we examine if adversarial Phishing webpage is a threat in reality by investigating how _human users_ perceive adversarial phishing webpages that evade ML-PWD (both commercial detectors and custom-made state-of-the-art Machine Learning based Phishing website detector).

**Story:** Machine Learning (ML) algorithms seek to autonomously learn (by “training” on a given
dataset) to identify patterns that may not be discernible to the human eye. ML-based phishing website detectors (ML-PWD) can detect previously unseen phishing websites while maintaining low rates of false positives by analyzing either textual or visual features from any given webpage, which has now become mainstream for the detection of phishing webpages. Unfortunately, ML-PWD are prone to adversarial evasions, evidenced by both academic studies and analyses of real-world adversarial phishing webpages. Evasion attacks introduce perturbations to the webpage (HTML or in some visual element) to craft “adversarial phishing webpage” (APW) that fool an ML-PWD. However, existing works mostly focused on assessing adversarial phishing webpages against ML-PWD, while neglecting a crucial aspect: investigating whether they can deceive the actual target of phishing—_the end users_. Our work target to investigate _'**What is the impact of Aadversarial ML on the end-users in practice?**'_, which is achieved by exploring questions:

* **Do adversarial webpages that bypass phishing detectors also deceive users?** (Are adversarial phishing webpages a threat in reality?)
* **What cues do users typically look for (and potentially rely on) to judge the legitimacy of any given website?** (How do users perceive adversarial phishing webpages?)
  
**How did we investigate?** We recruited **470** users to participate in our study, browsing and classifying webpages: legitimate, unperturbed phishing webpages and adversarial phishing webpages (including webpages in the wild bypassed commercial ML system and custom webpages evaded custom ML-PWD), and state their basis for the classification.

**What did we find?** Our results show that **Adversarial phishing webpage is a threat to both users and ML-PWD.** Specifically, three out of four custom-made adversarial perturbations have comparable effectiveness in deceiving users when compared to unperturbed phishing webpages. However, not all adversarial perturbations are equally effective in deceiving users. In which adversarial webpages with added typos are more noticeable to users.

**So what?**  Cyber Security should not only consider the security of complex algorithms or systems, but also human-oriented security. Assessing the users’ response to adversarial webpages should be a mandatory step to evaluate evasion attacks in the context of phishing webpage detection.

### Demonstrative Video (3 minutes)

You can see how we conducted our study in the video below (watch it in 1080p for better details)!

<iframe width="560" height="315" src="https://www.youtube.com/embed/2nSNUX2tKMA?rel=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

### Artifact and Resources

We submitted an Artifact of our paper to the WWW [Artifact Evaluation](https://www2024.thewebconf.org/calls/artifact-badging/), and we received an "Available" badge! 

<a href="https://www.acm.org/publications/policies/artifact-review-badging" target="_blank"><img src="https://www.acm.org/binaries/content/gallery/acm/publications/large-replication-badges/artifacts_available.jpg" alt="ACM Available Artifact" width="100"/></a>

We publicly release all the material  of our Artifact. Specifically:
* [GitHub Repository](https://github.com/hihey54/www24_threatAdvPhish), containing the source-code and instructions to replicate our results;
* [Preprint](https://arxiv.org/pdf/2404.02832.pdf) of the main paper.

If you use any of such resources, we kindly ask you to cite our paper with the following BibTeX entry:
```
@inproceedings{yuan2024are,
  title={{“Are Adversarial Phishing Webpages a Threat in Reality?” Understanding the Users’ Perception of Adversarial Webpages}},
  author={Yuan, Ying and Hao, Qingying and Apruzzese, Giovanni and Conti, Mauro and Wang, Gang},
  booktitle={ACM International World Wide Web Conference (TheWebConf)},
  year={2024},
  publisher={ACM, New York, USA},
  doi={10.1145/3589334.3645502}
}
```

#### Contact
Feel free to reach out to us! You can contact [Ying Yuan](mailto:yingyuan978@gmail.com) (you can also reach her at her [personal website](https://sites.google.com/view/yingyuan/home)). You can also post a comment on the [GitHub Repository](https://github.com/hihey54/www24_threatAdvPhish).