# Join the DAOs

First of all, when you register in PoH and start receiving UBI, you have access to participate in both projects' DAOs. Although they are very related, we will see that there are some differences. For simplicity, we will talk about the PoH DAO, and some points of difference with the UBI DAO.

### What does the DAO look like in practice?

You can start by reading and participating in both the telegram groups and the [forum](https://gov.proofofhumanity.id/), where issues related to Proof of Humanity and UBI are continuously discussed. Some members raise concerns, others raise ideas and so on. As a result, an improvement proposal called HIP (Human Improvement Proposal) or UIP (UBI Improvement Proposal) is created. For the proposal to be valid, it must follow the framework defined in the \[HIP-5]\(https://gov.proofofhumanity.id/t/hip-5-adopt-a-proper-poh-dao-governance-process- to-ensure-hip-quality/393). Yes, there was a HIP to define how to make a HIP :)

In the second and third phase of the process of a proposal, voting takes place. They are carried out on the [Snapshot](https://snapshot.org/#/) platform.

#### Snapshot&#x20;

Snapshot is not part of POH. However, it's a platform used by the majority of DAOS in the Ethereum ecosystem given its transparency. It allows the use of liquid democracy. What does it mean? The participants vote directly, abstaining if they so wish or delegating their votes to another wallet.

![](https://i.imgur.com/fnVITHM.png)

We must connect the same wallet that we use to register in POH in order to cast our vote. It is important to highlight that for this \*\* YOU DO NOT HAVE TO PAY ANYTHING \*\*. Only a message is signed with our wallet, it has no gas cost.

When a vote is in progress, there is usually a choice between "Accept changes" to the proposal or "Make no changes".



![](https://i.imgur.com/qYmbjB2.png)

Once the option is selected, you can see your voting power. We'll talk more about this a bit later:

![](https://i.imgur.com/NAuyl7F.png)

With Metamask (it is similar for other wallets) we will be asked to sign the voting message (again, without any gas cost).

![](https://i.imgur.com/3nNXd6n.png)

We sign and the vote will be registered. It is important to clarify that for HIPs, every human registered in POH has the same voting power. For UIPs, voting power is the square root of the number of UBIs you have in your wallet.

Once the voting ends, if the proposal concludes with positive votes, the HIP/UIP is implemented. As simple as that. With your vote, your point of view, your opinions and knowledge you contribute to improving each project.

* [PoH DAO Snapshot](https://snapshot.org/#/poh.eth)
* [UBI DAO Snapshot](https://snapshot.org/#/ubi-voting.eth)

### Clarifications

#### Technical impacts of a proposal

A proposal can have technical impacts, for example, modifying parameters of the POH or UBI smart contracts (i.e modifying the initial deposit cost). This occurs today through the figure of the **Governor**.

The governor is ANOTHER smart contract that supports the submission of "code to be executed" into a smart contract (in this case, POH or UBI contract). They are different contracts. Now, that "code to be executed" requires an escrow to be put down since Kleros dispute resolution is used. If no one challenges the technical implementation of the proposal, the code is executed and the POH or UBI smart contract is updated. This mechanism seeks to add transparency for any update. If the code to be executed doesn't do what was agreed in the proposal, anyone can appeal and will earn the reward of whoever is trying to update the protocol improperly.

#### Proposals without technical impact

Other proposals, on the other hand, may not have a technical impact. In short, they are agreements or conventions guide the governance of the community. The HIP-5 is the example of this. Since the entire DAO agreed that this was the format and process for a proposal, no future proposal can be valid if it does not follow that framework.

#### Vote Delegations

Snapshot allows [voting to be delegated](https://snapshot.org/#/delegate). This functionality is mostly used by people who can't follow the community discussions but don't want to miss out on voting. Therefore, they delegate their voting power to someone else. Let's see it with an example:

Bob delegates his vote to Alice. After paying the transaction with his wallet, in the next proposals that emerge, every vote made by Alice will count with Bob's additional vote. However, the delegation does not imply that Bob cannot vote again. Quite the contrary, whenever Bob wants to vote, he can do so, and in that case Alice will have only her vote without losing that delegation.

_**Reminder**_: the delegation feature do cost gas but it is a single transaction. From then on, the vote is already delegated until it is decided to eliminate the delegation.
