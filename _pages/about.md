---
permalink: /
title: "About Me"
excerpt: " - Yibo Huang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hey there! I am a Research Fellow at [CSE](https://cse.engin.umich.edu/people/postdocs/) of University of Michigan working with [Prof. Ang Chen](https://web.eecs.umich.edu/~chenang/).
Prior to that, I was a Postdoc Associate in [CS](https://cs.rice.edu/) at RICE University.
I was a high-speed network engineer at ByteDance focusing on developing RDMA systems during May. 2020 ~ Aug. 2022.
I got my Ph.D. degree in Computer Science at Fudan University, co-advised by Prof. Jie Wu and [Prof. Yang Xu](https://yangxu.info/) in Dec. 2021.
<!-- I got B.S. in Software Engineering from Central South University in Jun. 2016. -->

My research has received **ACM APNet 2025 Best Paper Award**, **Usenix Security 2023 Distinguished Paper Award** and **ACM CoNEXT 2022 Best Paper Award**.
I also received Distinguished RDMA Programming Instructor prize from the [HPC-AI advisory council](https://www.hpcadvisorycouncil.com/).

My research interests mainly lie in the general fields of systems, networking, and security, with a particular focus on applying hardware-software co-design, system-network co-design, and ML techniques to improve system performance, efficiency, and security. 

<!-- My PhD thesis is on "Building Fast, Compatible and Efficient Datacenter Systems with Kernel-bypass Networks". -->

<!-- In particular, I focus on the system design, development and optimization about RDMA-enhanced datacenter systems, eBPF systems, OS security, network protocol stack and RPC. -->

<!-- - Office: 3011 Duncan Hall -->
<!-- - Email: yhuang (at) rice (dot) edu -->
<!-- - Office: 4844 Bob and Betty Beyster Building Ann Arbor MI, 48109 -->
<!-- - Email: yiboh (at) umich (dot) edu -->
<!-- - Former Name : **Bobo Huang** -->

<!-- Feel free to reach out me through Email if you are interested in my research work. -->

<!-- Relevant and Interested Areas
======
---
- System enhancement with RDMA.
- High-performance network stack design.
- High-performance RPC framework. -->
<!-- - Hybrid computing framework. over modern hardware -->


Publications
======

{% for post in site.publications reversed %}
  {% include archive-single-bio-pub.html %}
{% endfor %}


Awards & Honors
======

* ACM APNet Best Paper Award  <span style="float:right">2025</span>
* UMPDA Professional Development Award, University of Michigan <span style="float:right">2025</span>
* UMPDA Conference Travel Award, University of Michigan <span style="float:right">2025</span>
* Usenix Security Distinguished Paper Award <span style="float:right">2023</span>
* ACM CoNEXT Best Paper Award  <span style="float:right">2022</span>
* Distinguished RDMA Programming Instructor, HPC-AI advisory council  <span style="float:right">2022</span>
* Intel PhD Fellowship, Intel <span style="float:right">2020</span>
* APNet Student Travel Grant <span style="float:right">2019</span>


Service
======

**Conference commitee**
- EuroSys 2026 [Shadow Program Committee](https://2026.eurosys.org/pc.html#pc)
- ICSC 2025 [Program Committee](http://www.ieeesatellite.org/index.html)
- FAST 2026 [Artifact Evaluations Committee](https://www.usenix.org/conference/fast26)
- OSDI 2025 [Artifact Evaluations Committee](https://www.usenix.org/conference/osdi25/call-for-artifacts)
- ACM CoNEXT 2025 [Artifact Evaluations Committee](https://conferences.sigcomm.org/co-next/2025/#!/artifact-committee)
- IFIP NPC 2025 [Program Committee](https://npc-2025.github.io/committees.html)
- USENIX Security 2025 [Artifact Evaluations Committee](https://www.usenix.org/conference/usenixsecurity25/call-for-artifacts)
- IFIP NPC 2024 [Program Committee](https://www.npc-conference.com/#/npc2024/committees)

<!-- the 20th IFIP International Conference on Network and Parallel Computing -->

**Journal Reviewer**
- IEEE/ACM Transactions on Networking
- Transactions on Computers
- IEEE Transactions on Mobile Computing
- ACM Transactions on Computer Systems
- IEEE Transactions on Cloud Computing
- Computer Networks
- Journal of Supercomputing
- Cluster Computing


News
======

<div style="height:250px;overflow-y:scroll" markdown="1">
- 08/2025 Our work "Exposing RDMA NIC Resources for Software-Defined Scheduling" is awarded **APNet 2025 Best Paper**. Congratulations!
- 07/2025 I am invited as a PC member of International Conference on Satellite Computing (ICSC) 2025 [Program Committee](http://www.ieeesatellite.org/index.html).
- 06/2025 I am selected as a PC member of EuroSys 2026 [Shadow Program Committee](https://2026.eurosys.org/pc.html#pc).
- 05/2025 I am selected as a PC member of the USENIX FAST 2026 [Artifact Evaluation Committee](https://www.usenix.org/conference/fast26).
- 04/2025 Our work "Exposing RDMA NIC Resources for Software-Defined Scheduling" is accepted by [APNet 2025](https://conferences.sigcomm.org/events/apnet2025/index.php).
- 04/2025 I am selected as a PC member of the ACM CoNEXT 2025 [Artifact Evaluation Committee](https://conferences.sigcomm.org/co-next/2025/#!/artifact-committee).
- 04/2025 I am selected as a PC member of the OSDI 2025 [Artifact Evaluation Committee](https://www.usenix.org/conference/osdi25/call-for-artifacts), validating the availability, functionality and reproducibility of artifacts associated with the accepted OSDI'25 papers.
- 12/2024 Our work "Automated Lifting for Cloud Infrastructure-as-Code Programs" is accepted by [AIOps 2025](https://cloudintelligenceworkshop.org/index.html).
- 11/2024 I am selected as a PC member of the [USENIX Security 2025 Artifact Evaluation Committee (AEC)](https://www.usenix.org/conference/usenixsecurity25/call-for-artifacts), and will help the community do availability verification + functionality/reproducibility assessments for accepted papers. 
- 09/2023 Our work "Cloudless Computing: Simplifying Cloud Management with Infrastructure Clarity" is accepted by [HotNets 2023](https://conferences.sigcomm.org/hotnets/2023/accepted.html).
- 09/2023 I start a new journey at the CSE divison of University of Michigan.
- 08/2023 Our RDMI work is awarded **[<b style="color:#FF0000">Distinguished Paper</b>](https://www.usenix.org/conference/usenixsecurity23/presentation/liu-hongyi)** at the Usenix Security 2023. Congratulations!
- 06/2023 Our work "Remote Direct Memory Introspection" (i.e., RDMI) for baremetal cloud security is accepted by [Usenix Security 2023](https://www.usenix.org/conference/usenixsecurity23/presentation/liu-hongyi).
- 04/2023 The co-authored work "PFtree: Optimizing Persistent Adaptive Radix Tree for PM Systems on eADR Platform" will be presented on [DASFAA 2023](http://www.tjudb.cn/dasfaa2023/programs).
- 12/2022 Our paper "An Ultra-Low Latency and Compatible PCIe Interconnect for Rack-scale Communication" is awarded **[<b style="color:#FF0000">Best Paper</b>](https://conferences2.sigcomm.org/co-next/2022/#!/home)** at the ACM CoNEXT 2022 conference. Congratulations!
- 11/2022 I am awarded "Distinguished RDMA Programming Instructor" by HPC-AI advisory council.
- 09/2022 Our research work about how to use advanced PCIe interconnect to rearchitect Rack-Scale communication is accepted by ACM CoNEXT 2022. Only 28 papers are accepted out of 151 submitted. Congratulations!
- 09/2022 I officially join the CS department of RICE University as a Postdoc Associate working closely with [Prof. Ang Chen](https://www.cs.rice.edu/~angchen/). 
- 01/2022 I officially join ByteDance High-Speed Network Lab, Network Engineering Group, as a Network Engineer.
- 12/2021 I get my Ph.D. in Fudan University.
- 12/2020 I am awarded an honorary title of "The Oceanwide Scholar" for excellent academic performance at Fudan University in the 2020 year, only 10 winners in FDU each year.
- 11/2020 I am awarded "Intel Fellowship" by Intel in Shanghai.
- 11/2020 Our **FDU Starry Team** led by me wins the **Second Prize** in [the 8th APAC RDMA Programming Competition](http://www.hpcadvisorycouncil.com/events/2020/rdma/). Congratulations!
- 05/2020 I join Bytedance High-Speed Network Lab, Network Engineering Group, as a Research Intern.
- 05/2020 One research paper is accepted by JPDC 2020.
- 12/2019 I am awarded the Award of Outstanding Ph.D. Students at FDU for the academic year 2019-2020.
- 12/2019 I win the 2nd "Fudan-Oceanwide Entrepreneurship Fund" (Exploration Fund) funding.
- 11/2019 Our **FDU Starry Team** led by me wins the **Second Prize** in [the 7th APAC RDMA Programming Competition](http://www.hpcadvisorycouncil.com/events/2019/rdma/). Congratulations!
- 10/2019 One research paper is accepted by IEEE TSC 2019.
- 06/2019 I win the "Excellent Doctoral Research Promotion Program" funding at FDU.
- 06/2019 One research paper is accepted by Information Sciences 2019.
- 12/2018 I am awarded the Award for Outstanding Ph.D. Students at FDU for the academic year 2018-2019.
- 10/2018 Our **FDU Starry Team** is awarded the **Second Prize** in [the 6th APAC RDMA Programming Competition](http://www.hpcadvisorycouncil.com/events/2018/rdma/). Congratulations!
- 08/2018 Our **FDU Starry Team** is established, focusing on research and buildup of RDMA-enhanced distributed systems.
- 03/2018 I am awarded the honor of the Outstanding Teaching Assistant of Fudan University in the academic session 2017-2018, semester 1.

</div>

<!-- Our project "A Trusted Identity Unified Verification System over Zero-Trust Architecture" -->
<!-- organized by HPC-AI Advisory Council -->
 <!-- organized by NSCC Singapore & HPC-AI Advisory Council -->
 <!-- - 08/2019 Our **FDU Starry Team** wins the **Merit Prize** in [2019 APAC HPC-AI Competition](http://www.hpcadvisorycouncil.com/events/2019/APAC-AI-HPC/index.php). Congratulations! -->

---

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=398&t=tt&d=KLze7yOvPww8OOApBWjCvydGhEiyz3rsS4IcHCkDMxA&co=2d78ad&ct=ffffff&cmo=3acc3a&cmn=ff5353'></script>
