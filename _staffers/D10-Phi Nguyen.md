---
name: Phi Nguyen, Mason Walk, Gavin Schag, Bijan Arbab

email: phi@sdge.com

photo:

website: https://www.sdge.com/

industry: true

domain: D10

title: "Time to Energize: Turning Messy Operational Data into Trustworthy Timelines"

bio: |
  I lead the data science and analytics team in SDG&E’s Business Transformation Office, where we apply data science, business intelligence, and process improvement to real utility operations problems. I am a UC San Diego alumnus, and I have mentored UCSD HDSI capstone students on SDG&E projects, most recently the 2025–2026 cohort. My team works with large-scale operational data in SAP, AWS, and Databricks, with a focus on forecasting, optimization, and turning messy enterprise data into decision-ready reporting. I enjoy helping students see how a rigorous data science approach translates into measurable business and customer impact.

description: |
  Under recent California legislation, large electric utilities must report how long it takes to connect new customers to the grid. The reporting is intended to make performance transparent, test compliance with statewide targets, and identify where process, staffing, materials, or customer handoffs are delaying service. SDG&E has responded by submitting the required biannual reports and improving the underlying data and analytics used to distinguish utility-controlled time from customer-controlled time, supporting its mission to deliver safe, reliable, and timely service to customers. At SDG&E, these timelines are not stored in one place; they must be reconstructed from work-management data (job notifications, prerequisite tasks, work requests, and milestone dates), which was built to run field operations rather than to answer regulatory questions. This domain explores how to turn messy operational records into trustworthy, auditable timelines through data modeling, process mapping, reconciliation of missing or inconsistent dates, and measuring data quality. Methods include SQL and pandas data wrangling, process mining, time-to-event modeling, and data-quality scoring.

  In Quarter 2, students will propose their own extensions. Examples include a project score reflecting how well a job went and how reliable its data inputs were; estimated completion dates for in-flight jobs; and linking in additional sources such as text reviews from SDG&E’s customers, field data, and inventory and material availability.

summer: |
  Suggested reading and review before Winter:
  • CPUC energization data reporting requirements and template: https://www.cpuc.ca.gov/industries-and-topics/electrical-energy/infrastructure/energization/energization-data-reporting-requirements-and-data-reporting-template

  • CPUC Decision 24-09-020, which establishes the eight-step energization process: https://docs.cpuc.ca.gov/PublishedDocs/Published/G000/M540/K806/540806654.PDF. Read the eight steps and think about what event or date would mark the start and end of each one.

  • SDG&E public biannual energization report: https://www.sdge.com/sites/default/files/regulatory/PUBLIC%20R24-01-018%20SDG%26E%20Biannual%20Energization%20Report.pdf. Focus on the report summary, reporting methodology, and identified data-quality limitations.

  • Skim the intro documentation for process mining (e.g., the PM4Py library) and time-to-event analysis (e.g., the lifelines library).

  • Search SAP Plant Module data model. Focus on how project and job notifications, work orders, prerequisite tasks, status changes, and milestone dates relate to one another across the energization lifecycle.

time: Flexible

modality: Hybrid meetings at SDG&E campus and Zoom/MS Teams

prerequisites: |
  None beyond the base prerequisites. Helpful but not required: process mining

style: |
  I will lead the section and be there every week. Members of my data science and analytics team, who work with this data daily, will support with data questions, domain context, and office hours. I will be hands-on in Winter, walking students through the process, the data, and the reporting requirements and reviewing their work at regular checkpoints. In Spring I expect students to own problem formulation, modeling choices, and delivery. I will also connect them with business subject-matter experts for feedback. The goal is for students to move from guided to independent over the two quarters, while always having someone to ask when they get stuck on the data.

seats: 6

tag: app

goal: |
  By the end of Quarter 1, students will have recreated the energization timeline reporting requirements from three inputs: SAP project data (CPD), the process diagram, and the written data requirements. Specifically, they will:
  1. Learn the eight-step energization process and how SAP records each step.
  2. Define the start and end event for each step and map each one to the SAP fields and tasks that capture it.
  3. Calculate the resulting timelines for a sample of jobs, including time with the utility versus time with the customer, and validate them against known results.
  4. Document data gaps and quality issues and deliver a reproducible notebook or pipeline plus a short write-up.
  5. Propose a Quarter 2 extension, such as a project score, estimated completion dates, or linking in additional data sources.

notes: |
  Because this project uses internal utility operations data, a data-sharing agreement (and possibly student NDAs) will likely be needed. I would like to start that process early with HDSI so students have data access at the beginning of Winter. Students do not need any energy-industry background. The work supports real regulatory reporting at SDG&E, so students will see their analysis applied to a real business problem.
---
