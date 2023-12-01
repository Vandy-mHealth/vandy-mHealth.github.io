---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

The MHGH Lab has a demonstrated track record of success operating at the unique interface of mobile and global health software development. We have ongoing collaborations outside of the Chemistry Department at Vanderbilt (Biomedical Engineering, Computer Science, Data Science Institute, Medical Center, Institute for Global Health), as well as beyond campus (Columbia University, Lurie’s Children’s Hospital in Chicago, Oxford University, Leiden University Medical Center, the Kenya Medical Research Institute, the Macha Research Trust). Our full-stack mHealth applications have solved problems in infectious disease surveillance (e.g., malaria, HIV, COVID-19, schistosomiasis), global health logistics (e.g., personnel, resource, scheduling management), data science (e.g., creation of “data-rich” environments with data capture apps, large-scale structured and unstructured data analysis, machine learning and model development), and mobile health infrastructure. We have received research support from the National Science Foundation, the National Institutes of Health, the Tennessee Center for AIDS Research, the Burroughs Wellcome Fund, Amazon Web Services, and Google Cloud. Software from our lab has been deployed domestically in the US (Nashville, Baltimore, New York, Chicago) and globally (Kenya, Zambia, South Africa, Côte d’Ivoire, Brazil).

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
