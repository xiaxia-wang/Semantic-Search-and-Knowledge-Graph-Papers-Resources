






*2022-06-13*

#### [SAKey: Scalable Almost Key Discovery in RDF Data](https://doi.org/10.1007/978-3-319-11964-9_3)

*Danai Symeonidou, Vincent Armant, Nathalie Pernelle, Fatiha Saïs*

*ISWC 2014*

This paper introduces SAKey, an approach to efficiently compute almost keys in RDF datasets. In practice, erroneous or duplicate data often exists thus causing trouble for precise key identification. An $n$-almost key is a set of properties with exception sets whose size is no more than $n$. SAKey approach derives such almost keys based on $n$-non keys, and incorporates filtering and pruning methods. An $n$-non key means for the set of properties, there is an exception set with size $>n$. The experiments are conducted over three datasets, i.e., DBpedia, YAGO and OAEI, where SAKey is also compared with other key identification methods. 


*2022-06-12*

#### [ROCKER – A Refinement Operator for Key Discovery](https://doi.org/10.1145/2736277.2741642)

*Tommaso Soru, Edgard Marx, Axel-Cyrille Ngonga Ngomo*

*WWW 2015*

This paper proposes an algorithm named ROCKER for finding keys, which is sets of properties for uniquely describing resources in linked datasets. Given a set of properties, if all the resources in the dataset are distinguishable, such a set can be called a key. For all properties in a given dataset, it firstly presents a quasi-ordering relation over the power set of the properties, with a score for each set of properties representing the fraction of subject resources that are distinguishable. Then it introduces a refinement operator for gradually adding and refining the keys. The algorithm for identifying keys is presented based on a priority queue, and is evaluated over twelve datasets. 


*2022-06-11*

#### [Profiling and Mining RDF Data with ProLOD++](https://doi.org/10.1109/ICDE.2014.6816740)

*Ziawasch Abedjan, Toni Grütze, Anja Jentzsch, Felix Naumann*

*ICDE 2014*

This demo paper introduces ProLOD++, the extension of a previous prototype ProLOD (at ICDE Workshop 2010) for profiling RDF datasets. It presents three kinds of tasks for ProLOD++, i.e., profiling, mining, and cleansing. Compared with the previous version, it adds uniqueness analysis to the prototype for analyzing the predicate combinations and usages to uniquely represent an entity. It also implements rule-based analysis methods for fact auto-completion and prediction. 


*2022-06-10*

#### [LODStats – An Extensible Framework for High-Performance Dataset Analytics](https://doi.org/10.1007/978-3-642-33876-2_31)

*Sören Auer, Jan Demter, Michael Martin, Jens Lehmann*

*EKAW 2012*

This paper introduces a set of evaluation metrics of RDF datasets analytics. The metrics are statement-stream-based and on triple level. In this paper, it firstly introduces the use cases of dataset analytics. Then it proposes the definition and criteria for statistical metrics, and presents a total of 32 schema level statistical metrics. Finally it talks about the implementation as python package and metadata representations. 


*2022-06-09*

#### [ExpLOD: Summary-Based Exploration of Interlinking and RDF Usage in the Linked Open Data Cloud](https://doi.org/10.1007/978-3-642-13489-0_19)

*Shahan Khatchadourian, Mariano P. Consens*

*ESWC 2010*

This paper introduces a RDF summarization method named ExpLOD, based on RDF graph bisimulation. Given a RDF graph, it firstly applies (literal) bisimulation labels to each of the instances, predicates and classes, including the prefix, types of the node, etc. Then it hierarchically contracts the labeled graph to generate the summary. It also provides several ways to implement the summarization, such as PRAIG which is a automatic construction method, SPARQL query-based subgraph extraction, etc. In the experiment, ExpLOD is evaluated on several popular RDF datasets. Its different implementations are also compared. 


*2022-06-08*

#### [Profiling Linked Open Data with ProLOD](https://doi.org/10.1109/ICDEW.2010.5452762)

*Christoph Böhm, Felix Naumann, Ziawasch Abedjan, Dandy Fenz, Toni Grütze, Daniel Hefenbrock, Matthias Pohl, David Sonnabend*

*ICDE Workshops 2010*

This paper introduces a Web-based prototype system named ProLOD for profiling RDF datasets. The back-end involves three main processes. For each dataset, (1) Clustering and Labeling mainly pre-computes the clusters of the dataset based on predicate similarity, and assigns a human-readable label for each element. (2) Schema Discovery uses statistical-based rules and algorithms to identify relations between predicates and attributes, such as co-occurrence, exclusive, etc., and uses these identified relation to refine the clusters. (3) Data Types and Pattern Statistics mainly counts and presents the numbers of the elements and patterns. 


*2022-06-07*

#### [RDF graph summarization for first-sight structure discovery](https://doi.org/10.1007/s00778-020-00611-y)

*François Goasdoué, Pawel Guzewicz, Ioana Manolescu*

*VLDB J 2020*

This paper discusses about quotient-based RDF graph summarization. It firstly introduces the equality conditions between nodes, strong/weak relations, etc. Then it presents the methods and conditions to generate summaries for RDF graphs, and also discusses the relationship between RDF graph saturation and summarization. It presents some sufficient conditions for saturated graph summary to be isomorphic to the summary of saturated graph (although seems strict and naive). It also talks about the visualization of RDF graph summaries which is in E-R style, with numbers of instances, properties, and inline types of entities. 


*2022-05-29*

#### [Characterizing the Semantic Web on the Web](https://link.springer.com/chapter/10.1007/11926078_18)

*Li Ding, Tim Finin*

*ISWC 2006*

This paper analyzes the semantic Web environment based on the data and resources collected by Swoogle. It firstly presents a model for semantic Web, including concepts about RDF graphs and their provenances (i.e., Web documents and agents). Then it proposes an effective way for harvesting documents and applies them in Swoogle to collect and analyze SWDs. The collected data is then analyzed to show the increasing trend of SWDs, distribution of domains and sizes, etc., and summarized into global statistics and implications. 


*2022-05-28*

#### [Swoogle: Searching for Knowledge on the Semantic Web](https://www.aaai.org/Papers/AAAI/2005/ISD05-007.pdf)

*Timothy W. Finin, Li Ding, Rong Pan, Anupam Joshi, Pranam Kolari, Akshay Java, Yun Peng*

*AAAI 2005 Demo*

This paper mainly presents the architecture of Swoogle and its interaction flow between RDF graphs and the semantic Web Documents. The architecture of Swoogle consists four bottom-up layers, namely, discovery, digest, analysis and service. For the service part, Swoogle provides both search service for human users and an ontology dictionary for software agents. This paper also provides an agent access model through navigation and links between semantic Web terms, documents, and ontologies. 


*2022-05-27*

#### [Swoogle: A Search and Metadata Engine for the Semantic Web](https://doi.org/10.1145/1031171.1031289)

*Li Ding, Timothy W. Finin, Anupam Joshi, Rong Pan, R. Scott Cost, Yun Peng, Pavan Reddivari, Vishal Doshi, Joel Sachs*

*CIKM 2004*

This paper introduces an influential search engine prototype "Swoogle" for semantic Web documents (SWDs). It firstly introduces the system architecture, including four parts: SWD discovery, metadata creation, data analysis and interface. Then it presents an analysis about the retrieved documents and their metadata. By identifying six relations such as imports, previous version and assigning their weights, Swoogle computes PageRank scores for document ranking. It also applies some IR-based methods such as n-grams for document retrieving. Overall, Swoogle acts as a famous search engine for SWDs at that time. 


*2022-05-26*

#### [An Intelligent Linked Data Quality Dashboard](http://ceur-ws.org/Vol-2563/aics_32.pdf)

*Ramneesh Vaidyambath, Jeremy Debattista, Neha Srivatsa, Rob Brennan*

*AICS 2019*

This paper introduces a tool for helping the user understand the linked datasets and make quality assessments. The system architecture consists of a Web-based service wrapper, an analytical dashboard, a triplestore, and an existing quality assessment tool. It supports detection of a set of quality problems, mainly related to undefined or incorrect classes and properties.  The dashboard provides an overview of the quality metric scores with further details. Finally, the usability of dashboard is evaluated by real human users, including "experts" and "general users".


*2022-05-25*

#### [How Matchable Are Four Thousand Ontologies on the Semantic Web](https://doi.org/10.1007/978-3-642-21034-1_20)

*Wei Hu, Jianfeng Chen, Hang Zhang, Yuzhong Qu*

*ESWC 2011*

This paper presents an overview about how and to what extent do ontologies match with each other. The analysis starts from identifying term-level mappings. Based on Falcon-AO, term mappings are computed. An undirected term mapping graph is built, and statistical results are reported, such as the number and distribution of connected components. Then, based on the term mapping, a directed ontology mapping graph is similarly built and analyzed. Besides, also based on the terms, an undirected pay-level-domain mapping graph is built. The metrics used in this paper are mainly from the network analysis fields.


*2022-05-24*

#### [A Snapshot of the OWL Web](https://doi.org/10.1007/978-3-642-41335-3_21)

*Nicolas Matentzoglu, Samantha Bail, Bijan Parsia*

*ISWC 2013*

This paper builds a corpus of OWL ontologies and compares it with other existing ontology collections, and reports the statistical results with analysis. It firstly introduces basic concepts about OWL and its profiles. Then the pipeline of obtaining and curating ontologies is introduced. Ontologies are crawled from the Web, filtered to reduce errors or duplicates, and grouped into clusters. Each remaining OWL DL document is parsed, and analyzed by domain sources, syntax distributions, etc. This paper also compares the entity usage of the proposed corpora with existing ontology collections. 


*2022-05-23*

#### [An Empirical Study of Vocabulary Relatedness and Its Application to Recommender Systems](https://doi.org/10.1007/978-3-642-25073-6_7)

*Gong Cheng, Saisai Gong, Yuzhong Qu*

*ISWC 2011*

This paper discusses relatedness measurements for Semantic Web vocabularies. It firstly presents six metrics from four aspects, and proposes relatedness-based recommendation strategy using linear combination of the proposed metrics. Four main aspects are considered to reflect relatedness in this paper. (1) Explicit relations between vocabularies such as `owl:imports`. An edge-weighted graph is built to capture the number of relations between vocabularies. Relatedness is then computed from the length of shortest path between vocabularies. Similarly, another graph indicating implicit references is also built and used as the second metric. (2) Content similarity is mainly based on string overlaps of class and property labels between vocabularies. (3) Expressivity closeness is measured by the extent of meta-terms (e.g., super classes) overlaps. (4) Distributional relatedness uses cosine similarity between term co-occurrence vectors to measure the closeness between vocabularies. 


*2022-05-22*

#### [Summarizing semantic graphs: a survey](https://doi.org/10.1007/s00778-018-0528-3)

*Sejla Cebiric, François Goasdoué, Haridimos Kondylakis, Dimitris Kotzinos, Ioana Manolescu, Georgia Troullinou, Mussab Zneika*

*VLDB J 2019*

This survey paper presents a taxonomy for semantic graph summarization, with the approaches and applications. It firstly introduces basic concepts about semantic graphs, such as RDF, RDFS, OWL, and BGP query. Then it describes the scope of this paper, the usage of different summarization methods, and the classification for the methods. In this paper, summarization methods are categorized into 4 kinds, namely, structural, statistical, pattern-mining and hybrid. In the following sections, it discusses each kind of methods respectively, including generic graph (non-RDF) summarization, structural RDF summarization, pattern-based RDF summarization, statistical summarization, and others. 


*2022-05-21*

#### [Profiling relational data: a survey](https://link.springer.com/article/10.1007/s00778-015-0389-y)

*Ziawasch Abedjan, Lukasz Golab, Felix Naumann*

*VLDB J 2015*

This survey paper introduces tasks and approaches for profiling relational tables. It firstly identifies the usages for data profiling and illustrates its importance. Then it introduces profiling tasks including single-column profiling, multi-column profiling, dependency detection, storage, etc. In the following sections, it comprehensively reviews existing efforts for each profiling task along with the primary usages. After that, this paper summarizes existing profiling tools, and presents a discussion about next generation of profiling integration and non-relational data (e.g., RDF) profiling. Some of the approaches for relational data might also be applicable or extendable for non-relational data. 


*2022-05-19*

#### [RDF dataset profiling – a survey of features, methods, vocabularies and applications](https://content.iospress.com/articles/semantic-web/sw294)

*Mohamed Ben Ellefi, Zohra Bellahsene, John G. Breslin, Elena Demidova, Stefan Dietze, Julian Szymanski, Konstantin Todorov*

*Semantic Web 2018*

This is a comprehensive and important survey paper for RDF dataset profiling that worth reading for several times. It reviews 85 publications over the past 2 decades about RDF datasets. Following the introduction and description of the survey process, it firstly presents a taxonomy for dataset profile features, including 7 main categories. Then it provides a systematic overview of dataset profile extraction tools and approaches based on the taxonomy. The third part is an overview and a classification of vocabularies used to characterize dataset profiles. The fourth part proposes an illustration for the use of dataset profiles within the application contexts. 


*2022-05-17*

#### [Visual Querying LOD sources with LODeX](https://dl.acm.org/doi/10.1145/2815833.2815849)

*Fabio Benedetti, Sonia Bergamaschi, Laura Po*

*K-CAP 2015*

This paper introduces a visual query system for linked open datasets named LODeX. Based on the datasets available on Data Hub, LODeX identifies four main steps to process the datasets and incorporate them into the system. (1) Indexes extraction builds statistical indexes including the number of usages for each class, property, and the domain-range relations between them. Based on the indexes, (2) Schema summary generation aims at producing statistical summaries for schema elements, including classes, properties, attributes, their labels, and the mapping function between them. (3)  Schema summary visualization provides the user with node-link style visualized summaries. (4) Query orchestration supports the user to create query by selecting nodes, links and classes. The query will be automatically transformed into SPARQL query and perform. 


*2022-05-15*

#### [OptiqueVQS: a Visual Query System over Ontologies for Industry](https://content.iospress.com/articles/semantic-web/sw293)

*Ahmet Soylu, Evgeny Kharlamov, Dmitriy Zheleznyakov, Ernesto Jiménez-Ruiz, Martin Giese, Martin G. Skjæveland, Dag Hovland, Rudolf Schlatte, Sebastian Brandt, Hallstein Lie, Ian Horrocks*

*Semantic Web 2018*

This paper introduces a visual query system named OptiqueVQS, aiming at assisting the user to formulate structured queries over industrial ontologies. It firstly proposes three main challenges for such a system, including identifying common query types, identifying query, task, user types, and identifying quality attributes. Then it accordingly lists a set of requirements for expressivity (supporting which type of queries) and quality attributes (how to measure the system). It demonstrates the system by examples and illustrates the function of each component, and conducts user studies with human experts and ordinary users.


*2022-05-14*

#### [RDF Explorer: A Visual Query Builder for Semantic Web Knowledge Graphs](http://ceur-ws.org/Vol-2456/paper60.pdf)

*Hernán Vargas, Carlos Buil Aranda, Aidan Hogan*

*ISWC Satellites 2019*

This demo paper introduces a visual query builder that allows non-expert user to formulate SPARQL queries by adding nodes and links rather than directly editing in the text box. In this paper, the query creation process is explained with an example based on Wikidata. 


*2022-05-12*

#### [HIEDS: A Generic and Efficient Approach to Hierarchical Dataset Summarization](https://www.ijcai.org/Abstract/16/521)

*Gong Cheng, Cheng Jin, Yuzhong Qu*

*IJCAI 2016*

This paper introduces HIEDS, a hierarchical summarization method for RDF datasets. It applies a hierarchical grouping method for entities by property-value pairs in their descriptions. To form each hierarchical level, a property is selected, and entities are grouped by the values of the property. There are also links and overlapping entities between sibling subgroups. The problem is formulated as a multidimensional knapsack problem to achieve a balanced division with higher cohesion in each group. Then this NP-hard problem is solved by a greedy strategy.


*2022-05-11*

#### [Knowledge graph exploration: where are we and where are we going?](https://dl.acm.org/doi/10.1145/3409481.3409485)

*Matteo Lissandrini, Torben Bach Pedersen, Katja Hose, Davide Mottin*

*SIGWEB Newsletter 2020*

This paper surveys and summarizes the knowledge graph exploration techniques in existing work, and proposes a taxonomy of them over a spectrum. It categories the exploration techniques into three kinds, (1) Summarization and profiling, which requires no user interaction, personalization and no domain knowledge, and whose output is high level overview. (2) Exploratory analytics, which requires median-level interactivity and high-level information need, whose output is overview of specific aspects. (3) Exploratory search, which requires high interactivity, personalization and detailed sample or query intent, whose output is detailed answers. This taxonomy also categories more specific exploration tasks, and discusses potential future work directions.


*2022-05-09*

#### [RDF Data Storage and Query Processing Schemes: A Survey](https://dl.acm.org/doi/10.1145/3177850)

*Marcin Wylot, Manfred Hauswirth, Philippe Cudré-Mauroux, Sherif Sakr*

*ACM Computing Surveys 2018*

This survey paper introduces a taxonomy of linked data/RDF data management systems. Here, management means storage and querying. In this taxonomy, systems are firstly categorized into centralized and distributed ones, then divided into more specific kinds such as statement table, graph-based, etc. Each kind of systems are introduced with typical example systems. 


*2022-05-05*

#### [Estimating Characteristic Sets for RDF Dataset Profiles Based on Sampling](https://link.springer.com/chapter/10.1007/978-3-030-49461-2_10)

*Lars Heling, Maribel Acosta*

*ESWC 2020*

This paper discusses statistical profile features of RDF datasets. It proposes the concept of "characteristic set" which in fact is the set of properties used to describe each entity in the dataset. This paper mainly focuses on the count of such characteristic sets, and the multiplicity of some properties to profile the RDF dataset. To address the problem of large RDF datasets are not easy to straight-forwardly count the characteristic sets for all entities,  this paper proposes a solution by firstly sampling a small subset of triples, then estimating the overall counts using designed projection function. It tries several sample methods (by entities, by weighted triples, etc.) and statistics-enhanced projection methods. Finally, the paper is concluded by answering 4 research questions. 


*2022-05-04*

#### [Personalized Knowledge Graph Summarization: From the Cloud to Your Pocket](https://ieeexplore.ieee.org/document/8970788)

*Tara Safavi, Caleb Belth, Lukas Faber, Davide Mottin, Emmanuel Müller, Danai Koutra*

*ICDM 2019*

This paper proposes GLIMPSE, a summarization method to extract triples that best meet the user's potential interest from the original large knowledge graph. It relies on the user's history list of queries to implement a probabilistic-based sampling. It measures the importance of each entity from its query history and all its neighbors, and measures the importance of each triple both by the entities it contains and whether the triple itself has appeared in the query history. The paper also proves that the probabilistic-based sample framework is sub-modular. Therefore, a greedy algorithm is able to achieve a constant approximation ratio of (1 - 1/e). It further improves the time complexity by incorporating pruning process. Finally, it conducts experiments over large real-world knowledge graphs and achieves good performance. 


*2022-05-03*

#### [Structural Properties as Proxy for Semantic Relevance in RDF Graph Sampling](https://doi.org/10.1007/978-3-319-11915-1_6)

*Laurens Rietveld, Rinke Hoekstra, Stefan Schlobach, Christophe Guéret*

*ISWC 2014*

This paper introduces SampLD, an RDF graph sampling method aiming to select a subset of triples from the original large RDF dataset, while trying to retain the same ability to answer SPARQL queries as the original one. It relies on network analysis methods and statistical-based features, such as PageRank, in-degree and out-degree. SampLD firstly rewrites the graph, then analyzes it with network features, assigns node weights, and finally performs sampling from the ranked list of triples. This paper also conducts experiments over several large (in 2014) RDF datasets. 


*2022-05-02*

#### [Dataset Discovery in Data Lakes](https://ieeexplore.ieee.org/document/9101607)

*Alex Bogatu, Alvaro A. A. Fernandes, Norman W. Paton, Nikolaos Konstantinou*

*ICDE 2020*

It is a database style paper. This paper mainly studies the data discovery problem in a data lake, i.e., how to identify relevant datasets (for a given target dataset, if provided) from a bunch of large, mixed, complex datasets. It introduces a data lake as "a repository whose items are datasets about which, we assume, we have no more metadata than, when in tabular form, their attribute names, and possible domain-independent types." This paper proposes "D3L" for data discovery. The datasets discussed in this paper are tabular data. It proposes a locality-sensitive hashing-based method to index each table, including hashing attribute names, data values, attribute formats, etc. The hash value itself for each dataset can be regarded as an embedding, which can be used for computing distances between different datasets. It conducts experiments over synthetic table sets and real-world tables. At least two test collections are open-sourced.


*2022-05-01*

#### [Google Dataset Search by the Numbers](https://link.springer.com/chapter/10.1007/978-3-030-62466-8_41)

*Omar Benjelloun, Shiyu Chen, Natasha F. Noy*

*ISWC 2020*

Google Dataset Search (or Google DS in short) has developed for about 4 years since launched in 2018. This paper was published in 2020, which introduces an overview about the snapshot of Google Dataset Search at that time with a series of statistical distributions and numbers. Generally, Google DS relies on schema.org, DCAT and other similar vocabularies to identify datasets from Web pages. By analyzing the Web pages crawled by Google's general Web crawler, the pages with specific Semantic Web annotations and especially the information about datasets are extracted, downloaded and indexed. This paper analyzes these records, provides the distributions of datasets by domains, languages, topics, formats, vocabularies within the metadata, etc. It also proposes some suggestions for Semantic Web researchers about how to further improve the data reusability and interchangeability. 


*2022-04-30*

#### [The Trials and Tribulations of Working with Structured Data - a Study on Information Seeking Behaviour](https://dl.acm.org/doi/10.1145/3025453.3025838)

*Laura M. Koesten, Emilia Kacprzak, Jenifer Fay Alys Tennison, Elena Simperl*

*CHI 2017*

(Probably the first paper that let me know about Dr. Koesten.)

This paper studies information seeking behaviors of people, i.e., how people find data, make sense of them, obtain information from the data, and use them. The authors conducted two experiments for this purpose. One is a user study by interview, the other is a search log analysis of data.gov.uk. For the user study, the recruited participants were required to have data-centric tasks in their daily work, the interview was about their activities such as data collections, data analysis, etc. The search log was mainly statistically analyzed. The lengths and distributions of queries and sessions were reported. By analyzing the user study and statistical results, this paper concludes a framework with 4 steps in a data interaction process, and major tasks within each step.


*2022-04-28*

####  [Talking datasets - Understanding data sensemaking behaviours](https://www.sciencedirect.com/science/article/pii/S1071581920301646?via%3Dihub)

*Laura Koesten, Kathleen Gregory, Paul Groth, Elena Simperl*

*Journal of Human-Computer Studies 2021*

This is an interesting article discussing how people make sense of data and how to reuse them. Specifically, it mainly focuses on two research questions: (1) what are the common patterns of sense-making activities for people to know about data, (2) how do these sense-making patterns enable potential data reuse, like what will be needed for reusing the data. This paper is mainly based on a large, comprehensive user interview with 31 independent participants. The interview process was recorded and analyzed. Each participant was asked to provide a familiar dataset, and introduced it in the interview, then the interviewer would also provide a unfamiliar dataset to the participant and let the participant try to make sense of it and summarize its content, followed by some other questions about their opinion of data reuse, data sharing, etc. After analyzing the interview results, this paper also provides some suggestions about how to better understand, analyze, and reuse the data. 


*2022-04-27*

#### [Open data User Needs: A Preliminary Synthesis](https://dl.acm.org/doi/10.1145/3366424.3386586)

*Auriol Degbelo*

*WWW 2020*

This is a brief "survey" paper which aims to act as a starting point to analyze the open government data (OGD) usages and user needs. Mainly by reviewing existing papers about users' data needs, search behaviors, etc., it selects 7 representative papers which focus on user behaviors with data. It aggregates all discussed user need statements and re-categorizes them from different aspects. It follows the pattern: ‘[A user] needs [need] in order to accomplish [goal]’, to identify the needs and goals, divides them in different types (informational / transactional / navigational) of information needs, and summarizes them into 10 kinds of data needs as an open data user needs taxonomy. The table-1 is quite clear and informational. The paper also explains the usefulness of this work, e.g., for Web agents, Web mining, etc.


*2022-04-24*

#### [IDOL: Comprehensive & Complete LOD Insights](https://doi.org/10.1145/3132218.3132238)

*Ciro Baron Neto, Dimitris Kontokostas, Amit Kirschenbaum, Gustavo Correa Publio, Diego Esteves, Sebastian Hellmann*

*Semantics 2017*

This paper provides an analysis about some existing RDF dataset repositories, the datasets they contain, and their subsets and distributions. Some ideas are very close to ours. Firstly, they obtain real-world RDF datasets and repositories from several well-known websites or data sources, including DBpedia, LOD laundromat, CKAN.org, etc., and they explain the reasons and steps to process the data sources. Secondly, according to the pipeline in Section 4, they follow the way to (1) get and store the metadata, (2) get, store and process the datasets by triples, (3) modify and republish the datasets' metadata. They have also conducted the deduplication process among triples, which seems as to determine subset relations. They have implemented a "Bloom Filter" to check triple equality, which is an approximate hash function with guaranteed accuracy. The time and space costs seem to be relatively large, they also incorporate some optimizing methods. Finally they report the analysis results of the overall repositories and datasets (a total of 174 repositories and 13,237 datasets), provide counts and distributions about them. 


*2022-04-23*

#### [Quality assessment for Linked Data: A Survey](https://content.iospress.com/articles/semantic-web/sw175)

*Amrapali Zaveri, Anisa Rula, Andrea Maurino, Ricardo Pietrobon, Jens Lehmann, and Sören Auer*

*Semantic Web Journal, 2016*

I've read this paper when preparing the submission to theWebConf'21, at that time we wanted to implement some quality measurements for each dataset, to improve the re-ranking performance for the retrieved result datasets. Intuitively it was because "Relying only on links mined from metadata is far from enough, incorporating the content can add some links, but still not enough. So we needed some quality measurements to help improve ranking as a complement." For this paper, it indeed provides various metrics from 4 aspects, include: (1) accessibility, e.g., availability, licensing, (2) intrinsic dimensions, which mainly related to semantic accuracy and schema consistency, (3) contextual dimensions, which mainly related to the contextual task or user satisfactory, e.g., trustworthiness, understandability, timeliness, (4) representational dimensions, measuring if the dataset is typical and usable, e.g., w/ or w/o multi-language version. Besides, this paper also illustrates the relations between the 4 kinds of dimensions, and provides a comparison among all surveyed papers and tools of all the summarized quality dimensions. 