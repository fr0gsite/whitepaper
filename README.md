# Fr0g.site Whitepaper

**A Decentralized Media Platform Built on EOS and IPFS**

---

**Fr0g.site Team**  
Contact: Fr0gsite@mailbox.org  
Version 2.1
October 2025

<!-- TODO: Add team member profiles, backgrounds, and LinkedIn profiles -->
<!-- TODO: Add advisory board members and their credentials -->

---

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Problem Statement](#problem-statement)
3. [Solution Overview](#solution-overview)
4. [Technical Architecture](#technical-architecture)
   - 4.1 [EOS Blockchain](#eos-blockchain)
   - 4.2 [Smart Contracts](#smart-contracts)
   - 4.3 [IPFS Network](#ipfs-network)
   - 4.4 [IPFS Gateway](#ipfs-gateway)
5. [Platform Implementation](#platform-implementation)

Fr0g.site implements comprehensive security measures to protect against attacks while maintaining an open, accessible platform.

### Attack Vector Prevention

#### Vote Manipulation Protection

**Pattern Detection**: System monitors voting patterns to identify suspicious activity
**Rate Limiting**: Cooldown periods prevent rapid-fire voting from single accounts
**Behavioral Analysis**: Users exhibiting bot-like voting patterns face automatic penalties
**Time-based Restrictions**: Minimum intervals required between votes to prevent spam

#### DDoS & Function Spam Mitigation

**Smart Contract Protection**: Built-in cooldowns prevent excessive function calls
**Resource Management**: EOS resource system naturally limits high-frequency attacks
**Load Distribution**: Multiple blockchain nodes distribute processing load
**Automatic Throttling**: System reduces service to suspected attack sources

#### Sybil Attack Resistance

**Account Creation Costs**: Post-airdrop accounts require token expenditure
**Resource Requirements**: New accounts need initial CPU/NET/RAM allocation
**Time-based Restrictions**: New accounts have limited functionality initially
**Social Verification**: Community can identify and report suspected fake accounts

### Network Security

#### Blockchain-Level Protection

**Delegated Proof of Stake**: DPoS consensus mechanism resists traditional blockchain attacks
**Block Producer Monitoring**: Community oversight of network validators
**Resource Allocation**: Economic incentives align validator interests with network health

#### Data Integrity

**Immutable Records**: Blockchain storage ensures content metadata cannot be altered
**Cryptographic Hashing**: IPFS content addressing prevents unauthorized modifications
**Distributed Storage**: Content replicated across multiple IPFS nodes prevents loss

### Ecosystem Applications

Beyond the core media platform, Fr0g.site's infrastructure supports additional applications and games.

#### Third-Party Development

**Open Smart Contract Platform**: Developers can deploy custom applications on the network
**Shared Infrastructure**: Applications benefit from existing user base and token economy
**Composability**: New applications can integrate with existing platform features

#### Example Applications

**Collaborative Art Projects**: Applications similar to Reddit's r/place where users collaborate on digital canvases
**Token Integration**: Pixel longevity or special features purchasable with platform tokens
**Community Games**: Various gaming applications that leverage the platform's social features

**Developer Benefits**:
- Established user base
- Integrated payment system
- Decentralized hosting
- Community governance framework

<!-- TODO: Add comprehensive risk assessment and mitigation strategies -->
<!-- TODO: Add security audit reports and penetration testing results -->
<!-- TODO: Add incident response procedures and disaster recovery plans -->
<!-- TODO: Add compliance with data protection regulations (GDPR, CCPA) -->

---

## Roadmap

*[Development roadmap to be defined based on community priorities and technical milestones]*

### Phase 1: Foundation (Months 1-6)
- Core smart contract deployment
- Basic user interface development
- Initial token distribution
- Alpha testing with limited users

### Phase 2: Community Growth (Months 6-12)
- Public beta launch
- Truster system implementation
- Content moderation tools
- Mobile application release

### Phase 3: Ecosystem Expansion (Year 2)
- Third-party developer tools
- Advanced governance features
- Cross-chain integration
- Enterprise partnerships

### Phase 4: Decentralization (Year 3+)
- Full community governance
- Autonomous operations
- Global scalability
- Ecosystem maturity

<!-- TODO: Add specific milestones with dates and success metrics -->
<!-- TODO: Add funding requirements for each development phase -->
<!-- TODO: Add risk assessment for each roadmap milestone -->
<!-- TODO: Add community growth targets and user adoption metrics -->

---

## Conclusion

Fr0g.site represents a fundamental reimagining of how digital media platforms can operate in the modern era. By leveraging blockchain technology, distributed storage, and community governance, the platform addresses the critical issues of censorship, unfair monetization, and centralized control that plague traditional social media.

The platform's technical architecture, combining EOS blockchain efficiency with IPFS distributed storage, creates a robust foundation for sustainable growth. The carefully designed tokenomics ensure fair value distribution among all participants while maintaining long-term economic viability.

Most importantly, Fr0g.site returns control to the users. Through democratic governance, transparent operations, and economic incentives aligned with community interests, the platform empowers users to shape their own digital environment.

As the digital landscape continues to evolve, Fr0g.site offers a compelling alternative to corporate-controlled platforms—one that prioritizes user sovereignty, free expression, and fair value distribution. The future of social media lies not in the hands of a few powerful corporations, but in the collective wisdom and participation of the global community.

---

## References

*[References to be added based on technical implementations and industry standards]*

1. EOS.IO Technical White Paper - https://github.com/EOSIO/Documentation
2. IPFS Protocol Documentation - https://docs.ipfs.io/
3. Delegated Proof of Stake Consensus - Academic research and implementations
4. Decentralized Autonomous Organizations - Governance best practices
5. Blockchain Social Media Platforms - Comparative analysis and lessons learned

<!-- TODO: Add comprehensive bibliography with academic papers and research -->
<!-- TODO: Add citations for specific claims and statistics throughout the document -->
<!-- TODO: Add links to technical documentation and code repositories -->
<!-- TODO: Add references to regulatory frameworks and legal precedents -->

---

**Disclaimer**: This whitepaper represents the current vision and technical approach for Fr0g.site. Implementation details, timelines, and features may evolve based on technical considerations, community feedback, and regulatory requirements. Token economics and platform mechanics will be finalized through community governance processes.

**Legal Notice**: This document is for informational purposes only and does not constitute investment advice, financial guidance, or a solicitation to purchase tokens. Potential participants should conduct their own research and consult with qualified professionals before making any decisions related to the platform or its tokens.Communication Flow](#communication-flow)
   - 5.2 [Smart Contract Functions](#smart-contract-functions)
   - 5.3 [User Interface](#user-interface)
6. [Tokenomics](#tokenomics)
   - 6.1 [Initial Distribution](#initial-distribution)
   - 6.2 [Inflation & Token Distribution](#inflation--token-distribution)
   - 6.3 [User Onboarding](#user-onboarding)
7. [Governance & Content Moderation](#governance--content-moderation)
   - 7.1 [Truster System](#truster-system)
   - 7.2 [Reporting Mechanism](#reporting-mechanism)
   - 7.3 [Community Rules](#community-rules)
8. [Economic Model](#economic-model)
   - 8.1 [Content Creation Incentives](#content-creation-incentives)
   - 8.2 [Token Demand Generation](#token-demand-generation)
9. [Security & Risk Mitigation](#security--risk-mitigation)
10. [Roadmap](#roadmap)
11. [Conclusion](#conclusion)
12. [References](#references)

<!-- TODO: Add section 4.5 - System Requirements & Performance Specifications -->
<!-- TODO: Add section 5.4 - Real-World Use Cases & Examples -->
<!-- TODO: Add section after Solution Overview - Competitive Landscape Analysis -->
<!-- TODO: Add section before Roadmap - Team & Partnerships -->
<!-- TODO: Add section before Conclusion - Legal & Regulatory Considerations -->
<!-- TODO: Add Financial Projections & Business Model -->
<!-- TODO: Add API Documentation & Technical Specifications -->

---

## Executive Summary

Fr0g.site represents a paradigm shift in digital media platforms, addressing critical issues of centralized control, censorship, and unfair content monetization that plague traditional platforms like YouTube, Facebook, and Reddit. Built on EOS blockchain technology and the InterPlanetary File System (IPFS), Fr0g.site creates a truly decentralized, community-governed media ecosystem.

**Key Features:**
- **Decentralized Architecture**: No single point of control or failure
- **Community Governance**: Token-based voting system for platform decisions
- **Creator Incentives**: Direct monetization through blockchain tokens
- **Transparent Operations**: Open-source code ensures accountability
- **Censorship Resistance**: Community-driven content moderation

The platform utilizes a native token system that incentivizes quality content creation, fair moderation, and active community participation. Unlike traditional platforms where algorithms and policies are controlled by corporate interests, Fr0g.site empowers its users to collectively shape the platform's direction and content standards.

---

## Problem Statement

Modern media platforms suffer from fundamental structural issues that limit free expression and fair value distribution:

### Centralized Control
Traditional platforms like YouTube, Facebook, and Reddit operate under centralized corporate control, making them vulnerable to:
- Political pressure and regulatory interference
- Corporate influence through investments and partnerships
- Arbitrary policy changes without community input
- Opaque algorithmic manipulation

### Content Censorship
A small group of decision-makers determines what content billions of users can access, leading to:
- Shadow banning of controversial or critical content
- Inconsistent policy enforcement
- Suppression of diverse viewpoints
- Lack of appeal mechanisms

### Unfair Monetization
Content creators face significant challenges in monetizing their work:
- Platform takes substantial revenue shares
- Demonetization without clear justification
- Limited monetization options
- No ownership of audience or content

### Algorithmic Opacity
Secret algorithms determine content reach and visibility:
- No transparency in content promotion
- Bias toward certain types of content
- Manipulation of public discourse
- No community input on algorithmic decisions

Fr0g.site addresses these fundamental issues through decentralized architecture, community governance, and transparent operations.

<!-- TODO: Add market size data and statistics for social media censorship -->
<!-- TODO: Add specific examples of recent censorship incidents -->
<!-- TODO: Add quantitative data on creator revenue loss due to platform policies -->

---

## Solution Overview

Fr0g.site creates a decentralized media platform that returns control to the community through innovative use of blockchain technology and distributed systems.

### Core Principles

**Decentralization**: Built on EOS blockchain and IPFS, eliminating single points of failure and control.

**Transparency**: Open-source codebase ensures all platform operations are auditable and verifiable.

**Community Governance**: Token holders participate in platform decisions through democratic voting mechanisms.

**Fair Value Distribution**: Content creators, moderators, and active users are rewarded with platform tokens that have real economic value.

**Censorship Resistance**: Content moderation is performed by elected community members following transparent rules.

### Technical Innovation

The platform combines several cutting-edge technologies:
- **EOS Blockchain**: Provides fast, fee-less transactions and smart contract execution
- **IPFS Network**: Ensures permanent, distributed storage of media content
- **Smart Contracts**: Automate platform operations and token distribution
- **Cross-Platform Interface**: Flutter-based application works across web, mobile, and desktop

### Economic Model

A sophisticated tokenomics system aligns incentives across all platform participants:
- Content creators earn tokens for popular posts
- Moderators (Trusters) earn tokens for fair content review
- Active users receive token distributions
- Platform governance is determined by token holdings

This creates a self-sustaining ecosystem where quality content and fair moderation are economically incentivized.

<!-- TODO: Add competitive landscape analysis comparing Fr0g.site to existing platforms -->
<!-- TODO: Add market opportunity size and target user segments -->
<!-- TODO: Add strategic partnerships and ecosystem integrations -->

---
## Technical Architecture

Fr0g.site's technical foundation combines several proven decentralized technologies to create a robust, scalable media platform. Understanding these core technologies is essential to appreciating the platform's capabilities and advantages.

### 4.1 EOS Blockchain

The EOS blockchain serves as the backbone of Fr0g.site, providing fast, scalable infrastructure for decentralized applications (DApps). EOS was chosen for its superior performance characteristics and developer-friendly features.

#### Delegated Proof of Stake (DPoS)
EOS utilizes a Delegated Proof of Stake consensus mechanism that enables:
- **High Transaction Throughput**: Capable of processing thousands of transactions per second
- **Low Latency**: Near-instantaneous transaction confirmation
- **Energy Efficiency**: Significantly lower energy consumption than Proof of Work systems

#### Block Producer System
The network is secured and operated by 21 Block Producers:
- **20 Elected Producers**: Chosen through continuous community voting
- **1 Standby Producer**: Randomly selected to prevent centralization
- **Democratic Selection**: Token holders vote for their preferred Block Producers
- **Accountability**: Poor performance results in removal through voting

#### Resource Management
EOS implements a sophisticated resource allocation system:

**CPU Resources**: Computational power for executing smart contracts
- Allocated through token staking
- Automatically replenished after 3 days
- Prevents spam while maintaining accessibility

**NET Resources**: Network bandwidth for data transmission
- Similar staking mechanism to CPU
- Ensures network stability under high load

**RAM**: Persistent storage within the blockchain
- Purchased rather than staked
- Limited resource that maintains its value
- Stores all metadata permanently

#### Key Advantages for Fr0g.site

**Fee-less Transactions**: Unlike Bitcoin or Ethereum, EOS transactions don't require gas fees, making microtransactions economically viable.

**Upgrade Flexibility**: The EOSIO Upgrade Proposal (EUP) system allows network improvements without hard forks.

**Scalability**: High transaction throughput supports a large user base without performance degradation.

**Interoperability**: Native support for cross-chain communication and token exchanges.

<!-- TODO: Add performance benchmarks and scalability testing results -->
<!-- TODO: Add comparison with other blockchain platforms (Ethereum, Solana, etc.) -->

### 4.2 Smart Contracts

Smart contracts are self-executing programs that run on the EOS blockchain, automating platform operations and ensuring transparent, tamper-proof execution of business logic.

#### Core Functions
Smart contracts on Fr0g.site handle critical platform operations:

**User Management**: Account creation, activation, and permission systems
**Content Operations**: Upload creation, tagging, commenting, and voting
**Token Economics**: Automated token distribution and reward calculations
**Governance**: Voting mechanisms and proposal systems
**Moderation**: Automated content review workflows

#### Development Advantages

**Multiple Contract Architecture**: Complex applications can be built using interconnected smart contracts, allowing for modular development and easier maintenance.

**EOSIO.token Standard**: Simplified token creation and management using proven, audited standards.

**Transparency**: All contract code and transactions are publicly verifiable, ensuring trust and accountability.

#### Security Features

**Access Control**: Robust permission systems prevent unauthorized actions
**Resource Limits**: Built-in protection against spam and abuse
**Formal Verification**: Smart contracts can be mathematically proven to behave correctly

<!-- TODO: Add smart contract audit results and security testing reports -->
<!-- TODO: Add technical specifications for smart contract interfaces -->
<!-- TODO: Add gas cost estimates and optimization strategies -->

### 4.3 IPFS Network

The InterPlanetary File System (IPFS) provides decentralized storage for all media content on Fr0g.site, ensuring permanent availability and censorship resistance.

#### How IPFS Works

**Content Addressing**: Files are identified by cryptographic hashes of their content rather than location-based URLs
- Hash uniquely identifies content
- Identical files always have the same hash
- Any modification creates a new hash

**Distributed Storage**: Content is distributed across multiple network nodes
- Files split into encrypted blocks
- Blocks stored on various peer computers
- Redundancy ensures availability even if some nodes go offline

**Peer-to-Peer Architecture**: Direct file sharing between network participants
- No central servers required
- Faster downloads from nearby peers
- Natural load distribution

#### Advantages Over Traditional Storage

**Censorship Resistance**: No single point of control means content cannot be easily removed
**Permanent Availability**: Content remains accessible as long as any peer stores it
**Bandwidth Efficiency**: Popular content is cached closer to users, reducing load times
**Cost Effectiveness**: Eliminates expensive centralized storage infrastructure

**Global Accessibility**: Content accessible from anywhere in the world

### 4.4 IPFS Gateway

IPFS Gateways serve as bridges between the decentralized IPFS network and the traditional web, making content accessible through standard HTTP protocols.

#### Gateway Functions

**Protocol Translation**: Converts IPFS addresses to HTTP URLs
**Content Retrieval**: Fetches files from the IPFS network on behalf of clients
**Caching**: Stores frequently accessed content for faster delivery
**Load Balancing**: Distributes requests across multiple IPFS nodes

#### Decentralization Benefits

Multiple gateway operators can serve the same content, preventing single points of failure and ensuring users always have access to their media, even if some gateways become unavailable.

<!-- TODO: Add IPFS pinning strategies and content redundancy specifications -->
<!-- TODO: Add content delivery network (CDN) integration plans -->
<!-- TODO: Add data retention policies and storage economics -->

---
## Platform Implementation

### 5.1 Communication Flow

Fr0g.site's architecture consists of several interconnected components that work together to provide a seamless user experience:

#### System Architecture

**IPFS Network**: Distributed storage for all media files (images, videos, documents)
**EOS Blockchain Fork**: Stores metadata and executes smart contracts
**IPFS Gateway**: Bridges the IPFS network with traditional web protocols
**Client Application**: Cross-platform user interface built with Flutter

#### Data Flow Process

1. **Node Discovery**: Client connects to web server hosting the platform viewer
2. **Blockchain Connection**: Server provides list of available blockchain node IP addresses
3. **Metadata Retrieval**: Client sends HTTP requests to blockchain nodes for content metadata (IPFS hashes, comments, tags, author information)
4. **Content Fetching**: Client connects to IPFS gateway to retrieve actual media files
5. **Media Delivery**: IPFS gateway fetches content from the IPFS network and delivers to client

#### Version History

Is on [GitHub](https://github.com/fr0gsite)

### 5.2 Smart Contract Functions

The platform operates through the cbased smart contract deployed on the EOS blockchain fork. This contract has unlimited resources (CPU, NET, RAM) to ensure reliable platform operation.

#### Core Contract Functions

| Function | Database Table | Description |
|----------|----------------|-------------|
| `createupload` | uploads | Create new posts/uploads |
| `addtag` | tags, globaltags, withthistag | Add tags to content |
| `addcomment` | comments | Add comments to posts |
| `activate` | active | Activate user account for platform |
| `deactivate` | active | Deactivate user account |
| `report` | report | Report content for moderation |
| `closereport` | report, active | Process moderation decisions |
| `voteupload` | voteuploads | Vote on uploads |
| `votetag` | votetags | Vote on tags |
| `votecomment` | votecomments | Vote on comments |
| `cooldown` | cooldown | Manage action cooldowns |
| `deleteupload` | uploads | Remove uploads and associated data |

#### Security Features

**Access Management**: Each function verifies user permissions before execution
**Spam Protection**: Cooldown mechanisms prevent automated attacks
**Rate Limiting**: Prevents system abuse through excessive requests

<!-- TODO: Add API rate limiting specifications and developer guidelines -->
<!-- TODO: Add smart contract upgrade and governance mechanisms -->
<!-- TODO: Add database schema and data flow diagrams -->

### 5.3 User Interface

The Fr0g.site application is built using Flutter, enabling deployment across multiple platforms from a single codebase.

#### Platform Support
- **Web**: Browser-based access
- **Mobile**: Native Android and iOS applications
- **Desktop**: Windows, macOS, and Linux applications

Prioritizes is Web and Mobile platforms for initial releases.

#### Open Source Development
- Source code will be made open source during development
- Community contributions encouraged
- Fork-friendly architecture allows custom implementations

#### Viewer Operation Model
Multiple independent viewer operators can run their own instances:
- **Revenue Models**: Advertising, donations, premium features
- **Block Producer Benefits**: Operating a viewer instance builds community goodwill, increasing vote likelihood
- **Decentralization**: No single point of control for user interface

#### Recommendation Algorithm
The platform uses a balanced content discovery algorithm that combines:
- **Popular Content**: Trending posts based on community engagement
- **Fresh Content**: Recently published posts to ensure new creators get visibility
- **Personalization**: User preference learning for customized feeds

<!-- TODO: Add UI/UX design mockups and user journey flows -->
<!-- TODO: Add accessibility features and internationalization support -->
<!-- TODO: Add performance optimization strategies for mobile devices -->
<!-- TODO: Add integration with browser extensions and third-party tools -->

--- 
## Tokenomics

Fr0g.site's economic model is designed to create sustainable incentives for all platform participants while maintaining long-term value for token holders.

### 6.1 Initial Distribution

The platform launches with **200,000,000 system tokens**, representing 2% of the maximum supply of **10,000,000,000 tokens**. This conservative initial issuance ensures sustainable growth and prevents immediate inflation.

#### Token Allocation

| Purpose | Percentage | Tokens | Description |
|---------|------------|--------|-------------|
| User Base Reserve | 60% | 120,000,000 | Reserved for future user rewards and community growth |
| Foundation | 10% | 20,000,000 | Platform development and operations |
| Game Development Pool | 5% | 10,000,000 | Funding for platform games and applications |
| Marketing & Free Accounts | 5% | 10,000,000 | User acquisition and free account subsidies |
| Investors | 10% | 20,000,000 | Private investment funding |
| Team & Founders | 10% | 20,000,000 | Development team allocation |

### 6.2 Inflation & Token Distribution

The platform operates with a **5% annual inflation rate**, with new tokens distributed among key stakeholder groups to maintain platform operations and incentivize participation.

#### Distribution Categories

| Recipient | Description | Distribution Method |
|-----------|-------------|-------------------|
| **Block Producers** | Network validators processing transactions | Immediate distribution |
| **Content Creators** | Users creating popular uploads, comments, and tags | Pool-based rewards |
| **Trusters** | Community moderators reviewing reported content | Pool-based rewards |
| **Development Team** | Ongoing platform development and maintenance | Immediate distribution |
| **Active Users** | Regular platform participants | Pool-based rewards |

**Distribution Mechanism**: Block Producer and Development Team tokens are distributed immediately upon creation. All other tokens enter reward pools from which eligible users can claim their allocations.

### 6.3 User Onboarding

#### Free Account Airdrop

The first **20,000 users** receive free account creation through an automated airdrop system:

**Starting Resources**: Each new user receives initial allocations of CPU, NET, and RAM resources to begin using the platform immediately.

#### Post-Airdrop Account Creation

After the airdrop concludes, new accounts can be created through:

**Existing User Sponsorship**: Current users can create new accounts for others
- Account creator pays EOS network storage fees
- Variable cost based on current network RAM prices
- Creator provides private key to new user

**Account Activation**: New EOS accounts must be activated for Fr0g.site through the platform's smart contract
- Activation fee scales with monthly created accounts
- 30-day waiting period before new users can apply for Truster roles

<!-- TODO: Add detailed token vesting schedules for team and investors -->
<!-- TODO: Add token burn mechanisms and deflationary measures -->
<!-- TODO: Add staking rewards and liquidity provider incentives -->
<!-- TODO: Add cross-chain bridge specifications and multi-chain support -->

---

## Governance & Content Moderation

Fr0g.site implements a sophisticated community governance system that balances free expression with quality content standards through decentralized moderation.

### 7.1 Truster System

Trusters are elected community members responsible for reviewing reported content and maintaining platform quality standards. This system ensures democratic content moderation without centralized control.

#### Truster Selection

**Limited Positions**: Maximum of 200 Trusters at any time to maintain quality and accountability
**Democratic Selection**: Random selection from applicant pool when positions are available
**Application Process**: 
- Requires security deposit
- 30-day waiting period for new accounts

#### Karma System

Trusters maintain a reputation score that determines their standing and continued eligibility:

**Starting Karma**: 500 points for all new Trusters
**Maximum Karma**: 600 points
**Minimum Threshold**: Below 1 point results in permanent disqualification

**Karma Adjustments**:
- **Correct Decisions**: +karma (aligned with majority vote)
- **Incorrect Decisions**: -karma (opposed to majority vote)
- **Missed Deadlines**: -100 karma for failing to vote within 22 hours
- **Timely Participation**: +50 karma for votes within deadline

#### Compensation Structure

Trusters receive TRUST tokens for their moderation work, convertible to system tokens:

| Time to Vote (Hours) | Reward (TRUST Tokens) |
|---------------------|----------------------|
| < 12 | 100% of allocated reward |
| 12-16 | 75% of allocated reward |
| 16-19 | 50% of allocated reward |
| 19-22 | 25% of allocated reward |
| 22-23 | 0% for selected Trusters, 50% for any Truster |
| 23-24 | 0% for selected Trusters, 75% for any Truster |

### 7.2 Reporting Mechanism

The platform's content moderation relies on community reporting and democratic review rather than automated censorship.

#### Reporting Process

1. **Content Flagging**: Any user can report content they believe violates platform rules
2. **Truster Assignment**: System selects 7 random Trusters (always odd number for decisive voting)
3. **Review Period**: Trusters have 22 hours to evaluate and vote on reported content
4. **Decision**: Majority vote determines outcome (keep/remove content)
5. **Enforcement**: Sanctions applied automatically based on Truster decision

#### Fallback Mechanisms

**Insufficient Trusters**: If 7 Trusters unavailable, smaller odd-numbered group selected
**No Available Trusters**: Content remains unless community volunteers step forward
**Delayed Decisions**: After 24 hours with incomplete votes, content is automatically removed

#### Appeals Process

**Transparent Voting**: All votes and reasoning should be visible to community (technical limitations may require compromise)
**Community Oversight**: Truster decisions subject to community review and karma adjustments

### 7.3 Community Rules

Platform rules are categorized by severity to ensure proportionate responses to violations.

#### Serious Violations
Result in immediate and permanent account suspension:
- [Specific rules to be defined in governance process]
- [Focus on illegal content, harassment, threats]

#### Moderate Violations  
Result in warnings and temporary restrictions:
- [Specific rules to be defined in governance process]
- [Multiple violations lead to escalating penalties]
- [Three moderate violations result in permanent suspension]

#### Governance Principles

**Free Expression**: Platform allows all words and expressions within legal boundaries
**Community Standards**: Rules developed through democratic governance process
**Transparency**: All moderation decisions and rules are publicly documented
**Proportional Response**: Penalties match the severity of violations

**Rule Development**: Community governance process will establish specific rule categories and enforcement guidelines through token-weighted voting.

<!-- TODO: Add specific community rules and guidelines -->
<!-- TODO: Add appeals process and dispute resolution mechanisms -->
<!-- TODO: Add governance voting procedures and quorum requirements -->
<!-- TODO: Add emergency response protocols for critical situations -->

---

## Economic Model

Fr0g.site's economic architecture creates sustainable value for all participants while maintaining platform quality through carefully designed incentive mechanisms.

### 8.1 Content Creation Incentives

#### Content Quotas & Quality Standards

**Free Content Allowance**: Each user receives a quota of free posts per period
**Automatic Cleanup**: Posts not reaching minimum engagement levels are automatically removed after 14 days
**Storage Optimization**: Ensures platform storage is reserved for popular or premium content

#### Voting & Reward System

**ACT Token Distribution**: Users receive 100 ACT tokens every 24 hours for content evaluation
**Non-Transferable**: ACT tokens cannot be traded between users, preventing vote manipulation
**Conversion Mechanism**: Content creators can convert earned ACT tokens to system tokens
**Rate Limiting**: Each user can award maximum 1 ACT token per post

**Creator Revenue Flow**:
1. Create quality content
2. Receive FAME tokens for good content
3. Convert FAME tokens to system tokens
4. Exchange system tokens for fiat currency on exchanges

#### Multi-Token Consideration
*Future development may implement separate token types for different engagement activities to optimize incentive alignment.*

### 8.2 Token Demand Generation

Creating sustainable token demand is crucial for maintaining economic value and platform sustainability.

#### Reach & Advertising

**Promoted Content**: Users can purchase increased visibility for their posts using system tokens
**Targeted Advertising**: Businesses can promote content to specific communities or interests
**Revenue Distribution**: Tokens spent on promotion flow back to the community pool for redistribution

**Benefits for Advertisers**:
- Direct access to engaged communities
- Granular targeting by tags and interests
- Transparent, democratic platform environment
- Lower costs than traditional advertising platforms

#### Storage & Features

**Extended Storage**: Users can purchase additional storage beyond free quotas using system tokens
**Premium Features**: Enhanced capabilities (unlimited favorites, advanced analytics) available for token holders
**Exclusive Access**: Certain platform features reserved for token stakeholders

#### Governance Influence

**Voting Power**: Token holdings determine influence in platform governance decisions
**Block Producer Elections**: Token holders elect network validators
**Policy Decisions**: Community votes on platform rules and development priorities

**Demand Drivers Summary**:
- Content promotion and advertising spend
- Premium feature access
- Extended storage needs  
- Governance participation rights
- Network validation rewards

<!-- TODO: Add detailed token economics modeling and simulations -->
<!-- TODO: Add creator monetization case studies and projections -->
<!-- TODO: Add advertising revenue sharing models -->
<!-- TODO: Add subscription and premium feature pricing strategies -->

---
