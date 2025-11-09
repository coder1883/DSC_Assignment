# DSC_Assignment
This is a github repository to store my data science assignment
The answers are mentioned at the end of the assignment. So I am once again uploading it here as well.

Node 0 and 33 remain consistent across splits.

Betweenness centrality changes the most across splits. Nodes that act as bridges between groups lose betweenness when the graph is partitioned and those connections disappear.

Closeness centrality often increases for nodes that end up in small, tightly connected communities since distances between nodes decrease.

Degree centrality is mostly stable, because it depends only on immediate neighbors and does not change much across the splits.

Clustering coefficient often increases as clustering progresses, for nodes that become part of tightly connected communities, while it may decrease or remain stable for nodes that lose connections or remain peripheral.

Community structure has a strong impact on how we interpret node importance. A node may look central in the full graph but lose influence after separation, or may become more central inside its own smaller, cohesive subcommunity.