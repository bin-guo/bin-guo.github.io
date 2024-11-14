# About Me
I am an assistant professor at the Computer Science Department of [Trent University](https://www.trentu.ca/cois/) starting in Jan. 2024. Also, I am an adjunct assistant professor at the Computing & Software Department of [McMaster University](https://www.eng.mcmaster.ca/cas/). Before that, I was a postdoctoral fellow at [McMaster University](https://dailynews.mcmaster.ca/) from May 2023 to Dec. 2023. I obtained my Ph.D. degree in Computer Science from [McMaster University](https://dailynews.mcmaster.ca/) in May 2023. I obtained my Master's degree in Applied Computer Science from [Winnipeg University](https://www.uwinnipeg.ca/) in May 2018. 

My research area mainly focused on parallel and distributed computing, especially on graph algorithms and graph mining. Recently, I have been interested in computer security for data graph analytics. My favorite conferences are ICPP, SPAA, PPoPP, VLDB, and ICDE. My favorite journals are [The Journal of Supercompouting](https://link.springer.com/journal/11227) and [IEEE Transactions on Parallel and Distributed Systems (TPDS)](https://www.computer.org/csdl/journal/td).


I work at the Peterborough campus of Trent University in person; my Email address is [binguo\[at\]trentu.ca](mailto:binguo@trentu.ca) and my name on the department website is [here](https://www.trentu.ca/cois/faculty-research). As an adjunct assistant professor at McMaster University, my Email address is [guob15\[at\]mcmaster.ca](mailto:guob15@mcmaster.ca) and my name on the department website is [here](https://www.eng.mcmaster.ca/cas/people/adjuncts-and-associates/).

<span style="color:red; font-size:20px;">Currely, I am recruiting highly motivated Master's and PhD students! For details see my section "Recruit Students".</span> 



---

# Trent University 

Trent University is a public liberal arts university in Peterborough, Ontario, with a satellite campus in Oshawa, which serves the Regional Municipality of Durham. Trent is known for its Oxbridge college system and small class sizes. 

As a collegiate university, Trent is made up of five colleges. Each college has its own residence halls, dining rooms, and student government. The student government (Cabinet) and its committees cooperate with the College Office and dons in planning and delivering a variety of events for both its non-resident and resident members: visiting scholars, artists, musicians, and scientists; College dinners and dances; Fall and Winter College Weekend; and intramural co-educational competitions in a number of sports. Although Trent University is predominantly undergraduate, graduate programs are offered at the master's and doctoral levels.

The Symons campus of Trent, named after founding president Thomas Symons, is located on the banks of the Otonabee River at the northeast corner of the City of Peterborough. The Symons campus plan and its original college buildings, including Champlain College, Lady Eaton College, Bata Library, Chemistry Building, and the Faryon bridge which spans the Otonabee, were designed by Canadian architect Ron Thom.

Over 9 000 undergraduate students and over 800 graduate students are enrolled at the Peterborough campus while Trent University Durham GTA serves over 1 900 full- and part-time students at the campus on Thornton Road in Oshawa. The university is represented in Canadian Interuniversity Sport by the Trent Excalibur.
See [Wiki](https://en.wikipedia.org/wiki/Trent_University).  


## 1) Computer Science Master's Program
Currently, Trent University has a master's program in Computer Science under the [Applied Modelling and Quantitative Methods](https://www.trentu.ca/amod/). This is an interdisciplinary program that leads towards an M.Sc. or M.A. degree in the application of techniques and theory of modelling in the natural sciences and social sciences. It encompasses the following traditional disciplines: Biology, Business Administration, Chemistry, **Computer Science**, Economics, Geography, Humanities, Mathematics, Philosophy, Physics & Astronomy, and Psychology. The program is designed to overcome some of the barriers to interdisciplinary collaboration by bringing together, at the graduate level, students who are actively applying modelling techniques in their thesis research in a broad range of disciplines. The research is in the social and natural sciences, and in fields in which Trent has demonstrated strong research performance. Although it is oriented towards quantitative models, utilizing computational, mathematical, or statistical techniques, it is discipline-based and is not a program in applied mathematics. 

Our Computer Science department recruits master's students under the **Applied Modelling and Quantitative Methods** program. If you apply to this program, you would like to be a master's student in Computer Sciences. The detailed qualification for **Applied Modelling and Quantitative Methods** is [here](https://www.trentu.ca/graduatestudies/sites/trentu.ca.graduatestudies/files/documents/Programs%20at%20a%20Glance%20from%20TrentU_GradStudies_Viewbook2023_Digital%5B65%5D.pdf). If your first language is not English or you do not have study experience at English countries, you should have **IELTS** (International English language Testing Services) and the minimum acceptance score is **6.5** with no band below **6.0**. The detailed proof of English Language is [here](https://www.trentu.ca/graduatestudies/how-apply/international-applicants).

<span style="color:red; font-size:20px;">Good News!</span>  Currently, more and more master's students joining our Master's program. We are planning to set up our own independent Computer Science Master's program, which is not under AMOD. This program will include course-based and thesis-based, like other Canadian Universities. The process may cost half to one year.

---

# Research Projects
My research interest lies broadly in graphs. Graphs are important data structures that have many applications, such as social networks, weblink networks, and biological networks. Specifically, I study many kinds of graph algorithms in parallel and distributed computing. My Ph.D. studies focus on parallel algorithms of k-core decomposition and maintenance on shared memory multi-core machines. My recent research focuses on parallel or distributed algorithms in terms of graph queries and graph mining. The below two pictures show an example of social networks.  

<!--
<img align="center" width="400" src="assets/social-network.jpg">
<img align="center" width="400" src="assets/graph-data.jpeg">
-->

<table>
<tr>
<td>

<img align="center" width="400" src="assets/social-network.jpg">

</td>
<td>

<img align="center" width="400" src="assets/graph-data.jpeg">

</td>
</tr>
</table>

Here are several research projects that I am currently doing or plan to do:

## 1) Parallel Graph Algorithms
The traditional sequential graph algorithms need to be parallelized. The multi-core shared memory architectures are prevalent in recent years. We design parallel graph algorithms that can execute on multi-core CPUs, e.g. AMD Ryzen Threadripper 3990X with 64 cores, to achieve good speedups. For details, you can read my selected papers: 
* [Parallel Order-Based Core Maintenance in Dynamic Graphs](https://dl.acm.org/doi/abs/10.1145/3605573.3605597). This paper has been published at the top conference, the 52nd International Conference on Parallel Processing (ICPP 2023). It proposes a parallel algorithm of core maintenance, which is an important graph algorithm and has many applications. 
* [Efficient parallel graph trimming by arc-consistency](https://link.springer.com/article/10.1007/s11227-022-04457-9). This paper has been published in the Journal of Supercomputing.

## 2) Distributed and Federated Graph Algorithms 
The traditional distributed graph algorithms tend to use centralized servers for synchronization and never consider data privacy & security. We try to improve these distributed algorithms by using decentralized methods and protecting private information, so-called federated algorithms. Currently, I am working on the Federated Core Maintenance Problems. 

## 3) Computer Security and Privacy
Our research on graph algorithms can be extended to privacy and security. The problem is to design algorithms that can finish the calculation without leaking users' private information. 



---

# Recruit Students

## 1) Master's Students at Trent University
If you want to apply the course-based program like Big Data, you can directly apply without a supervisor. 

I am seeking highly motivated and dedicated Master's students (thesis-based computer science stream) starting from Winter 2024. Before connecting with me, you must satisfy the basic requirement of our department, e.g, minimum GPA 77% in last 10 credits and IELTS 6.5 with no band below 6.0. 

Prospective candidates should have a background in __data structure and algorithms__ (especially on graphs), __parallel computing__, and C/C++ programming experience. __If you do not have such a background or your major is not computer science, it does not matter__; we still can talk and make a good research plan. During your master's studies, you will do experiments (mostly C++ programming) and finish a thesis. You will have the opportunity to work closely with me and collaborate with our team members.

Here is the [School of Graduate Studies](https://www.trentu.ca/graduatestudies/) and you can apply for [Applied Modelling and Quantitative Methods](https://www.trentu.ca/graduatestudies/sites/trentu.ca.graduatestudies/files/documents/Programs%20at%20a%20Glance%20from%20TrentU_GradStudies_Viewbook2023_Digital%5B65%5D.pdf), as our master program of Computer Science is under such program (see my front introduction to Trent University). If you are interested in **thesis-based**, you must find a supervisor to finish a research thesis and I am happy to be your supervisor; please send me an email including your CV, transcripts, and what kinds of research you would like to do. If you are interested in **course-based**, you must finish courses and do a project and you can directly apply. 

### Thesis-based AMOD program Funding and Tuition Fee
For the coming years, I am sure that our AMOD program will provide a fixed amount of funding for thesis-based master's students as the following table. 

|Source of Funding | Year 1 (2024-2025)| Year 2 (2025-2026)|
|---	|---	|---	|
|Graduate Teaching Assistantship| $11,515.91 | $11,515.91|
|Graduate Research Fellowship |$4,500 |$4,500|
|Research Fellowship Award <br /> (optional from the Supervisor)| | |
|Total Funding |$16,015.91 | $16,015.91|

The [tuition fee](https://www.trentu.ca/graduatestudies/financial-matters/student-account-and-tuition/research-and-thesis-based-program-fees) for international students is very high, around $24,806 per academic year. I am actively applying for funding; if I obtain the funding, I could provide $5,000 to $10,000 per academic year. Such funding can provide you with lots of financial support. 

For domestic students (including those who have PR), the [tuition fee](https://www.trentu.ca/graduatestudies/financial-matters/student-account-and-tuition/research-and-thesis-based-program-fees) is $9,196 (Ontario) or $10,569 (Other Canadia) per academic year. Also, domestic students can apply to the [OSAP](https://www.ontario.ca/page/osap-ontario-student-assistance-program) (grants and loans, mostly no interest); the amount can be higher if you have lower income and funding, which can cover basic living fee.  

If you are interested, please send me your CV and a proposal to my [email](mailto:binguo@trentu.ca). I am happy to be your supervisor. 

## 2) Master's Student at McMaster University
Since I am an adjunct member at McMaster University, I am also seeking Master's students at McMaster University. There are two steam: MEng and MSc

For the [MEng](https://www.eng.mcmaster.ca/cas/degree-options/computing-and-software-meng/) program, you will study at McMaster and I can be your co-supervisor. __You may not get the funding.__ Students must successfully complete six half (one-term) graduate courses and an independent project demonstrating the ability to carry out independent studies and reach a satisfactory conclusion in an area of Computing and Software.

Also, for the [MSc](https://www.eng.mcmaster.ca/cas/degree-options/computer-science-msc/) program, you will study at McMaster and I can be your co-supervisor. __You are possible to get the funding and we can discuss the details if you are interested.__ Student must successfully complete four half (two-term) graduate courses and a high-quality independent master's thesis. 

If you are interested, please send me your CV and a proposal to my [email](mailto:binguo@trentu.ca). I am happy to be your co-supervisor. 

## 3) PhD Students at McMaster University

I am also recruiting PhD students. Since I am an adjunct member at McMaster University and Trent does not have a Computer Science PhD program, I can collaborate with the [Computing and Sofware Department at McMaster University](https://www.eng.mcmaster.ca/cas/programs/degree-options/phd-computer-science/) as a cosupervisor. That means you are McMaster's PhD students; you have a supervisor at McMaster and me as a cosupervisor. 


At McMaster University, the Computing and Software department will provide many funding or scholarship opportunities; I can also provide part of the funding to support you. The funding will be enough to pay for tuition fees and basic living expenses (the international students will get the same support). 

If you are interested, please send me your CV and a proposal to my [email](mailto:binguo@trentu.ca). I am happy to be your supervisor. 

## 4) International Students

Finally, if you like living in Canada, I encourage **international students** to apply for the master's and PhD programs. 
After graduating, you can apply for a [nomination for permanent residence in Ontario](https://www.ontario.ca/page/oinp-masters-graduate-stream), if you have a master's or PhD degree from an Ontario university.

---

# My Students

## 1) Current Students
Summer Student:
* Issec Lee, summer student at Trent, 2024, Experimental Evaluation of Multi-CAS in Concurrency.
  
Master: 
* R.Z. Zhao, MEng at McMaster University (Cosupervise with Dr. Emil Sekerinski), 2023 - now,  Experimental Evaluation of Distributed Core Decomposition.


---

# Teaching 

At Trent University: 
- COIS-3320H: Fundamentals of Operating Systems \[Winter 2024\]
- COIS-4370H: Computer and Information Security \[Winter 2024\]
  
At McMaster University:
- COMPSCI 1MD3: Introduction to Programming \[Spring 2023\] 
- COMPSCI 1DM3: Discrete Mathematics for Computer Science\[Winter 2022\]
- SFWRENG 3BB4: Concurrent System Design \[Fall 2021\]

---

# Selected Publication
My full publication list is on the [Google Scholar](https://scholar.google.com/citations?user=m3ONACQAAAAJ&hl=en). All papers have the arXiv version for reading. 
Here is my thesis and selected important publication. 

## 1) Preprint


- Guo, Bin; Sekerinski, Emil; Chu, Lingyuang. "Federated k-Core Decomposition: A Secure Distributed Approach" [Full paper](https://arxiv.org/pdf/2410.02544), P[Poster on CASCON 24](publication/CASCON/cascon24-poster.pdf)

## 2) Conference
- Guo, Bin; Sekerinski, Emil. "New Parallel Order Maintenance Data Structure" PCDS(2024). [Presentation pdf](publication/PCDS2024/PCDS-BinGuo.pdf), [Presentation ppt](publication/PCDS2024/PCDS-BinGuo.pptx), [PCDS paper](publication/PCDS2024/PCDS-BinGuo.pdf), [full paper](https://arxiv.org/pdf/2208.07800)
  - Useful links: [A Lock-Free, Parallel Order Maintenance Data Structure for Multicore Systems](https://linnk.ai/insight/algorithms-and-data-structures/a-lock-free-parallel-order-maintenance-data-structure-for-multicore-systems-OoKVQTjU/)

- Guo, Bin, and Emil Sekerinski. "Parallel order-based core maintenance in dynamic graphs." ICPP (2023). [arXiv pdf](https://arxiv.org/pdf/2210.14290.pdf), [Presentation ppt](publication/icpp2023/icpp23-2.pptx), [Presentation pdf](publication/icpp2023/icpp23-2.pdf), [Poster pdf](publication/icpp2023/icpp23-poster.pdf), [Full Paper](publication/icpp2023/paralle-om-full-paper.pdf), [ICPP paper](publication/icpp2023/parallel-om-icpp.pdf).

- Guo, Bin; Nagy, Jason; Sekerinski, Emil; 	Universal Design of Interactive Mathematical Notebooks on Programming,	Proceedings of the 53rd ACM Technical Symposium on Computer Science Education V. 2			1132-1132	2022, [pdf](publication/sigcse2022.pdf)



## 3) Journal
- Guo, Bin; Sekerinski, Emil; 	"Simplified Algorithms for Order-Based Core Maintenance" The Journal of Supercomputing (2024) [springer](https://link.springer.com/article/10.1007/s11227-024-06190-x?utm_source=rct_congratemailt&utm_medium=email&utm_campaign=nonoa_20240528&utm_content=10.1007/s11227-024-06190-x), [pdf](publication/SC/Simplified.pdf)
  
- Guo, Bin, and Emil Sekerinski. "Efficient parallel graph trimming by arc-consistency." The Journal of Supercomputing 78.13 (2022): 15269-15313. [springer](https://link.springer.com/article/10.1007/s11227-022-04457-9), [pdf](publication/SC/Efficient.pdf)
  
- Chen, Yangjun; Guo, Bin; Huang, Xingyue; 	δ-Transitive closures and triangle consistency checking: a new way to evaluate graph pattern queries in large graph databases	The Journal of Supercomputing	76		8140-8174	2020	Springer US, [pdf](publication/SC/Transitive.pdf)

## 4) Thesis 
- MULTI-CORE PARALLEL GRAPH ALGORITHMS. Bin Guo. PhD Thesis. 2023. [Thesis pdf](https://macsphere.mcmaster.ca/bitstream/11375/28562/2/Guo_Bin_2023May_PhD.pdf), [Defense Slides ppt](publication/thesis/Defense-2.pptx), [Defense slides pdf](publication/thesis/Defense-2.pdf)

- On the Evaluation of Pattern Match Queries in Large Graph Databases. Bin Guo. Master Thesis. 2018 [Thesis pdf](https://winnspace.uwinnipeg.ca/bitstream/handle/10680/1997/Guo_Bin_final_thesis.pdf?sequence=1), [Defense Slides ppt](publication/thesis/defence-V1.5.pptx), [Defense slides pdf](publication/thesis/defence-V1.5.pdf)






