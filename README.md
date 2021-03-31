# Baseline Protocol Specifications

![Baseline Logo](https://raw.githubusercontent.com/ethereum-oasis/baseline/master/docs/assets/baseline-logo/Web/examples/PNGs/horizontal/baselineHorizontal-Logo-FullColor.png)

*Read the full documentation [here at docs.baseline-protocol.org](https://docs.baseline-protocol.org/).*
*Join our [Slack workspace](https://communityinviter.com/apps/ethereum-baseline/join-us), [Discord channel](https://discord.com/invite/NE8AYD7), [Telegram channel](https://t.me/baselineprotocol) and follow us on [Twitter](https://twitter.com/baselineproto) for Baseline news and updates!* 

## Overview

This folder contains the specifications for the Baseline protocol, a technique which combines advances in cryptography, messaging, and blockchain to coordinate complex business processes at low cost via the public Mainnet while leaving private data on traditional systems of record.

The main goal of this folder is to provide accurate reference documentation for the aspects of the protocol that are independent of language or implementation. 

In addition to describing the current state of th Baseline protocol, the specs folder serves as a coordination point and a venue to drive the development of the Baseline OASIS standards. 

## Status

The Baseline protocol specifications are currently work in progress.

## Specifications

There are currently two specifications in development:

OASIS Spec 1 - The Baseline CORE Specifications document: The document describes the minimal set of business and technical prerequisites, functional and non-functional requirements, together with a reference architecture that when implemented ensures that two or more systems of record can synchronize their system state over a permissionless public Distributed Ledger Technology (DLT) network.

[CORE latest working draft](https://github.com/ethereum-oasis/baseline-standard/blob/main/core/baseline-core-v1.0-psd01.md)

OASIS Spec 2- The Baseline API & Data Model Specifications document: The document describes the Baseline programming interface and expected behaviors of all instances of this interface together with the required programming interface data model.

[API latest working draft](https://github.com/ethereum-oasis/baseline-standard/blob/main/api/baseline-api-v1.0-psd01.md)

## Quick Links - Specification Components

<table>
<tr>
    <th>Component</th>
    <th>Link</th>
    <th>Description</th>
    <th>Roadmap status</th>
  </tr>
<tr>
    <td>Glossary</td>
    <td>#2</td>
    <td>Provides terminology/definitions of key concepts.</td>
    <td>Status: In progress - Main concepts have been defined and reviewed by the team. New keywords should be defined and added as we go.</td>
  </tr>
<tr>
    <td>API Spec</td>
    <td>#37</td>
    <td>Describes the Baseline programming interface and expected behaviors of all instances of this interface together with the required programming interface data model.</td>
    <td>Status: In progress - PRIORITY </td>
  </tr>
<tr>
    <td>CORE Spec - Communication</td>
    <td>#38</td>
    <td>Describes messaging mechanisms between parties' baseline stacks and between systems of records and baseline stacks.</td>
    <td>Status: Started - actively looking for individuals to take the lead on this.</td>
  </tr>
<tr>
    <td>CORE Spec  - Privacy & Confidentiality</td>
    <td>#39</td>
    <td>Describes mechanisms to ensure counterparties confidentiality and shielded private transactions.</td>
    <td>Status - Not started</td>
  </tr>
<tr>
    <td>CORE Spec  - Agreement Execution</td>
    <td>#40</td>
    <td>Describes the functionalities, events and terms required for baselining.</td>
    <td>Status: Started - actively looking for individuals to take the lead on this.</td>
  </tr>
<tr>
    <td>CORE Spec  - Governance</td>
    <td>#41</td>
    <td>Describes the required functionalities to implement governance processes at every functional layer of the Baseline specification.</td>
    <td>Status: Not started </td>
  </tr>
<tr>
    <td>CORE Spec  - Security Considerations</td>
    <td>#42</td>
    <td>Describes security topics that should be important in Baseline implementations but that are NOT requirements. </td>
    <td>Status: Not started </td>
  </tr>
<tr>
    <td>CORE Spec  - Conformance</td>
    <td>#43</td>
    <td>Describes the conformance clauses and tests required to achieve baseline compliant implementations.</td>
    <td>Status: Not started </td>
  </tr>
</table>

**#Quick Links - Documentation**

<table>
<tr>
    <th>Document</th>
    <th>Link</th>
    <th>Description</th>
    <th>Roadmap status</th>
  </tr>
<tr>
    <td>Cookbook</td>
    <td>#29</td>
    <td>Add specification-related content to Cookbook</th>
    <td>Not started</td>
  </tr>
</table>


## License

All contribution in this repo is released under the CC0 1.0 Universal public domain dedication. For the full license text, refer to [LICENSE](https://github.com/ethereum-oasis/baseline/blob/master/LICENSE).

## Contributions

To participate in the evolution of Baseline via the specs process, please see our [Contributors Guidelines](https://docs.baseline-protocol.org/community/contributors).
