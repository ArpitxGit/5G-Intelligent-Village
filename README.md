>
>The goal is to develop a UPI prototype and deploying AUSF/PCF(5G NR Functions) for secure slice operations, enabling secure financial transactions and minimizing cyber-attacks, allowing UPI transactions just with bare minimum 5G network in rural India, harness 5G technology to transform rural life, driving digital inclusion and economic growth, and showcasing the transformative potential of 5G.

# 5G-Intelligent-Village

## [TTDF Call for Proposals](https://ttdf.usof.gov.in/)

#### ”[From Connectivity Gaps to Smart Solutions: Designing 5G Networks for Rural Innovation- 5G Intelligent Villages](https://ttdf.usof.gov.in/users/intelligentvillage)”

## TITLE: Securing the Future of Rural Finance: 5G UPI Solutions with Blockchain and Advanced Network Functions

Please refer to the proposal PDF for full context and reach out if interested, we are happy to discuss any aspect fo 5G, Telco, Modern Cryptography, Blockchain and Hardware Infra.
---
# Major Components

## UPI 
UPI is an Indian instant payment system as well as protocol developed by the National Payments Corporation of India in 2016. It is based on IMPS infrastructre, IMPS offer an instant, 24*7 interbank electronic fund transfer service capable of processing person to person, person to account and person to merchant remittances via mobile, internet and ATMs.

## Network Slicing
5G network slicing is a network architecture that enables the multiplexing of virtualized and independent logical networks on the same physical network infrastructure. Each network slice is an isolated end-to-end network tailored to fulfill diverse requirements requested by a particular application.

## AUSF/PCF(5G NR Functions)
AUSF and PCF are functions responsible user equipment authentication and policy control in 5G NR architecture.  
- The Authentication Server Function (AUSF) is in a home network and performs authentication with a UE. It makes the decision on UE authentication, but it relies on backend service for computing the authentication data and keying materials when 5G-AKA or EAP-AKA' is used.
- The 5G PCF performs the same function as the PCRF in 4G networks. Provides policy rules for control plane functions. This includes network slicing, roaming and mobility management. Accesses subscription information for policy decisions taken by the UDR.
---

# Idealogy

>
>India has built an ambitious platform for digital payments, including a system for sending rupees between any bank or smartphone app – Bill Gates on UPI

This project aligns with the Aatmanirbhar Bharat vision and the '5G Intelligent Villages' initiative by leveraging 5G technology to uplift rural communities:
Fostering Self-Reliance: By developing a UPI prototype integrated with advanced 5G technologies like AUSF and PCF, this project supports self-reliance in creating secure, scalable financial systems critical for India's digital economy. Encouraging domestic innovation in telecommunications and financial technology reduces dependence on foreign technologies and promotes local expertise and solutions.
- **Extending 5G Coverage**: The project's focus on deploying 5G for secure financial transactions includes plans to extend 5G connectivity to unserved areas, thus bringing advanced communication services to underserved regions.
- **Holistic Development**: This project not only promotes self-reliance but also contributes to the holistic development of rural communities, aligning with the broader goals of Aatmanirbhar Bharat and the 5G Intelligent Villages initiative.

And this proposal is designed to bring this ambitious platform to people living in rural areas for many benefits but need to make sure that the solution is "**secure**" and "**fast**".
Incorporating "**Zero Knowledge Proofs**" and "**Smart Contracts**" for secure by design and "**5G Network Slice For Finanacial Transaction Authenticstion**" for the fastest possibility.

### Why Zero Knowledge Proofs in AUSF?

Research in zero-knowledge proofs has been motivated by authentication systems where one party wants to prove its identity to a second party via some secret information (such as a password) but doesn't want the second party to learn anything about this secret. This is called a "zero-knowledge proof of knowledge". However, a password is typically too small or insufficiently random to be used in many schemes for zero-knowledge proofs of knowledge. A zero-knowledge password proof is a special kind of zero-knowledge proof of knowledge that addresses the limited size of passwords.
More ZKPs application:
- Ethical behavior
- Blockchains
- Decentralised Identifiers and more

The Authentication Server Function (AUSF) is a critical component in 5G networks responsible for authenticating users and devices, ensuring that only legitimate entities gain access to network resources. Integrating zero-knowledge proofs (ZKPs) into the AUSF enhances security by allowing the authentication process to be both verifiable and confidential without exposing sensitive information.

#### Key Features of Zero-Knowledge AUSF can be but not limited to:

- Confidential Authentication: Enable the AUSF to verify the user equipment credentials without requiring the disclosure of private data. This ensures that sensitive credentials are never exposed, even during the authentication process, significantly reducing the risk of data breaches, specially in rural areas where services are just being provided but they are not taken care of to their full extent, not even in security.
- Resistance to Replay Attacks: By employing ZKPs, the AUSF can generate fresh, non-reusable proofs for each authentication attempt. This dynamic nature of zero-knowledge proofs ensures that even if an attacker intercepts the proof, they cannot use it to impersonate the user in future sessions, thereby thwarting replay attacks.
- Minimal Data Exchange: Zero-knowledge proofs typically involve a minimal amount of data being sent between the prover (user) and the verifier (AUSF). This makes the authentication process more efficient and less susceptible to interception, as there is less information for potential attackers to capture.
- Scalability and Flexibility: Zero-knowledge AUSF can be adapted to various authentication scenarios, including multi-factor authentication (MFA), where users may need to prove knowledge of multiple secrets without revealing any of them. This scalability makes zero-knowledge AUSF suitable for diverse applications within 5G networks, from consumer devices to IoT systems.
- Compliance with Privacy Regulations: By ensuring that sensitive information is never exposed during the authentication process, zero-knowledge AUSF helps network operators comply with stringent privacy regulations such as GDPR. This is particularly important in sectors where the protection of personal data is paramount, such as finance and healthcare.

By integrating zero-knowledge proofs into the AUSF, 5G networks can offer a higher level of security for user authentication, protecting sensitive information while maintaining the efficiency and scalability required for modern digital services.

### Why Smart Contracts in PCF?
>
>By 1996, Nick Szabo was using the term "smart contract" to refer to contracts which would be enforced by physical property (such as hardware or software) instead of by law. Szabo described vending machines as an example of this concept. In 1998, the term was used to describe objects in rights management service layer of the system The Stanford Infobus, which was a part of Stanford Digital Library Project.

In this case, financial transactions, smart contracts can be used to enforce transaction-related policies within dedicated network slices. For example, a smart contract could automatically enforce a policy that prioritizes financial transaction traffic over other types of data during peak hours, ensuring that critical financial operations are not delayed. This integration ensures that the PCF is capable of maintaining the integrity and performance of the network, even under high loads, while also providing an auditable trail of all policy enforcement actions.

Integrating smart contracts in PCF to automate the enforcement of policies within network slices. Smart contracts ensure that policies are consistently applied and can be dynamically adjusted based on real-time network data.

#### Key Advantages of Using Smart Contracts as PCF:
- Automated Policy Enforcement: Smart contracts can be programmed with specific rules and conditions that automatically trigger actions when certain criteria are met. This eliminates the need for manual intervention in policy enforcement, ensuring that policies are applied consistently across the network.
- Transparency and Trust: Since smart contracts are executed on a blockchain, their operations are transparent and verifiable by all stakeholders. This transparency fosters trust among users, network operators, and regulators, as the policy enforcement process is open to scrutiny and cannot be tampered with.
- Immutable and Secure Policy Rules: Once deployed, smart contracts cannot be altered without consensus from the involved parties. This immutability ensures that the policy rules remain secure and consistent, reducing the risk of unauthorized changes that could compromise network integrity.
- Real-Time Policy Adjustments: Smart contracts can be designed to react in real-time to changes in network conditions or user behavior. For instance, if a network slice experiences congestion, the smart contract could automatically adjust bandwidth allocation policies to maintain Quality of Service (QoS) standards.
- Decentralized Control: Using smart contracts for PCF decentralizes policy control, reducing reliance on a central authority. This can enhance the resilience of the network by distributing control across multiple nodes, making it harder for any single point of failure to disrupt network operations.
- Compliance with Regulatory Requirements: Smart contracts can encode regulatory compliance rules directly into the network’s operational framework. This ensures that all policy decisions are made in accordance with legal and regulatory standards, which is particularly important in sectors like finance where compliance is critical.
- Dynamic and Scalable Policy Management: As 5G networks scale and become more complex, smart contracts can manage a wide range of policies across different network slices and services. They enable the PCF to handle diverse requirements, such as those of different applications, devices, and user groups, efficiently and effectively.

# Architecture
![Screenshot 2024-08-30 at 11 01 40 PM](https://github.com/user-attachments/assets/2f7f40da-b4f4-4345-be63-96393d1ea025)

The UPI tech architecture remains the same but we propose an additional layer in Network Security,
<img width="1241" alt="Screenshot 2024-09-10 at 2 53 38 AM" src="https://github.com/user-attachments/assets/26dbc5c3-cd53-40cd-8be4-2e325435bef0">

5G network slice incorporating ZK AUSF and Smart Contract PCF represents a cutting-edge solution for secure and efficient financial transactions, particularly for Unified Payments Interface (UPI) systems. In this architecture, the ZK AUSF (Zero-Knowledge Authentication Server Function) employs zero-knowledge proofs to authenticate users without disclosing sensitive information, leveraging techniques such as garbled circuits and multi-party oblivious transfers for enhanced privacy and security. Complementing this, the Smart Contract PCF (Policy Control Function) utilizes blockchain technology to automate and enforce network policies, ensuring robust policy management through smart contracts. This combination enables real-time control of network resources and dynamic policy enforcement, while blockchain integration guarantees immutable and transparent transaction records. The result is a secure, scalable, and efficient network slice that not only supports the demands of modern financial transactions but also aligns with regulatory requirements and enhances overall system integrity.

<img width="828" alt="Screenshot 2024-09-10 at 2 54 21 AM" src="https://github.com/user-attachments/assets/d9ff09e2-80dd-45c5-895e-b0e510dc3382">

# Zero Knowledge 5G Authentication Server Function

The ZK-AUSF protocol leverages ZKBoo (Zero Knowledge Boolean Circuits using garbled circuits and multi-party oblivious transfers) to enable privacy-preserving authentication in the context of a 2PC (Two-Party Computation) framework. In this protocol, the focus is on ensuring minimal information disclosure while achieving robust authentication. ZKBoo empowers a prover (e.g., the User Equipment or UE) to authenticate itself to a verifier (e.g., the Authentication Server Function or AUSF) without disclosing the actual credentials. This is accomplished by securely computing the required functions using garbled circuits and oblivious transfer techniques.

The first contribution of this protocol is the application of ZKBoo’s approach to the AUSF architecture, where authentication is framed as a Two-Party Computation problem. By employing garbled circuits, the protocol ensures that the prover’s credentials remain confidential while the verifier performs the necessary computations to validate the authentication process. The use of multi-party oblivious transfers further enhances the privacy and security of the interaction.

Our second contribution addresses the challenge of privacy in authentication protocols. The ZK-AUSF protocol ensures that even though the verifier does not learn the prover’s credentials, it can still verify the authenticity of the provided proof. This is achieved through zero-knowledge proofs that maintain the integrity of the authentication process without revealing sensitive information. This approach represents a significant advancement in achieving secure and privacy-preserving authentication in modern 5G networks.

**Keywords:** ZKBoo, zero-knowledge proofs, Two-Party Computation, garbled circuits, multi-party oblivious transfers, authentication protocols.

The **ZK-AUSF** protocol ensures that the **AUSF** can authenticate the user based on their credentials without learning sensitive information about them, leveraging the ZKBoo framework. The computation is divided into two parties:

1. **Prover (UE - User Equipment)**: The user with credentials who wants to authenticate to the network.
2. **Verifier (AUSF - Authentication Server Function)**: The network entity responsible for validating the UE’s credentials.

Using ZKBoo, the UE can prove the correctness of its identity via a **zero-knowledge proof** by performing computations on Boolean circuits and sharing garbled circuits with the AUSF. The AUSF verifies the computation while ensuring confidentiality.

### **High-Level ZK-AUSF Protocol Steps:**

1. **Setup**:
    - The UE and AUSF agree on a common function (e.g., a Boolean circuit representing the authentication algorithm, such as verifying the random challenge RAND and authentication token AUTN).
    - The function will verify if the UE's secret (its credentials) matches the expected values stored by the AUSF, without revealing those secrets.
2. **Prover's Computation (UE)**:
    - The UE (prover) uses its credentials, such as **SUPI**, **RAND**, and **AUTN**, to compute a response RES and session key `K_seaf` using a Boolean circuit representing the authentication algorithm (e.g., AKA algorithm).
    - The UE garbles the circuit using ZKBoo's three-party sharing scheme, which creates **garbled circuits** based on the authentication logic.
    - For each gate of the Boolean circuit, the UE generates a **commitment** and splits the computation into **three shares**, which are then used in **multi-party oblivious transfers**.
3. **Proof Generation**:
    - The UE sends the **garbled circuits** to the AUSF, along with commitments to each share of the Boolean circuit.
    - The UE also provides a zero-knowledge proof showing that the garbled circuit's output (e.g., the computed RES) is consistent with its credentials and does not leak any private information.
    - The proof consists of three parts: the Boolean circuits, the commitments to the shares, and the result of the computation (output of the garbled circuit).
4. **Verifier's Computation (AUSF)**:
    - The AUSF verifies the UE's proof by checking the commitments and evaluating the garbled circuit using **multi-party oblivious transfers** (MOT).
    - The AUSF verifies that the output of the garbled circuit is consistent with the expected output based on its stored authentication challenge RAND and AUTN.
    - If the garbled circuit evaluation succeeds, the AUSF accepts the proof and authenticates the UE.
5. **Session Key Generation**:
    - Upon successful verification, the AUSF and UE agree on a **session key** (e.g., `K_seaf`), ensuring a secure communication channel for further exchanges.
    - The key is derived from the garbled circuit’s output and allows the UE and AUSF to establish a **security context** for future encrypted communication.

### **Detailed Protocol Steps:**

### **Step 1: Initialization**

- The UE (prover) and AUSF (verifier) agree on a Boolean circuit that represents the 5G-AKA authentication process, including computation of the response RES and generation of the session key `K_seaf`.
- The UE holds its private credentials (e.g., SUPI, AUTN, RAND) and will prove knowledge of a correct response based on these without revealing the actual credentials.

### **Step 2: Prover (UE) - Garbled Circuit Creation**

- The UE generates a **garbled circuit** that computes the AKA response and session key based on its private input.
- For each gate in the Boolean circuit, the UE computes:
    - A **garbled version** of the gate.
    - Three **shares** of the inputs for each gate, following ZKBoo’s approach.
- The UE sends the **garbled circuit** and shares to the AUSF.

### **Step 3: Multi-Party Oblivious Transfer (MOT)**

- The AUSF uses **oblivious transfer** to receive two of the three shares for each gate from the UE, ensuring it does not learn the UE’s private inputs.
- The oblivious transfer ensures that the AUSF can compute the output of the garbled circuit without seeing the intermediate values of the UE's private credentials.

### **Step 4: Verification and Commitment Checking**

- The AUSF checks the commitments to the garbled circuit and verifies that the outputs match the expected values.
- The AUSF evaluates the garbled circuit and verifies the proof, ensuring that the response RES is valid without learning the UE’s credentials.
- If the verification passes, the AUSF confirms that the UE has been authenticated.

### **Step 5: Session Key Agreement**

- If the authentication is successful, the AUSF and UE use the garbled circuit’s output to derive the session key `K_seaf`.
- The session key is then used to secure future communications between the UE and the network.

### **Security Guarantees:**

- **Zero Knowledge**: The AUSF learns nothing about the UE’s credentials, but can still verify that the UE holds valid credentials.
- **Soundness**: If the UE tries to authenticate with incorrect credentials, the AUSF will reject the proof, ensuring the protocol's correctness.
- **Privacy**: The UE’s secrets (e.g., SUPI, AUTN) remain hidden even during the verification process.

# Smart Contract 5G Policy Control Function

The Smart Contract PCF (Policy Control Function) protocol introduces a novel approach to automating policy enforcement and network management in 5G networks through the use of smart contracts. This protocol integrates smart contracts with the Policy Control Function (PCF) to create a robust and flexible framework for managing network policies and ensuring secure communications. The core innovation lies in leveraging blockchain technology to automate and enforce policies within dedicated network slices, thereby enhancing security and operational efficiency.

Our first contribution is the design of a smart contract-based PCF system that utilizes blockchain’s transparency and immutability to enforce network policies. By encoding policy rules and enforcement mechanisms into smart contracts, the protocol ensures that policies are applied consistently and transparently across network slices. This approach not only streamlines policy management but also reduces the potential for human error and operational inefficiencies.

The second contribution of this protocol is the integration of end-to-end encryption and automated policy enforcement. Smart contracts manage the dynamic allocation of resources and the application of security measures based on predefined policies, allowing for real-time adjustments and compliance with regulatory requirements. This results in a highly secure and adaptable network environment that can respond swiftly to changes in network conditions and policy requirements.

**Keywords:** Smart Contracts, Policy Control Function, blockchain, network slicing, automated policy enforcement, 5G network management.

---

The Policy Control Function (PCF) is a critical component of the 5G Service-Based Architecture (SBA), extending the capabilities of the 4G Policy and Charging Rules Function (PCRF). While the PCRF provides policy enforcement and flow-based charging in 4G networks, the PCF enhances these functions with advanced features for network slicing, roaming, and real-time policy management. This protocol aims to leverage smart contracts to automate policy enforcement, streamline network management, and provide robust security through blockchain integration.

### Protocol Design:

1. **Smart Contract Integration:** The Smart Contract PCF protocol integrates smart contracts into the PCF architecture to automate the definition, enforcement, and management of network policies. Smart contracts encode policy rules and control mechanisms, ensuring consistent and transparent policy enforcement across network slices.
2. **Policy Automation:** By utilizing blockchain’s transparency and immutability, the protocol automates policy enforcement processes, reducing the potential for human error and operational inefficiencies. Smart contracts manage policies for various 5G use cases, including enhanced mobile broadband (EMBB), ultra-reliable low-latency communication (URLLC), and massive IoT.
3. **Real-Time Analytics:** The Smart Contract PCF protocol supports advanced business intelligence (BI) insights with real-time analytics. This capability enables service providers to dynamically adjust policies, create new offerings, and respond to changing network conditions and user demands.
4. **Unified Policy Framework:** The protocol supports a unified policy framework for managing network behavior. It utilizes policy subscription information from the User Data Repository (UDR) to provide policy rules to network functions, such as the Session Management Function (SMF) and Access and Mobility Management Function (AMF).
5. **Interworking with Legacy Systems:** To address the challenge of transitioning from 4G to 5G, the Smart Contract PCF protocol includes provisions for interworking with legacy PCRF functions. This ensures a smooth migration and compatibility between 4G and 5G network domains.

# 5G Use Cases

1. **Secure Financial Transactions with UPI Integration**(This Proposal)
- Description: Deployment of UPI integrated with 5G network functions such as AUSF and PCF to ensure secure, low-latency financial transactions. This includes the use of blockchain for secure, immutable transaction records.
- Impact: Facilitates instant and secure financial transactions, critical for rural economic growth and financial inclusion.
2. **Digital Identity Verification using Zero-Knowledge Proofs**
- Description: Use of zero-knowledge proofs (ZKPs) for secure and private digital identity verification within the AUSF for financial services. This ensures user privacy while maintaining robust security.
- Impact: Enhances trust in digital financial services by protecting user data during authentication, crucial for adoption in rural areas.
3. **Smart Contracts for Automated Policy Enforcement**(This Proposal)
- Description: Implementation of smart contracts within the PCF to enforce financial and data security policies automatically. These contracts can dynamically adjust to network conditions, ensuring continuous compliance and security.
- Impact: Automates policy enforcement, reducing the risk of human error and ensuring consistent application of security protocols.
4. **Network Slicing for Secure Financial Operations**(This Proposal)
- Description: Utilization of 5G network slicing to create dedicated, secure slices for financial transactions. This isolates sensitive operations from other network traffic, reducing the risk of cyber-attacks.
- Impact: Guarantees secure and reliable financial services by protecting critical data and operations from network vulnerabilities.
5. **Remote Banking and Financial Services**
- Description: Deployment of remote banking solutions enabled by 5G's ultra-reliable low-latency communication (URLLC). These services include virtual banking, video-based customer service, and secure mobile banking apps.
- Impact: Provides rural populations with access to banking services without the need for physical bank branches, improving financial inclusion.
6. **IoT-Enabled Financial Inclusion**
- Description: Integration of IoT devices with 5G to enable financial services like micro-loans and insurance through automated data collection (e.g., crop health, weather conditions). Data is securely transmitted over 5G for processing and decision-making.
- Impact: Facilitates access to financial products tailored to the needs of rural communities, improving economic resilience and financial inclusion.
7. **Blockchain for Supply Chain Financing**
- Description: Use of blockchain to track and verify transactions in supply chain financing, ensuring transparency and trust between small-scale farmers and financial institutions.
- Impact: Enables rural businesses to access financing by providing secure, verifiable transaction histories, thereby boosting economic activity.
8. **Real-Time Data Analytics for Financial Risk Management**
- Description: Deployment of 5G-enabled real-time data analytics platforms for monitoring financial transactions and detecting fraud or other risks. These platforms can be integrated with UPI to provide instant risk assessments.
- Impact: Enhances the security and reliability of financial services by enabling proactive risk management and fraud detection.
9. **Rural E-Governance Services**
- Description: Leveraging 5G to deliver secure e-governance services related to finance, such as subsidy distribution, tax payments, and social security benefits directly to rural citizens.
- Impact: Simplifies access to government services for rural populations, ensuring transparency and reducing corruption in financial distributions.
10. **Mobile Wallets and Microfinance Solutions**
- Description: Deployment of 5G-enabled mobile wallets and microfinance platforms that can operate in low-bandwidth rural environments, providing access to small-scale financial services.
- Impact: Increases financial access for unbanked or underbanked rural populations, enabling economic growth and development.
---
This is a step toward upgrading the telco infra with modern cryptography for data integrity, please reach out for potential discussion and collaboration.

Thankyou!
