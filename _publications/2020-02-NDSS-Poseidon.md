---
title: "Poseidon: Mitigating Volumetric DDoS Attacks with Programmable Switches"
collection: publications
permalink: /publications/2020-02-NDSS-Poseidon
excerpt: 'This paper proposes a programmable defense system against volumetric DDoS attacks.'
date: 2020-02-26
venue: 'The Network and Distributed System Security Symposium (NDSS)'
paperurl: 'https://www.ndss-symposium.org/wp-content/uploads/2020/02/24007-paper.pdf'

citation: '<i>Menghao Zhang, <b>Guanyu Li</b>, Shicheng Wang, Chang Liu, Ang Chen, Hongxin Hu, Guofei Gu, Qi Li, Mingwei Xu, Jianping Wu. &quot;Poseidon: Mitigating Volumetric DDoS Attacks with Programmable Switches&quot;. In The 27th Network and Distributed System Security Symposium (NDSS ''20), San Diego, CA, USA, February 23-26, 2020.</i>'

cnrate: 'NDSS：CCF-A/TH-CPL-A，安全领域顶级会议'

---
**Abstract:**  
Distributed Denial-of-Service (DDoS) attacks have become a critical threat to the Internet. Due to the increasing number of vulnerable Internet of Things (IoT) devices, attackers can easily compromise a large set of nodes and launch highvolume DDoS attacks from the botnets. State-of-the-art DDoS
defenses, however, have not caught up with the fast development of the attacks. Middlebox-based defenses can achieve high performance with specialized hardware; however, these defenses incur a high cost, and deploying new defenses typically requires a device upgrade. On the other hand, software-based defenses are highly flexible, but software-based packet processing leads to high performance overheads. In this paper, we propose Poseidon, a system that addresses these limitations in today’s DDoS defenses. It leverages emerging programmable switches, which can be reconfigured in the field without additional hardware upgrade. Users of Poseidon can specify their defense strategies in a modular fashion in the form of a set of defense primitives; this can be further customized easily for each network and extended to include new defenses. Poseidon then maps the defense primitives to run on programmable switches—and when necessary, on server software—for effective defense. When attacks change, Poseidon can reconfigure the underlying defense primitives to respond to the new attack patterns. Evaluations using our prototype demonstrate that Poseidon can effectively defend against highvolume attacks, easily support customization of defense strategies, and adapt to dynamic attacks with low overheads.

**Paper URL:**  
[Read or download the complete paper here](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24007-paper.pdf){:target="\_blank"}
