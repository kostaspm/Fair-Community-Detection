# Fair-Community-Detection
This is the repository for the final project of Online Social Networks and Media.

In this work, we execute community detection algorithms and study their fairness against a protected attribute.
We also propose a post-processing algorithm that tries to fix the fairness for the communities with fairness lower than the global fairness of the network.

#### Community Detection
For the community detection procedure we used two community detection algorithms that depend on node attributes 
- Label Propagation
- Louvain Communities
and an algorithm based on node embeddings
- [ComE](https://github.com/andompesta/ComE)

#### Datasets
We evaluated the algorithm in 5 real world Datasets
1. [Deezer](http://snap.stanford.edu/data/feather-deezer-social.html)
2. [Facebook](http://snap.stanford.edu/data/ego-Facebook.html)
3. [Twitch Gamers](https://snap.stanford.edu/data/twitch_gamers.html)
4. [Google Plus](http://snap.stanford.edu/data/ego-Gplus.html)
5. [Pokec](https://snap.stanford.edu/data/soc-Pokec.html)

---
A project by Christos Gkartzios <chgartzios@cs.uoi.gr> & Konstantinos Manolis <kmanolis@cs.uoi.gr> 
