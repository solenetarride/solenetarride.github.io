---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


## Work experience

* Since Feb 2022: Deep Learning Researcher, [Teklia](https://teklia.com/) (Paris, France)
  * Improvement of deep learning methods for information extraction from handwritten or printed documents
  * Collaboration with public and private institutions on national (Finlam, DAICREDIT, Socface) and international (Balsac, Hugin Munin) research projects
  * Customer project management (data collection, model training, results analysis, communication)
  * Development and maintenance of open source and internal ML projects (models, metrics, tools)
  * Scientific communication (scientific papers, presentations)
* Feb. 2019 - Jan. 2022: Ph.D. student, [Doptim](http://doptim.eu/) & [IRISA](https://www.irisa.fr/en), (Rennes, France)
  * Deep learning for the extraction of genealogical information from French historical registers
  * Scientific communication (scientific papers and presentations)
  * Teaching assistant for master’s level students (Agile Methodology/Development)
* Oct. 2018 - Jan. 2019: Research Engineer, [IRISA](https://www.irisa.fr/en), (Rennes, France)
  * Automatic understanding of administrative forms (CERFA documents)
* Apr. 2018 - Sept. 2018 : Research intern, Université de Rennes 1, (Rennes, France)
  * Deep Learning for automatic segmentation of multiple sclerosis lesions in MRI images

## Education

* Ph.D. in Computer Science, INSA Rennes (Rennes, France), 2022
* M.Sc. in Data Science (Research-oriented), Université Paris-Saclay (Paris, France), 2018
* M.Eng. in Computer Science and Applied Mathematics, ENSIIE (Evry, France), 2015-2018
* B.Sc. in Applied Mathematics, Univerité d’Évry (Evry, France), 2016
* Classes Préparatoires aux Grandes Ecoles - Mathematics, Physics, Lycée Cézanne (Aix-en-Provence, France), 2013-2015
* French Baccalaureate, European section, graduated with honours, Lycée Cézanne (Aix-en-Provence, France), 2013

## Skills

### Machine Learning Development
- Proficient in Python ML frameworks (Pytorch, HuggingFace, Tensorflow, Keras)
- Adherence to industry best practices: git, unit tests, code reviews, CI/CD, documentation (mkdocs)
- Development and maintenance of open-source models (PyLaia, DAN) and tools (Nerval)
- Publication of open-source models (HuggingFace, PyPi) and demonstrators (Docker, HuggingFace Spaces)
- Mastery of experiment management tools (Weights & Biases, MLFLow, Tensorboard)
- Knowledge of distributed computing on GPUs and resource management (OAR, SLURM)

### Machine Learning Research
- Expertise in deep learning, specializing in vision and language
- In-depth knowledge of state-of-the-art models: automatic text recognition, object detection, image/text classification, named entity recognition, image/text generation, machine translation, visual question answering
- Conducting research, including defining objectives, strategizing and executing experiments, and analyzing results
- Writing scientific articles (DAS, ICDAR, IJDAR)
- Delivering oral presentations at scientific conferences (DAS2022, ICDAR2023)
- Peer-reviewing scientific articles (ICFHR, ICDAR, ICML, ICLR, HIP, IJDAR, ICIAP)

### Cross-functional skills
- Project management 
  - Effective teamwork with ML engineers, computer science researchers, social scientists & historians, and archivists
  - International collaboration experience, participating in national and international research projects
  - Proficient in project administration, including writing research project proposals, progress reports, and evaluation reports 
  - Provided scientific supervision for several research interns
- Social & science
  - Organized team seminars and team-building events at IRISA
  - Co-organized the Pint Of Science festival in Rennes
  - Mentored middle school girls to challenge stereotypes related to computer science through [L codent L créent](http://lclc-rennes.irisa.fr/)
- Social representation
  - Elected as a student representative to the Board of Directors of ENSIIE (2016-2017)
  - Invited as a student representative to the Academic Council of ENSIIE (2015-2017)
  - Served as President of the Liien Association, fostering communication between students and teaching staff at ENSIIE (2016-2017)

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Talks

  <ul>{% for post in site.communications reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  