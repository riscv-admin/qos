# SoC Infrastructure HC minutes 2022/06/15

- We continued to discuss [the strategy paper from QoS SIG](2022-06-01_qos_strategy.pdf):
- Discussed the interactions with possible future technologies that may
  place restrictions on access to shared resources. An example of such
  may be a future security technology. We agreed that the restrictions
  should be co-existing and the most stringent restriction should apply.
  The paper was updated with a paragraph discussing this.
- The QoS SIG recommendations:
  - Fast track a QoS ID extension
  - Take a QoS ID extension to device context to the IOMMU TG
  - Start a QoS TG to define the QoS register interface targeting
    cache and memory controllers.
  - QoS SIG to continue working on strategy for additional shared
    resources.
- Paul asked if the adoption of the QRI may become mandatory per a profile/
  platform specification in future. We discussed this would be unlikely to be
  mandatory.
- Cameron raised a concern about defining a non-ISA specification for the   register interface vs. a software API/abstraction.
- We agreed to adopt this strategy and move forward with the recommendations. 
