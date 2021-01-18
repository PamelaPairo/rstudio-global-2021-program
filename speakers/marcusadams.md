---
talk_id: 187
url: https://global.rstudio.com/student/page/40622
type: talk
track: B
blocks:
  - foxtrot
  - lima
name: Marcus Adams
affiliation: Merck
links:
  homepage: null
  twitter: "@mtotheadams"
  github: https://github.com/adamsma
  linkedin: https://www.linkedin.com/in/marcus-adams-6779852a
location: United States
---

# Not The App We Deserve. The App We Need: Putting a GMP Shiny App into Production

In February 2020, the Digital Proactive Process Analytics (DPPA) group within Merck’s manufacturing division officially launched a Shiny app to automate the creation of Continuous Process Verification (CPV) reports into production. That’s right – the almighty, mysterious, coveted production.  From a technical perspective, the app is nothing particularly special (except other than getting LaTeX successfully installed to support the use of R Markdown). Users enter a few parameters and out pops a PDF with a series statistical analyses of a product’s quality testing data. The R blogosphere is filled with examples of similar Shiny apps.

What mattered was the app was in production, and furthermore it was approved for GMP use.  This meant these reports could be submitted to the FDA and other regulatory agencies. This meant the data could be used to support product release decisions. This meant Merck’s engineers were about to save thousands of hours per year in compiling data, generating charts, and calculating summary statistics. This was the app manufacturing sites needed.

Most of the work in getting this app into production was not implementing the top-level features. Sorry, no discussion of fancy statistical process control methods here. Instead this talk will discuss some of the many things the development team (none of which came from a software development background) needed to learn in order to create a robust, secure, and maintainable production application.


# Speaker bio

Marcus Adams is an Associate Director, Engineering at the biopharmaceutical company Merck. He earned his BEng and MS in Chemical Engineering from the University of Delaware and Villanova University, respectively. His more than decade of experience at Merck spans the bio-pharmaceutical spectrum and includes experience in pre-clinical PK/PD modeling, product commercialization, in-line technology support, procurement, and vaccine distribution technology development. Currently, he works as a part of the Digital Proactive Process Analytics team, leveraging Merck’s Big Data Platform in the development of manufacturing information data models, report automation tools, and integrated-systems analysis applications.  His professional interests include effective digital visualization, reproducible research/analysis, and convincing his coworkers of the diverse, flourishing world beyond Microsoft Excel.
