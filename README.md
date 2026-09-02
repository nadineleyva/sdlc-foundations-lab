# sdlc-foundations-lab

STUDENT WORKSHEET: SDLC, AGILE, DEVOPS & GIT FOUNDATIONS

Course Code / Subject: NTC_PC14 - Software Engineering
Student Name: Princess Nadine Leyva
Date: August 29, 2026	Section: 3.5 BSIT

GitHub Repository URL: https://github.com/nadineleyva/sdlc-foundations-lab.git

PART 1: GITHUB ONBOARDING & SETUP VERIFICATION 

Part 1: GitHub Account Creation & Onboarding 
Objective: Set up a centralized remote repository environment for future CI/CD and GitFlow collaboration.
Account Registration 
Go to github.com and click Sign Up.
Enter your academic email address, create a strong password, and select a professional username (e.g., j-perminola).
Complete the verification puzzle and enter the launch code sent to your email.
Profile & Security Setup 
Set your display name to your full name and upload a profile picture.
Go to Settings > Password and authentication and enable Two-Factor Authentication (2FA) using an authenticator app or SMS.
Verification Task 
Click the + icon in the top right and select New repository.
Name the repository sdlc-foundations-lab, set visibility to Public, check Add a README file, and click Create repository.
Copy your public repository URL to submit alongside Part 2.

Task Checklist
[ ] Created GitHub account using academic email.
[ ] Enabled Two-Factor Authentication (2FA) in Settings.
[ ] Created public repository named sdlc-foundations-lab with a README.md.
[ ] Pasted public repository link in the header above.



PART 2: REAL-WORLD ENGINEERING SCENARIOS 
Scenario A: SDLC & Framework Selection

Context: A fintech company wants to release a new peer-to-peer payment feature. A government regulatory agency requires complete compliance auditing before release, but competitors are rapidly capturing market share.
Task:
Compare Waterfall vs. Agile (Scrum) for this launch using the criteria below:
Adaptability & Time-to-Market

Regulatory & Compliance Risk Handling

Choose a hybrid or primary framework (e.g., Scrum vs. Waterfall vs. Spiral). Explain your reasoning in 2–3 sentences.


Framework Comparison Table


Criteria
Waterfall 
Agile (Scrum) 
Adaptability & Time-to-Market


Less adaptable because the project follows a fixed sequence of phases. It can take longer to release the payment feature because changes made later can cause delays and require the team to go back to previous steps. 
More adaptable because the feature can be developed in smaller sprints. The team can quickly make changes based on feedback and release working parts sooner, which is helpful since competitors are already gaining market share.
Regulatory & Compliance Risk Handling


Good for handling strict compliance requirements because the requirements, documentation, and testing can be planned and completed before the final release.
Can handle compliance by including security and regulatory requirements in each sprint. However, because the company needs a complete compliance audit before release, the team would still need to make sure all documentation and compliance checks are completed before launching.


2. Framework Recommendation & Justification:
Which primary or hybrid framework (e.g., Scrum, Waterfall, or Spiral) do you recommend for this fintech regulatory project? Explain your choice in 2–3 sentences.

Answer: I would recommend a hybrid approach using Scrum and Waterfall. Scrum would help the team develop the payment feature faster and make changes when needed, while Waterfall can be used for the documentation, testing, and required compliance audit. This way, the company can keep up with competitors while still making sure the feature follows the government’s regulations.







Scenario B: DevOps & CI/CD Pipeline Breakdown

Context: A team merges code, but the production app breaks during deployment because testing was done manually on individual laptops rather than in an automated pipeline.
Task:
Identify where the communication and process gap occurred between Dev and Ops.
Map out the automated CI/CD pipeline stages (Plan -> Code -> Build -> Test -> Release -> Deploy ->Operate -> Monitor) and state which stage would catch this bug before it reaches production.

1. Gap Analysis:
Identify where the communication and process breakdown occurred between Dev and Ops.
Answer: The breakdown happened because the Dev team tested the code only on their individual laptops, while the Ops team deployed it in the production environment. Since there was no automated testing pipeline to check the merged code in a similar environment before deployment, bugs or compatibility issues were not caught early. This caused the application to break when it was finally deployed.

2. Pipeline Stage Identification:
Fill in the missing stages of the continuous assembly line and circle/bold the stage that catches local testing bugs before production release:

Plan -> Code ->  Build  ->  Test  -> Release -> Deploy -> Operate -> Monitor

Scenario C: Git Lifecycle & Branching Strategy
1. Data Movement Command Mapping

Write the standard Git command used to transfer code between each environment:

Working Directory ->  Staging Area: git add


Staging Area -> Local Repository: git commit


Local Repository -> Remote Repository (GitHub): git push


Remote Repository -> Working Directory: git pull


2. GitFlow Collision Prevention:
Explain how utilizing Feature Branches and a Develop branch prevents two developers from overwriting each other's code on Main. ( 2 to 3 sentences)

Answer: Feature branches allow each developer to work on their own changes without affecting the main branch. The develop branch is then used to combine and test everyone’s work before it is moved to the main. This helps prevent developers from accidentally overwriting each other’s code and makes it easier to find and fix conflicts.




FINAL SUBMISSION CHECKLIST
[ ] Part 1 checklist completely verified.
[ ] All scenario questions answered clearly.
[ ] Repository set to Public for grading access.



