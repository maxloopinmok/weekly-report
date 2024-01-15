As of Sunday 11.15pm this week, I have worked on the following:

# Primary Task:
- To learn how to do better programming and researching to support and contribute to our projects.

## Nine Subtasks:

### 1) Attend the Mirdin course on Monday at 11am and 10am on alternating weeks over a few months.
Actions:
- In progress.
- I attended the Mirdin Unit 4 tutorial at 10am on Monday.
- I tried to read some of the relevant readings and have tried the exercises and drills until "The Equational Reasoning Drill".  I have yet to do "Mechanical Refactoring", "Hidden Coupling Drill", and "Case Study: A Tale of Two Parsers".
- Some relevant links:
    - https://advanced-software-design.disco.co/p/advanced-software-design-feb-2023/dashboard
    - https://app.slack.com/client/T9F5D6U4R/C04MPE8AULX
    - https://app.slack.com/client/T012Q6P08BY/C04N48SN57V

### 2) Attend the Well Typed Haskell course on Monday at 3pm.
Actions:
- In progress.
- Some relevant links:
    - https://chat.well-typed.com/cclaw/channels/town-square
    - https://code.well-typed.com/maxloo
    - https://code.well-typed.com/cclaw/haskell-course

### 3) Develop a workflow to load in the article chunks (FTA/...../*.html) into the web mockup
Actions:
- Completed.
- As an extension to this task, I may explore more NLP to compare the HTML documents.
- This may dovetail with Item 6 in this report due to a common exploration of BERT.
- I've successfully used distilBERT with Python on Google Colabs to highlight the similarities and differences between 2 sections of text from FTAs.  However, this semantic comparison may not be very accurate, and depends on the adjustment of the similarity_threshold in the function compare_and_highlight before calling the function.
- Some relevant links:
    - https://github.com/maxloosmu/mti
    - https://github.com/smucclaw/usecases/tree/main/vue
    - https://github.com/maxloosmu/bert

### 4) Take a look at the impress.js repo and see how to adapt that framework for our needs
Actions:
- I've installed and tried impress.js.
- I've updated the source file of impress.js to remove all rotations during transitions.  I've also updated the index.html of the fta example to constrain slide transitions to only the FTAs.  Both efforts are just for a better understanding of impress.js.
- I've also tried using impress.js with my Flask-Vue-Bulma stack, but although I managed to get the slides working, I could not stop the slides.
- I finally tried to directly create slide transitions from Vue-Bulma itself using CSS, but although I managed to get the first slide shown, I have not yet gotten the slides to successfully transition.
- Some relevant links:
    - https://github.com/smucclaw/impress.js/blob/fta/examples/fta/index.html
    - https://github.com/smucclaw/impress.js/blob/fta/src/impress.js
    - https://github.com/smucclaw/usecases/tree/main/vue

To Do:
- To get slide transitions working, and ensure they can be stopped.

### 5) Learning AWS S3, Textract, DynamoDB
Actions:
- Have not worked on this due to work on other tasks.
- Some relevant links:
    - https://eresources.nlb.gov.sg/main/browse?browseBy=type&filter=18

### 6) Explore the Semantic possibilities of Legal BERT and other alternatives for our L4 DSL
Actions:
- This may dovetail with Item 3 in this report due to a common exploration of BERT.
- Some relevant links:
    - https://github.com/maxloosmu/weekly-report/blob/main/Review%20of%20GPT4%20from%20a%20user%20perspective.md

### 7) Encode S10 of policy into L4 with considerations and trade-offs in comments
Actions:
- Some relevant links:
    - https://docs.google.com/spreadsheets/d/1u5aizEaRfnDJD7N0Zz4pJeBd3lMx36BdqKwdE-lppV8/edit#gid=0
    - https://docs.google.com/spreadsheets/d/1dZrYqf87UZGzEfz_vxYXFl-v7vlyddweYNy6wtV2WEU/edit#gid=1890284544

### 8) [Stage 2] [everyone] **Sketch** backend implementation (but NOT the compiler)
Actions:
- I've created a draft webpage frontend and backend implementation plan with the help of GPT4.
- Some relevant links:
    - https://app.asana.com/0/1204211889758721/1204379268152484/f
    - https://smucclaw.slack.com/archives/C024BC50FFA/p1681724568268529

### 9) Testing Parsr and other PDF text extraction tools
- I've tried Parsr but unsure if it has run properly because output file with text extracted from pdf is not found.
- I've found and tried successfully an alternative: pdf2htmlEX, but I've realised that this Docker image creates HTML files riddled with excessive CSS and JavaScript.
- Some relevant links:
    - https://pypi.org/project/parsr-client/
    - https://github.com/axa-group/Parsr
    - https://github.com/axa-group/Parsr/blob/master/server/defaultConfig.json
    - https://github.com/axa-group/Parsr/issues/663
    - https://github.com/smucclaw/usecases/tree/main/vue/pdf2htmlex

To Do:
- To try Pandoc.

# Secondary Tasks:

### 10) Occasional work related matters as they come by from Slack, Asana, emails or our meetings currently or in the past.
Actions:
- I contributed to CCLAW Slack discussions.
- I updated Asana:
    - https://app.asana.com/0/1189209909138566/list
- There was no Monday FrontEnd meeting at 1.30pm.
- I attended Thursday's Tech meeting at 2.30pm.
- I regularly use https://chat.openai.com/.

# Upcoming Leave and Medical Appointments:
- Tuesday 9 May 2023 10.50am CGH Digestive Diseases Centre
- Wednesday 17 May 2023 3pm CGH Urology Clinic
- Wednesday 17 May 2023 3.40pm/4.10pm CGH Radiology DDR CT Scan
- Friday 19 May 2023 11am IMH Clinic B
- Tuesday 30 May 2023 9.40am/10.40am CGH Urology Clinic
- Friday 24 November 2023 10.15am SNEC Eye Clinic @ CGH