# LING530F: Deep Learning for Natural Language Processing (DL-NLP)
### The University of British Columbia

**Year:** Winter Session I 2018-2019

**Time:** Mon Wed. 13:30 - 15:00pm.

**Location:** West Mall Swing Space Room 408

**Instructor:** Dr. Muhammad Abdul-Mageed

**Office location:** School of Information (iSchool) 494

**Office phone:** 6048-274-530

**Office hours:** Tues. 12:00-14:00pm or by appointment. *(I can also handle inquiries via email or Skype.)*

**E-mail address:** muhammad.mageed@ubc.ca

**Student Portal:** <http://canvas.ubc.ca>


## 1.	Course Rationale & Goal: 

**Rationale/Background:** *Natural language processing (NLP)* is the field focused at teaching computers to *understand* and *generate* human language. Dialog systems where the computer interacts with humans, such as the Amazon Echo, constitute an instance of both language understanding and generation, as the machine attempts to identify the meaning of questions and generate meaningful answers. Recent advances in machine learning, especially in  *Deep learning*, a class of machine learning methods inspired by information processing in the human brain, have boosted performance on several NLP tasks.

*Deep learning of natural language* is in its infancy, with expected breakthroughs ahead. Solving NLP problems directly contributes to the development of pervasive technologies with significant social and economic impacts and the potential to enhance the lives of millions of people. Given the central role that language plays in our lives, advances in deep learning of natural language have implications across almost all fields of science and technology, as well as many other disciplines like linguistics, as NLP and deep learning are instrumental for making sense of the ever-growing data collected in these fields.


**Goal:** This course provides a graduate-level introduction to Natural Language Processing With Deep Learning. The goal of the course is to familiarize students with the major NLP problems and the primary deep learning methods being developed to solve them. This includes problems at various linguistic levels (e.g., word and sub-word, phrase, clause, and discourse). Methodologically, this involves unsupervised, distributed representations and supervised deep learning methods across these linguistic levels. The course also includes providing an introductory level of hands-on experience in using deep learning software as well as opportunities to develop advanced solutions for NLP problems in the context of a final project.

**Potential audiences for this course are:**

* Students with a linguistics and/or a computer science background interested in learning novel NLP methods, with a focus on deep learning.
* People interested in NLP, text analytics, information retrieval, information visualization, human-information interaction, machine learning and deep learning, etc., who want to prepare for, or advance, carrying out research in these fields exploiting deep learning of natural language methods.

## 2.	Course Objectives: 
Upon completion of this course students will be able to:

* *identify* the inherent ambiguity in natural language, and appreciate challenges associated with teaching machines to understand and generate it
    
* *become* aware of a core of NLP problems, and *demonstrate* how these are relevant to the lives of diverse individuals, communities and organizations.
    
* *become* aware of the major deep learning methods being developed for solving NLP problems, and be in a position to *apply* this deepened understanding in critical, creative, and novel ways
    
* *collaborate* effectively with peers through course assignments

* *identify* an NLP problem (existing or novel) and *apply* deep learning methods to *develop* a solution for it 


## 3.	Course Topics:

* ambiguity in human language (across different levels) % week 01
* learning words \& phrases (word vectors)% weeks 2, 3%, and sentences
* recurrent neural networks 
* convolutional neural networks
* seq2seq models
* generative deep learning

### Applications ###

* POS tagging and morphological disambiguation
* learning in low-resource languages
* language/dialect identification
* emotion and sentiment analysis
* natural language inference
* machine translation

## 4.	Prerequisites:  

* have some familiarity with at least one linguistics field
* have some familiarity with basic linear algebra, basic calculus, \\and basic probability (basic $=$ high school level)
* have programming experience in Python
* have access to a computer (preferably with a GPU) on a regular basis
 
Students lacking any of the above pre-requisites must be open to learn outside their comfort zone to make up, including investing time outside class learning these pre-requisites on their own. Some relevant material across these pre-requisites will be provided as part of the syllabus. Should you have questions about pre-requisites, please email the instructor.
 
 
## 5.	Format of the course: 
•	This course will involve lectures, class hands-on activities, individual and group work, and instructor-, peer-, and self-assessment. 

## 6. Course syllabus:

**Required books:**

* Goodfellow, I., Bengio, Y., Courville, A., & Bengio, Y. (2016). Deep learning (Vol. 1). Cambridge: MIT press. Available at: [[link](http://www.deeplearningbook.org/)]. 

* Goldberg, Y. (2017). Neural network methods for natural language processing. Synthesis Lectures on Human Language Technologies, 10(1), 1-309. 

* Jurafsky, D., & Martin, J. H. (2017). Speech and language processing. London:: Pearson. Available at [[link](https://web.stanford.edu/~jurafsky/slp3/ed3book.pdf)].

**Other recommended books:**

* Bird, S., Klein, E., & Loper, E. (2009). Natural language processing with Python. O'Reilly Media, Inc. [[link](http://www.nltk.org/book/)].
* Weekly readings will be assigned from materials available through the UBC library and online.
* See "Readings Section below"

## 7. Calendar / Weekly schedule (tentative)

| Date | Slides   | Related Content                 | What is due/out            |
|------|--------|----------------------------------|----------------------------|
| Mon Sept 3    |  Labor Day – UBC closed  | NA  |            |
| Wed Sept 5    |  Course overview  | NA  |            |
| Mon Sept 10    |  Guest speaker (MAM@ECML)  | Linear Algebra: [[DLB CH02](https://www.deeplearningbook.org/contents/linear_algebra.html)[MIT Course](https://www.youtube.com/watch?v=ZK3O402wf1c&list=PLE7DDD91010BC51F8)]  |            |
| Wed Sept 12    |  Guest speaker (MAM@ECML)  | NA  |            |
| Mon Sept 17    |    Probability  | [[DLB CH03](https://www.deeplearningbook.org/contents/prob.html)]  |         |
| Wed Sept 19    |    Information Theory  |  [[DLB CH03](https://www.deeplearningbook.org/contents/prob.html)]  |        |
| Mon Sept 24    |    Machine Learning Basics | [[DLB CH05](https://www.deeplearningbook.org/contents/ml.html)]  |         |
| Wed Sept 26    |    Word meaning; Feedforward Networks |  [[DLB CH06](https://www.deeplearningbook.org/contents/mlp.html)] |           |
| Mon Oct 1    |    Language Models and Word2Vec |   |           |
| Wed Oct 3    |    Recurrent Neural Networks I  | [[DLB CH10](https://www.deeplearningbook.org/contents/rnn.html)]  | hw01 due     |
| Mon Oct 8    |    Thanksgiving Day – UBC closed  | NA  |            |
| Wed Oct 10    |    Recurrent Neural Networks II  | [[DLB CH10](https://www.deeplearningbook.org/contents/rnn.html)]   |          |
| Mon Oct 15    |    Neural Morphology  |    |          |
| Wed Oct 17    |     Neural Sentiment Analysis  |    |          |
| Mon Oct 22   |     Neural Emotion Detection |     |         |
| Wed Oct 24   |    Embeddings from Language Models  |    |   hw02 due       |
| Mon Oct 29    |    ConvNets I  |   [[DLB CH09](https://www.deeplearningbook.org/contents/convnets.html)]   |        |
| Wed Oct 31    |    ConvNets II  |  [[DLB CH09](https://www.deeplearningbook.org/contents/convnets.html)]   |         |
| Mon Nov 5    |    Text Classification: Lexical Dialectology   |   |   hw03_a due        |
| Wed Nov 7    |    Seq2Seq; Neural Machine Translation  |      |        |
| Mon Nov 12    |  Remembrance Day – UBC closed  | NA  |            |
| Wed Nov 14    |    Memory & Attention; Neural Misinformation  Detection |     |         |
| Mon Nov 19    |    (Variational) Auto-Encoders  | [[DLB CH14](https://www.deeplearningbook.org/contents/autoencoders.html)]  |           |
| Wed Nov 21    |    Generative Adversarial Networks |    |          |
| Mon Nov 26    |    Projects |      |        |
| Wed Nov 28    |    Projects  |      |        |
| Mon Dec 2    |    | --  |   Final project due  (hw03_b)       |



## 8. Readings:  
    
## 9. Course Assignments/Grades:
| Assignment | Due date | Weight |
| ---------- | -------- | ------ |
| Professionalization & Class Participation |  Throughout | 15% |
| ASSIGNMENT 1: Individual assignment: Word Embeddings |  Oct 3 | 15% |
| ASSIGNMENT 2: Individual assignment: Text Classification with RNNs |  Oct. 24 | 20% |
| ASSIGNMENT 3_A: Group assignment: Project Proposal |    Nov. 5 | 5% |
| ASSIGNMENT 3_B: Group assignment: Term Project (GROUP of 3) |   Dec 3   | 45% |

## Notes on Assignments:


### ASSIGNMENT 1: *Word Embeddings* 

In this assignment, students will train a word embeddings model (using either Word2Vec of FastText) on a dataset provided to them, and use the trained model for a number of tasks. The students will write a report using the Jupyter platform describing their work. The reprot will include both the code used and the results acquired, in a step-wise, organized fashion. The students are expected to use enabling Python libraries (e.g., NLTK, gensim, scikit-learn) and illustrate their work with visualizations automatically generated from the data. A rubric will be provided to walk students through the different steps. 

**Deliverables: *Jupyter Notebook describing the work students carried out***

### ASSIGNMENT 2: *Text Classification with RNNs* 

For this assignment, students will build a fully-fledged text classifier using RNNs, and its variations (e.g., LSTMs, GRUs). For this, the students will be provided a labeled dataset. As such, the task is cast as supervised machine learning. The students will need to demonstrate understanding of the theoritical part of the course. For example, a detailed description of pre-processing, data splits (concepts like train, dev, and test sets and/or n-fold cross validation), model capacity (e.g., the architecture of the network used in terms of layers and number of units in each layer), activation functions, regularization, cost functions, baselines and meaningful comparisons (which baselines are chosen and why), etc. 

**Deliverables: *A short paper (4 pages main body+ 2 pages references) + Jupyter notebook***

Students will then write a 4-page report + 2 extra pages for references. A maximum of 2 extra pages can be allowed, without instructor permission, but need to be justfied in a footnote in the report. Students will also need to submit an accompanying Jupyter notebook with their code. Students will be provided an ACL LaTex template to use for writing the report, and a rubric walking them through some of the major details of how to write the report.

### ASSIGNMENT 3: *Term Project*

The purposes of this assignment include:
- Identifying and describing an interesting (i.e., challenging, novel, socially-relevant, has practical applications) NLP problem;
- Reviewing previous literature on relevant to the task, showing a clear understanding of previous scholarship;
- Proposing and developing (in the engineering sense via code) a solution to the problem using deep learning;
- Clearly describing the work, justifying decisons made, in a way that lends work to replication;
- Developing oral and written communication skills through discussions with classmates and instructor;
- Demonstrating ability to work as part of a team, including initiative taking, integrity, dependability and co-operation, and effective collaboration.

For this assignment, each student is required to work as part of a group of of 3\* on a project involving a practical task. Example projects will be discussed in class.

* A group of a different size may be possible after consultation with the instructor.

**Deliverables** 
**Proposal: 1-2 pages in ACL Style LaTex**
- Who are the the group members?
- What is the problem you are proposing a solution for?
- What motivates your work? Why is it important or useful to undertake the chosen task?
- How does your project compare to NLP and deep learning published research?
- What are the different steps you will take to ensure success of the project? What are the smaller segments of which the bigger task is composed? And how will you conduct each small task?
- How does the work bread down and what each member of the team be contributing?
- Timeline for completing the project, including goals for each segment. 
Note: You may like to provide a table breaking down who is doing what and when.
The LaTex files will be provided to you as part of the rubric for the final project.

**Final Paper: 6-8 pages (ACL Style)** 
The final deliverable includes:
- A detailed and clear description of your project, including the necessary sections, as appropriate. For example, you will need to include an abstract, introduction, possibly research questions, a literature review, a description of dataset (collection, splits), methods (implementation details, experimental conditions, settings, comparisons, baselines), results (in tables), analysis of results (e.g., with visulaizations, error analyses), and a conclusion describing limitations and future directions;
- All data used, whenever possible, and/or links to where the data are housed;
- Pointers to a live version of the project, if any;
- As appropriate, you should situate your work within the wider context of published works and approaches, with supporting arguments. You will have an unlimited number of pages for references, but you should plan to have at least 15 sources;
- Employment of figures, tables, and visualizations as appropriate to enhance argument and facilitate communicating your findings/results;

## 10. Course Policies

**Attendance:** The UBC calendar states: “Regular attendance is expected of students in all their classes (including lectures, laboratories, tutorials, seminars, etc.). Students who neglect their academic work and assignments may be excluded from the final examinations. Students who are unavoidably absent because of illness or disability should report to their instructors on return to classes.”

**Evaluation:** All assignments will be marked using the evaluative criteria given in this syllabus.


**Access & Diversity:** Access & Diversity works with the University to create an inclusive living and learning environment in which all students can thrive. The University accommodates students with disabilities who have registered with the [Access and Diversity unit](https://students.ubc.ca/about-student-services/access-diversity). You must register with the Disability Resource Centre to be granted special accommodations for any on-going conditions. 
**Religious Accommodation:** The University accommodates students whose religious obligations conflict with attendance, submitting assignments, or completing scheduled tests and examinations. Please let your instructor know in advance, preferably in the first week of class, if you will require any accommodation on these grounds. Students who plan to be absent for varsity athletics, family obligations, or other similar commitments, cannot assume they will be accommodated, and should discuss their commitments with the instructor before the course drop date. [UBC policy on Religious Holidays](http://www.universitycounsel.ubc.ca/policies/policy65.pdf).

## Academic Integrity
**Plagiarism**
The Faculty of Arts considers plagiarism to be the most serious academic offence that a student can commit. Regardless of whether or not it was committed intentionally, plagiarism has serious academic consequences and can result in expulsion from the university. Plagiarism involves the improper use of somebody else's words or ideas in one's work. 

It is your responsibility to make sure you fully understand what plagiarism is. Many students who think they understand plagiarism do in fact commit what UBC calls "reckless plagiarism." Below is an excerpt on reckless plagiarism from UBC Faculty of Arts' leaflet, [Plagiarism Avoided: Taking Responsibility for Your Work](http://www.arts.ubc.ca/arts-students/plagiarism-avoided.html).

"The bulk of plagiarism falls into this category. Reckless plagiarism is often the result of careless research, poor time management, and a lack of confidence in your own ability to think critically. Examples of reckless plagiarism include:

* Taking phrases, sentences, paragraphs, or statistical findings from a variety of sources and piecing them together into an essay (piecemeal plagiarism);
* Taking the words of another author and failing to note clearly that they are not your own. In other words, you have not put a direct quotation within quotation marks;
* Using statistical findings without acknowledging your source;
* Taking another author's idea, without your own critical analysis, and failing to acknowledge that this idea is not yours;
* Paraphrasing (i.e. rewording or rearranging words so that your work resembles, but does not copy, the original) without acknowledging your source;
* Using footnotes or material quoted in other sources as if they were the results of your own research; and
* Submitting a piece of work with inaccurate text references, sloppy footnotes, or incomplete source (bibliographic) information."

Bear in mind that this is only one example of the different forms of plagiarism. Before preparing for their written assignments, students are strongly encouraged to familiarize themselves with the following source on plagiarism: the [Academic Integrity Resource Centre](http://help.library.ubc.ca/researching/academic-integrity).

If after reading these materials you still are unsure about how to properly use sources in your work, please ask me for clarification. Students are held responsible for knowing and following all University regulations regarding academic dishonesty. If a student does not know how to properly cite a source or what constitutes proper use of a source it is the student's personal responsibility to obtain the needed information and to apply it within University guidelines and policies. If evidence of academic dishonesty is found in a course assignment, previously submitted work in this course may be reviewed for possible academic dishonesty and grades modified as appropriate. UBC policy requires that all suspected cases of academic dishonesty must be forwarded to the Dean for possible action. 

