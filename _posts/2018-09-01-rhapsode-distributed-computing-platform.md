---
layout: post
title: "Rhapsode: Distributed Event-driven Computing Platform"
date: 2018-09-01 23:26:06
---

# Statement

Decentralized Computing Platform for Event-driven Execution of Network Stored Code.

# Overview

Rhapsode will be a [Function-as-a-Service (FaaS)](https://en.wikipedia.org/wiki/Function_as_a_service) [blockchain](https://en.wikipedia.org/wiki/Blockchain)-integrated distributed cloud computing platform that leverages existing cloud-based server infrastructure to create a decentralized marketplace for computational resources.

The platform will utilize a set of interconnected [Merkle trees](https://en.wikipedia.org/wiki/Merkle_tree) to provide consistent and tamper-proof technology for ensuring authentic pre-synchronized data regarding financial transactions and code management. The need for real-time processing of a specified segment of code with minimal CPU and I/O overhead is crucial to the next step of decentralized applications. The general reliability and performance of existing '[serverless](https://en.wikipedia.org/wiki/Serverless_computing)' cloud-computing services are brought to a peer-to-peer network of working nodes that are incentivized to execute the code specified, as programmed. The nodes keep all copies of user deployed code, and accept all incoming transactions and requests in exchange for the network's monetary units or coins; a cryptocurrency.

Unlike traditional web services, Rhapsode does not have an account-based user experience that requires identity verification, have the need for sensitive financial information, nor have the potential for downtime, censorship, fraud or third-party interference. Developers deploy functions that are either stored in container instances or code blocks with the network suggested amount of coin, and a static `serviceHash` is returned that can be used to call the deployed code. The service hash allows coins to be sent to it, which is how nodes are paid to run the correct code or container instance. A pool of coins can be stored in a server hash, which means users of the deployed service do not need to pay a fee unless they want to, unlike current decentralized networks that charge a fee for each smart contract request such as Ethereum. The public key that deployed the service hash is noted as the deployer or owner of that service, and is thus in full control of it.

Deployed services have the ability to be updated while keeping the same static `serviceHash`. The service hash actually points to a [self-describing content-addressed identifier](https://github.com/ipld/cid) of the container instance or code block specified by the deployer or owner of that service hash. This allows a version control system to be managed under the service hash, with the latest version being executed by all up-to-date nodes. Users can then send formatted input to the service hash, and the input will be processed by the code deployed and return an output. The output could be sent to the user, to the developer, or to another service. For example, a user could request a certain stored file to be downloaded from a decentralized application, and the service would return the requested files to the user from where ever it was located.

## Use Cases

Any function or subroutine that needs to be executed in a centralized or decentralized application either immutably, anonymously, with version control, without censorship and/or with fault-tolerance.

For example:

- Agile workloads
- Form submissions
- Cryptocurrency payment gateways
- Image-rich applications
- Virtual assistance and chatbots
- Scheduled tasks
- Online games

The ideas are endless, it is up to the developers' imaginations. 

**More Updates Coming...**
