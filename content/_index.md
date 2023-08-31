---
# Leave the homepage title empty to use the site title
title: Ming Shan
date: 2023-08-30
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: Ming-Shan-Hee
  - block: markdown
    id: news
    content:
      title: News
      text: "
        **Aug 2023**: Invited to serve as a Reviewer for EMNLP 2023 <br/>
        **Jul 2023**: Three papers accepted at [ACM MM'23](https://www.acmmm2023.org/) <br/>
        **Apr 2023**: Two papers accepted at [IJCAI'23](https://ijcai-23.org/) <br/>
        **Mar 2023**: One paper accepted at [ACM MMSys'23](https://2023.acmmmsys.org/) <br/>
        **Dec 2022**: Passed Qualifying Preliminary Examination (QPE) ! <br/>
        **Jan 2022**: One paper accepted at [TheWebConf'22](https://www2022.thewebconf.org)
      "
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  # - block: collection
  #   id: news
  #   content:
  #     title: News
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - news
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  - block: collection
    id: publication
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
---
