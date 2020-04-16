# genomics-study-group

This is a self-study guide for learning genomic signal processing. Before we can learn GSP, we must understand the foundations of information theory and sequential sequence procesing- the fundamentals upon which genomic data science is based.


## Subject definitions
- [DNA Sequencing](https://en.wikipedia.org/wiki/DNA_sequencing) is the process of determining the nucleic acid sequence – the order of nucleotides in DNA. It includes any method or technology that is used to determine the order of the four bases: adenine, guanine, cytosine, and thymine. The advent of rapid DNA sequencing methods has greatly accelerated biological and medical research and discovery.

- [Sanger Sequencing](https://en.wikipedia.org/wiki/Sanger_sequencing) is a method of DNA sequencing. Developed by Frederick Sanger and colleagues in 1977, it was the most widely used sequencing method for approximately 40 years.  More recently, higher volume Sanger sequencing has been replaced by ["Next-Gen" sequencing methods](https://www.illumina.com/content/dam/illumina-marketing/documents/products/illumina_sequencing_introduction.pdf).

- [Systems Biology](https://en.wikipedia.org/wiki/Systems_biology): Systems biology is the computational and mathematical modeling of complex biological systems. It is a biology-based interdisciplinary field of study that focuses on complex interactions within biological systems, using a holistic approach (holism instead of the more traditional reductionism) to biological research.

- [Genomics wikipedia](https://en.wikipedia.org/wiki/Genomics) Genomics is an interdisciplinary field of science focusing on the structure, function, evolution, mapping, and editing of genomes. A genome is an organism's complete set of DNA, including all of its genes. In contrast to genetics, which refers to the study of individual genes and their roles in inheritance, genomics aims at the collective characterization and quantification of genes, which direct the production of proteins with the assistance of enzymes and messenger molecules.

- [Genomic Signal Processing](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2766787/): defined by Edward Dougherty. Genomic Signal Processing (GSP) has been defined as the analysis, processing, and use of genomic signals for gaining biological knowledge and the translation of that knowledge into systems-based applications, where by genomic signals we mean the measurable events, principally the production of mRNA and protein carried out within the cell. Owing to the defining role of DNA in the production of mRNA, the structural characterization of DNA is inevitably a part of GSP and, interestingly, signal processing methods are utilized in understanding DNA structure.

## Videos

- [Careers in Bioinformatics and Precision Medicine - Career Development Week](https://youtu.be/UuSFWlohYEg): by Semyon Kruglyak. Precision medicine integrates molecular and clinical research with patient data and outcomes, aiming to place the patient at the center of all elements. In this emerging field, bioinformatics is a core technology. Learn how bioinformatics has evolved to deal with Next Gen Sequencing data and explore new career opportunities for biomedical and clinical researchers. Recorded on 03/25/2014.

- [From the Human Genome Project to Precision Medicine: A Journey to Advance Human Health](https://www.youtube.com/watch?v=M9OGNXwCq3c):by Eric D. Green, Director, National Human Genome Research Institute. Dr. Green is the founding director of the NIH Intramural Sequencing Center (1997-2009). Prior to that, he played an integral role in the Human Genome Project.


# Start here for serious study

- MIT Open Courseware's [Foundations of Computational And-Systems Biology, Spring 2014](https://ocw.mit.edu/courses/biology/7-91j-foundations-of-computational-and-systems-biology-spring-2014/index.htm). 
This course is an introduction to computational biology emphasizing the fundamentals of nucleic acid and protein sequence and structural analysis; it also includes an introduction to the analysis of complex biological systems. Topics covered in the course include principles and methods used for sequence alignment, motif finding, structural modeling, structure prediction and network modeling, as well as currently emerging research areas. [Video Lectures from Spring 2014 at MIT](https://ocw.mit.edu/courses/biology/7-91j-foundations-of-computational-and-systems-biology-spring-2014/video-lectures/).

## Papers

- [Evaluating Protein Transfer Learning with TAPE](https://www.biorxiv.org/content/10.1101/676825v1): by Roshan Rao, Nicholas Bhattacharya, Neil Thomas, Yan Duan, Xi Chen, John Canny, Pieter Abbeel, Yun S. Song. 
Protein modeling is an increasingly popular area of machine learning research. Semi-supervised learning has emerged as an important paradigm in protein modeling due to the high cost of acquiring supervised protein labels, but the current literature is fragmented when it comes to datasets and standardized evaluation techniques. To facilitate progress in this field, we introduce the Tasks Assessing Protein Embeddings (TAPE), a set of five biologically relevant semi-supervised learning tasks spread across different domains of protein biology. We curate tasks into specific training, validation, and test splits to ensure that each task tests biologically relevant generalization that transfers to real-life scenarios. We bench-mark a range of approaches to semi-supervised protein representation learning, which span recent work as well as canonical sequence learning techniques. We find that self-supervised pretraining is helpful for almost all models on all tasks, more than doubling performance in some cases. Despite this increase, in several cases features learned by self-supervised pretraining still lag behind features extracted by state-of-the-art non-neural techniques. This gap in performance suggests a huge opportunity for innovative architecture design and improved modeling paradigms that better capture the signal in biological sequences. TAPE will help the machine learning community focus effort on scientifically relevant problems. Toward this end, all data and code used to run these experiments are available at [tape repo](https://github.com/songlab-cal/tape).



- [2001 A computational analysis of sequence features involved in recognition of short introns](https://www.pnas.org/content/98/20/11193) by Lim and Burge. "Splicing of short introns by the nuclear pre-mRNA splicing machinery is thought to proceed via an “intron definition” mechanism, in which the 5′ and 3′ splice sites (5′ss, 3′ss, respectively) are initially recognized and paired across the intron. Here, we describe a computational analysis of sequence features involved in recognition of short introns by using available transcript data from five eukaryotes with complete or nearly complete genomic sequences." Complete [PDF](https://www.pnas.org/content/pnas/98/20/11193.full.pdf)

- [Tree based machine learning framework for predicting ground state energies of molecules ](https://arxiv.org/abs/1609.07124) 
by Burak Himmetoglu.  We present an application of the boosted regression tree algorithm for predicting ground state energies of molecules made up of C, H, N, O, P, and S (CHNOPS). The PubChem chemical compound database has been incorporated to construct a dataset of 16,242 molecules, whose electronic ground state energies have been computed using density functional theory.


- [IEEE Spectrum article: Genomics Signal Processing](https://pdfs.semanticscholar.org/eb87/1f4b1840e9357a78df2a1809161dbbee4796.pdf): 
by Dimitris Anastassiou. Genomic information is digital in a very real sense; it is
represented in the form of sequences of which each element
can be one out of a finite number of entities. 

- [Deep Learning for Genomics: A Concise Overview](https://arxiv.org/pdf/1802.00810.pdf) Tianwei Yue tyue@andrew.cmu.edu
Haohan Wang haohanw@cs.cmu.edu
School of Computer Science
Carnegie Mellon University
Pittsburgh, PA 15213, USA
Abstract
This data explosion driven by advancements in genomic research, such as high-throughput
sequencing techniques, is constantly challenging conventional methods used in genomics.
In parallel with the urgent demand for robust algorithms, deep learning has succeeded
in a variety of fields such as vision, speech, and text processing. Yet genomics entails
unique challenges to deep learning since we are expecting from deep learning a superhuman
intelligence that explores beyond our knowledge to interpret the genome. A powerful deep
learning model should rely on insightful utilization of task-specific knowledge. In this
paper, we briefly discuss the strengths of different deep learning models from a genomic
perspective so as to fit each particular task with a proper deep architecture, and remark on
practical considerations of developing modern deep learning architectures for genomics. We
also provide a concise review of deep learning applications in various aspects of genomic
research, as well as pointing out current challenges and potential research directions for
future genomics applications.


- [A primer on deep learning in genomics](./zou2018primer.pdf)  by James Zou et. al. Deep learning methods are a class of machine learning techniques capable of identifying highly complex patterns in large data-
sets. Here, we provide a perspective and primer on deep learning applications for genome analysis. We discuss successful
applications in the fields of regulatory genomics, variant calling and pathogenicity scores. We include general guidance for how
to effectively use deep learning methods as well as a practical guide to tools and resources. This primer is accompanied by an interactive online tutorial.

  - Associated with colabratory notebook:[A Primer on Deep Learning in Genomics - Public.ipynb](https://colab.research.google.com/drive/17E4h5aAOioh5DiTo7MZg4hpL6Z_0FyWr#scrollTo=eiiwjw4yhX0P)

- [Genome Functional Annotation using Deep Convolutional
Neural Network](https://www.biorxiv.org/content/biorxiv/early/2018/05/25/330308.full.pdf) by 
Ghazaleh Khodabandelou
, Etienne Routhier and Julien Mozziconacci. In genomics, which deals with DNA sequences, the development of deep
neural networks is expected to revolutionize current practice, from fundamental issues
such as understanding the evolution of genomes to more specific applications such as
the development of personalized medicine. Several approaches have been developed
relying on convolution neural networks (CNN) to identify the functional role of
sequences such as promoters, enhancers or protein binding sites along genomes. These
approaches rely on the generation of sequences batches with known annotations for
learning purpose. While they show good performance to predict annotations from a test
subset of these batches, they usually work less well when applied genome-wide; i.e. for
whole genome annotation. In this paper, we address this issue and propose an optimal
strategy to train CNN for this specific application. We use as a case study gene
Transcription Start Sites (TSS) and show that a model trained on one organism (e.g.
human) can be used to predict TSS in a different specie (e.g. mouse)

## Resources
- [Glossary of Next Gen Sequencing](https://www.illumina.com/science/technology/next-generation-sequencing/beginners/glossary.html): terms used in in NGS defined by Illumina. Video overview: [NGS for beginners](https://www.illumina.com/science/technology/next-generation-sequencing/beginners.html).

- [Bioinformatics Algorithms](https://www.bioinformaticsalgorithms.org/): Book and methodology by Phillip Compeau and Pavel Pevzner. Great.
   - [Bioinformatics I: Finding Hidden Messages in DNA at Stepik](https://stepik.org/course/55929/promo#toc): by Phillip Compeau and Pavel Pevzner. The first half of the course, we investigate DNA replication, and ask the question, where in the genome does DNA replication begin? We will see that we can answer this question for many bacteria using only some straightforward algorithms to look for hidden messages in the genome.
   - [DNA Analysis on Coursera by Pavel Pevzner and Phillip Compeau](https://www.coursera.org/learn/dna-analysis): 8 part course on DNA statistics.
  
- [Rosalind](http://rosalind.info/problems/locations): Rosalind is a platform for learning bioinformatics and programming through problem solving.

## Data Sets
- [Google genomics data sets](https://cloud.google.com/genomics/docs/public-datasets/) Cloud Genomics provides a variety of public datasets that you can access for free and integrate into your applications. Google hosts these datasets, providing public access to the data.

## Software
- [HCA](https://mloss.org/software/title/?page=11) Multi-core non-parametric and bursty topic models (HDP-LDA, DCMLDA, and other variants of LDA) implemented in C using efficient Gibbs sampling, with hyperparameter sampling and other flexible controls.

## Companies

- [Tempus](https://www.tempus.com/) is a technology company that has built the world’s largest library of clinical and molecular data and an operating system to make that data accessible and useful, starting with cancer. Our goal is for each patient to benefit from the treatment of others who came before.

- [Illumina](https://www.illumina.com/company/about-us/fact-sheet.html) is a leading developer, manufacturer, and marketer of life science tools and integrated systems for large-scale analysis of genetic variation and function. These systems are enabling studies that were not even imaginable just a few years ago, and moving us closer to the realization of personalized medicine. With rapid advances in technology taking place, it is mission-critical to offer solutions that are not only innovative, but flexible, and scalable, with industry-leading support and service.
