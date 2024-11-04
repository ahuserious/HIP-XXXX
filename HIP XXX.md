# HIP XXX: Enhancing CBRS Radio Investments, Multi-Carrier Network Expansion, and PoC Rewards Integrity

- Author(s): [Author Names]
- Start Date: [Date]
- Category: Economic
- Original HIP PR: [Link to PR]
- Tracking Issue: [Link to Issue]
- Vote Requirements: [Voting Requirements]

## Summary
This Helium Improvement Proposal (HIP) addresses several shortcomings of [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) and the potential underlying reversal strategies. The indended actions are to strategically reverse [HIP 113's](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) inherent shortsided narrative undermines CBRS's utility by the network, CBRS deployers and Helium Mobile customers. 

This HIP introduces a multi-faceted strategy to protect investments in Citizen Band Radio Spectrum (CBRS) radios, optimize Proof-of-Coverage (PoC) rewards, and expand Helium's capabilities through multi-carrier approaches and efficient data offloading. It focuses on supporting rural last-mile deployments to bridge connectivity gaps while mitigating potential abuse of the PoC reward system in other environments.

## Motivation 

### CBRS gateways and radios have been the main way to deploy mobile coverage since the beginning of the Helium 5G network.
 CBRS was portrayed in [HIP 113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) to be impractical and substantially changed coverage points, and, [HIP 93](https://github.com/helium/HIP/issues/754) introduced Wi-Fi Access Points (APs), which do provide some coverage within 800 feet, but with the short range of connectivity, it far from solves the challenges of long range 5G connectivity. CBRS radios' longer range and ease of deployment can extend into the last mile and add to existing mobile network coverage, especially in rural areas, where coverage is needed most.  CBRS radio represents significant investments by network participants, and there is a need to align their deployments with the mission of democratizing the citizen band spectrum. The current PoC reward system has imbalances that are vulnerable to exploitation, leading to disproportionate rewards for certain setups while under-rewarding legitimate deployments. By introducing multi-carrier support and data offloading mechanisms, we aim to enhance network reliability and utility, particularly in rural areas where connectivity challenges are most acute.
## Explorer stats compared by timeframe
Presented below are helium network stats via [moken.io explorer](https://explorer.moken.io/network-stats/detailed). 
### Pre HIP 0113
#### [Hotspots](https://imgur.com/oeU6ZTg)
#### [Cells](https://imgur.com/LtAi4ld)
#### [Cell Types](https://imgur.com/75Y8Rq6)
#### [Rewarded Cells by Manufacturer](https://imgur.com/PBpp1As)
#### [Mobile Data](https://imgur.com/XRrIEgN)
### Post HIP 0113
#### [Hotspots](https://imgur.com/83enfQ2)
#### [Cells](https://imgur.com/GilH5iJ)
#### [Cell Types](https://imgur.com/NXd2LtL)
#### [Rewarded Cells by Manufacturer](https://imgur.com/PwcuEZd)
#### [Mobile Data](https://imgur.com/XgT1qZo)

The chronology of 7 months prior to and since the passing of [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) show the stagnation of growth in CBRS and primary dependence on indoor and outdoor WiFi hotspots. 

## Stakeholders

- **Deployers:** CBRS radio owners, especially those in rural areas, who will benefit from optimized rewards and support for multi-carrier networks.
- **Subscribers:** Users who will experience improved network coverage and reliability through expanded multi-carrier support and efficient data offloading.
- **Service Providers:** Entities that will collaborate on multi-carrier solutions, enhancing network capabilities and reach.
- **Token Holders:** Members of the Helium community invested in the fairness and integrity of the PoC reward system. 
- **Helium Community:** The broader network participants are affected by changes in network utility and PoC reward distribution.

### Concept Introduction
The Citizen Broadband Radio Service (CBRS) was created to decentralize and democratize access to wireless spectrum, allowing citizens and businesses to manage their own networks. However, [HIP 0113](https://github.com/helium/HIP/blob/main/0093-addition-of-wifi-aps-to-mobile-subdao.md), with its centralization of Proof of Coverage (PoC) and Oracle-based verification, directly contradicts these principles. More critically, it undermines the significant efforts of the federal government to bridge the digital divide by expanding rural and last-mile connectivity. This proposal argues that [HIP 0113](https://github.com/helium/HIP/blob/main/0093-addition-of-wifi-aps-to-mobile-subdao.md) is not only counterproductive to the CBRS citizen-first model but also actively works against federal initiatives to increase wireless access, particularly in underserved areas.

[HIP 0113's](https://github.com/helium/HIP/blob/main/0093-addition-of-wifi-aps-to-mobile-subdao.md) centralization of network control and its exclusionary practices—such as limiting SIM providers and restricting CBRS deployers from using their own Spectrum Access Systems (SAS)—represent a backward step in democratizing wireless access. By maintaining this centralized approach, Helium is essentially a “dagger in the back” of ongoing government efforts to provide funding and resources to enhance connectivity in rural and marginalized areas, and for the United States of America to become a global leader in Open RAN – areas that Helium could otherwise help to serve.

## Supporting Statements
### 1. CBRS: "Citizen" as the Core Principle
The essence of CBRS is to empower citizens and businesses to manage wireless spectrum access without depending on large telecom providers. [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md), however, reduces the ability of everyday citizens to participate actively in the Helium network, especially by centralizing coverage verification into Oracle-controlled processes. This centralization contradicts the CBRS goal of putting individuals in control of network infrastructure and discourages decentralized wireless innovation. 

### 2. Limiting SIM Providers and CBRS Deployers is Antithetical to Wireless Democratization
By limiting SIM providers from creating and distributing their own SIMs that use the Helium network, Helium is blocking a vital form of decentralization and innovation. SIM providers could potentially empower a wide range of devices to access the Helium network in a more citizen-driven model. Helium’s current approach keeps power and control centralized within a small group, reducing market opportunities for smaller players to innovate and bring services to their local communities. This stifles innovation, particularly in rural areas, where flexible, local spectrum management is crucial for effective broadband deployment. Allowing SIM providers and local CBRS deployers more freedom would encourage a more diverse and inclusive wireless environment, in line with the goals of federal digital divide programs.

### 3. CBRS: A Citizen-Driven Initiative 
At the heart of CBRS is the idea that citizens, communities, and businesses should be able to manage wireless spectrum access independently. By centralizing network verification and SIM control, Helium is essentially undermining the CBRS vision of empowering individuals and smaller entities. This directly contradicts the citizen-first focus and prevents decentralized network growth—shutting out local communities, particularly those in rural areas, from building and managing their own wireless infrastructure.

### 4. Helium is Undermining Federal Efforts to Bridge the Digital Divide
The U.S. federal government has invested billions in initiatives like the [Rural Digital Opportunity Fund](https://www.usac.org/high-cost/funds/rural-digital-opportunity-fund/) (RDOF) and the [Broadband Equity, Access, and Deployment](https://broadbandusa.ntia.doc.gov/funding-programs/broadband-equity-access-and-deployment-bead-program) (BEAD) program, specifically aimed at closing the digital divide in rural and underserved areas. [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) runs counter to these efforts by centralizing network control, stifling innovation, and excluding community-based participation. The shift away from decentralized PoC disproportionately impacts rural deployments, which benefit most from community-driven wireless infrastructure due to the unique challenges of last-mile connectivity.

### 5. [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) Undermines Rural Connectivity Solutions
In underserved areas, local control over network infrastructure is vital to expanding coverage. However, [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md)’s centralization restricts this reducing the ability of rural communities to leverage the Helium network for affordable, decentralized last-mile connectivity. By imposing top-down control over wireless validation and network management, [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) makes it difficult for rural areas to independently build and manage wireless infrastructure that could benefit from federal broadband grants and funding programs.

### 6. Federal Broadband Funding Expects Decentralized, Community-Driven Solutions
Many federal programs, such as [[USDA's Reconnect Program]](https://www.usda.gov/reconnect) and [NTIA’s Broadband Infrastructure Program](https://broadbandusa.ntia.doc.gov/broadband-infrastructure-program), aim to empower local stakeholders, including citizens, cooperatives, and municipalities, to develop broadband solutions tailored to their communities. ['HIP 0113's'](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) centralized approach to network management and verification discourages local involvement, thus making Helium ineligible or unsuitable for participation in such programs, where decentralized, community-driven solutions are explicitly encouraged. This failure to align with federal objectives limits Helium's potential to play a major role in these broadband expansion efforts.

### 7. Limiting CBRS Deployers from Using their Own SAS
The U.S. federal government has invested billions in initiatives like the Rural Digital Opportunity Fund (RDOF) and the Broadband Equity, Access, and Deployment (BEAD) program, specifically aimed at closing the digital divide in rural and underserved areas. [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) runs counter to these efforts by centralizing network control, stifling innovation, and excluding community-based participation. The shift away from decentralized PoC disproportionately impacts rural deployments, which benefit most from community-driven wireless infrastructure due to the unique challenges of last-mile connectivity.

### 8. [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) Stifles Federal Efforts
By centralizing control and excluding community-driven participation, [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) fundamentally opposes the spirit of federal programs designed to enhance rural and last-mile connectivity. These programs prioritize decentralization, local ownership, and innovation—values that are eroded by the top-down control embedded in [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md). Helium’s current trajectory risks becoming a barrier to the government’s mission of achieving universal broadband access, a mission that requires more flexible, community-led, decentralized solutions.

## This proposal outlines key changes aimed at enhancing network stability, security, and efficiency:
### Reverse the POC Rewards Rebalancing - outlined in [HIP 0113](https://github.com/helium/HIP/blob/main/0093-addition-of-wifi-aps-to-mobile-subdao.md) 
### EXAMPLE - HIP 0113 PROPOSED:: 
#### Current Rewards
|:------:|:COVERAGE POINTS :|:MOBILE REWARDS :| :% TOTAL:|
|:CBRS:  | :26,199,967:     |:36,756,229:     |:75.5%:   |
|:WiFi:  |:8,492,786:       |:11,916,220:     |:24.5%:   |
|:Total: |:34,692,753:      |:48,672,449      |:100.0%:  |

#### Proposed Rewards
|:------:|:COVERAGE POINTS :|:MOBILE REWARDS :| :% TOTAL:| :% CHANGE: |
|:CBRS:  |:6,549,992:-------|:36,756,229:     |:43.5%:   |:-42.3%:    |
|:WiFi:  |:8,492,786:-------|:11,916,220:     |:56.5%:   |:+130.6%:   |
|:Total: |:15,042,778:------|:48,672,449:     |:100.0%:  |:0%:        |

### Proposed Reversal *Retroactive
|:------:|:COVERAGE POINTS :|:MOBILE REWARDS :| :% TOTAL:| :% CHANGE: |
|:CBRS:  |:26,199,967:      |:36,756,229:     |:75.5%:   |:+42.3%:    |
|:WiFi:  |:8,492,786:       |:11,916,220:     |:24.5%:   |:-130.6%:   |
|:Total: |:34,692,753:      |:48,672,449      |:100.0%:  |:0%:        |

### Reintroduce PoC Validation: 
Return to the original system where hotspots are responsible for verifying coverage using peer-to-peer signal validation. This could be implemented with a weighted reward system that prioritizes rural deployments where connectivity is most needed. This system will adjust PoC rewards to provide greater incentives for CBRS radios deployed in underserved rural areas. Deployments in densely populated urban areas will be scrutinized for potential manipulation and may receive adjusted rewards accordingly, ensuring fairness and discouraging exploitative practices.

[Helium Mobile - December 21, 2022 - 7000 active radios deployed](https://blog.hellohelium.com/you-asked-we-answered/)

### Multi-Carrier Network Expansion
Introduce support for multi-carrier approaches, allowing hotspots to interact with multiple carriers. This will enhance network reliability, particularly in areas where a single carrier lacks sufficient coverage. By leveraging partnerships with multiple carriers, we can expand the network's capabilities and provide a more seamless experience for subscribers.
### Data Offloading Optimization
Integrate data offloading mechanisms for IoT devices to enable efficient data traffic management. This will provide additional revenue streams for operators and enhance the network's overall utility. Efficient data offloading will help manage network congestion and improve performance.

### Protection of CBRS Radio Investments
Provide special incentives for CBRS radio operators who offer valuable rural connectivity, especially those involved in multi-carrier setups. This ensures that investments in CBRS technology are protected and yield tangible benefits, encouraging continued deployment and maintenance in areas where they can have the most significant impact.

### Automated Abuse Detection Mechanisms
Develop and deploy automated systems using machine learning algorithms and geographic data analytics to detect suspicious clustering or PoC activities. These systems will actively monitor the network for potential abuse, flagging anomalies for further investigation. This helps maintain the integrity of the PoC reward system and discourages manipulative practices.

### Representative Example
A rural hotspot operator using a CBRS radio to provide last-mile connectivity will be incentivized through increased PoC rewards, multi-carrier partnerships, and data offloading capabilities. This ensures maximized uptime and efficient data flow, directly benefiting both the operator and subscribers in the area. 

## Drawbacks and Rationale
### Drawbacks
Implementing this proposal may have the following drawbacks:

- **Increased Complexity:** Introducing multi-carrier support and data offloading may increase network complexity and require additional infrastructure and coordination efforts.
- **Potential Friction:** Reward rebalancing might cause dissatisfaction among urban hotspot owners who may perceive the adjustments as unfairly impacting them.
- **False Positives:** Automated abuse detection mechanisms might occasionally flag legitimate operators, leading to unwarranted investigations or reward adjustments.
- **Regulatory and Technical Challenges:** Coordinating with multiple carriers could present regulatory hurdles and technical integration challenges that need to be carefully managed.
- **Shift in Focus:** Overemphasis on data offloading might shift focus away from decentralized coverage, potentially impacting the network's core objectives.

### Rationale

This design aims to balance equitable reward distribution, enhance rural connectivity, and improve network efficiency. By leveraging advanced algorithms and multi-carrier support, we can ensure fairness, sustainability, and increased utility of the network. The proposed changes address existing vulnerabilities in the PoC reward system and align incentives with the network's mission.

## Alternatives Considered

- **Blanket Penalties for Urban Deployments:** Imposing across-the-board penalties for urban deployments was considered but deemed unfair and potentially alienating to community members operating in urban areas.
- **Increased Hotspot Costs:** Raising the costs for hotspot deployment was considered but could stifle network growth and discourage new participants.
- **Do Nothing:** Maintaining the status quo would allow ongoing reward exploitation and fail to address connectivity challenges in rural areas, ultimately degrading network trust and utility.

## Unresolved Questions

Several aspects of this proposal require further discussion and refinement:

- **Reward Scaling Factors:** Determining the appropriate scaling factors for rewards based on deployment location (rural vs. urban) needs careful analysis to ensure fairness.
- **Abuse Detection Thresholds:** Establishing thresholds for flagging potential abuse requires balancing sensitivity and specificity to minimize false positives.
- **Multi-Carrier Coordination:** The specifics of integrating and coordinating with multiple carriers need to be detailed, including technical and contractual considerations.
- **Implementation Details:** The development of machine learning models for abuse detection, data pipelines, and integration of geographic data for reward adjustments will require further planning.

## Deployment Impact

Implementation of this HIP will have the following impacts:

- **Effect on Users:** Urban operators may see adjustments in PoC rewards if their deployments are flagged for potential abuse. Rural and CBRS radio operators should experience increased rewards and benefits from multi-carrier support.
- **Documentation Updates:** Helium's documentation regarding PoC rewards, abuse detection mechanisms, rural incentives, and multi-carrier setups will need to be updated to reflect the changes.
- **Backward Compatibility:** The proposal is backward compatible in terms of network functionality. However, adjustments to PoC rewards are forward-moving changes that cannot be undone without further consensus and action.
- **Implementation Timeline:** A clear timeline and milestones will need to be established for the development and deployment of the proposed systems.

## Success Metrics

To evaluate the success of this proposal, we will monitor the following metrics:

- **Increase in Rural Deployments:** A measurable rise in the number of hotspots deployed in rural areas, particularly those utilizing CBRS radios.
- **Multi-Carrier Integrations:** Successful partnerships and integrations with multiple carriers, leading to improved network coverage and reliability.
- **Reduction in Abuse Cases:** A decrease in flagged or suspicious PoC activities, indicating effective abuse detection and deterrence.
- **Fair Reward Distribution:** Evidence of more equitable PoC rewards aligned with network utility and contribution.
- **Community Feedback:** Positive feedback from rural operators and token holders, with reduced complaints related to PoC rewards and network performance.

## Conclusion

[HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) not only undermines the decentralized vision of CBRS but also hinders federal efforts to bridge the digital divide and expand broadband access to rural and underserved communities. Helium must reverse [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) to restore decentralized control over wireless infrastructure and align with the broader mission of wireless democratization and rural connectivity. By doing so, Helium can become a leader in the push to close the digital divide, rather than acting as a barrier to progress.

[HIP 0113's](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md) centralization of wireless validation and restriction on citizen-driven wireless innovation runs counter to the goals of the CBRS model. If Helium is to truly democratize wireless access, it must reverse [HIP 0113](https://github.com/helium/HIP/blob/main/0113-reward-cbrs-as-experimental.md), allow SIM providers to provision devices on the network freely, and give CBRS deployers control over their own SAS systems. This proposal calls for a restoration of decentralization and citizen empowerment in line with the original mission of Helium and the principles of CBRS.


[IMAGE GALLERY](https://imgur.com/a/hip-113-implications-zCcXIHY)

