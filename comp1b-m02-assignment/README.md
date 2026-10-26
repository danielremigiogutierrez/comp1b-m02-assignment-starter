# comp1b-m02-assignment

## This starter is for one task only

Course: COMP1B. Module 2. Task: assignment.

Use a NEW folder and NEW GitHub repository named `comp1b-m02-assignment` (or an equally clear unique name). The lecture activity and coding assignment must have different repository URLs. This ZIP contains only this task’s project.

## Goal and scope

Measure the 240px content-box and border-box states, record content/border-box/margin footprints, compare display modes, and leave a flexible card tested at 375 and 1024px.

Follow the matching Canvas directions and existing rubric for the precise required evidence. The activity is required/ungraded; the coding assignment/draft/final uses its existing rubric. The starter is scaffolding, not a finished solution.

## Open and run

1. Extract this ZIP. Open the `comp1b-m02-assignment` folder containing index.html in VS Code, rather than the ZIP or a parent folder.
2. Root files supplied: index.html, main.css.
3. Open index.html in a browser; save and refresh after source changes. No npm packages or build command are required.

## Source record

- Starter: comp1b-m02-assignment-starter.zip
- Earlier work copied, if any: [repository URL + baseline commit, or none]
- My own changes for THIS task: [explain]

## Measured box model

Write actual observations in this README.md. Replace placeholders with your results, including failures and limitations. A planned test is not a completed test. Add rows as needed; a check that found no defect should say so honestly. The matching Canvas task defines the work due at this stage.

| Controlled state | Content width | Border-box width | Outside left / right margins | Total horizontal footprint | Prediction and measured result |
| --- | --- | --- | --- | --- | --- |
| 240px content-box | [240px] | [276px] | [12px each] | [300px] | [After the lesson in class, I remembered it would be 240, 276, 300. I was correct this time.] |
| 240px border-box | [204px] | [240px] | [12px each] | [264px] | [Like earlier, the lesson helped me see it would be 204, 240, 264.] |

## Display and flexible-card evidence

Block / inline / inline-block comparison: [When I use either block or inline-block, the box stays intact. They would move a little (up & down) whenever I would flip between the two. However, there wasn't really a significant difference. However, when I used inline, the box fell apart. It broke and didn't hold the content inside anymore.]

Final flexible-card choices: [sizing, padding, border and margin decisions]

| Check | Actual result / correction / retest |
| --- | --- |
| 375px | [375px, padding 20px, border 3px, margin 0 0 1rem] [375, 421, 421] [Because the margins did not affect the horizontal size, the footprint was the same.] |
| 1024px | [1024px, padding 20px, border 3px, margin 0 0 1rem] [1024, 1070, 1070] [Like earlier, the margins did not affect the horizontal size, so the footprint was the same.] |
| CSS validation | ['Congratulations! No Error Found.'] |

## Independent transfer check

Answer the new case in the matching Canvas assignment. Predict before using the inspector; explain the rule behind your answer, then record your own measured test and correction.

- Case and conditions: [280px width, 20px padding, 3px border, 12px margin, content-box]
- Prediction and calculation: [I think it will show up as 280, 326, 350. I think by adding the left & right sides of both padding and border measurements, you get the border box, which I ended up getting 326px. By adding both sides of margin, I ended up with 350.]
- Inspector observation: [I saw that I was correct. It gave me the answer I predicted.]
- Minimal correction and reason: [I already got the correct answer.]
- Retest and explanation: [Same answer as above.]

Temporary inspector experiments do not replace the assignment's final saved flexible-card CSS.

## Predictions and actual tests

Write actual observations in this README.md. Replace placeholders with your results, including failures and limitations. A planned test is not a completed test. Add rows as needed; a check that found no defect should say so honestly. The matching Canvas task defines the work due at this stage.

| Action / input / conditions | Prediction before running | Actual before change | My change or none | Actual after / explanation |
| --- | --- | --- | --- | --- |
| [] | [prediction] | [observation] | [file / selector / change or none] | [retest] |

## Submission checklist

- [ ] My source and README belong to this task’s separate folder/repository.
- [ ] I saved, committed, pushed, and opened this repository on GitHub to verify the files.
- [ ] Repository URL: [https://github.com/danielremigiogutierrez/comp1b-m02-assignment-starter]
- [ ] Live GitHub Pages URL(s), when required: [THIS project’s deployed URL(s)]
- [ ] I submitted THIS repository URL to the matching Canvas item using Website URL and checked the submission confirmation.

Activity Text Entry remains available only as described in the Canvas directions. A push or deployment does not submit Canvas work. Future-use drafts have no current submission or deadline until activated.

## Academic integrity and privacy

AI-assisted or AI-generated content is prohibited. Complete and explain your own work under the existing course policy. Do not include keys, credentials, tokens, or private settings. Preserve the supplied license and identify reused material.
