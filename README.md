# Pandar – Crypto-Powered Digital Wallet & Payments Platform (Architecture Case Study)

## Overview

**Pandar** is a fintech platform that enables users to store, manage, and convert digital assets such as cryptocurrency and gift cards into Nigerian Naira. The platform also supports bill payments, wallet transfers, and other everyday financial operations, making digital assets practical and usable for a wide range of users.

This repository is a **public architecture and system design case study**. The production codebase is private.

---

## Problem Statement

For many users in Nigeria and similar markets, managing digital assets comes with several challenges:

* Converting cryptocurrency or gift cards into local currency is often slow or unreliable
* Existing platforms can be complex and intimidating for non-technical users
* Settlement delays and hidden fees reduce trust in digital payment systems
* Users lack a single platform to manage conversions, payments, and transfers

Pandar was built to solve these problems by offering a **simple, fast, and reliable digital wallet experience** that bridges crypto assets with everyday financial needs.

---

## Solution

Pandar provides:

* **Digital wallets** for holding and managing user balances
* **Instant asset conversion** from cryptocurrency and gift cards to Naira
* **Bill payment and wallet transfer** functionality
* A streamlined user experience focused on clarity, speed, and trust

The platform emphasizes transaction reliability, performance, and security while abstracting away the complexity of underlying crypto infrastructure.

---

## My Role

I worked as a **Senior Full Stack / Backend Engineer** contributing to the design, implementation, and maintenance of Pandar’s backend systems.

My responsibilities included:

* Developing and maintaining **Node.js backend services** that power wallet operations and transaction flows
* Contributing to API design for asset conversion, payments, and transfers
* Working with databases that store sensitive financial and transactional data
* Collaborating with cross-functional teams to ship features and improvements
* Ensuring system reliability, performance, and correctness in a production fintech environment

This role required a strong focus on correctness, scalability, and collaboration due to the financial nature of the product.

---

## System Architecture

### High-Level Architecture

* **Frontend:** Web and/or mobile clients consuming backend APIs
* **Backend:** Node.js services exposing RESTful APIs for wallet, conversion, and payment flows
* **Database:** Relational database storing users, balances, transactions, and asset records
* **Integrations:** Third-party services for crypto processing, banking payouts, and bill payments
* **Infrastructure:** Cloud-hosted services with CI/CD pipelines for deployment and monitoring

The system is designed to be modular and scalable, allowing independent evolution of wallet, conversion, and payment components.

---

## Key Engineering Contributions

* Implemented and maintained backend services handling **high-volume financial transactions**
* Contributed to asset conversion workflows ensuring accurate balances and transaction integrity
* Supported integrations with external payment and banking providers
* Improved system reliability through bug fixes, performance optimizations, and careful data handling
* Collaborated on production releases and post-deployment monitoring

---

## Challenges & Trade-offs

* Ensuring transactional consistency in financial operations
* Balancing fast processing times with strict correctness requirements
* Coordinating changes across multiple integrations and services
* Maintaining system stability while shipping new features

---

## Impact

* Supported a platform that enables users to **convert and use digital assets in everyday financial activities**
* Helped maintain reliable transaction processing in a live fintech product
* Contributed to improved user trust through stable and predictable system behavior
* Supported scalability as user adoption and transaction volume grew

---

## Tech Stack

* Node.js
* REST APIs
* PostgreSQL / MySQL
* Redis (where applicable)
* Git & CI/CD

---

## Notes

This repository intentionally excludes production source code. Its purpose is to demonstrate **system design thinking, fintech backend experience, and real-world collaboration** in a production environment.

---

## Contact

**Princess Jewel Jel-Edema**
Senior Full Stack Engineer (React & Node.js)
Portfolio: [https://princess-jewel.vercel.app](https://princess-jewel.vercel.app)
LinkedIn: [https://linkedin.com/in/princess-jewel-jel-edema](https://linkedin.com/in/princess-jewel-jel-edema)
