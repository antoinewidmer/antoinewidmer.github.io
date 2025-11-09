---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Build Your Landing Pages with Hugo Blox
      text: 🧱 EASY. FREE (OPEN SOURCE). NO-CODE  🧱
      primary_action:
        text: Get Started
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
      announcement:
        text: "Announcing the release of version 1."
        link:
          text: "Read more"
          url: "/consortium/"
    design:
    #   spacing:
    #     padding: [0, 0, 0, 0]
    #     margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
  - block: hero
    content:
      title: "**Reimagining Mental Health Prevention through Immersive Technologies**"
      announcement:
        text: "**Countries:** 🇨🇭 Switzerland · 🇫🇷 France · 🇵🇱 Poland"	
        link:
          text: "Learn more"
          url: "/consortium/"		
  - block: markdown
    content:
      title: "Immersive Prevention Centers for Mental Health"
      image:
        filename: vrheadset.png
      text: |
        <br>
        
        By combining immersive group sessions, individualized exercises, and interoperable digital infrastructures, IPC4MH seeks to **extend clinical capacity**, **improve accessibility** for vulnerable populations, and **generate robust evidence** on acceptability, usability, and clinical impact across multiple European contexts.

  - block: features
    id: quick-facts
    content:
      title: "At a glance"
      items:
        - icon: calendar
          name: "Duration"
          description: "36 months"
        - icon: globe
          name: "Countries"
          description: "Switzerland • France • Poland"
        - icon: map
          name: "Sites"
          description: "Sierre (CH), Nantes (FR), Warsaw (PL)"
        - icon: users
          name: "Populations"
          description: "Junior (NDD) • Senior (depressive/cognitive frailty)"
        - icon: layers
          name: "Work Packages"
          description: "WP1–WP6"
        - icon: file-text
          name: "Public Deliverables"
          description: "Open PDFs & DOIs"
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

  - block: hero
    content:
      title: "Funding"
      image:
        filename: THCS_Logo.jpg
      text: |
        <br>
        Supported under the THCS Partnership; views expressed are those of the authors.
---
