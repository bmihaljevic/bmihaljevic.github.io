---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Journal papers

    Bojan Mihaljević, Pedro Larrañaga, Ruth Benavides-Piccione, Javier DeFelipe, and Concha Bielza. Comparing basal dendrite branches in human and mouse hippocampal CA1 pyramidal neurons with Bayesian networks. Scientific Reports 10, 18592, 2020.
    Mihaljević, B., Benavides-Piccione, P., Bielza, C., Larrañaga, P., and DeFelipe, J. “Classification of GABAergic interneurons by leading neuroscientists”. Scientific Data 6, Article number: 221, 2019.
    Mihaljević, B., Bielza, C., and Larrañaga, P."bnclassify: Learning Bayesian Network Classifiers." The R Journal, vol. 10, no. 2, pp. 455–468, 2018
    Mihaljević, B., Larrañaga, P., Benavides-Piccione, R., Hill, S., DeFelipe, J., and Bielza, C. “Towards a supervised classification of neocortical interneuron morphologies“, BMC Bioinformatics, vol. 19, no. 1, pp. 511, 2018
    Mihaljević, B., Benavides-Piccione, R., Guerra, L., DeFelipe, J., Larrañaga, P., Bielza, C. Classifying GABAergic interneurons with semi-supervised projected model-based clustering. Artificial Intelligence in Medicine, vol. 65, pp. 49-59, 2015,
    Mihaljević, B., Benavides-Piccione, R., Bielza, C., DeFelipe, J., Larrañaga, P. Bayesian network classifiers for categorizing cortical GABAergic interneurons. Neuroinformatics, vol. 13, no. 2, pp. 192–208, April, 2015.
    Mihaljević, B., Bielza, C., Benavides-Piccione, R., DeFelipe, J., Larrañaga, P. Multi-expert multi-dimensional classification of GABAergic interneurons with label Bayesian networks. Frontiers in Computational Neuroscience, vol. 8, pp. Article 150, 2014.

Book chapters

    Mihaljević, B., Bielza, C., and Larrañaga, P. (2018). Learning Bayesian network classifiers with completed partially directed acyclic graphs. In Kratochvíl, V. and Studený, M., editors, Proceedings of the Ninth International Conference on Probabilistic Graphical Models , volume 72 of Proceedings of Machine Learning Research, pages 272–283, Prague, Czech Republic
    Mihaljevic, B., Larrañaga, P. & Bielza, C (2013). Augmented Semi-naive Bayes Classifier. In C. Bielza et al. (editor), Advances in Artificial Intelligence, Proceedings of the 15th MultiConference of the Spanish Association for Artificial Intelligence, LNAI 8109, pages 159-167. Springer.

Workshop papers & conference abstracts

    Mihaljevic, B., Larrañaga, P. & Bielza, C (2016). Automatic classification of cortical interneuron morphologies. Proceedings of the Workshop on Advances and Applications of Data Science & Engineering, Real Academia de Ingenieria, 2016, Madrid
    Mihaljevic, B., Bielza, C. & Larrañaga, P. (2013). BayesClass: An R package for learning Bayesian network classifiers. Proceedings of UseR! –The R User Conference 2013, 53


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
