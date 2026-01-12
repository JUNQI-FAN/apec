---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Animal Physiological Ecology and Conservation Lab
      text: |
        The APEC (Animal Physiological Ecology and Conservation) Lab at Sun Yat-sen University focuses on the physiological ecology and conservation of terrestrial animals, especially reptiles and birds. Our research integrates field and controlled experiments with mechanistic and statistical models to explore how animals interact with their environment. By studying physiological responses and ecological dynamics, we assess species’ adaptability and vulnerability to environmental change. Our work aims to enhance biodiversity conservation by bridging experimental research with predictive modeling.
      image:
        filename: research_topic.jpg

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '2'

  - block: collection
    content:
      title: Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: ''
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title: Join Our Team
      subtitle:
      text: |
        We are always looking for motivated students and researchers to join our group.

        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
