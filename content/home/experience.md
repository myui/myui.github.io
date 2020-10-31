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

+++
