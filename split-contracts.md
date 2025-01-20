---
title: "Splits contract for Retro Funding Distribution"
description: "Retro Funding rewards are currently transferred to a single address given by the admin(s) of the project. For projects with multiple contributors, this often results in a second step where they distribute the tokens to the contributors themselves. For these teams, it would be beneficial to enter a contract address as the token recipient, and the contract address could manage the distribution of tokens to contributors.

This idea should integrate with the roadmap for Retro Funding sign up and project creation, and respect the contributor graph set up in Retro Funding sign-up, rather than trying to create a new contributor graph."
lang: "en-US"
type: "Project Idea"
authors: ["@C-Emily-Furlong"]
category: 'dapp-idea'
effort: "Small"
skill-sets: ["Protocol Development"]
labels: ["Governance"]
contributions:
  contributors: [""]
  discussion-link: ""
  links: [""]
  execution-status: "not-started"
---

# Splits contract for Retro Funding Distribution

## Summary

Allow teams that receive Retro Funding to automatically split the rewards among their contributors via a splits contract.

## Possible Features

- Set the percentages of rewards that the various contributors will receive (contributors are identified by their farcaster id and part of the project definition)
- set a limit (in OP) for the rewards distributed to contributors vs. staying in the treasury (i.e. any rewards under 50k OP are distributed to contributors via the contract)
- set a timeframe for the rewards to be gradually released to contributors

## Why this is cool

It will make it easier for Retro Funding recipients to manage their rewards
