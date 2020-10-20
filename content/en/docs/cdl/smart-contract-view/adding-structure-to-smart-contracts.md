---
title: Adding structure with CDL
date: 2020-10-15T00:00:00+01:00
menu:
  cordapp-design-language:
    parent: cdl-smart-contract-view
    identifier: cdl-smart-contract-view-adding-structure
    weight: 30

tags:
- cdl
- cordapp design language
- smart contract
- cordapp diagram
---

# Use CDL to add structure to Smart Contracts

For many simple CorDapps, you may not feel the need for a structured language to represent your CorDapp design. If you have a simple state, with a single implied status and only one or two commands, you may find it simple enough to write the contract code, which will fit on one screen, and see exactly what's going on.

However,if you want to do anything beyond a basic proof of concept, things are likely to get more complicated. If you are writing production grade CorDapps that need to deal with many different scenarios, you need to organise your designs carefully and methodically. The primary benefit of CDL is that it provides a level of abstraction that allows you to work on more complicated designs without having to hold all the details in your head. This reduces the risk of creating errors and making mistakes. 

The way the abstraction works is to split the elements of the Smart Contract design into a standard set of considerations, such as:

- What's my state data?
- What different statuses can the data be in?
- Who are the participants for each status?
- How can I move between each status?

By splitting the design process into these different predefined considerations, you add structure and robustness to your design thinking. Providing a standardised way to represent each of these considerations in a neat, single-page view further empowers you to communicate and reason about the design. By defining standardised ways to implement and test each consideration, you increase confidence in the faithful implementation of the design.
