## ADA p3_gaussiens

**Authors** :
- Diego Canton (259304)
- Sébastien Emery (258565)
- Richie Wan (258934)

# 1. Title 

**Birds of a feather**

# 2. Abstract :
    In this creative extension, we propose to analyse the network in order to find communities. We posit that there are communities clustered around an influencial user, i.e. a group of "friends" centered around a "leader". Doing so, we aim to analyse whether a central user has influence on the vote of his community. Since the Wikipedia election dataset provides us with the time of an edge formation, we aim to predict whether all nodes within a cluster will vote the same. In the end, we will try to estimate the difference on multiple scales : global, local, individual and compare the different social theories.
    
## 1. Research Questions
    Do central nodes have influence on their clusters for Wikipedia election votes?
    As an extension, what social theory do the clusters follow between them for edge formation?
    Some individual nodes have many edges (600+), what (social theory) behaviour do these individuals follow?
    
## 2. Proposed Dataset
    Wikipedia election dataset
    
    Update:

    Wikipedia
    Epinions dataset
    Slashdot dataset
    
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

    Update: Contrary to what we tought, we spent most of our time looking for a coherent analysis around our datasets. Our first idea was to analysis behavior and influence of centralized nodes in the wikie elections and check how their vote would influence results of election. However, to be able to characterize the influence of such node, we would have needed the real relationship between nodes, here the voting behavior was a significant value to infer on relation between nodes (users). Thus, the main part of our project was to find a coherent analysis and to really understand the meaning of the different values used to characterize influence, centrality and behavior between nodes. This research part was perfromed equally by all group members and finally agreed to change the dataste and look into the analysis of homophily in epinions and slashdot datasets. The coding part also. Then we divided the work to write the Datastory, explain the analysis and compile a notebook with our different researchs. 

# 6. Questions for TAs (optional)
    Are there packages you would recommend besides networkX because that is VERY slow
    Otherwise add 3 days to code