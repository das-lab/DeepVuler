# DeepVuler
A Deep Vulnerability Intelligence Mining System for Open-Source Communities

## Research paper
We present the findings of this work in the following research paper:
Susheng Wu, Bin Chen, MingXu Sun, Renyu Duan, Qixiang Zhang, Cheng Huang: DeepVuler: A Vulnerability Intelligence Mining System for Open-Source Communities
## Introduction
Open-source code repositories play an important role in software development, but they also introduce a slew of security issues. Firstly, everyone can use open-source projects and libraries from the third-party ecosystem, which increases the risk of vulnerabilities attacking. Secondly, it may cause a domino effect and make these products inherit these vulnerabilities when referring to vulnerable repositories. Traditional technical methods were unable to detect these public flaws in a timely manner, leaving these developers in an insecure situation. Although vulnerability management institutes like CVE and NVD provide inadequate coverage, leading to a lack of timely, reliable, and detailed information about open-source projects' vulnerabilities. To better detect and repair vulnerability, we designed a vulnerability intelligence mining system named DeepVuler based on threads analysis and changed code in open-source communities using machine learning. We choose and define a series of effective features extracted from open-source communities to early infer vulnerability intelligence. Our result shows that two proposed models of DeepVuler achieve a detection rate of 0.979 in threads and 0.890 in changed codes. Besides, the detection from DeepVuler is often days or weeks ahead of official vulnerability disclosure.

## Dataset

