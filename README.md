# Detecting and Localizing Network Faults in RoCE-Based AI Clouds Under Restricted Telemetry (Extended Version)

Sinuo Cao, Weiqi Zhu, Jie Gui, Jintao He, Qun Huang (Peking University);
Hao Liang, Yang Wang, Bolong Cui, Tingfeng Jiang, Weiling Gu, Tao Peng,
Xudong Liu, Ronghua Sun, Zhi Zhang, Xiangyang Wu, Wei Song (Huawei
Technologies Co. Ltd)

This repository hosts the **extended version** of our paper accepted for
publication at *The 2026 ACM SIGOPS Annual Technical Conference (SIGOPS
ATC 2026)*:

> **Detecting and Localizing Network Faults in RoCE-Based AI Clouds Under
> Restricted Telemetry.** To appear in Proceedings of the 2026 ACM SIGOPS
> Annual Technical Conference (SIGOPS ATC 2026).
> https://doi.org/10.1145/3828523.3857027

**Note:** the DOI has been assigned but will not become resolvable until
the paper is officially published in the ACM Digital Library.

The content of the extended version is identical to the version accepted for publication,
except that it additionally includes **Appendix A**, which details the
optional LossFromProbe signal (active probing architecture: controller,
agents, and analyzer).

## About the paper

FACT is a production fault detection and localization system for RoCE-based
AI public cloud infrastructures. Operating under public-cloud
constraints and commodity-switch hardware, it exploits protocol-native
signals already present in the network — NAK packets, packet-conservation
counters, and per-flow throughput computed from mirrored packet headers —
organized in a two-tier architecture that separates fault detection from
root-cause analysis. FACT has run in multiple production infrastructures;
in 2025 it localized 99.95% of network faults within 10 minutes.

## License

The paper is distributed under the
[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

© 2026 Copyright held by the owner/author(s).
