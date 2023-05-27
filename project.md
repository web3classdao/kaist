---
layout: page
title: Project
nav_order: 6
description: Final Project | Web3@KAIST 2023
---

# Final Project Submission and Evaluation

## Project peer-evaluation by on-chain governance
이것은 2023년 봄학기 Web3@KAIST 수업의 프로젝트를 peer evaluation 하기 위한 on-chain governance 이다. Web3@KAIST는 2023년 봄학기에 KAIST에 개설된 수업으로 Web3 programming을 가르치고, 프로젝트로서 Web3 서비스를 만들거나 사업계획을 하는 수업이다. 수강생 150명, 청강생 120명, 멘토 60명, 교수 및 스탭 10여명이 참여해 340명 가량의 수업 커뮤니티를 구성해 community-driven class로 운영하고 있다.

학생들은 최종 프로젝트로서 Web3 app prototype을 제출하거나 Web3 startup proposal을 제출해야 한다. 제출 방식은 여기에 proposal로 등록해야 한다. 이후 커뮤니티 멤버들에 의해 각 proposal에 대해 투표가 진행되고, 투표 기간 이후에 투표 성공하는 경우 Certificate of Achievement SBT가 자동으로 프로젝트팀에게 민팅될 것이다. 커뮤니티 멤버들에게 governance token이 민팅될 것이고, 토큰이 있어야 proposal을 만들 수 있고 투표에 참여할 수 있다. 

이 과정을 통해 학생들이 on-chain governance를 경험해 보고, smart contract에 의해 proposal이 voting을 거쳐 execution까지 진행되는 과정을 이해할 수 있는 기회가 되길 바란다. 

## 모든 멤버의 준비사항

* Metamask에서 네트워크를 Sepolia testnet으로 지정하고 계정으로 들어간다.
* Metamask에서 Governance token을 import한다.
```
Token contract address: 0x7E68DD4A243c2505B142213B8Bf8c091138941A8
Token symbol: W3K23
Token decimal: 18
```
* governance token은 다음과 같이 전송됬다.
** project team: 10
** other auditors who sent an address: 10
** mentors and staff: 20
** professors: 30

* SepoliaETH가 없는 경우 Faucet 서비스에서 0.5 SepoliaETH 받는다.
** https://sepoliafaucet.com/

* Web3@KAIST Governance 서비스에 접속한다. 
** https://www.tally.xyz/gov/web3atkaist-2023

* Metamask로 Sign in 해서 들어간다.

* Delegate 메뉴를 클릭해서 Myself로 delegate 한다. (Metamask로 tx 승인 필요)


--------------------------------

# Final Project Delieverables

You are required to submit three deliverables for each option by **midnight this Tuesday, May 30.** <br>
All deliverables must be submitted in English.

## Option 1) Web3 app prototype (submit all three)
1. Running Web3 app URL & Github public repo URL (*If your project isn’t a web app, you don’t need to submit an app URL. Instead, you have to show the screen running the result in the video.*)
2. Web3 app introduction deck URL (a presentation file under 10 slides)
3. Youtube video URL to present your Web3 app prototype running and intro deck (within 5 minutes)

## Option 2) Web3 startup proposal (submit all three)
1. Web3 app whitepaper URL (a word file under 10 pages)
2. Web3 startup pitch deck URL (a presentation file under 10 slides) (*Refer to [other pitch decks](https://www.hubspot.com/startups/startup-pitch-decks) (especially Dropbox)*)
3. Youtube video URL to present the pitch deck (within 5 minutes)

For this class, we don't plan to receive and store project deliverables.<br>
Therefore, all deliverables must be submitted as URL links.<br>
They will then be viewed and voted on by the class community members during the evaluation period.

------------------

# Final Project Proposal

You are required to submit a 1-page proposal for your final project by **midnight this Friday, April 14.** 
- The link to submit was provided in last week's email.
- Proposals will be open to the community. 
- Idea change will be allowed in the final deliverable. (need to submit a revised proposal)
- If you don't submit a proposal, you're warned that you may fail.


## Advice on 1-page proposal

There is some advice for finding project ideas and writing proposals from Prof. Jason.
This advice is based on the online voting service project we shared as [a proposal template file](http://web3classdao.xyz/kaist/assets/files/web3kaist-proposal-teamname.pdf).
We've focused on a prototype implementation of Option 1, but the same can be applied to Option 2.

**There are already more than 350 potential users in the Web3@KAIST community. We recommend that you create a service for them, or propose a service for students on campus.** The online voting service in the example is the one we propose to use to evaluate the final projects in this class.

### Problem
> **Keep the problem you're trying to solve small.<br>
> If possible, find a problem that solves a specific area or limited situation.<br>
> Once you've solved a problem in a specific area, you'll see a path to generalization.**<br>

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
> **Don't try to solve every aspect of the problem.<br>
> The important thing is to make your proposed solution different.** <br>

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
> **You need to seriously ask yourself why you should use blockchain.<br>
> If the reason to use blockchain is forced, it's not the right problem.**<br>

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
- And more

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


*****
*****

## Advice for 1-page proposal (Korean)

프로젝트 아이디어를 찾고 제안서를 작성하는데 몇 가지 조언을 드립니다.
이 조언은 [제안서 템플릿](http://web3classdao.xyz/kaist/assets/files/web3kaist-proposal-teamname.pdf)으로 공유드린 온라인 투표 서비스 프로젝트를 에시로 설명드립니다.
Option 1. 프로토타입 구현하는 경우에 포커스를 맞췄지만, Option 2에도 동일하게 적용될 수 있습니다.

**Web3@KAIST 커뮤니티에는 이미 350명 이상의 잠재적인 사용자가 있다. 이들을 위한 서비스를 만들어 써 보게 하는 것을 추천한다. 또는 교내 학생들을 위한 서비스를 제안해 보는 것도 좋다.** 예시로 든 온라인 투표 서비스 역시 이번 수업에서 프로젝트를 평가하기 위해 활용하려고 제안하는 것이다. 

### Problem
> **풀려고 하는 문제를 작게 잡아라.<br>
> 가능한한 특정 영역이나 제한된 상황을 해결하는 문제를 찾아라.<br>
> 제한된 영역에서 먼저 문제를 풀고 나면 일반화할 수 있는 길이 보일거다.**<br>

예를 들어, 온라인 투표의 조작 가능성과 신뢰 문제를 해결하는 프로젝트를 제안한다고 하자.
온라인 투표는 어디에나 적용할 수 있기 때문에 문제가 브로드하고 제너럴하다.
그렇게 되면 해결해야 할 이슈가 많아진다. 
범위를 좁혀보자. 경진대회나 해커톤으로 범위를 줄일 수 있다.
유명 오디션 프로그램에서도 문자 투표를 이용한 청중 평가를 하고 있다.
전문 심사위원이 아닌, 청중들이 직접 평가에 참여하는거다. 
여기에서 데이터 조작과 신뢰 이슈가 발생한다. 
경진대회나 해커톤은 청중이 없을 수 있다. 
따라서, 청중에만 국한하지 않고, 참가자로 범위를 넓힌다.
여기서 참가자는 주최측, 스탭, 대회 참가자, 청중 모두 포함될 수 있다. 

### Solution
> **문제의 모든 측면을 해결하려 하지 마라.<br>
> 중요한 것은 제안하는 솔루션의 차별점을 만들어 내는 것이다.**<br> 

온라인 투표 프로젝트로 설명해 보자.
온라인 투표를 블록체인으로 구현하려면 고민해야 할 사항이 많다.
하지만, 완벽한 온라인 투표를 구현하는게 목표가 아니다.
차별화된 솔루션을 제안하고 그것에 집중하는거다.
두 가지 차별화 포인트가 있다.
1) 스마트 컨트랙트로 온라인 투표를 구현하여 조작이 불가능하게 만든다.
2) Quadratic Voting(제곱투표)를 적용하여 선호도에 따라 차등적으로 투표할 수 있게 한다.

만약 완벽한 온라인 투표를 구현하려고 한다면, 해결할 이슈가 더 많다. 예를 들어,
- 투표 프라이버시 보장: 투표 데이터가 투명하게 공개되는데 어떻게 프라이버시를 보호할 것인가?
- 등록 단계에서 신원 인증: 참가자가 아닌 사람들을 등록하는걸 어떻게 막을 수 있나? 
- 사용자 앱의 UX: 지갑이 필요한데, 어떻게 쉽게 접근할 수 있는 UX를 제공할 것인가?

이렇게 많은 이슈들이 남아있지만, 이걸 다 해결하는게 아니라, 두가지 차별화 포인트에 집중하여 구현하는 것이다.  

### Why Blockchain
> **왜 블록체인을 이용해야 하는지 심각하게 질문해야 한다.<br>
> 만약 블록체인을 이용해야 하는 이유가 억지스럽다면, 적합한 문제가 아닌거다.**<br>

블록체인을 적용하는 이유에 대해 예시를 들자면,
- 여러 party들 간에 신뢰를 높이기 위해
- 중요한 데이터에 대한 위변조를 막기 위해
- 중요한 프로세스/로직에 대해 인간의 개입을 최소화 하기 위해(스마트컨트랙트 이용)
- 이력을 투명하고 신뢰할 수 있게 추적하기 위해
- 영속적으로 데이터를 남기기 위해 (회사나 기관은 영속적이지 않음)
- 디지털에서 가치를 인정받기 어려웠던 것을 자산화 하기 위해
- 한정판의 디지털 아이템을 만들기 위해
- 공개적이고 표준적인 디지털 객체를 만들어 써드파티 활용도를 높이기 위해 (NFT)
- 참여자들에게 동기 부여할 수 있는 유연한 방법을 제공하기 위해
- 중개자 없이 안전한 거래를 만들기 위해
- 중개자 없이 참여자들간 목표를 달성하기 위해
- 참여자들이 의사결정에 참여할 수 있는 구조를 만들기 위해
- 다른 서비스들이 사용할 수 있는 프로토콜을 만들기 위해
- 서비스의 비허가 결합성을 높이기 위해
- 그 외

블록체인의 모든 컨셉을 적용할 필요는 없습니다.
풀려고 하는 문제에 적합한 블록체인의 장점만 가져다 이용하면 됩니다.
Lecture 2 에서 설명한 Web3 stack 중에 용도에 맞게 가져다 쓰면 됩니다.
탈중앙화하지 않아도 되고, 토큰이나 코인을 발행하지 않아도 됩니다.
커뮤니티를 만들거나 거버넌스를 적용하지 않아도 됩니다.
중요한 것은 풀려고 하는 문제에 자연스럽게 어울리는 특징을 찾아 적용하는 것입니다.

온라인 투표 프로젝트로 설명해 보죠.
위에 블록체인을 적용하는 이유 중에 
중요한 프로세스에 인간의 개입을 최소화하고
중요한 데이터의 위변조를 막기 위해 사용하는 것입니다.
그리고 Quadratic Voting을 구현하기 위해 토큰을 발행하는 것이구요.
이 토큰은 투표 크레딧으로만 쓰일 뿐이지, 가상자산을 만든건 아닙니다.

