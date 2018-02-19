# FIFO order for reviewing of pull requests

## Summary
[summary]: #summary

Bring some order into the pull request review process in order to minimize third party contributors' frustration and loss of time due to having to maintain pull requests for a long time.

## Motivation
[motivation]: #motivation

It has come to my attention that for some time now third-party pull requests have a tendency to not get reviewed for a __very__ long time.
E.g. this [(de)serialization series of PRs](https://github.com/googlecartographer/cartographer/issues/549) has been ready and waiting to be merged since September.
Almost all of the PRs in the series have been merged, but the final one is still awaiting a review - I could bring up a few other examples of my PRs being set aside for a long time.
It's a frustrating feeling to see PRs originating from the Cartographer team appear and get approved almost instantly, and when the merged PRs cause conflicts with already existing PRs.

## Approach - PR neutrality
[approach]: #approach

Introduce a FIFO principle of reviewing pull requests, treating all the PRs equally.
The proposer of the RFC understands that the Cartographer team has staffing growth issues and a lot on their backlog.
The RFC hopes to bring to Cartographer team's attention that the third party contributors can also happen to have a lot on their backlog, and would benefit from not having to maintain feature branches for the stuff that they hope to get merged into upstream.
(Even a negative review is helpful regarding this - it means that there is no need to further maintain the offending branch separately.)

Thank you for helping us help you help us all!

## Discussion Points
[discussion]: #discussion
