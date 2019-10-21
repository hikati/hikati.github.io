## Hikati

## _Company overview_
We are a small software company.  When not working on our own projects, we help companies get their software projects started or back on track.

## _Core Technologies_

While we are open to working with all technologies, here is a list of some of the technologies we have the most experience with.

*  Microservices API architecture:  Java, Spring Boot, REST
*  Databases:  MongoDB, RDS, MySQL
*  Centralized logging:  ELK (ElasticSearch Kibana Logstash), trace logging
*  Firebase
*  AWS: ECS, EKS, EC2, ELB, Route 53, etc..
*  Front-end:  Java Server Faces (JSF), Vaadin
*  crypto:  masternode setup and management
*  SRE, continuous integration, Jenkins
*  security:  oauth2, API security, HMAC, local file integrity



**Below is a list of some of the projects we have recently worked on.**

## _Pacnode_

Pacnode is a fully managed Masternode Hosting Service for the PacGlobal Cryptocurrency Coin. Featuring a unique blend of both Shared and Full Masternode Hosting options allows a wide variety of customer demographics while delivering the same experience to each customer regardless of how much they invest. Removing the technical obstacles of running a masternode by providing a simple yet information rich Customer Dashboard simplifies the investor experience to focus on returns and reinvesting instead of worrying about configurations, server status and wallet upgrades.

#### Technology Stack

Pacnode is written from the ground up using the right tool for the right job. Separate modules allow for seamless upgrades and enhancements with the least amount of downtime.

*   Website Module: Core Java, JavaServer Faces with Primefaces, Apache, Apache Tomcat, Google Cloud Services
*   Payment Processing: Core Java, Amazon WebServices
*   Crypto Transaction Parsing: Core Java, AWS
*   Monitoring: Core Java, Ansible, Amazon WebServices
*   Database: MySQL

#### Project Highlights

Pacnode features custom code written specifically for Cryptocurrencies and Masternode Hosting with security being the top priority. There are a number of unique implementations that are present:

*   Anonymous and secure Customer Website that never exposes identifying details
*   Each customer is assigned a unique user id and a random secure password that is not user generated
*   One-Click Instant Customer Reward Withdrawal and Reinvesting from a secure Dashboard
*   Customer Proposal Voting that allows all customers an equal voice regardless of how much is invested
*   Blockchain Transactions are parsed on stand-alone hardware and updated remotely for optimum performance and security
*   Payment Processing is conducted on a secure isolated server that does not perform any other functions and does not talk to any 3rd party API’s for the highest level of security
*   Full Network Monitoring utilizing Ansible to check every server for proper functionality and alerts an engineer priority team in the event of a verifiable outage event, reducing false positives to below .1% and increasing response time to within 2 alert cycles
*   Complete and accurate data records that include every transaction and every user event for auditing and verification
*   Fully backed up and redundant databases which can use point in time recovery to eliminate the risk of catastrophic data loss

## _Turret Master_

Turret Master is a desktop video game that is a combination of two popular genres; shoot 'em up and tower defense.  The game is sold in the Steam app store.

#### Technology Stack

Turret Master has 3 main parts, the video game software itself, the packaging tool, and the backend webservices.

*   The game is coded in Core Java and JavaFX.
*   The game is packaged using Inno Setup.
*   The backend has a few components worth mentioning:
    *  Spring Boot microservices
    *  Netty for the PvP mode
    *  MySQL (via AWS RDS)
    *  AWS, EKS (Elastic Kubernetes Services) 

#### Project Highlights

*   The Campaign mode of the game allows a player to build up their weaponry using gold gained from killing enemy units in the game.
*   The game has a survival mode that has endless enemy waves of increasing difficulty.
*   Custom maps and games.  Players can create their own version of the game.  They can create a game and customize almost everything about it, from the cost of weapon upgrades, to the number of rounds, and a lot more.
    *  Custom games can be shared and forked by other players.  The custom games are versioned, so player can keep improving and releasing newer version.
*   All the rounds in the game have their own leaderboard where players can compete to get the to top.
*   The game uses advanced security measures that go way beyond what a video game would normally require.  We felt this was needed to protect the leaderboard's relevance and importance.
*   The PvP mode allows players to compete head to head.  The game uses ELO algorithm to calculate ranking.
*   The game has various achievement badges.  Some of the badges are global in scope and can be lost, for example being in top 10 of aleaderboard is a bacge that can be lost if other players move up higher on the leaderboard and knock you out of the top 10.

## _Radiologex_

Radiologex is a technology product which serves multiple facets of the healthcare industry.

#### Technology Stack

Radiologex uses cutting edge technology in order to deliver the first imaging platform built to work with a blockchain delivery system.

*   Google Firebase
*   Firestore
*   Firebase Cloud Functions
*   Firebase Cloud Messaging
*   Firebase Hosting
*   FireStorage
*   React for IoS and Android Mobile Application
*   Radiologex Blockchain

#### Project Highlights

Specializing in custom Firebase Cloud Functions to standardize and secure application data access across different clients, over 50 unique cloud functions have been developed and deployed successfully.

*   Account Registration and Management
*   Automatic compression of uploaded User images
*   Full featured Marketplace database and APIs to facilitate product buying and selling
*   Blockchain Transaction Parsing and data enrichment for full order visibility and accountability
*   Single and Group Push Messaging using Firebase Cloud Messaging
*   Request and Response Auditing using custom StackDriver logging
*   Complete User Profile management APIs
*   Business Registration and Management including member access and secure document uploads

## _Pacnode Cold Wallet Hosting_

Pacnode Cold Wallet Hosting is an automated Infrastructure as a Service Masternode Hosting solution. Guided by an Intuitive Website design, User’s can fund their accounts, create orders for specific Masternode Servers and activate their Masternodes without waiting on anyone else.

#### Technology Stack

Pacnode Cold Wallet Hosting uses Java and Vaadin to create a unique experience with full redundancy and maximum availability. Broken up into self-contained modules, updating and enhancing the framework results in no disruption in customer services.

*   Website: Java Spring with Vaadin on a Kubernetes Cluster backed by Redis and managed from Jenkins
*   Blockchain Information Services: Java Spring Microservices
*   Payment Processing: Core Java

#### Project Highlights

Pacnode Cold Wallet Hosting represents years of reducing the complexity of Blockchain based Masternode Hosting. As users continue to get more familiar with Cryptocurrency wallets, setting up and configuring Masternodes still represents a technological pain point and struggle.

*   Self-Service Website using Guiding Principals: By creating a minimalist website design with specific Calls to Action, the User is guided every step of the way without needing to talk or wait for any help. Bulk options allow Power Users to quickly create and activate any number of Masternodes at once, saving time and frustration.
*   Invoicing made Simple: Invoices are created with only the information needed at the time payment is due, allowing the Customer to quickly see the total amount due with simple options to pay. This reduces information overload and panic and allows the Customer to easily resolve the bill and continue with their business.
*   Drill Down Data History: Invoice History allows for a Customer to Deep Dive into their Monthly when they have time or the need arises. Nothing is hidden and information is presented in a straight forward and organized manner.
*   Payment Processing: Multiple Payment options allowing for Pre-funding the Customers account so they do not have to worry about overdue invoices. Blockchain based options automatically convert the cryptocurrency value into USD for simplified account balances and takes the guess work out of it.

## _Masternode Services_

Masternode Services specializes in CryptoCurrency based Business class Customer use cases, where the scope would normally overwhelm an organization not familiar with Blockchain powered Masternode Investments. Providing a unified Dashboard that shows all data metrics in logical groupings, the investor can easily breakdown the data in any number of ways to fit different reports and utilize trending to create future projections.

#### Technology Stack

Masternodes Services is built on Java, Java Server Faces and Primefaces Elite.

#### Project Highlights

The core of Masternode Services is data presentation. In order to create visually digestible data points and metrics, a unique Dashboard system was created to empower the Investor with creating their own reports.

*   Support for any number of different Cryptocurrencies and multiple sub-accounts with separate tracking all on the same Dashboard
*   Detailed metrics for each cryptocurrency masternode network, including how many masternodes are live on the network
*   Conversions for cryptocurrency to USD value, updated daily
*   Complete history for every Masternode Reward right from the blockchain
*   Daily and Total Reward and Investment Metrics
*   Summary and At a Glance Status Metrics for all Masternodes
*   Elegant use of different layout techniques and graphs for creating easy to understand data points
