---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        IPC4MH - Immersive Prevention Center for Mental Health
      image:
        filename: ipclogo.png
      text: |
        <br>
        
        IPC4MH is shaping the future of mental health prevention through immersive environments, advanced sensing, and human-centred innovation.
        
    - block: features
    id: quick-facts
    content:
      title: "At a glance"
      items:
        - icon: calendar
          title: "Duration"
          text: "36 months"
        - icon: globe
          title: "Countries"
          text: "Switzerland • France • Poland"
        - icon: map
          title: "Sites"
          text: "Sierre (CH), Nantes (FR), Warsaw (PL)"
        - icon: users
          title: "Populations"
          text: "Junior (NDD) • Senior (depressive/cognitive frailty)"
        - icon: layers
          title: "Work Packages"
          text: "WP1–WP6"
        - icon: file-text
          title: "Public Deliverables"
          text: "Open PDFs & DOIs"
    design:
      columns: "3"

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

  
  
---
