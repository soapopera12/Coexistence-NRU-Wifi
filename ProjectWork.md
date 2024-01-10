# A Hybrid Channel Access Mechanism for NR-U to Improve the Coexistence Performance
The saturated licensed spectrum is insufficient to meet the increasing demand for data traffic, which paves the path for exploring new bands. Since the unlicensed bands are free of cost, efforts are made to offload the cellular data to unlicensed bands, which results in unlicensed versions of cellular technologies. New Radio Unlicensed (NR-U) is the unlicensed version of New Radio (NR). Since anyone can access unlicensed frequency, the devices follow listen before talk (LBT) to gain access to the unlicensed band. Unlike WiFi, the dominant technology in unlicensed bands,  the cellular node can not transmit data immediately after the LBT procedure. The node has to wait for the next licensed slot boundary to occur since it is scheduled technology. However, the LBT procedure can end before the occurrence of slot boundary; the period after LBT to the slot bound boundary by sending a reservation signal (RS) or staying idle using a gap.  The RS approach yields high fairness with less efficiency, whereas the gap-based approach gives better fairness with comparatively less fairness. To deal with the tradeoff in fairness and efficiency, we have proposed a hybrid channel access method that uses both gap and RS approaches. In the proposed method, the duration of RS is limited by a threshold, and the RS is transmitted as fragments. The proposed method achieves 54% to 128% higher fairness than the gap-based approach and 10% to 28% than the RS-based approach for the given simulation scenario.

## Introduction

![Comparing NR-U and WiFi channel access scheme](./images/coexistence.png)

## Results

![Comparing NR-U and WiFi channel access scheme](./images/efficiency.png)

![Comparing NR-U and WiFi channel access scheme](./images/fairness.png)

![Comparing NR-U and WiFi channel access scheme](./images/15nodesfragRs.png)

![Comparing NR-U and WiFi channel access scheme](./images/15nodesnum1fragRS.png)

![Comparing NR-U and WiFi channel access scheme](./images/9nodesnum0fragRS.png)

![Comparing NR-U and WiFi channel access scheme](./images/RSvsFragRS.png)



## conclusion