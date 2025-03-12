# Editor Guide

You can use the [Editor checklist template](./templates/editor_checks_template.md) as a basis for responses on the review thread.

## Editor Checklist

### Accessibility

(Note to Editor: [the WAVE Web Accessibility Evaluation Tool][wave]
(also available as a browser extension) may be useful when completing these checks.)

- [ ] All figures are also described in image alternative text or elsewhere in the lesson body.
- [ ] The lesson uses appropriate heading levels:
    - [ ] h2 is used for sections within a page.
    - [ ] no “jumps” are present between heading levels e.g. h2->h4.
    - [ ] no  page contains more than one h1 element i.e. none of the source files include first-level headings.
- [ ] The contrast ratio of text in all figures is at least 4.5:1.

### Content

- [ ] The lesson teaches data and/or computational skills that could promote efficient, open, and reproducible research.
- [ ] All non-discussion exercises have solutions. (See note 1, below.)
- [ ] Opportunities for formative assessments are included and distributed throughout the lesson sufficiently to track learner progress. (We aim for at least one formative assessment every 10-15 minutes.)
- [ ] Any data sets used in the lesson are published under a permissive open license i.e. CC0 or equivalent.

### Design

- [ ] Learning objectives are defined for the lesson and every episode.
- [ ] The target audience of the lesson is identified specifically and in sufficient detail.

### Repository

The lesson repository includes:
  - [ ] a CC-BY or CC0 license.
  - [ ] a CODE_OF_CONDUCT.md file that links to The Carpentries Code of Conduct.
  - [ ] a list of lesson maintainers.
  - [ ] tabs to display Issues and Pull Requests for the project.

### Structure

- [ ] Estimated times are included in every episode for teaching and completing exercises.
- [ ] Episodes lengths are appropriate for the management of cognitive load throughout the lesson.

### Supporting information

The lesson includes:

  - [ ] a list of required prior skills and/or knowledge.
  - [ ] setup and installation instructions.
  - [ ] a glossary of key terms or links out to definitions in an external glossary e.g. [Glosario][glosario].

[glosario]: https://carpentries.github.io/glosario/
[wave]: https://wave.webaim.org/

### Notes
1. Ideally we would like to see solutions for every challenge, since they provide helpful guidance for Instructors and learners. However, in cases where no single solution is really feasible, guidance on the kinds of things that learners should consider/look out for/do when completing the exercise is sufficient. (See the solution provided with [the main exercise in the DC Ecology Spreadsheets lesson](https://datacarpentry.github.io/spreadsheet-ecology-lesson/01-format-data.html#exercise) for an example.) Solutions are not required for exercises with the `discussion` class (rendered with a speech bubble icon at the top-left of the exercise box).


## Issue Labels

Issue labels should be used by Editors to track the progress of each review.
There should be only one of these labels on each review issue:
when the Editor adds a new label,
they should remove the label for the preceding stage of the review process.
(These issue labels are taken from the set
[used by ROpenSci in their software package review system][ropensci-editor-guide].)

- `1/editor-checks`:
  the Editor is working through initial checks on the lesson,
  described in the [Editor checklist](#editor-checklist) below.
- `2/seeking-reviewers`:
  the points in [the Editor checklist](#editor-checklist) have been addressed satisfactorily,
  and the Editor is now looking for Reviewers for the lesson.
- `3/reviewer(s)-assigned`:
  the Editor has assigned at least one Reviewer to the lesson.
- `4/review(s)-in-awaiting-changes`:
  review(s) have been posted to the issue thread and are waiting to be addressed by
  the author(s)
- `5/awaiting-reviewer(s)-response`:
  author(s) has responded to and/or attempted to address to reviewer comments
  and the issue is waiting for reviewers to respond.
- `6/approved`:
  all Reviewer comments have been addressed satisfactorily
  and the lesson is approved for inclusion in The Carpentries Lab.

  [ropensci-editor-guide]: https://devguide.ropensci.org/editorguide.html

## Workflow

### Initial submission
Once the editor confirmed that the lesson was suitable to be sent out to review,
these steps need to be taken:
1. ask the authors to add a review badge to the README for their lesson repository using the code below and replacing `<issue number>` with the issue associated with the submission:
   ```
   [![The Carpentries Lab Review Status](http://badges.carpentries-lab.org/<issue number>_status.svg)](https://github.com/carpentries-lab/reviews/issues/<issue number>)
   ```
2. set the GitHub topics, if they haven't been set yet. Topics should include at least `lesson` and the appropriate life-cycle badge.

### Performing editorial checks
Using the checklist above, perform the basic editorial checks to ensure that the
lesson is ready for review.
Share the results of the checklist with the authors in the review thread,
highlighting any points that need to be addressed before the lesson can be reviewed.

When the editorial checks have been satisfied,
you can begin looking for reviewers.

### Finding reviewers
Each lesson should be reviewed by two people.
Ideally, reviewers will provide a diversity of perspectives, representing e.g.
different levels of expertise in the lesson topic and
different local/domain communities.
This helps to ensure that the lesson is accessible
and guards against [expertise awareness gap](https://carpentries.github.io/instructor-training/04-expertise.html#mind-the-gap).

So far, reviewers have been identified through a combination of:

* responses to the Lab review volunteer form
* the Editor's professional network
* exploring the lists of 'watchers' on the repository of the lesson under review,
  membership of any relevant Slack channels, etc

Invitations to review have been made privately, by email/Slack message,
followed by public invitation and confirmation on the review thread in this repository.
(See examples of these posts in [the _Good Enough Practices_ lesson review thread](https://github.com/carpentries-lab/reviews/issues/24#issuecomment-1451796473).)

Potential reviewers frequently ask what the time frame is for review.
We do not have a strict policy,
but hope to receive reviews within six weeks of confirmation.
However, we would rather receive good reviews from reviewers who are a good fit for the lesson.
So the Editor should encourage would-be reviewers to
estimate a timeframe that would work for them
and try to communicate that to the authors.

When looking for reviewers, please keep in mind our
[Conflict of Interest Policy](https://github.com/carpentries-lab/reviews/blob/main/docs/coi_policy.md)

#### Support for Editors from The Carpentries
The [Curriculum Team](mailto:curriculum@carpentries.org) can provide a list of
people who have volunteered to review lessons in the Lab,
and can contact people on your behalf
e.g. where you have identfied a potential reviewer from the community,
whose details are stored in AMY.

### Supporting the Review Process
After assigning reviewers, the Editor should continue to support the process by:

- answering questions from authors and reviewers in the review thread
- reaching out to reviewers/authors after a long period without response
- summarising reviews when they come in,
  e.g. to collate and re-state the requested changes for authors to respond to
- providing guidance on which changes are within scope for a reviewer to request,
  based on [the _Review Scope_ section of the Reviewer Guide](https://github.com/carpentries-lab/reviews/blob/main/docs/reviewer_guide.md#review-scope)
  in combination with the Editor's own judgement.

#### Public vs private communication

Apart from the initial approach to potential reviewers,
we prefer for all communication about the lesson review to take place
in the same issue thread.
Reviewers are encouraged to contribute directly in issues and pull requests to
the repository of the lesson under review, but are asked to link to these
"side conversations" from the main review thread.

Nevertheless, the editor may feel that it is sometimes necessary to communicate
in private e.g. to reach out to unresponsive authors or reviewers,
or to help resolve conflicts.
If you do communicate with reviewers and/or authors privately, please
ensure that anything pertinent to the review of the lesson
(e.g. feedback given or changes requested)
is summarised in the review thread.
If you are in any doubt about whether it is appropriate to contact authors/reviewers
privately during the review, please reach out to the [Curriculum Team](mailto:curriculum@carpentries.org).

### Accepting lessons
After authors have responded to reviewer's comments and requested changes,
the Editor should ask the reviewers to evaluate the lesson again
and respond (at least) once more, either
to confirm that they are happy for the lesson to be accepted, or
to make further comments/request additional changes.
([See the _Good Enough Practices_ review thread for an example](https://github.com/carpentries-lab/reviews/issues/24#issuecomment-1588926986).)

### After acceptance
1. If the author(s) have indicated that they would like to submit the lesson to JOSE,
  assist them with getting started on that process and ensure that the JOSE editors
  are aware that the lesson has already been accepted to The Carpentries Lab.
2. Update `life_cycle` banner config
3. Remove the `5/awaiting-reviewer(s)-response` label and add the `6/approved`
  label to the relevant issue in `carpentries-lab/reviews`
4. If the lesson repository includes a `master` branch, rename it to `main`
5. Work with The Carpentries Infrastructure Team to set up cloud hosting for the lesson,
  to provide a `carpentries-lab.org` URL
6. Publish a new release via Zenodo

For a collection/curriculum composed of multiple lessons:

1. Ensure that the lesson repositories are named consistently,
   to signal their relationship more clearly
   and so that they appear together in any alphabetical listing of repositories in the Lab.
