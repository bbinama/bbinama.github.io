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
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Postdoctoral Researcher
          company: Georg-August-Universität Göttingen
          company_url: 'https://conserwa.eu/'
          location: Göttingen, Germany
          date_start: '2024-04-01'
          date_end: ''
          description: |2-
              Department of Crop Sciences, Crop Genetics.

              * Research on how environmental variables shape evidence-based support for the transition to agroecological weed management across farming systems and European regions ([CONSERWA](https://conserwa.eu/))
        - title: Individual Consultant
          company: ICCROM
          company_url: 'https://www.iccrom.org/'
          location: Lake Malawi National Park, Malawi
          date_start: '2026-03-01'
          date_end: '2026-05-31'
          description: Capacity building on the Enhancing Our Heritage (EoH) Toolkit 2.0 management effectiveness assessment at the Lake Malawi National Park World Heritage property (online and in-person).
        - title: Individual Consultant
          company: IUCN
          company_url: 'https://www.iucn.org/'
          location: Laos
          date_start: '2024-09-01'
          date_end: '2025-03-31'
          description: IUCN evaluation of Hin Nam No National Park, a transboundary extension of Phong Nha-Ke Bang World Heritage Site nominated for the World Heritage List.
        - title: Research Assistant
          company: Bielefeld University
          company_url: ''
          location: Bielefeld, Germany
          date_start: '2019-07-01'
          date_end: '2023-03-31'
          description: |2-
              Department of Chemical Ecology.

              * Teaching: plant defence mechanisms, biology of invasive plants, data analysis with R
              * Supervision of project modules and bachelor's students
        - title: Individual Consultant
          company: UNESCO World Heritage Centre
          company_url: 'https://whc.unesco.org/'
          location: Sierra Leone
          date_start: '2022-11-01'
          date_end: '2022-12-31'
          description: Drafting and reviewing nomination dossiers and finalising maps for the Gola-Tiwai Complex.
        - title: Research Affiliate
          company: Centre of Excellence in Biodiversity and Natural Resource Management (CoEB)
          company_url: ''
          location: Rwanda
          date_start: '2018-11-01'
          date_end: '2019-06-30'
          description: Coordinated the biodiversity information system project for Rwanda and the BITC2 biodiversity data management meeting (with Oxford University).
    design:
      columns: '2'
  - block: accomplishments
    content:
      title: 'Awards & Fellow&shy;ships'
      subtitle:
      date_format: '2006'
      items:
        - title: GEO-TREES Research Award ($15,000)
          organization: GEO-TREES
          organization_url: ''
          date_start: '2025-01-01'
          description: Integrating multi-scale remote sensing and ecological data for improved biomass estimation in Kibale National Park, Uganda.
        - title: Fellow
          organization: Smithsonian Tropical Research Institute
          organization_url: 'https://stri.si.edu/'
          date_start: '2025-01-01'
          date_end: '2026-12-31'
          description: ''
        - title: MAB Young Scientist Research Award ($5,000)
          organization: UNESCO Man and the Biosphere Programme
          organization_url: 'https://www.unesco.org/en/mab'
          date_start: '2024-01-01'
          description: Understanding and managing invasive plants in forest restoration.
        - title: Young Scientist Award
          organization: Georg-August-Universität Göttingen
          organization_url: ''
          date_start: '2024-01-01'
          description: Developing predictive models for genetic–environment interactions.
        - title: Youth Jury, World Green City Award 2024
          organization: International Association of Horticultural Producers (AIPH)
          organization_url: ''
          date_start: '2024-01-01'
          description: ''
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Tropical forests
          tag: Tropical forests
        - name: Invasive plants
          tag: Invasive plants
        - name: Agroecology
          tag: Agroecology
    design:
      columns: '1'
      view: showcase
      flip_alt_rows: true
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: skills
    content:
      title: Skills
      text: ''
      username: admin
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        I welcome enquiries about collaborations, consultancies and research on biodiversity, forest restoration and plant ecology.
      email: binablaiso120@gmail.com
      address:
        city: Göttingen
        country: Germany
        country_code: DE
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: Connect on LinkedIn
          link: 'https://www.linkedin.com/in/blaise-binama'
      autolink: true
    design:
      columns: '2'
---
