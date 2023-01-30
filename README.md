# Parikshit Gopalan's homepage
---


I am a machine learning researcher at [Apple](https://machinelearning.apple.com/) where I work on the foundations of machine learning. I aspire to do fundamental theoretical research that impacts practical problems. My current focus is on the interplay between multigroup fairness, loss minimization and indistinguishability. I am also interested in questions related to calibration, distribution drift and anomaly detection. 

I have broad interests in theoretical computer science, having worked on coding and information theory, pseudorandomness and computational complexity. On the applied side, I have worked on systems for storing and interactively visualizing large datasets. 

In the past, I have been a researcher at [VMware Research](https://research.vmware.com/), [Microsoft Research](https://www.microsoft.com/en-us/research/) in Redmond and Silicon Valley, a graduate student at [Georgia Tech](https://aco.gatech.edu/) and an undergraduate at [IIT Bombay](https://www.cse.iitb.ac.in/). See my [C.V.](http://parikg.github.io/cv.pdf) for more details.

**Contact:** parikg at apple or gmail

For a full list of publications, see my [C.V.](http://parikg.github.io/cv.pdf), [dblp page](https://dblp.org/pid/16/1585.html) or [google scholar page](https://scholar.google.com/citations?user=fb2-dasAAAAJ&hl=en&oi=ao).

--- 

## Selected Research Projects


**Loss minimization, fairness and indistinguishability:**

This project aims to reconcile three different perspectives on the goal of learning:
1. Loss minimization where the goal is to find a model that minimizes a certain loss.
2. Fairness, where the goal is to guarantee statistical validity of the predictions for various subpopulations.
3. Indistinguishability, where the goal is to produce predictions that are indistinguishable from the ground truth. 

Some papers on this topic which explore connections and tradeoffs between these notions:
- [Omnipredictors](https://arxiv.org/abs/2109.05389) with Adam Tauman Kalai, Omer Reingold, Vatsal Sharan and Udi Wieder, appeared at ITCS'22.
- [Low-degree multicalibration](https://arxiv.org/abs/2203.01255) with Michael P. Kim, Mihir Singhal, Shengjia Zhao, appeared at COLT'22. 
- [Loss minimization through the lens of outcome indistinguishability](https://arxiv.org/abs/2210.08649) with Lunjia Hu, Michael P. Kim, Omer Reingold and Udi Wieder, to appear at ITCS'23.

Here is a talk I gave at the [IAS TCSDM seminar](https://youtu.be/fUO7Mdew8Fk) in April, and a shorter version from the [TOC4fairness seminar](https://youtu.be/fwwNfdLCsNs). Also, [this talk by Omer Reingold](https://toc4fairness.org/good-research-karma-the-unexpected-benefits-of-striving-for-algorithmic-fairness/) gives a good high-level introduction to the area. 

---

**Erasure Coding for distributed storage:**

Motivated by applications in data storage, we introduce the notion of local recovery for an error correcting code, which allows the quick reconstruction of any single data symbol in the event of a single of few symbols being lost. We show fundamental tradeoffs between locality, distance and rate in a codeword, and construct optimal codes that achieve this tradeoff (LRCs). These codes were implemented in Microsoft Azure storage. 
1. The paper introducing the notion of [Locality of a codeword symbol](https://arxiv.org/abs/1106.3625) with Cheng Huang, Huseyin Simitci and Sergey Yekhanin. This paper won the [2014 Information Theory/Communication Society joint paper prize](https://www.itsoc.org/honors/comsoc-information-theory-joint-paper-award).
2. The paper describing their use of [LRCs in Azure Storage](https://www.usenix.org/system/files/conference/atc12/atc12-final181_0.pdf). This paper won the [Best Paper prize at USENIX ATC 2012](https://www.usenix.org/conference/atc12/technical-sessions).
3. An press article from Microsoft on the use of [LRCs in Azure](https://www.microsoft.com/en-us/research/blog/better-way-store-data/). [Another article](https://www.microsoft.com/en-us/research/blog/the-code-that-no-one-in-the-cloud-can-live-without/) from Microsoft.
4. A paper constructing [maximally recoverable LRCs](https://arxiv.org/abs/1307.4150?context=cs) with Cheng Huang, Bob Jenkins and Sergey Yekhanin. Maximal recoverability is a beyond worst-case notion of reliability tailored towards data storage. Another paper exploring this notion for [grid-like topologies](https://arxiv.org/abs/1605.05412) with Guangda Hu, Swastik Kopparty, Shubhangi Saraf, Carol Wang, Sergey Yekhanin.

A two-part tutorial I gave on this topic from a bootcamp at the Simons institute: [part 1](https://youtu.be/-UvC5YxYprs) and [part 2](https://youtu.be/knsbJO7yf70).

---

**Interactive data visualization via Hillview**

[Hillview](https://research.vmware.com/projects/hillview) is an open-source tool for fast interactive visualization and exploration of massive data sets using just the click of a mouse. HillView combines a distributed, parallel computation platform with highly optimized sketching and sampling algorithms for fast renderings. 
- [Paper on Hillview](https://arxiv.org/abs/1907.04827) with Mihai Budiu, Lalith Suresh, Udi Wieder, Han Kruiger and Marcos Aguilera appeared at VLDB 2018.
Code is available from [GitHub](https://github.com/vmware/hillview). 
- [Overlook](https://research.vmware.com/publications/overlook-differentially-private-exploratory-visualization-for-big-data) adds a differential privacy layer to Hillview. [Paper on Overlook](https://arxiv.org/abs/2006.12018) with Pratiksha Thaker, Mihai Budiu, Udi Wieder and Matei Zaharia, appeared in the Journal of Privacy and Confidentiality. 

---
---


## Other Recent ML Publications

- [A Unifying Theory of Distance from Calibration](https://arxiv.org/abs/2211.16886) with Jaroslaw Blasiok, Parikshit Gopalan, Lunjia Hu, Preetum Nakkiran (under submission).
- [KL divergence estimation with multigroup attribution](https://arxiv.org/abs/2202.13576) with Nina Narodytska, Omer Reingold, Vatsal Sharan, Udi Wieder (under submission).
- [Multicalibrated Partitions for Importance Weights](https://arxiv.org/abs/2103.05853) with Omer Reingold, Vatsal Sharan, Udi Wieder (ALT'22).
- [PIDForest:Anomaly Detection via Partial Identification](https://arxiv.org/abs/1912.03582) with Vatsal Sharan and Udi Wieder. (Neurips'18 spotlight).

--- 

## Other selected publications

- [Degree and sensitivity: tails of two distributions](https://arxiv.org/abs/1604.07432) with Rocco A. Servedio and Avi Wigderson (CCC'16).
- [Better pseduorandom generators from milder pseudorandom restrictions](https://arxiv.org/abs/1210.0049) with Raghu Meka, Omer Reingold, Salil Vadhan
  and Luca Trevisan (FOCS'12). 
- [Making the Long code shorter](https://arxiv.org/abs/1111.0405v1) with Boaz Barak, Johan Hastad, Raghu
  Meka, Prasad Raghavendra and David Steurer (FOCS'12).
- [DNF Sparsification and a faster deterministic counting algorithm](https://arxiv.org/abs/1205.3534) with Raghu Meka and Omer Reingold (CCC'12).
- [Matching Vector Codes](https://oar.princeton.edu/bitstream/88435/pr1kv6j/1/MatchingVectorCodes.pdf) with Zeev Dvir and Sergey Yekhanin (FOCS'10).
- [Finding duplicates in a data stream](https://dl.acm.org/doi/10.5555/1496770.1496815) with the one and only Jaikumar Radhakrishnan (SODA'09).
- [Bounded independence fools halfspaces](https://arxiv.org/abs/0902.3757) with Ilias Diakonikolas, Ragesh Jaiswal, Rocco Servedio and Emanuele Viola (FOCS'08).
- [List-Decoding Reed-Muller codes over small fields](https://www.cs.utexas.edu/~klivans/rm.pdf) with Adam R. Klivans and David Zuckerman (STOC'08).
- [On agnostic learning of parities, monomials and halfspaces](https://cs.nyu.edu/~khot/papers/hs-parity-monomial_SIAM.pdf) with Vitaly Feldman, Subhash Khot and Ashok Ponnuswami (FOCS'06).  

---
---

## Interns mentored: 

I have been fortunate to work with several fabulous interns over the years:
- Yi Wu, Carnegie Mellon University, now at Google (2009).
- [Raghu Meka](https://hackmd.io/@raghum/index), University of Texas at Austin, now at UCLA. (2010, 2011).
- [Yuan Zhou](https://yuanz.web.illinois.edu/), Carnegie Mellon University, now at UIUC. (2012).
- Abhishek Bhowmick, University of Texas at Austin. (2013).
- [Li-Yang Tan](http://theory.stanford.edu/~liyang/), Columbia University, now at Stanford University. (2014).
- [Vatsal Sharan](https://vatsalsharan.github.io/), Stanford University, now at USC. (2017, 2020).
- [Michael P. Kim](https://cs.stanford.edu/~mpkim/), Stanford University, currently Miller fellow at UC Berkeley (2017).
- [Roie Levin](https://roielevin.com/), CMU, currently Fullbright postdoctoral fellow at Tel-Aviv Univeristy (2019).
- [Shivam Garg](https://cs.stanford.edu/people/shivamg/), Stanford (2021).
- Mihir Singhal, MIT (2021).
- [Lunjia Hu](https://sites.google.com/stanford.edu/lunjia), Stanford (2022).
