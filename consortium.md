
| ![200](HESSOlogo.png) | ![200](LogoNantesU.png)    | ![](CHUNantesLogo.png) |
| ----------------------- | -------------------------- | ---------------------- |
| ![200](logoC2Care.png)  | ![200](diverssitylogo.png) | ![](poland_logo.png)   |



|<a href="https://www.hevs.ch" target="_blank"><img src="/uploads/partners/HESSOlogo.png" width="300"> </a> | <a href="https://www.univ-nantes.fr/" target="_blank"><img src="/uploads/partners/LogoNantesU.png" width="300"> </a>  |<a href="https://www.univ-nantes.fr/" target="_blank"><img src="/uploads/partners/CHUNantesLogo.png" width="300"> </a>|
            | ----------------------- | -------------------------- | ---------------------- |
            | <a href="https://www.univ-nantes.fr/" target="_blank"><img src="/uploads/partners/logoC2Care.png" width="300"> </a> | <a href="https://www.univ-nantes.fr/" target="_blank"><img src="/uploads/partners/diverssitylogo.png" width="300"> </a> | <a href="https://www.univ-nantes.fr/" target="_blank"><img src="/uploads/partners/poland_logo.png" width="300"> </a>  |



| <a href="https://www.hevs.ch" target="_blank"><img src="/uploads/partners/HESSOlogo.png" width="300"> </a> | <a href="https://www.univ-nantes.fr/" target="_blank"><img src="/uploads/partners/LogoNantesU.png" width="300"> </a>  |
            <a href="https://www.univ-nantes.fr/" target="_blank"><img src="/uploads/partners/CHUNantesLogo.png" width="300"> </a>|
            | ----------------------- | -------------------------- | ---------------------- |
            | <a href="https://www.univ-nantes.fr/" target="_blank"><img src="/uploads/partners/logoC2Care.png" width="300"> </a> | <a href="https://www.univ-nantes.fr/" target="_blank"><img src="/uploads/partners/diverssitylogo.png" width="300"> </a> | <a href="https://www.univ-nantes.fr/" target="_blank"><img src="/uploads/partners/poland_logo.png" width="300"> </a>  |




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
      columns: '1'

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'


- block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'










- block: markdown
    id: value-proposition
    content:
      title: "Why IPCs?"
      text: |
        Health systems face long waiting times and fragmented access to mental-health services.
        **Immersive Prevention Centers (IPCs)** extend clinical capacity by combining supervised
        group sessions in social VR with guided home exercises. IPC4MH focuses on **safety,
        accessibility, and evidence**—integrating with established care pathways rather than
        replacing them.

  - block: featurette
    id: pillars
    content:
      title: "Three pillars"
      items:
        - icon: network
          title: "Open Platform"
          subtitle: "Interoperable, standards-based (e.g., OpenXR), identity/session services, and secure logging."
        - icon: activity
          title: "Clinical Pilots"
          subtitle: "Junior & Senior archetypes co-designed with clinicians and end-users; multi-site deployment."
        - icon: check-circle
          title: "Evidence & Scale-up"
          subtitle: "Mixed-methods evaluation; policy & sustainability roadmap for EU health systems."
    design:
      columns: "3"

  - block: cta_card
    id: pilots-cta
    content:
      title: "Pilots & Evaluation"
      text: "See inclusion/exclusion criteria, procedures, instruments, and ethics status."
      cta:
        label: "View Pilots"
        url: "/docs/pilots/"
        icon: "arrow-right"
    design:
      background:
        color: "neutral"

  - block: timeline
    id: timeline
    content:
      title: "Timeline (M1–M36)"
      items:
        - title: "M1–M6"
          content: "Co-design & requirements baseline; governance & handbook."
        - title: "M7–M12"
          content: "Platform v1, content packaging v1; ethics approvals; pilot rehearsal."
        - title: "M13–M24"
          content: "Multi-site deployment; interim analysis; policy roundtable."
        - title: "M25–M36"
          content: "Full analysis; public deliverables; scale-up roadmap."
    design:
      style: "horizontal"  # use "vertical" if preferred

  