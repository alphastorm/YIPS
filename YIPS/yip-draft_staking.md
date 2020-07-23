---
yip: <to be assigned>
title: Replace YFI burning with staking
status: WIP
author: Sunil Srivatsa (@alphastorm) on behalf of yfi_whale
discussions-to: https://gov.yearn.finance/t/yfi-whale-proposals-list/348
created: 2020-07-23
updated: N/A
---

## Simple Summary
Replace YFI burning with staking for claiming pro-rata protocol fees.

## Abstract
All yEarn fees (currently $60/wk) are routed to this Vault and normalized to aDAI.

YFI represents a claim on those fees. To claim fees, YFI must be burned.

This YIP is to decide whether or not keep this mechanism the same or change it to a stake based system where those who stake YFI are entitled to a pro-rata claim on the reward pool (without having to burn YFI).

## Motivation
It makes no sense to burn because the price of YFI will always be higher than the claimable fee value. This is because YFI represents current assets in the fee pool plus future expected cashflows. Staking is just obviously better.

## Specification
<!--The specification should describe the syntax and semantics of any new feature, there are five sections
1. Overview
2. Rationale
3. Technical Specification
4. Test Cases
5. Configurable Values
-->

### Overview
<!--This is a high level overview of *how* the YIP will solve the problem. The overview should clearly describe how the new feature will be implemented.-->
N/A.

### Rationale
<!--This is where you explain the reasoning behind how you propose to solve the problem. Why did you propose to implement the change in this way, what were the considerations and trade-offs. The rationale fleshes out what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.-->
N/A.

### Technical Specification
<!--The technical specification should outline the public API of the changes proposed. That is, changes to any of the interfaces yEarn Finance currently exposes or the creations of new ones.-->
N/A.

### Test Cases
<!--Test cases for an implementation are mandatory for YIPs but can be included with the implementation..-->
N/A.


## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
