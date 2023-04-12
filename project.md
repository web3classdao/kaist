---
layout: page
title: Project
nav_order: 6
description: Final Project | Web3@KAIST 2023
---

# Final Project

## Advice for 1-page proposal

There is some advice for finding project ideas and writing proposals from Prof. Jason.
This advice is based on the online voting service project we shared as a proposal template file.
We've focused on a prototype implementation of Option 1, but the same can be applied to Option 2.

### Problem
Keep the problem you're trying to solve small.
If possible, find a problem that solves a specific area or limited situation.
Once you've solved a problem in a specific area, you'll see a path to generalization.

For example, let's say you propose a project to solve the problem of manipulability and trust in online voting.
The problem is broad and general because online voting can be applied anywhere.
That leaves you with a lot of issues to solve. 
Narrow it down. You can narrow it down to a contest or hackathon.
Even popular audition shows like Produce 101 use SMS voting for audience evaluation.
Instead of professional judges, the audience participates in the evaluation. 
This is where data manipulation and trust issues arise. 
Competitions and hackathons may not have an audience. 
Therefore, instead of limiting the audience, we expand the scope to participants.
Participants can include the organizers, staff, competitors, and the audience. 

### Solution
Don't try to solve every aspect of the problem.
The important thing is to make your proposed solution different. 

Let's use the example of an online voting project.
There are many things to consider when implementing online voting on a blockchain.
However, the goal is not to implement the perfect online voting.
It is to propose a differentiated solution and focus on it.
There are two points of differentiation
1) We implement online voting with smart contracts, making it impossible to manipulate.
2) We apply Quadratic Voting, which allows users to vote differently based on their preferences.

If you want to implement perfect online voting, there are many more issues to address. For example
- Ensuring voting privacy: How do you protect privacy when voting data is transparently public?
- Identity verification at the registration stage: How do you prevent people from registering who are not participants? 
- UX of the user app: If a wallet is required, how do we provide an easily accessible UX?

There are a lot of issues, but the idea is not to solve them all, but to focus on two points of differentiation and implement them.  

### Why Blockchain
You need to seriously ask yourself why you should use blockchain.
If the reason to use blockchain is forced, it's not the right problem.

Here are some examples of why you might want to apply blockchain,
- To increase trust between multiple parties
- To prevent tampering with sensitive data
- To minimize human intervention in critical processes/logic (using smart contracts).
- To provide transparent and reliable tracking of history and provenance
- To leave data in perpetuity (companies and organizations don't last forever)
- To assetize something that has never been valued digitally.
- To create limited edition digital items
- To create open, standardized digital objects to increase third-party utilization (NFTs)
- To provide a flexible way to motivate participants
- To create secure transactions without intermediaries
- To achieve goals between participants without intermediaries.
- To create a structure for participants to participate in decision-making.
- To create a protocol that other services can use.
- To increase the permissionless composabilityof services

You don't need to apply every concept of blockchain.
You just need to take the best aspects of blockchain that are appropriate for the problem you're trying to solve.
You can take any of the Web3 stacks described in Lecture 2 and repurpose them.
You don't have to be decentralized, you don't have to issue tokens or coins.
You don't have to create a community or apply governance.
The important thing is to find the features that are a natural fit for the problem you're trying to solve and apply them.

Let's illustrate with an online voting project.
Among the reasons for applying blockchain to the above 
To minimize human intervention in critical processes
and to prevent tampering with sensitive data.
And to implement Quadratic Voting, we issue a token.
These tokens are only used as voting credits, not to create a cryptocurrency.
