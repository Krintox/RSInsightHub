# Tokenized Real Estate Investment Platform

## Introduction

This document outlines the software requirements for the development of the Tokenized Real Estate Investment Platform.

### Purpose

The purpose of this platform is to revolutionize real estate investment by leveraging blockchain, machine learning (ML), and natural language processing (NLP) technologies.

### Document Conventions

**Abbreviations:**
- ETH: Ethereum
- NLP: Natural Language Processing
- ML: Machine Learning
- NLTK: Natural Language Toolkit

### Intended Audience and Reading Suggestions

This document is intended for the development team, project stakeholders, and future maintainers of the system.

### Project Scope

The Tokenized Real Estate Investment Platform aims to tokenize real estate assets, providing a seamless and innovative investment experience.

### References

- [Ethereum Documentation](https://ethereum.org/en/developers/docs/)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Express.js Documentation](https://expressjs.com/)
- [React.js Documentation](https://reactjs.org/docs/getting-started.html)
- [MongoDB Documentation](https://docs.mongodb.com/)
- [TensorFlow Documentation](https://www.tensorflow.org/guide)
- [NLTK Documentation](https://www.nltk.org/)

## Overall Description

### Product Perspective

The Tokenized Real Estate Investment Platform is a standalone system interacting with blockchain networks and external data sources.

### Product Features

#### Tokenization

- **Description:** Real estate assets are represented as digital tokens on the Ethereum blockchain.
- **Inputs:** Property details, ownership information.
- **Outputs:** Tokenized assets on the Ethereum blockchain.
- **Tech Stack:**
  - Smart Contracts: Solidity
  - Blockchain Platform: Ethereum

#### Blockchain-based Transactions

- **Description:** Execution of secure and transparent transactions through smart contracts on the Ethereum blockchain.
- **Inputs:** Transaction details, user authentication.
- **Outputs:** Immutable transaction records on the Ethereum blockchain.
- **Tech Stack:**
  - Smart Contracts: Solidity
  - Blockchain Platform: Ethereum

#### Market Trend Prediction (ML)

- **Description:** Prediction of real estate market trends using machine learning algorithms.
- **Inputs:** Historical data, economic indicators.
- **Outputs:** Trend forecasts, risk assessments.
- **Tech Stack:**
  - ML Framework: Pytorch/ScikitLearn
  - Programming Language: Python

#### Chatbot for Investor Assistance

- **Description:** NLP-driven chatbot for assisting investors with platform navigation and inquiries.
- **Inputs:** User queries, platform updates.
- **Outputs:** Real-time assistance, updates.
- **Tech Stack:**
  - Chatbot Framework: Dialogflow
  - NLP Library: NLTK
  - Programming Language: Python

#### Predictive Maintenance for Property Management

- **Description:** ML-based prediction of maintenance needs and costs for properties.
- **Inputs:** Property details, maintenance history.
- **Outputs:** Predictive maintenance schedules, cost estimates.
- **Tech Stack:**
  - ML Framework: TensorFlow
  - Programming Language: Python

#### Tenant Sentiment Analysis

- **Description:** NLP analysis of tenant reviews and feedback.
- **Inputs:** Tenant reviews, feedback data.
- **Outputs:** Tenant satisfaction insights, performance assessments.
- **Tech Stack:**
  - NLP Library: Transformers
  - Programming Language: Python

#### Natural Language Contract Processing

- **Description:** NLP for processing and understanding terms and conditions in real estate contracts.
- **Inputs:** Legal documents, contract terms.
- **Outputs:** Extracted contract details, comprehension analysis.
- **Tech Stack:**
  - NLP Library: NLTK

### User Classes and Characteristics

Users are divided into two classes: Customers (individuals interested in investing) and Employees (platform administrators).

### Operating Environment

The operating environment includes a distributed database, client/server system, Windows OS, MongoDB, and Ethereum blockchain.

### Design and Implementation Constraints

Design and implementation constraints include global schema, fragmentation schema, and allocation schema for the distributed database.

### Assumptions and Dependencies

Assumptions include the system being used within college premises and implementation based on guidance from college professors.

## System Features

### Functional Requirements

Functional requirements include tokenization, blockchain-based transactions, ML predictions, and NLP sentiment analysis.

### External Interface Requirements

#### User Interfaces

User interfaces include React.js for the frontend and Node.js/Express.js for the backend.

#### Hardware Interfaces

Hardware interfaces include the Windows operating system and a browser supporting CGI, HTML, and JavaScript.

#### Software Interfaces

Software interfaces include Windows OS, MongoDB, Ethereum blockchain, and external APIs for data integration.

### Software Used

| Software Used           | Description                                               |
|-------------------------|-----------------------------------------------------------|
| Ethereum Blockchain     | Decentralized blockchain platform for tokenized assets.   |
| MongoDB                 | NoSQL database for storing non-blockchain data.            |
| React.js                | Frontend JavaScript library for building user interfaces. |
| Node.js                 | JavaScript runtime for server-side development.           |
| Express.js              | Web application framework for Node.js.                    |
| Axios                   | Promise-based HTTP client for making API requests.        |
| Scikit-Learn            | Machine learning library for ML model development.        |
| Natural Language Toolkit (NLTK) | Library for NLP and text processing.                |
| TensorFlow              | Open-source machine learning framework.                   |
| spaCy                   | NLP library for advanced text processing.                 |


## Contributors

 - SHASHANK SUGGALA 21BDS0268
 - DEVANG JOSHI 21BDS0275
 - HARSH KUMAR 21BCE2161
