# Name of your Project

- **Team Name:** EcoRide
- **Payment Address:** 1RnRrawcyt4M2rkW4WuoNM5idUxNRoMAYU8zELp9zSyzoEN

## Project Overview :page_facing_up:

### Overview

**Tagline:**  
EcoRide Rustavi  e-scooter rental platform.

**Description:**  
EcoRide Rustavi is an electric scooter rental service built on smart contracts. The system tracks ride data (start time, end time, distance, pricing, and location) directly on-chain. Users rent scooters via a mobile app using fiat payments (e.g. bank card), while blockchain records every ride as a verified transaction. This guarantees transparency, data integrity, and auditability for users and regulators.

**ink! ecosystem relevance:**  
EcoRide uses ink! smart contracts deployed on a Substrate-based chain to:
- Record rental sessions
- Assign and update ride metadata
- Provide immutable logs for ride history

**Chosen category:**  
Canary Dapp — A functional and auditable consumer-facing dApp using ink! contracts in a real-world mobility business.

**Team interest:**  
We are building a real mobility product in Georgia and see blockchain as a unique solution for integrity, accountability, and scalability in transportation services.

---

### Ink! Ecosystem Impact

EcoRide Rustavi showcases in a real-world business case. Benefits:
- Demonstrates ink! smart contracts for real-time microtransactions and data logging.
- Inspires other smart city or mobility solutions to integrate ink!-based auditing mechanisms.
- Encourages trust among regulators, investors, and customers through immutable rental data.

We will open-source key modules such as:
- Ride recorder contract
- Pricing calculation module
- Audit-ready ride explorer dashboard

This will make it easy for other teams to fork and launch similar micro-mobility dApps using ink!.

**Business Model:**  
- Revenue from per-minute ride charges: ₾1 unlock + ₾0.40/min
- Target market: Rustavi and other mid-size cities in Georgia
- Scalability: Expand to new locations + offer platform-as-a-service for other operators

**Production Plans:**  
- Launch MVP with 100 scooters in Rustavi
- Integrate smart contract-backed ride logs with user app
- Partner with municipalities for smart city integrations

---

### Project Details

- Core Functionality: ink! smart contracts recording ride data
- API: JSON-RPC endpoints for mobile app to log sessions on-chain
- Tech Stack:
  - Mobile app: Flutter
  - Backend: Rust + Node.js bridge
  - Chain: Substrate node + ink! contracts
- Documentation: Public repo and user documentation
- Not implementing: crypto payment gateway, tokenomics, or public token sale

---

## Team :busts_in_silhouette:

### Team Members

- **Team Leader:** Rati Katamadze
- **Team Member:** Georgi Kipshidze

### Contact

- **Contact Name:** Rati Katamadze  
- **Contact Email:** ratikatamadze26@gmail.com  
- **Website:** *not available yet*

### Legal Structure

- **Registered Address:** Rustavi, Georgia  
- **Registered Legal Entity:** EcoRide

### Experience

- Rati: Founder of Middle Corridor Logistics; entrepreneur with experience in mobility and logistics
- I have hands-on experience managing the construction of residential apartment blocks, including planning and supervising smart building integrations. My background includes coordinating teams, overseeing budgets and timelines, and ensuring modern technologies—such as energy-efficient systems and smart infrastructure—are embedded into the construction process.

### Team Repos

- https://github.com/EcoRide1/Ecosystem-Grants

### GitHub Accounts

- https://github.com/EcoRide1  

---

## Development Status :open_book:

Currently developing:
- Ride recording prototype smart contract
- Flutter app prototype
- Early tests with ink! contract deployment to local node

---

## Development Roadmap :nut_and_bolt:

### Overview

- **Total Estimated Duration:** 2 months  
- **Full-Time Equivalent (FTE):** 2  
- **Total Costs:** 85,000 USD

---

### Milestone 1 — Smart Contract Ride Logging

- **Estimated duration:** 1 month  
- **FTE:** 1.5  
- **Costs:** 42,500 USD

| Number | Deliverable | Specification |
|--------|-------------|---------------|
| 0a. | License | MIT |
| 0b. | Documentation | Inline docs + dev tutorial |
| 0c. | Testing Guide | Full unit tests with ride simulation |
| 0d. | Docker | Dockerfile for test setup |
| 1. | ink! contract: `RideLog` | Contract to log start/end of rides with user ID, time, location, and price |
| 2. | ink! contract: `RideHistoryView` | View contract to query all past rides per user |
| 3. | Admin dashboard (MVP) | Web dashboard to view ride logs from blockchain |
| 4. | Flutter App Integration (simulated) | App connects to chain and logs simulated rides |

---

### Milestone 2 — Production Readiness

- **Estimated Duration:** 1 month  
- **FTE:** 1.5  
- **Costs:** 42,500 USD

| Number | Deliverable | Specification |
|--------|-------------|---------------|
| 0a. | License | MIT |
| 0b. | Documentation | Final user and developer docs |
| 0c. | Testing Guide | QA and regression testing for production release |
| 0d. | Docker | Full system Docker container |
| 0e. | Article | Blog post on how EcoRide uses ink! |
| 1. | ink! pricing module | Modular pricing logic for on-chain calculation |
| 2. | Flutter App (beta) | Testable app with blockchain interaction |
| 3. | Ride analytics backend | Optional off-chain analytics dashboard pulling from on-chain data |

---

## Future Plans

- Go live in Rustavi with 100 scooters  
- Use ink! contracts to log 1,000+ rides/month  
- Scale to other cities (Tbilisi, Kutaisi)  
- Release a white-label version of the platform for other operators

---

## Additional Information :heavy_plus_sign:

**How did you hear about the Bounty Program?**  
Via GitHub research and Element channels

**Additional notes:**   
We’re actively looking for strategic technical and financial partners for long-term scaling.
