# What Is The FOCUSED Project

FOCUSED stands for Fostering Open Collaboration Using Shared Ecosystem Dependencies. The goal of this project is to learn if simply sharing detailed dependency information between organizations is enough to spur collaboration, or if further intervention is needed.

This project was funded through the [Critical Digital Infrastracture Research](https://www.fordfoundation.org/campaigns/critical-digital-infrastructure-research/) project.

# Original Project Proposal Text

## What is your research question, and why is it important to answer?
*Will cross-company visibility into shared free and open source dependencies lead to cross-company collaboration and efforts to sustain shared dependencies?*

Companies historically do not share detailed information about their free and open source dependencies, unless they are talking about their innovative use of high-profile technologies in order to build up their brand as an employer. Because detailed dependency information is closely held, it is difficult to make informed collective decisions about where to direct dependency support. This means individual organizations typically prioritize support based on their own needs and project name recognition. We see this borne out in the open source funding space as projects with strong name recognition draw the majority of funds, while lesser-known but important shared dependencies struggle. By identifying and highlighting shared dependencies, we can begin to develop frameworks that will encourage companies to take a more holistic view of the free and open source ecosystem. Answering this question will be the first step in developing these frameworks.

## What is the state of the research on this question?
The Core Infrastructure Initiative has produced useful research to identify the most widely used shared dependencies<sup>1</sup>. Allison Randall has conducted useful research on the subject of the development of organizational open source capabilities<sup>2</sup>. Ciesielska and Westenholz have described useful levels of engagement between companies and open source communities<sup>3</sup>. Morgan & Finnegan have developed a useful framework for classifying areas of business value<sup>4</sup>. This body of research will support the project, but there has been limited research on the subject of driving corporate engagement and support into open source communities using the approaches we describe. 

## Who is the project team and how are they qualified to address the research question?
Duane O'Brien (PI) currently serves as the Head of Open Source at Indeed. Duane has experience building cross-company collaboration through the TODO Group, a working group of corporate open source program offices. Duane has also led the creation of the FOSS Contributor Fund, a funding sustainability initiative that has been adopted at Indeed, Salesforce, and Microsoft. The project will be supported by Alyssa Wright from Open Collective. 

## What is the research methodology?
We will begin by mapping the existing landscape of Open Source Programs Offices (OSPOs), classifying organizations using a rubric that accounts for company size, areas of business value, program status, program output, and organizational capabilities. We will include in this mapping software companies that do not appear to have formal Open Source Programs but still produce open source software. We will seek to identify organizations that fit within a well-bounded cohort, and recruit a total of twenty organizations to participate in the project. Ten organizations will serve as a control, and ten organizations will serve as the test subjects. All participating organizations will be asked to share known GitHub IDs associated with their organizations, and will be assisted in executing a process to create a detailed dependency graph for their organizations. Prior to intervention, we will conduct a baseline measurement of existing collaboration between organizations using the provided GitHub IDs and dependency graphs, supplementing this information based on observations of the dataset available in the GitHub Archive project. We will then share dependency insights with the test subjects, aid them in identifying individuals who work on related dependencies, and assist in hosting meet and greet sessions between potential collaborators. We will perform monthly analysis to measure open source contribution activity originating from the participating organizations. Data will be supplemented with participant interviews.

The participating organizations are likely to be biased primarily by their desire to drive open source culture in their organization and by their willingness to opt-in to the dependency sharing process. The likely impact of these biases is that the sample set will be skewed toward organizations that are in an open source adoption and growth phase, or who already have developed significant open source organizational capabilities.

Because of the nature of the experiment, it will be necessary to recruit organizations with a constrained set of language ecosystems and technology stacks.

## What is the work plan?
The project will lead with 6 months of preparation, to allow sufficient time to navigate complex corporate policies and processes. We will conduct 12 months of experiment execution, marked by regular data collection and informally hosted collaboration sessions that will provide space for connection and collaboration.

We will front-load tooling development, organization recruitment, and OSPO classification in Q1 2021. We will spend Q2 2021 performing baseline measurements and conducting dependency analysis. Baseline measurements and visualizations will be contracted to Bitergia<sup>5</sup>, an organization with deep experience in open source metrics and strong roots in the CHAOSS community<sup>6</sup>. We will distribute shared dependency analysis insights at the beginning of Q3 2021, and host subsequent collaboration sessions over the next 12 months. At the end of Q2 2022, we will produce summary materials and reports.


## What are the outputs and impact of the research project?
The tools and processes used to collect dependency information and identify collaboration opportunities will be documented in a runbook that will allow other organizations to recreate the experiment. A set of best practices based on data and participant research will help inform future cross-company collaboration on shared dependencies. All code written in support of the project will be released under an open source license, or contributed to an existing open source project, and all documents will be provided under a Creative Commons license. Diagrams and visualizations that represent the collaborations before and after intervention will support conference presentations and blog posts describing the project and outcomes.

## How will the project attend to diversity, equity, and inclusion?
We will source tool developers, consultants, and support contractors from groups that are historically under-represented in the open source community. As we identify the test and control cohorts, we will ensure that we have global representation in our participating technology companies. We have established gender parity among the currently identified project collaborators and contractors.

## Citations
1. [CII Census II - Vulnerabilities in the core](https://www.coreinfrastructure.org/wp-content/uploads/sites/6/2020/02/census_ii_vulnerabilities_in_the_core.pdf)
1. [Turing Lecture: Open source influences on technology innovation](https://www.youtube.com/watch?v=f4nCMVfNqqM)
1. [Dilemmas within commercial involvement in open source software](https://www.researchgate.net/publication/301663840_Dilemmas_within_commercial_involvement_in_open_source_software)
1. [Beyond free software: An exploration of the business value of strategic open source](https://www.researchgate.net/publication/264560850_Beyond_free_software_An_exploration_of_the_business_value_of_strategic_open_source)
1. [Bitergia](https://bitergia.com/)
1. [CHAOSS: Community Health Analytics Open Source Software](https://chaoss.community/)
