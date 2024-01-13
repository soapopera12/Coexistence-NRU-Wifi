# A Hybrid Channel Access Mechanism for NR-U to Improve the Coexistence Performance
The saturated licensed spectrum is insufficient to meet the increasing demand for data traffic, which paves the path for exploring new bands. Since the unlicensed bands are free of cost, efforts are made to offload the cellular data to unlicensed bands, which results in unlicensed versions of cellular technologies. New Radio Unlicensed (NR-U) is the unlicensed version of New Radio (NR). Since anyone can access unlicensed frequency, the devices follow listen before talk (LBT) to gain access to the unlicensed band. Unlike WiFi, the dominant technology in unlicensed bands,  the cellular node can not transmit data immediately after the LBT procedure. The node has to wait for the next licensed slot boundary to occur since it is scheduled technology. However, the LBT procedure can end before the occurrence of slot boundary; the period after LBT to the slot bound boundary by sending a reservation signal (RS) or staying idle using a gap.  The RS approach yields high fairness with less efficiency, whereas the gap-based approach gives better fairness with comparatively less fairness. To deal with the tradeoff in fairness and efficiency, we have proposed a hybrid channel access method that uses both gap and RS approaches. In the proposed method, the duration of RS is limited by a threshold, and the RS is transmitted as fragments. The proposed method achieves 54% to 128% higher fairness than the gap-based approach and 10% to 28% than the RS-based approach for the given simulation scenario.

## Introduction

channel access mechanism in Wi-Fi and NR-U.

![Comparing NR-U and WiFi channel access scheme](./images/coexistence.png)

## Results

Efficiency graph for gap and reservation mechanism.

![Comparing NR-U and WiFi channel access scheme](./images/efficiency.png)

Fairness graph for gap and reservation mechanism.

![Comparing NR-U and WiFi channel access scheme](./images/fairness.png)

Fairness/Eficiency graph for fragemented reservation mechanism for 15 nodes in numerology 0 scenario by varying RS threshold duration.

![Comparing NR-U and WiFi channel access scheme](./images/15nodesfragRs.png)

Fairness/Eficiency graph for fragemented reservation mechanism for 15 nodes in numerology 1 scenario by varying RS threshold duration.

![Comparing NR-U and WiFi channel access scheme](./images/15nodesnum1fragRS.png)

Fairness/Eficiency graph for gap vs reservation vs fragemented reservation mechanism for 9 nodes in numerology 0 scenario (for different RS threshold duration only fragmented RS).

![Comparing NR-U and WiFi channel access scheme](./images/9nodesnum0fragRS.png)

Fairness/Eficiency graph for reservation vs fragemented reservation mechanism for 9 nodes in numerology 0 scenario for different RS threshold duration.

![Comparing NR-U and WiFi channel access scheme](./images/RSvsFragRS.png)


## Conclusion

The conventional RS-based channel access method gives higher fairness with less efficiency. The gap-based channel access method yields better efficiency where no control over fairness exists. This tradeoff in efficiency and fairness made the researchers invent new channel access schemes for NR-U. This paper proposes a hybrid channel access mechanism that combines Gap and RS-based channel access schemes. The use of fragmented RS transmission yields better efficiency than the conventional RS approach. We also proved that the proposed method gives better fairness than the normal channel access scheme. With the proposed scheme we have provided a notion of tuning the reservation signal duration according to the efficiency and fairness requirements of the user. In future work, we plan to give a mathematical model for the channel access mechanism and find the RS duration tuning function.