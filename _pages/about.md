---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



Short bio
---

I am a Senior Machine Learning Scientist working on creating new solutions for [AWS SageMaker](https://aws.amazon.com/de/sagemaker/) and managing a team of scientists doing research on Continual Learning. I also organize the [AutoML Seminars](https://automl-seminars.github.io/) in collaboration with [Aaron Kelin](https://aaronkl.github.io/), [Arber Zela](https://ml.informatik.uni-freiburg.de/profile/zela/) and [Jovita Lukasik](https://www.uni-mannheim.de/dws/people/researchers/phd-students/jovita-lukasik/) with the support of the ELLIS units Berlin and Freiburg.

Previously I worked on exporation/exploitation methods for recommendation systems. Those solutions
were deployed in several experiences within Amazon Music, most notably the ranking of content on the homepage
and the selection of playable entities based on customers' queries for the Alexa experience.

Before joining Amazon I have been PhD Student in Applied Mathematics, at University of Milan (Italy) under the supervision of [Prof. Nicol&ograve; Cesa-Bianchi](http://homes.di.unimi.it/~cesabian/). 
During my PhD I also had the the opportunity to collaborate closely with [Prof. Claudio Gentile](https://sites.google.com/view/cgentile) and [Fabio Vitale](http://researchers.lille.inria.fr/vitale/).

Something that you cannot find on [my LinkedIn profile](http://it.linkedin.com/in/giovannizappella): some my jokes have been selected for [this book](http://www.amazon.it/Spinoza-Un-libro-serissimo-Andreoli/dp/8874245823/).



News
---

* You can now speedup your HPO/NAS jobs using [RUSH](https://arxiv.org/abs/2103.16111). An implementation of the algorithm has been added to the [SyneTune library](https://github.com/awslabs/syne-tune) (kudos to [Martin](https://scholar.google.de/citations?user=pTULHVsAAAAJ) for that).
* We created a YouTube channel for the [AutoML seminars](https://automl-seminars.github.io/) were you can find the video of the most recent talks. Check it out [here](https://www.youtube.com/channel/UC3NoO2L7cGs7O3583ig--EA/videos).


Publications
---

I do not update this page with preprints, but in most cases you can find them looking at [my Arxiv profile](https://arxiv.org/search/cs?searchtype=author&query=Zappella%2C+G).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
