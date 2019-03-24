**#HackBMU2019_TheWanderars**<br />

**Blockchain based decentralized Prevention of Digital Evidence Tampering System**<br />



**Problem Statement**<br />

Suppose a person has a criminal/civil case against him/her. So, they would face some disadvantages like unable to travel to certain foreign destinations, apply for visas, stand in elections etc. So, some highly influential people try to modify or tamper with the evidence such as modification of the original FIRs, modification of the Digital forensic evidence. This issue can be solved using Blockchain technologies. A solution to this problem will help reduce the cases of corruption and ensure that the judgement is fair. 
<br />

**Solution Approach**<br />

In this system, the on duty police officer will be required to upload the evidence/Information Report at the first instance of collection. This will be further uploaded on the IPFS system as an image and later obtained IPFS hash will be stored on Blockchain.
Anyone having the IPFS hash can see the evidence collected//Information Report, this will ensure transparency in the system and ensure that any modification is prevented. We have 2 layers of security namely distributed file on different peers of IPFS and storing the IPFS that is address of Information Report/Evidence collected, on Blockchain. 
<br />

**Dependencies**<br />

1.	NodeJS and ReactJS for frontend and web application part
2.	IPFS framework for uploading images
3.	Ganache for the Blockchain uploading Part

<br />

**How to run?**
<br>
1. npm install. //This should be done in the main folder
2. load your ganache
3. configure a metamask and connect to the ganache to get ethers
4. the contract is deployed on remix
5. npm run start
6. cd mywebsite && nodemon server.js
7. both the servers have been deployed. visit localhost:3001 for home page.
