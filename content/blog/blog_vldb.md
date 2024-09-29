---
title: "VLDB’24 Trip Report"

tags: [ "conference", "database", "trip_report"]

date: "2024-09-29"

draft: false

---

The VLDB 2024 was held in Guangzhou, China, a city where I spent five years living for my bachelor’s. The conference lasted from 26th to 30th August and was held at the Langham Place Hotel, Pazhou, which is a new district in the city.



{{< figure src="../../../images/conf.jpg" alt="conference_room" caption="The VLDB'24 meeting room " class="center" width="400" >}}



Before attending the conference, I went through the list of presentations and have listed the ones that I am particularly interested in, mainly about LLMs for Data Management, Knowledge Graphs, Graphs, and Information Extraction. Doing research at the intersection of machine learning, data management, and knowledge graphs gives me the advantage of finding relevant works from different communities and conferences.  

From my experiences, I have the impression that the work at database conferences such as VLDB and SIGMOD is more engineering-oriented and practical. A lot of them focus on the impact and applicability to real-world applications. However, work on the semantic web or NLP conferences can be more theoretical. Of course, this only applies to the work that I am interested in, not the other topics within the field. From a PhD student’s perspective, this can also help them to navigate which community/conference they want to publish in, depending on their interests.

The conference was full of fun and great talks. LLMs are still hot topics. Unfortunately, quite a few papers that I marked interesting didn’t come to present at the conference (such as CHORUS: Foundation Models for Unified Data Discovery and Exploration). However, I still listened to a few and talked to a few demo authors. Furthermore, I have also listened to the tutorial on LLMs for Data Management. The talks have shown the LLM’s impressive capacity for solving tasks that were previously challenging and semantic-demanding. They also often show that relying on a one-time LLM call will not solve the task. You often need back-and-forth LLM calls or use LLMs as different modules. In my opinion, the works are similar to what others presented at SIGMOD’24 but extend to different tasks. 

There were also really cool demos, such as [DataLoom](https://www.vldb.org/pvldb/vol17/p4449-renen.pdf): Simplifying Data Loading with LLMs. The best thing about demos is that it is really cool to see things that **work**, and LLMs are making dreadful tasks much easier. The demo also shows there are many future improvements that can be applied to extend the tool to real-world applications. 
Similarly, I had a chat with the author of LLMs for Data Engineering on Enterprise Data, where they also studied data wrangling tasks on real-world tabular data from SAP. Results show that LLMs are still inadequate when it comes to complex real-world data without having domain knowledge, despite having good performance on toy datasets. 

I also found the GraphRAG tutorial presented at the LLMKG workshop quite interesting. GraphRAG has been a recent hot topic since Microsoft published their tool kit. I spent some time thinking about the more suitable scenarios and domains for using GraphRAG. KGs have the advantage of providing hierarchical information rather than unstructured texts. One solution for having better RAG-based models, especially when the contexts are long, is to summarize the contexts. In a way, we can see KGs as summarized contexts with relations between entities. In the tutorial, [NebulaGraph](https://www.nebula-graph.io/posts/graph-llm) presented their ways of building enterprise-specific GraphRAG. However, building high-quality KGs is still challenging, efficiently retrieving relevant KGs is also challenging. 

There were also some other notes coming up during the conference. When texting Till, we chatted about how posters can help people intuitively understand the paper in a shorter time. I thought it would be a great idea for the authors and conference to put up both the posters and paper online at the same time, which I think some researchers are already doing. 

There were many other interesting sparking conversations and I have met many interesting people from different institutes or companies. Overall, it has been a very good conference, especially when I was only there to learn (many many thanks to my supervisor). 

