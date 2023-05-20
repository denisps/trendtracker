# Trend Tracker Concept

World wide distributed trend and meta-tag tracking
World wide distributed trend and meta-tag tracking.

This is an open colaboration initiative to create a fully decentralized base trend and meta-tag tracking platform on top of which a fully distributed Twitter/Youtube/Google/Email/Facebook/Reddit/Web3 alternatives could be implemented.

Join our wi[WiKi](https://github.com/denisps/trendtracker/wiki/Concept-of-the-Trend-Tracker)ki to colaborate, discuss, and brainstorm the concept, chalanges, volnerabilities, proof of concept, and integration of the Trend Tracker.

## Types of trends and meta-tags
To assist in the creation of the distributed services listed above the platform must be able to track the following items:
1) IDs
2) Channel IDs
3) Describers
4) Popularity
5) Associatively
6) Timestamps

### Content Associatively

Now, Content Associatively is a concept that is not being widely used, especially in the distributed systems, but it may be a key building block in the web3 world. When thinking Content Associatively, think about Twitter's Community Notes, it is a piece of content that people associate with another piece of content.

Content Associatively can provide a fully distributed tags, comments, debunks, reviews, topics, and possibly even name services. Content Associatively can be implemented only in a close integration with the items 1, 2, 3, and 4.

## Implementation requirements

To assist in the creation of the distributed services listed above the platform must be able to handle:
1) 8+ billion people each of whom can contribute to many trends and meta-tags
2) Be the decentralized, fault tolerant, censorship resistant, and as private as possible
3) Require no configuration and be ready for use right out of the box

## Initial concept overview

Let us assume we have 8 billion people. Haw can we track the trends:
1) Each peice of content can be adressed by its hash (Immutable Content ID) and distributed by the peers that subscribe to it
2) Each user can be a content creator and is represented by Channel ID (Public Key)
3) Each user must be abble to describe thousands of content IDs
4) The more users subscribe to a content ID the more responsibility falls on the content tracker (think 8 billion requests per minute)
5) Current DHTs are incapable of tracking millions of subscribers, let alone billions, so the trackers around the content IDs must be able to scale horizontally
6) The Trackers must also track Popularity, Associatively, Timestamps, Channel Updates, and other Trackers
