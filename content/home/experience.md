+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Principal Engineer"
  company = "Arm Treasure Data"
  company_url = "https://www.treasuredata.com/"
  location = "Tokyo, Japan"
  date_start = "2018-08-02"
  date_end = ""
  description = """
Leading the development of a large scale machine learning service (ML-as-a-Service) in Treasure Data cloud service. My work has became productized as the heart of [CDP predictive scoring](https://www.treasuredata.com/product/segmentation/) (Predictive models with automated feature engineering) and [Content Affinity Engine](https://www.slideshare.net/treasure-data/hands-on-javascript-sdk/23) (Data augumentation of user interests using NLP, Ontology, and Wikipedia Corpus). 

Also, I worked on an [Airflow](https://airflow.apache.org/)-like workflow management system (OSS'd as [Digdag](https://www.digdag.io/)) and it's next generation Docker runtime design and implementation using AWS ECS cluster auto scaling. A number of customers are using it for running/managing machine learning workflows. Some of example ML workflows can be seen in [this repository](https://github.com/treasure-data/treasure-boxes/tree/master/machine-learning-box).
  """

[[experience]]
  title = "Research Engineer"
  company = "Treasure Data ([Acquired by Arm](https://blog.treasuredata.com/blog/2018/08/02/the-next-chapter/))"
  company_url = "https://www.treasuredata.com/"
  location = "Tokyo, Japan"
  date_start = "2015-04-01"
  date_end = "2018-08-01"
description = """
* Worked as the company's 1st machine learning engineer. Grow machine learning team and leaded machine learning applications at the company. 
Productized [Apache Hivemall](https://hivemall.apache.org/) in Treasure Data cloud service. Aside from development, I did anything I can contribute to the company growth as a startup member including ML consulting for customers, presentations in sales meeting, talks at external events as well at the early stage of the company.

* **Internship management:** 
I initiated and organized Summer Internship program from 2015 to 2018 and mentored a number of students. We [implemented various Ranking measure and anonaly detection algorithms](https://speakerdeck.com/takuti/treasure-data-summer-internship-2016). Another student worked on [Field-aware Factorization Machines and online Kernel SVM](https://www.slideshare.net/SotaroSugimoto/spring-2016-intern-at-treasure-data).
We successfully finished the intership program and 5 master students joined to Treasure Data in the past 3 years. This accomplishments are what I'm proud of.

* **Consulting:** 
Aside from development tasks, I consulted 20~30 customer-facing machine learning projects from Fortune 500 companies to foreign startups (Indonesia, Taipei, Israel). Consulted industrial segments includes: Telecom, Insurance, Automobile, Ad-tech, EC, Media Agency, Internet-related Service, Real-estate, Gaming, and Online Publishers. My consulting work for Subaru is featured by CEO's talk at Softbank world. Those consulting gave me precious and unique experiece applying ML to diverse domain problems such as dealing with overfitting (data leakage), feedback loops, and pitfalls for optimization by evaluation measures.

* **External talks:** 
I presented talks in various conferences (such as [ApacheCon](https://www.slideshare.net/myui/introduction-to-apache-hivemall-v050-116894003), [Hadoop Conference](https://www.slideshare.net/myui/hadoopsummit16-myui), Annnual event of Japan DataScientist Society) and gave demos at research conferences ([RecSys'18](https://dl.acm.org/doi/10.1145/3240323.3241592)).
"""

[[experience]]
  title = "Apache Hivemall PPMC member"
  company = "The Apache Software Foundation"
  company_url = "https://hivemall.apache.org/"
  location = ""
  date_start = "2016-09-13"
  date_end = ""
description = """
Leading the development of Apache Hivemall at Apache Incubator as [the original creator](https://github.com/myui/hivemall) ([slide](https://www.slideshare.net/myui/podling-hivemall-in-the-apache-incubator)).
"""

[[experience]]
  title = "Senior Researcher"
  company = "National Institute of Advanced Industrial Science and Technology (AIST)"
  company_url = "https://www.aist.go.jp/"
  location = "Tsukuba, Japan"
  date_start = "2010-04-01"
  date_end = "2015-03-31"
description = """
Working on distributed and parallel data processing and large-scale machine learning at the data science research group.
Designed and managed 50 nodes Hadoop cluster for managing scientific workflows. Promoted to a Senior Researcher in the 3rd year at AIST.
"""

[[experience]]
  title = "Visiting Researcher"
  company = "The University of Edinburgh"
  company_url = "https://www.ed.ac.uk/informatics"
  location = "Edinburgh, UK"
  date_start = "2011-09-01"
  date_end = "2011-11-30"
description = """
As a visiting researcher from AIST, I worked with Paolo Basala and Prof. Malcolm Atkinson at Data Intensive Research (DIR) group.
Designed a distributed streaming data processing system on EDIM1 data-intensive machine (an energy-efficient PC cluster) for scientific workflows.
"""

[[experience]]
  title = "Visiting Postdoc"
  company = "Centrum Wiskunde and Informatica (CWI)"
  company_url = "https://www.cwi.nl/research/groups/database-architectures"
  location = "Amesterdam, Nederlands"
  date_start = "2009-10-01"
  date_end = "2010-03-31"
description = """
Worked with Peter Boncz and Prof. Martin Kersten at INS1 database research group. Designed and implemented a parallel database system on the top of shared-nothing MonetDB servers.
"""

[[experience]]
  title = "Visiting Researcher"
  company = "Waseda University"
  company_url = "https://www.yama.info.waseda.ac.jp/"
  location = "Tokyo, Japan"
  date_start = "2009-04-01"
  date_end = "2010-03-31"
description = """
While I'm receiving my JSPS followship, I worked with [Prof. Yamana](https://www.yama.info.waseda.ac.jp/~yamana/yamana_eng2015.htm).
"""

[[experience]]
  title = "System Engineer"
  company = "NEC Infomatic Systems, Ltd"
  company_url = ""
  location = "Tokyo, Japan"
  date_start = "2004-04-01"
  date_end = "2006-03-31"
description = """
Designed and implemented RM4GS (Reliable Messaging for Grid Services) as a reference implementation of [OASIS WSRM](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=wsrm) which provides reliable messaging facilities for Web Services.
"""

+++
