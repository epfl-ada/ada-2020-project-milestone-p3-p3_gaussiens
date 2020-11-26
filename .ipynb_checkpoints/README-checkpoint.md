## ADA p3_gaussiens

**Authors** :
- Diego Canton (259304)
- Sébastien Emery (258565)
- Richie Wan (258934)

# 1. Title 

**Analysing the influence of users in a Signed Network using graph centrality**

# 2. Abstract :
    In this creative extension, we propose to analyse the network in order to find communities. We posit that there are communities clustered around an influencial user, i.e. a group of "friends" centered around a "leader". Doing so, we aim to analyse whether a central user has influence on the vote of his community. Since the Wikipedia election dataset provides us with the time of an edge formation, we aim to predict whether all nodes within a cluster will vote the same. In the end, we will try to estimate the difference on multiple scales : global, local, individual and compare the different social theories.
    
## 1. Research Questions
    Do central nodes have influence on their clusters for Wikipedia election votes?
    As an extension, what social theory do the clusters follow between them for edge formation?
    Some individual nodes have many edges (600+), what (social theory) behaviour do these individuals follow?
    
## 2. Proposed Dataset
    Wikipedia election dataset
    
# 3. Methods
    Graph analysis : Find clusters and their "centers", using centrality, degree of connection, etc.
    Try to predict whether the whole cluster votes the same, or don't vote at all.
    
# 4. Proposed Timeline
    Code : Done by Sunday 6th December
    Analysis : Done by 11th December
    Video + Website/Report : Done by 18th December
    
# 5. Organization within the team

    Seb code + video
    Diego code + website
    Richie code + analysis

# 6. Questions for TAs (optional)
    Are there packages you would recommend besides networkX because that is VERY slow
    Otherwise add 3 days to code