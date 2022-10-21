---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Research
subtitle: 

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: CEO
    company: GenCoin
    company_url: ''
#   company_logo: org-gc
    location: California
    date_start: '2021-01-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * Analysing
        * Modelling
        * Deploying

  - title: Professor of Semiconductor Physics
    company: Berkeley Wireless Research Center(BWRC), University of California, Berkeley
    company_url: ''
    location: Beijing, China
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: |2-
        Evaluated DC characteristics of transistors in the commercial 45nm PD-SOI processfor down to 2.5K cryogenic temperatures on different types of devices.
        
        * Extracted key design parameters and analyzed them with the corresponding low-temperature effect.
        * Introduced an effective temperature formulation to capture the effects of the band tail states and presented a compact model that corrects the low-temperature threshold voltage for the band-tail states, Fermi–Dirac statistics, and interface traps.
        * Used Cadence Virtuoso and Matlab to model the experimental data of 45nm PDSOI CMOS from room temperature down to cryogenic temperatures.

  - title: Designed a testboard system for a clock-data-recovery chip
    company: GenCoin
    company_url: ''
    location: Beijing, China
    date_start: '2021-01-01'
    date_end: ''
    description:
    #description: |2-
        Designed a testboard system for a clock-data-recovery chip using Altium Designer.
        
        * Calculated the characteristic impedance of transmission line to decrease the reflection and increase the transmission of the high frequency signals.
        * Modeled and simulated the differential coplanar waveguide on board, using Advanced Design System.
        * Chose a kind of low dropout regulator for the powerboard according to key parameters and used multiple decoupling capacitors to depress the current ripple.

design:
  columns: '2'
---
