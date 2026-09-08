---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    content:
      title: News📢
      subtitle: ''
      text: |-
        - [Aug. 2026] I am a TA for 11-768 AI Agents at CMU this fall!
        - [Jul. 2026] Two papers received Best Paper Awards at the ICML 2026 RLxF Workshop!
        - [May. 2026] I started my research intern at Meta in Redmond!
        - [May. 2026] PaperMentor to appear in ACL 2026 Demo and CauSciBench to appear in ICML 2026!
        - [Jan. 2026] Two papers to appear in EACL 2026!
        - [Jan. 2026] I am a TA for 11-830 Ethics, Safety, and Social Impact in NLP and LLMs at CMU this spring!
        - [Dec. 2025] Invited talk at Nice-NLP on honest language models for deductive reasoning.
        - [Nov. 2025] Two papers to appear in EMNLP 2025, see you in Suzhou!
        - [May. 2025] I started my applied scientist intern at Amazon Rufus in Seattle!
        - [May. 2025] Four papers to appear in ACL 2025!
        - [Jan. 2025] One paper to appear in ICLR 2025!
        - [Dec. 2024] Best Paper Award at the NeurIPS 2024 Pluralistic Alignment Workshop!
        - [Sep. 2024] One paper to appear in EMNLP 2024, see you in Miami!
        - [May. 2024] I started my applied scientist intern at Amazon AWS!
        - [Mar. 2024] One paper to appear in NAACL 2024 as Oral Presentation!
        - [Jan. 2024] One paper to appear in ICLR 2024, see you in Vienna!
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      text: '\* indicates equal contribution.'
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: community/citation_pub
---
