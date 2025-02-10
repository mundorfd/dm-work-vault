---
title: EMGT 562 Interactive Quiz User Stories
created: 2025-02-04 14:02
modified: 2025-02-05 9:02
share: true
---

# EMGT 562 Interactive Quiz User Stories

Suggested user stories for the custom web interactive app based on the asana request, [EMGT 562 - S25 - Quiz (Matching Activity) - Asana](https://app.asana.com/0/1208553871383665/1208573157201912)

## User Stories

### Student User Stories

- **As a student**,
   I want to match items in three columns by selecting the correct corresponding terms,
   So that I can demonstrate my understanding of change management frameworks.
	- _Related Requirement: Matching functionality (Scalable Layout)_
- **As a student**,
   I want the matching items to appear in a randomized order each time I attempt the activity,
   So that I cannot simply memorize positions and must actively engage with the content.
	- _Related Requirement: Randomization of items for each attempt (Randomization)_
	- _note from Doug: Re: randomness: the dev version of the app is random but set via a seed, so it produces the same results each time. That'll help us with testing but won't appear to meet that requirement. The prod version then switches to actual random._
- **As a student**,
   I want an optional text box to explain my reasoning for my matches,
   So that I can justify my answers and earn additional points.
	- _Related Requirement: Commenting capability (Commenting Capability)_
- **As a student**,
   I want to submit my completed matches and comments,
   So that the instructor can review and grade my work.
	- _Related Requirement: Submission system for student responses (Grading)_
- **As a student**,
   I want to receive feedback on my matches and comments after submission,
   So that I can learn from my mistakes and improve my understanding.
	- _Related Requirement: Feedback mechanism for students after submission (Grading, Instructor Control)_

### Instructor User Stories

- **As an instructor**,
   I want to create a matching activity by defining the correct combinations of terms,
   So that students can engage with the material interactively.
	- _Related Requirement: Instructor input of correct match combinations (Instructor Control)_
- **As an instructor**,
   I want the ability to enable or disable the optional comment box,
   So that I can customize whether students need to provide explanations for their matches.
	- _Related Requirement: Commenting capability toggle (Instructor Control, Commenting Capability)_
- **As an instructor**,
   I want the matching items to be randomized for each student,
   So that students must focus on understanding concepts rather than memorizing positions.
	- _Related Requirement: Randomization of items (Randomization)_
- **As an instructor**,
   I want to view student submissions, including their matched items and comments,
   So that I can assess their understanding and provide feedback.
	- _Related Requirement: Instructor access to student responses (Grading, Commenting Capability)_
- **As an instructor**,
   I want to assign a customizable point value to each correctly matched item and comment,
   So that I can control grading criteria and allow for partial credit.
	- _Related Requirement: Customizable scoring system (Grading)_
- **As an instructor**,
   I want the ability to modify the terms, correct matches, and redeploy the activity,
   So that I can reuse the exercise in different weeks or future course offerings.
	- _Related Requirement: Instructor control over content and redeployment (Instructor Control)_
- **As an instructor**,
   I want an exportable grading report that shows student scores and comments,
   So that I can efficiently track student performance and import scores into my LMS.
	- _Related Requirement: Exportable grading report (Grading, Instructor Control)_
- **As an instructor**,
   I want to control the number of rows, columns, and distractor terms,
   So that I can adjust the difficulty and complexity of the activity.
	- _Related Requirement: Scalable layout with instructor-defined parameters (Scalable Layout, Instructor Control)_

[[UQATE|UQATE]]

[[EMG 562|EMG 562]]
