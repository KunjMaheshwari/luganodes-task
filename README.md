Task Document for VIT SDE Hiring - Luganodes
Comment
Task Title: Ethereum Deposit Tracker
Discord Invite Link: https://discord.gg/vMRBy7by
Objective:
Develop a robust and efficient Ethereum Deposit Tracker to monitor and record ETH deposits on the Beacon Deposit Contract.

Examples of Deposits to be Tracked:
Deposit Transaction: 0x1391be19259f10e01336a383217cf35344dd7aa157e95030f46235448ef5e5d6
Deposit through contract: 0x53c98c3371014fd54275ebc90a6e42dffa2eee427915cab5f80f1e3e9c64eba4
Project Components:
Language/Framework:
Anything that suits you. The sky is the limit.
RPC:
Use Ethereum RPC methods to interact with the Ethereum blockchain (Checkout Alchemy).
Task Breakdown:
RPC Integration:

Establish an RPC connection to an Ethereum node (Infura, Alchemy, or a local node).
Develop functions to use Ethereum RPC methods for fetching deposit data.
Ensure the solution can handle real-time data fetching and processing.
Deposit Tracking Logic:

Implement logic to monitor the Beacon Deposit Contract address 0x00000000219ab540356cBB839Cbe05303d7705Fa for incoming ETH deposits.
Develop functions to record and store deposit details (amount, sender address, timestamp, etc.).
Ensure the tracking system can handle multiple deposits made in a single transaction (internal transactions, see example above).
Error Handling and Logging:

Implement comprehensive error handling for API calls and RPC interactions.
Add logging mechanisms to track errors and important events.
Alerting and Notifications (optional):

Integrate alerting mechanisms to notify when new deposits are detected.
Set up a Grafana dashboard to visualize deposit data and system metrics.
Implement Telegram notifications to alert users of new deposits.
Documentation:

Document the setup process, including environment configuration and dependency installation.
Provide detailed usage instructions for the ETH deposit tracker.
Include comments in the codebase for better readability and maintenance.
Schema of Deposit to be Saved:
Deposit {
    blockNumber;
    blockTimestamp;
    fee;
    hash;
    pubkey;
}
Deliverables:
An ETH deposit tracker application.
A private repository with the complete source code, properly structured and documented.
A comprehensive README file with setup, usage instructions, and examples.
Error handling and logging mechanisms integrated into the application.
Alerting system with Grafana dashboard and Telegram notifications (optional).
Add the listed GitHub usernames as collaborators for the project.
mannan-goyal
rohilsaraf97
bitoffabyte
guptaharsh13
nimishjn
Submit your task with all the relevant details here before the given deadline.
Evaluation Criteria:
Code quality and adherence to best practices.
Efficiency and accuracy of the ETH deposit tracking.
Robustness of error handling and logging.
Clarity and comprehensiveness of documentation.
Bonus points for Dockerizing the application.