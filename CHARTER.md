# Quality of Service (QoS) SIG Charter

Quality of Service (QoS) SIG objective is to identify high priority gaps in the RISC-V technology portfolio relating to QoS in all segments of the RISC-V ecosystem.

Quality of Service (QoS) is the minimal end-to-end performance that is guaranteed in advance by a service level agreement (SLA) to an application as measured through metrics such as instructions per cycle (IPC), latency of servicing work, etc. When multiple applications run concurrently on modern processors with large core counts, multiple cache hierarchies, and multiple memory controllers, the performance of an application may become less deterministic or even non-deterministic as the performance depends on the behavior of all the other applications in the machine that contend for the shared resources leading to unfair and/or unexpected performance impacts to the application.

The QoS SIG objective is to define the strategy to address the desire for achieving deterministic performance by minimizing the interference caused by contention for shared resources. The QoS SIG will work on a gap analysis to identify RISC-V technology gaps and define the strategy and priority to address the identified gaps. In conducting that work, it is expected that the QoS SIG will recommend formation of TGs to define the HW and SW interfaces in the form of non-ISA and/or ISA extensions that solutions can be built upon.

The QoS SIG, under the SoC Infra HC, will work closely with other SIGs, TGs, and HCs to develop the necessary hardware and software technologies.
