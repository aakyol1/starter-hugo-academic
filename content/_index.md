---
# Leave the homepage title empty to use the site title
title: Ali Akyol
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: portfolio
    id: projects
    content:
      title: Working Papers
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: akyol (at) telfer (dot) uottawa (dot) ca
      contact_links:
        - icon: google-scholar
          icon_pack: ai
          name: Google Scholar
          link: 'https://scholar.google.com.au/citations?user=jo6u02UAAAAJ'
        - icon: ssrn
          icon_pack: ai
          name: SSRN
          link: 'https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=523338'
        - icon: orcid
          icon_pack: ai
          name: ORCID
          link: 'https://orcid.org/0000-0002-3493-0359'
        - icon: researcherid
          icon_pack: ai
          name: ResearcherID
          link: 'https://publons.com/researcher/2495820/ali-c-akyol/'
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: 'https://ca.linkedin.com/in/ali-akyol-309a631a3'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
