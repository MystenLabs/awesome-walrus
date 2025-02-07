Walrus Tools from Brightlystake
---

At Brightlystake we are extremely thrilled about the possibilities that comes with decentralised storage WalrusProtocol provides.

We have created a tool for the $WAL operators to measure their performance over a period of time. 

## Tooling Category
- [X] Visualization
- [ ] Cli Tools

## Features
1. [Overall Dashboard](https://walrus.brightlystake.com)
  - Timelines 
    - Red highlight 
      - When the node status is not in Active status 
      - When the `event_pending` is NA
    - Yellow highlight - When the `event_pending > 0`
  - Operator status 
    - GREEN - if Active. 
    - RED - if not Active.
    - GREY - if NA
  - Event Pending 
    - GREEN if 0
    - YELLOW - if > 0 and < 200. 
    - RED - if > 200. 
    - GREY - if NA

2. [Shards Dashboard](https://walrus.brightlystake.com/shard-owners)
  - Display which shard is assigned to which operator.
  - Depending upon how many previous assignment the shard had we highlight in different colors.

## Latest Version Number of Walrus Tested On
Testnet
