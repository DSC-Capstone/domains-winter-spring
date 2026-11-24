---
dual: true
trio: true
name1: Ren Wang
website1: https://wangren.github.io/
email1: ren.wang@intel.com
name2: Giuseppe Raffa
website2:
email2: giuseppe.raffa@intel.com
name3: Pallavi Pandit
website3:
email3: pallavi.pandit@intel.com
photo1:
photo2:
photo3:
domain: D08

title: "Intel AET (Application Energy Telemetry): Workload-Aware Energy & Activity Telemetry for Smart Computing"

bio: |
  Ren Wang is a Senior Research Scientist at Intel in Portland, Oregon. Her research spans computer architecture, compute networking, and energy-efficient systems, with a focus on how modern CPU accelerators and memory technologies (CXL, DSA, DDIO) can improve the performance and efficiency of datacenter and cloud workloads.  She has contributed to a wide spectrum of work ranging from TCP congestion control and energy efficiency to hardware/software co-design for systems, in-network computing, and tiered memory systems. Her publications have appeared in top computer architecture and systems venues including ISCA, MICRO, HPCA, ASPLOS, OSDI, and SIGCOMM. She also holds 100+ patents.

  Giuseppe “Beppe” Raffa is a Principal AI Engineer and AI Academic Research Program Director at Intel, where he leads partnerships that advance AI research and bring it into real-world use. With 15+ years of experience, he has led teams building human-centered AI for manufacturing, education, smart homes, and the future of work. His expertise spans generative and multimodal AI, agentic systems, software engineering, and human-computer interaction. He has submitted 100+ patent applications, holds 40+ granted patents, and has authored 20+ publications. He also supports the research community through NSF initiatives, university partnerships, and academic service.

description: |
  In modern data centers, cloud computing, edge and client environments, managing and optimizing energy consumption is a critical challenge. Historically, energy monitoring has been limited to coarse, socket-level measurements (such as RAPL), making it difficult to attribute power/energy usage to individual software contexts like specific threads, applications, VMs, or containers. This domain explores fine-grained, workload-aware power and activity characterization using Intel’s new Application Energy Telemetry (AET) technology. AET introduces per-RMID (Resource Monitoring ID) core energy tracking (measured in Joules) and machine-invariant core activity tracking (Cdyn, measured in nano Farads). By analyzing these two metrics across different workloads, configuration knobs (such as CPU frequency or P-states), and model architectures (such as various AI/ML inference models), students will build empirical datasets and data-science pipelines to understand how software behavior interacts with the underlying hardware operating point. Their many usages toward building application energy/power atlas, enabling cleaner software profiling, anomaly detection, AI model profiling fairer cloud billing/chargeback models, energy-aware scheduling/placement policies, and more sustainable green-software pipelines.

summer: |
  Setup, test and understand basic AET functionalities; run microbenchmark and SpecCPU benchmarks and collect data.

time: Maybe Monday or Friday noon could be better. We can figure out later.

modality: Zoom, and also in person when possible since Beppe is in SD.

industry: true

prerequisites: |
  Nice to have some Computer Architecture understanding

style: |
  We will provide both hands on and research direction mentorship.

seats: 10

tag: sys

goal: |
  understand AET materials, set up systems, configure SW correctly, run basic microbenchmarks and some or whole of SpecCPU
---
