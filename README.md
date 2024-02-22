<h1>Application Communication Workflow:</h1>
<br>
![comm_flow_image](https://github.com/harshil3662/enterprise-hyperledger-fabric/assets/87032930/5c7de930-f981-4c64-8c7e-22992df8eb68)
<br>

- User will interact with the Todos client application, in their browser.<br>
- When the user performs any action, the client application calls the server application API where the registered admin interacts with the Hyperledger Blockchain Network.<br>
- Reading or writing the ledger is known as a proposal. This proposal is built by Todos Server (via the SDK) and then sent to a blockchain peer.<br>
- The peer will communicate to its Todos chaincode container. The chaincode will run/simulate the transaction. If there are no issues it will endorse the transaction and send it back to our Todos application.<br>
- Todos (via the SDK) will then send the endorsed proposal to the ordering service. The orderer will package many proposals from the whole network into a block. Then it will broadcast the new block to peers in the network.<br>
- Finally the peer will validate the block and write it to its ledger. The transaction has now taken effect and any subsequent reads will reflect this change.<br>

<h1>Using the todo list application:</h1>
<br>
![todo-authentication](https://github.com/harshil3662/enterprise-hyperledger-fabric/assets/87032930/2e535b10-4539-4953-84da-a7e168a8c19e)
<br>
![todo-list](https://github.com/harshil3662/enterprise-hyperledger-fabric/assets/87032930/275719b6-6cc7-4dc7-9c85-a70df6019d9b)
<br>

<h2>Karan (Business Analyst):</h2>
<h3>Responsibilities:</h3>
• Gather business requirements and translate them into functional specifications.
• Conduct market research and analysis to identify potential business opportunities.
• Ensure alignment between technical solutions and business objectives.
Contributions:
• Business requirements documentation.
• Functional specifications.

<h2>Harshil (Blockchain Developer):</h2>
<h3>Responsibilities:</h3>
• Design, develop, and maintain the Hyperledger Fabric blockchain network.
• Implement smart contracts using Chaincode.
• Integrate blockchain components with the application.
Contributions:
• Chaincode implementation.
• Blockchain network setup and configuration.

<h2>Robin (Application Architect):</h2>
<h3>Responsibilities:</h3>
• Design the overall architecture of the application, ensuring scalability, security, and
maintainability.
• Define system components, interfaces, and interactions.
• Coordinate with stakeholders to validate architecture decisions.
Contributions:
• Application architecture design.
• System interface specifications.

<h2>Rohan (Full Stack Developer):</h2>
<h3>Responsibilities:</h3>
• Develop frontend and backend components of the application.
• Integrate application components with the blockchain network.
• Ensure the application meets performance, usability, and security requirements.
Contributions:
• Frontend and backend codebase.
• Integration documentation.
