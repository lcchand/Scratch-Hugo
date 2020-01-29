---
# YAML Front Matter
#
#
#
# Page Title
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
#
#
#
# Title for Category Section <h2>
section_title: Section Title
#
#
#
# Support Tab - defines On Call Groups for Table
# bh_support - Business Hours support
bh_support:
  - snow_group: Servicenow 1
    id: 12345
    amcom: AMCOM 1
  - snow_group: Servicenow 2
    id: 67890
    amcom: AMCOM 2
  - snow_group: Servicenow 3
    id: 54321
    amcom: AMCOM 3
#
#
#
# ah_support - After Hours Support
# sames as buisness hours array structure above
# I will create this later...
#
#
#
# Edit date for Support Table - Please update for every change
support_date: January 30, 2020
#
#
#
# End of YAML front matter
---

