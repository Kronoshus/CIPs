---
CPS: ?
Title: CIP Organization & Categorization
Status: Open
Category: Documentation
Authors:
  - Adam Dean <adam@crypto2099.io>
Proposed Solutions:
Discussions:
Created: 2023-07-19
---

# Abstract

This problem statement attempts to provide a focal point for discussion pertaining to the organization and structure of
the Cardano CIP repository in order to make it more easily manageable and navigable to new teams and developers entering
the ecosystem who may not know where to look to identify all relevant CIPs to their implementation or use cases.

# Problem

If we take just one facet of the current CIP repository under a microscope (native asset metadata standards), then we
see that there are already 12 different CIPs (10, 25, 26, 27, 54, 60, 67, 68, 71, 86, 88, 89) in _Accepted_ or 
_Proposed_ status as well as several currently in limbo in raw pull request stages that may be pertinent to teams 
looking to implement a project utilizing Cardano Native Assets in their project. The current organization of the
repository makes it difficult to identify the relevant, accurate, and complete picture of which standards are already
available/written, which may need modification or iteration, and how they fit within the overall scope of the ecosystem.

Furthermore, this is compounded, currently, by a recalcitrance to modify existing/established CIPs and a lack of
versioning in some existing standards enabling easier iteration and identification of the latest standard that can or
should be used.

# Use Case

The proposed use case of this Problem Statement is to collaborate, as a community, on best practices for organization,
structure, and methods for grouping, versioning, and iterating on existing standards in a way that makes those same
readily and easily discoverable to new entrants to the ecosystem and existing implementors who may be looking for the 
latest updates and proposals to already adopted standards.

# Goals

## 1. Grouping and Categorization

Establish an accepted structure for the CIP repository that makes it easy to identify and group CIP standards under
common "themes". Example: Governance, Plutus/Smart Contracts, Wallets, Tokens, etc.

## 2. Framework for Versioning

It is currently unclear if a given CIP, once accepted, should be set in stone (under a fixed version number) and if
subsequent CIPs should aim to modify this base CIP, introduce a new CIP as a subsequent version number, or extend this
CIP via a new tail. This problem statement aims to open discussion and finalize around a solution for consistency going
forward.

# Open Questions

## What broad categories/themes best encapsulate current CIP standards?

A few have already been mentioned in the content of this document including:
- [ ] Smart Contract Features and Functionality
- [ ] Wallet and Address Standards
- [ ] Native Asset Standards and Best Practices
- [ ] Governance and Voting Standards

## When to modify or extend an _Accepted_ standard?

Should we introduce a baseline expectation that all proposed CIPs introduce a versioning syntax and, once accepted, CIPs
aiming to modify or extend the functionality of a given CIP should create a new version or submodule/branch beneath the parent
scope?

## How best to organize an ever-growing repository in a way that is convenient and accessible?

The scope and breadth of CIPs is only likely to increase as new features, functionality, and use cases are brought to 
the Cardano ecosystem. How can we ensure that the process of discovering existing standards or introducing new ones
remains as intuitive and accessible to both new and old users alike moving forward?