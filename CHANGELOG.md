# Changelog

## 2026-11-06: Rating Column Cells Stay on One Line

- In the table's `A2b` column, each cell ("`A` Expert", "`2` 26–50%", and "`b` Reviewed") now stays on one line. On narrower screens, "26–50%" split after the dash, and "Reviewed" dropped below its `b`. A non-breaking space (`&nbsp;`) now joins each code to its word.
- "26–50%" no longer splits across two lines after the dash. Invisible word joiners (`&#8288;`) on each side of the dash stop the browser breaking the line there, and the text still reads "26–50%". Markdown tables on GitHub can't set column widths, so this is the way to keep it together.

## 2026-10-25: Approver, Optional Badge, and Listing

- The Maintainer Expertise row now gives the spec's rule for teams: rate "the least experienced person who can approve a change without someone more experienced also approving it", the same wording as the rating form on aicoderating.com. It said "whoever approves changes", which left out who counts. A team where junior reviewers can merge on their own could have rated itself at a senior reviewer's level.
- Step 1 of Rate Your Project now marks the README badge as optional: "copy the `ACR.md` and README badge (optional)". Only `ACR.md` is required by the spec, and the old wording made the badge sound like part of rating a project. This matches the home page on aicoderating.com, which no longer lists the badge as a step.
- Step 5 now gives a reason to ask to be listed in Rated Projects: "so others can find your project". Getting projects listed is the current stage of the roadmap, and the step was easy to read past as the last of five.

## 2026-10-08: Maintainer Expertise Starts From the Solo Case

- The Maintainer Expertise row now says it rates how experienced the person responsible for the code is: you in a solo project, whoever approves changes on a team. It used to say "who approves the code", which readers of solo projects took to mean the developer. The meaning is unchanged. This matches the same rewording on aicoderating.com.
