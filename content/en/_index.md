---
# Leave the homepage title empty to use the site title
title:
date: 2023-01-28
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    id: experience
    content:
      title: Experience
      design:
        columns: '2'
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: "Software Development Manager"
          company: "Higeco More"
          company_url: "https://www.higecomore.com/en"
          location: Belluno, Italy
          date_start: '2023-01-01'
          date_end: ""
          description: |
            Responsabilities include:

            * management of the sofware development workgroup;
            * maintenance of the existing software products;
            * managing client requests and reports;
            * defining procedures, tools and methods for software development.

        - title: "Data scientist and developer"
          company: "Higeco"
          company_url: "https://www.higeco.com/en"
          location: "Belluno, Italy"
          date_start: "2019-09-16"
          date_end: "2022-12-31"
          description: |
            Responsibilities include:

            * analysing and handling the vast amount of collected data;
            * short and medium term forecasting of power requirements for microgrids and production plants;
            * project development and research in new, unexplored possibilities of the company's hardware.
              In particular, I was the lead developer of a new Energy Management System for power and industrial plants,
              currently used in applications in four continents.

        - title: "Visiting scientist"
          company: "International Centre for Theoretical Physics - Earth System Physics group"
          company_url: "https://www.ictp.it/research/esp/members.aspx"
          location: "Trieste, Italy"
          date_start: "2019-03-15"
          date_end: "2019-08-31"
          description: |
            Responsibilities include:

            * analysing and handling data;
            * modelling climate and hydrology on HPC clusters;
            * technical support;
            * data visualisation;
            * creation of graphical user interfaces for data analysis.

        - title: "PhD Student"
          company: "University of Trieste, dept. of Mathematics and Geosciences"
          company_url: "https://web.units.it/dottorato/esfm/en"
          location: "Trieste, Italy"
          date_start: "2015-11-01"
          date_end: "2019-03-15"
          description: |
            PhD program in Earth Science and Fluid Mechanics in collaboration with ICTP-ESP and the Allianz insurance company.  
            Project title: _Climate change impact on flood hazard over Italy_.  
            Title obtained _cum laude_.

        - title: "Postlauream collaborator"
          company: "International Centre for Theoretical Physics - Earth System Physics group"
          company_url: "https://www.ictp.it/research/esp/members.aspx"
          location: "Trieste, Italy"
          date_start: "2015-03-20"
          date_end: "2015-11-01"
          description: Tidying up the work from my Master's thesis.

        - title: "Master's Student"
          company: "University of Trieste, dept. of Physics"
          company_url: "https://df.units.it/"
          location: "Trieste, Italy"
          date_start: "2012-12-20"
          date_end: "2015-03-20"
          description: |
            Specialisation in Earth Sciences.  
            Thesis title: _Evaluation of the impact of the high resolution for the Alpine region in a present-day and future scenario simulation with the regional climate model RegCM4_.  
            Evaluation: 110/110 _cum laude_.

        - title: "Bachelor Student"
          company: "University of Trieste, dept. of Physics"
          company_url: "https://df.units.it/"
          location: "Trieste, Italy"
          date_start: "2009-10-01"
          date_end: "2012-11-26"
          description: |
            Scholarship obtained from the [Collegio Fonda](https://www.collegiofonda.it/) after written and oral examinations.  
            Thesis title: _Use of the Arduino microcontroller to carry out measurements in the teaching of Physics in laboratories_ (in Italian).  
            Evaluation: 106/110.
---
