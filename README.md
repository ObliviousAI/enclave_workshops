<img align="right" height="28" src="https://oblv.io/badge" alt="OBLV: Made for Enclaves">

# The Enclave Workshop Series 📺

This repository is composed of a series of workshops on the theory and practice of using secure enclaves as a privacy enhancing technology (PET). If you have never come accross the concept of a secure enclave, not to worry as we will eneavour to start right from the beginning.

Enclaves, also known as trusted execution environments (TEEs) or confidential compute (CC), can be motivated by multiple drivers, including:
  
![](https://img.shields.io/badge/-Algorithmic%20Transparency-%23FFF3B5) <sup>Proving how data was processed</sup>

![](https://img.shields.io/badge/-Enhanced%20Security%20Transparency-%23FFC17A) <sup>Minimizing the attack surface of data throughout its life cycle</sup>

![](https://img.shields.io/badge/-Multiparty%20Computation-%231191AB) <sup>Brokering trusted computation between multiple parties who each input either data or algorithms</sup>

![](https://img.shields.io/badge/-Secure%20SaaS-%23515991) <sup>Gaurenteeing to SaaS consumers their queries and data will never be seen by or logged by the SaaS providers</sup>

In the workshops below, we will tage each workshop with the above tags so you can easily navigate towards topics most relivent to you. We will also use one more tag which will be used for generic fundamental topics in enclaves:

![](https://img.shields.io/badge/-Core%20Concept-%23C270A9) <sup>A fundamental or core concept to enclaves</sup>

## Workshops

### Workshop 1: Enclave Fundamentals 

![](https://img.shields.io/badge/-Core%20Concept-%23C270A9) ![](https://img.shields.io/badge/-Multiparty%20Computation-%231191AB)

<sup>_Workshop Length Estimate:_ 30 minutes.<sup>

In this workshop, we'll cover:

1. What are secure enclaves?
2. What types of enclaves are there? ( and a brief history of the domain)
3. How do we write software to deploy to an enclave?
  a. How to manage access control.
  b. How to allowlist outbound connections.
  c. How to make enclaves configureable.
4. How do we configure and deploy a secure enclave?
5. How can we securely connect to an enclave?

[Click here to start the workshop.](./workshops/1_Enclave_Fundamentals/README.md)


### Workshop 2: Synthetic Data from Multiple Private Data Sources

![](https://img.shields.io/badge/-Multiparty%20Computation-%231191AB)

<sup>_Workshop Length Estimate:_ 30 minutes.<sup>

In this workshop, we'll cover:

1. A brief recap of enclave fundamentals.
2. An introduction to (differentially private) synthetic data.
3. Why connect sensitive data sources in an enclave? 
4. A walk-through of building and interacting with a (differentially private) synthetic data enclave service.
5. Comparing the utility of enclave-generated joint synthetic data with synthetic data generated.

This workshop is coming soon. **Star / watch this repo to be notified when the next update will be live.**


### Workshop 3: Offering SaaS Services via Enclaves

![](https://img.shields.io/badge/-Secure%20SaaS-%23515991)

<sup>_Workshop Length Estimate:_ 30 minutes.<sup>

In this workshop, we'll cover:

1. A brief recap of enclave fundamentals.
2. Why deploy a SaaS via enclaves?
3. Example application: Inference-as-a-service
4. Example application: Privacy-ensured surveys

This workshop is coming soon. **Star / watch this repo to be notified when the next update will be live.**


