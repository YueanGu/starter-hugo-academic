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
  - title: 64baud/s Optical Transmitter Driver Chip Tapeout
    company: State Key Laboratory of semiconductor superlattices, Institute of Semiconductors, Chinese Academy of Sciences (CAS), supervised by Prof. Nan Qi
    company_url: ''
#   company_logo: org-gc
    location: Beijing, China
    date_start: '2022-08-31'
    date_end: ''
    description: |2-
        Working on designing a silicon photonic micro-ring based 64baud/s based optical transmitter with 2-tap Feed-Forward Equalization(FFE) and nonlinear equalization in 45nm SOI CMOS.
        
        * Currently focusing on designing Cherry-Hooper structure continuous-time linear equalizer (CTLE) stage and 2-stage variable gain amplifier(VGA). 
        * Expected to realize 15dB boost and 12 dB gain within the bandwidth of 35GHz. Modeled CTLE in Advanced Design System and wrote verilog-A model in Virtuoso to optimize circuit design.
        * Expected to tapeout in November.

  - title: 45RFSOI Mosfet Modeling Down to Cryogenic Temperatures
    company: Berkeley Wireless Research Center(BWRC), UC Berkeley, supervised by Prof. Vladimir Stojanovic
    company_url: ''
    location: Berkeley, U.S.
    date_start: '2022-03-13'
    date_end: '2022-08-13'
    description: |2-
        Evaluated DC characteristics of transistors in the commercial 45nm PD-SOI process down to 2.5K on different types of devices.
        
        * In an optical communication system, MOSFET works in cryogenic temperature environment for quantum computing and high-performance superconducting computing. An electronic-photonic egress link is used to connect cryogenic compute node with its room-temperature main memory. However, the existing BSIM model cannot predict 45RFSOI MOSFET performance at cryogenic temperatures correctly.
        * Introduced an effective temperature formulation to capture the effects of the band tail states.
        * Extracted key design parameters including threshold voltage, effective mobility and saturation velocity, presented a modified verilog-A compact model within industry-standard Berkeley short-channel IGFET model (BSIM) framework.
        * Introduced polynomial functions to replace the original threshold voltage expression in BSIM model, which has discontinuity points at cryogenic temperatures. Modelled id-vd curve and id-vg curve with a wide temperature range and mean absolute percentage error is smaller than 0.1 percent.

  - title: High-Speed PCB Design and Layout
    company: State Key Laboratory of semiconductor superlattices, Institute of Semiconductors, Chinese Academy of Sciences (CAS), supervised by Prof. Nan Qi
    company_url: ''
    location: Beijing, China
    date_start: '2021-07-13'
    date_end: '2021-09-13'
    description: |2-
        Designed high-speed evaluation boards for 4×25Gb/s De-Serializer with Baud-Rate Sampling CDR in Altium Designer. 
        
        * Designed differential coplanar waveguide on board, calculated characteristic impedance of transmission line to decrease reflection using SI9000 and simulated its performance using Advanced Design System.
        * Used multiple decoupling capacitors to depress the current ripple and magnetic beadso suppress high-frequency noise and spike interference on signal circuits and power circuits.

  - title: Optical Ising Machine Design
    company: State Key Laboratory on Integrated Optoelectronics, Institute of Semiconductors, Chinese Academy of Sciences (CAS), supervised by Prof. Ming Li
    company_url: ''
    location: Beijing, China
    date_start: '2021-03-13'
    date_end: '2021-05-13'
    description: |2-
       * Read literature regarding optoelectronic oscillator(OEO) and summarized recent progress in the field of OEOs.
            * Assisted in the design of an optical Ising machine, which is based on OEO and can be used to solve some optimization problems. Added an optical fiber of proper length to keep the feedback signal in the same phase with the forward signal and used Matlab to process the experimental data.

design:
  columns: '2'
---
