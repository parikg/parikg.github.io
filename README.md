## Parikshit Gopalan's homepage

![Parikshit Gopalan](http://parikg.github.io/photo.jpeg)

---

**Brief Bio:** I am a machine learning researcher at [Apple](https://machinelearning.apple.com/) where I work on the foundations of machine learning. My current interests focus on the interplay between fairness, loss minimization and indistinguishability. I am also interested in questions related to calibration, detecting and measuring distribution drift and anomaly detection. 

I have broad interests in theoretical comuter science, including topics such as coding and information theory, pseudorandomness and computational complexity. On the applied side, I have worked on systems for storing and interactively visualizing large datasets and anomaly detection.  

In the past, I have been a researcher at [VMware Research](https://research.vmware.com/), [Microsoft Research](https://www.microsoft.com/en-us/research/) in Redmond and Silicon Valley, a graduate student at [Georgia Tech](https://aco.gatech.edu/) and an undergraduate at [IIT Bombay](https://www.cse.iitb.ac.in/). See my [C.V.](http://parikg.github.io/cv.pdf) for more details.

**Contact:** parikg at apple or gmail

--- 

# Selected Research Projects and Publications

**Loss minimization, fairness and indistinguishability:**
This project aims to reconcile three different perspectives on the goal of learning:
1. Loss minimization where the goal is to find a model that minimizes a certain loss.
2. Fairness, where the goal is to guarantee statiscal validity of the predictions for various subpopulations.
3. Indistinguishaility, where the goal is to produce predictions that are indistinguishable from the ground truth. 

Here are some papers on this topic
- [Omnipredictors](https://arxiv.org/abs/2109.05389) with Adam Tauman Kalai, Omer Reingold, Vatsal Sharan and Udi Wieder, appeared at ITCS'22.
- [Loss minimization through the lens of outcome indistinguishability]() with Lunjia Hu, Michael Kim, Omer Reingold and Udi Wieder, to appear at ITCS'23.

Here is a talk I gave at the [IAS TCSDM seminar](https://youtu.be/fUO7Mdew8Fk) in April, and a shorter version from the [TOC4fairness seminar](https://youtu.be/fwwNfdLCsNs).

**Locally Recoverable Codes:**
Motivated by applications in data storage, we intorduce the notion of the local recovery for an error correcting code , which allows the quick reconstruction of any single data symbol in the codeword, in the event of a single of few symbols being lost. We show fundamental tradeoffs between locality, distance and rate in a codeword, and construct optimal codes that achieve this tradeoff (LRCs). These codes were implemented in Microsoft Azure storage. 
1. The paper introducing the notion fo [Locality of a codeword symbol](https://arxiv.org/abs/1106.3625) with Cheng Huang, Huseyin Simitci and Sergey Yekhanin. This paper won the [2014 Information Theory/Communication Society joint paper prize](https://www.itsoc.org/honors/comsoc-information-theory-joint-paper-award).
2. The paper describing ther use of [LRCs in Azure Storage](https://www.usenix.org/system/files/conference/atc12/atc12-final181_0.pdf). This paper won the [Best Paper prize at USENIX ATC 2012](https://www.usenix.org/conference/atc12/technical-sessions).
3. The paper constructing [maximally recoverable LRCs](https://arxiv.org/abs/1307.4150?context=cs) with Cheng Huang, Bob Jenkins and Sergey Yekhanin. Maxmial recoverbaility is a beyond worst-case notion of reliability tailored towards data storage.


**Interactive data visulization via Hillview**


**Other selected publications**
