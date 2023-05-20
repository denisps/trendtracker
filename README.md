# trendtracker
World wide distributed trend and meta-tag tracking.

This is an open colaboration initiative to create a fully decentralized base trend and meta-tag tracking platform on top of which a fully distributed Twitter/Youtube/Google/Email/Facebook/Reddit/Web3 alternatives could be implemented.

Join our wiki to colaborate and discuss the concept, chalanges, volnerabilities, proof of concept, and integration.

## Types of trends and meta-tags
To assist in the creation of the distributed services listed above the platform must be abble to track the following items:
1) IDs
2) Channel IDs
3) Describers
4) Popularity
5) Accociativity
7) Timestamps

### Content Accociativity
Now, Content Accociativity is a concept that is not being widely used, especially in the distributed systems, but it may be a key building block in the web3 world. When thinking Content Accociativity, think about Twitter's Community Notes, it is a peice of content that people associate with another peice of content.

Content Accociativity can provide a fully distributed tags, comments, debunks, reviews, topics, and possibly even name services. Content Accociativity can be implemented only in a close integration with the items 1, 2, 3, and 4.

## Implementation requarements
To assist in the creation of the distributed services listed above the platform must be abble to handle:
1) 8+ billion people each of whom can contribute to many trends and meta-tags
2) Be the decntralized, fault tollarent, censorship resistant, and as private as possible
3) Require no configuration and be ready for use right out of the box

## Initial concept overview
Let us assume we have 8 billion people. Haw can we track the trends:
1) Each peice of content can be adressed by its hash (Immutable Content ID) and distributed by the peers that subscribe to it
2) Each user can be a content creator and is represented by Channel ID (Public Key)
3) Each user must be abble to describe thousands of content IDs
4) The more users subscribe to a content ID the more responsibility falls on the content tracker (think 8 billion requests per minute)
5) Current DHTs are incapable of tracking milions of subscribers, let alone billions, so the trackers around the content IDs must be abble to scale horisontally
6) The Trackers must also track Popularity, Accociativity, Timestamps, Channel Updates, and other Trackers
