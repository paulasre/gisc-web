---
# Leave the homepage title empty to use the site title
title:
date: 2023-10-24
type: landing

sections:


  - block: about.avatar
    id: home
    content:
      username: admin


  - block: people
    id: people
    content:
      title: 
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Members
          - Grad Students
          - Administration
          - Visitors
          - Alumni
          - Former Members
          - PhD Students
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true


  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      count: 5  
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation


  - block: markdown
  id: posts
  content:
    title: Seminars
    subtitle: ''
    text: |
      <div style="position: relative; width: 100%; height: 0; padding-bottom: 75%; overflow: hidden;">
        <iframe
          src="https://calendar.google.com/calendar/embed?src=ma8425dntgta1ajssm1p27ic50%40group.calendar.google.com&ctz=Europe%2FMadrid&mode=AGENDA"
          style="border: 0; position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
          frameborder="0"
          scrolling="no">
        </iframe>
      </div>
  design:
    columns: '1'

  - block: collection
    id: projects
    content:
      title: Past Projects
      subtitle:
      text:
      count: 5
      offset: 0
      order: desc
      page_type: projects
    design:
      view: showcase
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: ""
      # Contact (add or remove contact options as necessary)
      email: 
      phone:
      appointment_url:
      address:
        street: Departamento de Matemáticas, Universidad Carlos III de Madrid, Avda. de la Universidad 30
        city: 28911 Leganés
        region: (Madrid) Spain
        postcode: 
        country: 
        country_code: 
      directions: 
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '40.33177'
        longitude: '-3.76698'  
      contact_links:
        - icon: 
          icon_pack:
          name: 
          link: 
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: 
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
