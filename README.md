# Neuro Workflows | Houston | Sep 6-7
## Brainstorming workshop

The DataJoint team and the Johns Hopkins University Applied Physics Lab will hold an open brainstorm workshop to define the roadmap for automated research workflows in neuroscience.
We will review the current landscape critically and define paths for implementing effective research workflows in neuroscience.

### Organizers and participants
 * JHU/APL: Daniel Xenes, Erik Johnson 
 * Columbia University: Taiga Abe, John Cunningham
 * [EBRAINS](https://ebrains.eu/) (remote): Michael Schirner, Petra Ritter
 * University of Utah, [Visus](https://visus.org): Amy Gooch, Valerio Pascucci
 * [Catalyst Neuro](https://www.catalystneuro.com/): Ben Dichter
 * DataJoint: Thinh Nguyen, Raphael Guzman, Monty Kosma, Kabi Gunalan, Joseph Burling, Chris Brozdowski, Tolga Dincer, Sidharth Hulyalkar, Jaerong Ahn, Kushal Bakshi, Dimitri Yatsenko

### Where
The workshop will be held at [DataJoint in Houston, TX](https://www.datajoint.com/about).

Address: [4265 San Felipe St, Ste 1025](https://goo.gl/maps/SMHvhV1ARFsGWXWA8), Houston, TX 77027

###  Focus 
Aim:
  * to vastly increase the speed, scale, and validity of neuroscience research
  * to provide a clear competitive advantage to researchers
    - time to launch
    - high-performance computing
    - latest analysis tools
    - ability to collaborate
    - time to publish 

Approach: Implement [Research Workflow Automation](https://nap.nationalacademies.org/read/26532)
 - reduce barriers to participation / collaboration
 - expand capabilities -> tackle new problems
 - ease access to cyberinfrastructure
 - transparency and reproducibility
 - integration of diverse tools and resources
 - proper incentives and credit assignment

What is needed to implement automated workflows in neuroscience
 - framework + tools = a language for formal workflows = **DataJoint Core**
 - reference implementations + integrations = **DataJoint Elements**
 - community + support + resources + services = **DataJoint Works**

Breakfast and lunch will be provided. 

The workshop will identify general directions for addressing the challenges in team science and data-driven research workflows. 
Day 1 and Day 2 will map the current trends and challenges in the field.  
This session will  be open to interested researchers -- please notify Dimitri Yatsenko August 31, 2022 if you would like to attend. 
Day 3 will focus on the roadmap for the emerging DataJoint platform and will be limited to the DataJoint and JHU/APL teams. 

## Day 1 (2022-09-06) 

7.30 am - Breakfast 

8 am - Automated Workflows for Neuroscience - Dimitri

9 am - Current Challanges - Erik, Dimitri, Thinh
 - Major friction points in data-driven research 
 - The structure of typical vs highly successful projects
 - Advanced neurotechnologies and multi-modal experiments
 - Data acquisition and aggregation
 - Team organization, collaboration process
 - IT Infrastructure - Use of cloud
 - Collaborative analysis
 - Credit assignment
 - Human in the loop -- curation 
 - AI in the loop
 - Reproducibility, integrity, continuity
 - Budgeting and cost controls

10 am - Virtual Research Environments - Michael  

11 am - BRAIN Initiative Neuroinformatics Developments - Erik
  - A critical review of the current and emerging  neuroinformatics initiatives
  - Global efforts - INCF

12 noon - lunch

1 pm - Visus. Data streaming, HPC infrastructure - Valerio

2 pm - collaborative analysis tools, platforms, and environments. DANDI, PanNeuro - Ben ,Erik 

 - 30 mins  - PanNeuro - Ben 

3 pm - ML integration. Human-in-the loop - Dimitri, Erik


## Day 2 (2022-09-07) 

7.30 am breakfast

8 am:  An overview of Formal Workflow management tools - Raphael, Erik
  - Prefect, Apache Airflow, Flyte, Argo -> [Common Workflow Language](https://www.commonwl.org/)

Most widely used bioinformatics workflow systems (from [Reiter-2020](https://academic.oup.com/gigascience/article/10/1/giaa140/6092773?fbclid=IwAR1I92LXvDbpesunIQOENtLRa4vm3zH4pvC8HJQ269luTaQ_WBwWIuMeFh8#312918873)):

 |  Workflow system  | Documentation | Example workflow | Tutorial |
 | :--- | :--- | :--- | :--- |
 | Snakemake | [Docs](https://snakemake.readthedocs.io) |  [ChipSeq](https://github.com/snakemake-workflows/chipseq) | [Tutorial](https://snakemake.readthedocs.io/en/stable/tutorial/tutorial.html) |
 | Nextflow | [Docs](https://www.nextflow.io/) | [Sarek](https://github.com/nf-core/sarek) | [Get Started](https://www.nextflow.io/docs/latest/getstarted.html) |
 | CWL | [commonwl.org](https://www.commonwl.org/) | [EBI-Metagenomics](https://github.com/EBI-Metagenomics/pipeline-v5) | [User Guide Example](https://www.commonwl.org/user_guide/02-1st-example/index.html) |
 | WDL | [openwdl.org](https://openwdl.org/) | [gatk4](https://github.com/gatk-workflows/gatk4-data-processing) | [HOWTO](https://support.terra.bio/hc/en-us/articles/360037127992–1-howto-Write-your-first-WDL-script-running-GATK-HaplotypeCaller) |

9 am Infrastructure access, orchestration - Erik, Raphael, Joseph, Taiga
  - Infrastructure: e.g. NeuroCAAS - Taiga, John Cunningham 
  - Job orchestration - Raphael

10 am  Data Management, the role of databases - Dimitri
  - workflows + data management 
  - data models: structured vs self-describing data 
  - data consistency, integrity
  - query speed,indexing 

11 am - Accessibility, provenance, versioning - Erik, Ben, Dimitri
  - association between code, data
  - Joint management of code, environment, and data

12 noon - lunch

1 pm - Neuroinformatics resources - Erik, Dimitri, Ben
  - Allen and Janelia atlases
  - Catalogs, nomenclatures, ontologies 
  - Data standards, archives, public data repositories and databases.
  - Analysis tools 
  - Collaboration platforms

2 pm  - The DataJoint experience - Thinh
  - DataJoint Core - differentiators, performance, gap analysis
  - DataJoint Elements - User experience
  - DataJoint Works - user experience
  - Interfaces:
  - Platform for tool developers - dissemination, tracking, credit assignment

3 pm - Teamflows - Erik, Thinh
   - Roles, team structure 
   - Software Engineering in Research
   - incentives, credit assignment
   - informal collaborations 
   - integration of community development
   - funding, support

4 pm - Online research platforms - Erik
  - Examples: Galaxy, [HubMap](https://portal.hubmapconsortium.org/)

## Day 3 - September 8, 2022

7.30 am - breakfast

8 am - DataJoint Platform  Workshop -- internal.  DataJoint and JHU APL only.

* Aims for DataJoint SciOps
  - Key differentiators
  - SciOps user experience 
* Framework development
* Integration of DataJoint Elements
* Integrations - acquisition software, atlases, archives
* Aim 1
* Aim 2
* Aim 3
* Milestones, Statement of work, Roles and responsibilities

1 pm - lunch, adjourn

