# Automated Workflows Roadmap Brainstorm | Houston | Sep 6-7

The DataJoint team and the Johns Hopkins University Applied Physics Lab will hold a two-day workshop to define the roadmap for automated research workflows in neuroscience.

The workshop will be held at the [DataJoint in Houston, TX](https://www.datajoint.com/about):

> 4265 San Felipe St, Ste 1025
> Houston, TX 77027

[Google Maps](https://goo.gl/maps/SMHvhV1ARFsGWXWA8)

Breakfast and lunch will be provided. 

The workshop will identify general directions for addressing the challenges in team science and data-driven research workflows. 
Day 1 and Day 2 will map the current trends and challenges in the field.  
This session will  be open to interested researchers -- please notify Dimitri Yatsenko August 25, 2022 if you would like to attend. 
DataJoint will provide coffee and lunch and arrange the meeting space.

Day 3 will focus on the roadmap for the emerging DataJoint SciOps platform and will be limited to the DataJoint and JHU/APL teams. 

## Day 1 (2022-09-06) 
Time: 8:30-16:30 CDT + lunch. 

* Aim for Automated Research Workflows 
  - reduce barriers for participation
    - time, access, distance, and interdisciplinary
  - vastly accelerate and scale research to tackle new kinds of problems
  - maximize opportunity for discovery
  - vastly improve quality of research through transparency and reproducibility
  - confer competitive advantage to users 

* Challenges in current neuroscience research workflows
  - The structure of typical and highly successful projects
  - Advanced neurotechnologies and multi-modal experiments
  - Data acquisition and aggregation
  - Team organization
  - IT Infrastructure - Use of cloud
  - Collaborative analysis
  - Credit assignment
  - Human in the loop -- curation 
  - AI in the loop
  - Reproducibility, integrity, continuity
  - Budgeting and cost controls

* Role of Databases and data repositories 
  - Data models: structured vs self-describing
  - Data consistency, integrity
  - Query speed,indexing 

* A critical review of the current and emerging  neuroinformatics initiatives
  - Data standards, archives, public data repositories and databases.
  - Analysis tools 
  - Collaboration platforms


## Day 2 (2022-09-07) 
Time: 8:30-16:30 pm + lunch

* Roadmap for Automated Research Workflows 
  - DataOps for team science 
  - Collaboration platforms 
  - Definitions: workflow, pipeline, job orchestration 
  - Data queries, visualization 

* Joint management of code, environment, and data
    
* Workflow management systems
  - Prefect, Apache Airflow, Flyte, Argo ->  Common Workflow Language  
  - Job orchestration 
  - Environment Management 

Most widely used bioinformatics workflow systems (from [Reiter-2020](https://academic.oup.com/gigascience/article/10/1/giaa140/6092773?fbclid=IwAR1I92LXvDbpesunIQOENtLRa4vm3zH4pvC8HJQ269luTaQ_WBwWIuMeFh8#312918873)):

 |  Workflow system  | Documentation | Example workflow | Tutorial |
 | :--- | :--- | :--- | :--- |
 | Snakemake | [Docs](https://snakemake.readthedocs.io) |  [ChipSeq](https://github.com/snakemake-workflows/chipseq) | [Tutorial](https://snakemake.readthedocs.io/en/stable/tutorial/tutorial.html) |
 | Nextflow | [Docs](https://www.nextflow.io/) | [Sarek](https://github.com/nf-core/sarek) | [Get Started](https://www.nextflow.io/docs/latest/getstarted.html) |
 | CWL | [commonwl.org](https://www.commonwl.org/) | [EBI-Metagenomics](https://github.com/EBI-Metagenomics/pipeline-v5) | [User Guide Example](https://www.commonwl.org/user_guide/02-1st-example/index.html) |
 | WDL | [openwdl.org](https://openwdl.org/) | [gatk4](https://github.com/gatk-workflows/gatk4-data-processing) | [HOWTO](https://support.terra.bio/hc/en-us/articles/360037127992–1-howto-Write-your-first-WDL-script-running-GATK-HaplotypeCaller) |

* DataJoint experience 
  - DataJoint framework - differentiators, performance, gap analysis 
  - DataJoint Elements - User experience
  - DataJoint SciOps - user experience 
  - Interfaces: 
  - Platform for tool developers - dissemination, tracking, credit assignment 

## Day 3 - September 8, 2022
Time: 8:30-16:30 pm + lunch

DataJoint SciOps Workshop -- internal.  DataJoint and JHU APL only.

* Aims for DataJoint SciOps
  - Key differentiation from existing platforms
  - SciOps user experience 
* DataJoint framework development
* Integration with DataJoint Elements
* Integrations
* Aim 1
* Aim 2
* Aim 3
* Milestones, Statement of work, Roles and responsibilities
