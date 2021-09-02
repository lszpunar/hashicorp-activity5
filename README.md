# Instructions
Please review and revise the multiple-choice question and performance-based scenario. We have provided a simplified question style guide, but it is not an exhaustive list of things to check for. Use your own experience to edit the exam content. Feel free to use GitHub comments to explain your thought process, assumptions you have made, or call out unanswered questions. We are not expecting you to edit this question/scenario exactly like we would. We are more interested in your approach to assessment editing.

**Note about `multiple-choice-question.md`:** During production, our multiple-choice questions are formatted with the answers in the YAML front matter, followed by the question itself in markdown. This (backward) format is rendered during the exam experience to look like a multiple choice question should—with the question first followed by clickable radio buttons next to each possible answer. Here is what the activity question might look like on the exam-platform:

**Note about `performance-based-scenario.md`:** You can assume the candidate has access to the lab envrionment discribed in the scenario and instructions on how to access it.

![markdown example of performance based layout](/images/hashicorp-activity-multiple-choice-screenshot.PNG)

## Steps
1. Create a PR (pull request) with your edits for both the multiple-choice question, and the performance based scenario. If doing two PRs (one for each file) is easier, that is fine too. The number of commits does not matter.

2. Use the commenting feature in GitHub or send a separate email to Lszpunar@hashicorp.com with any notes about your work that you would like to share.

# Style Guide

## Both Content Types
- Use plain language in the active voice
- This is a formative assessment. Questions/scenarios should not be a teaching moment
- Spell out acronyms on the first occurance
- Fence words to be code formatted in `backticks`
- Capitalize proper nouns. If in doubt, check how brand names are spelled on their own site to see if you should capitalize or not.

## Multiple-choice
- Format the item stem as complete sentences. Format it as a question with a question mark
- Answers can be sentence fragments

## Performance-based
- Organize the scenario into the following section headings:
    - Your Environment
    - Instructions
    - Important Notes
- Format instructions into clear numbered/bulleted steps where possible
- Here is a screenshot of the recomended layout for performance based content:
![markdown example of performance based layout](/images/hashicorp-activity-performance-based-sample.PNG)
