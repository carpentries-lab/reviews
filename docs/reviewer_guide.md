# Reviewer Guide

## Information for New Reviewers

Thank you for accepting the invitation to review a lesson for The Carpentries Lab!
This document provides guidance to help you with your review.

By accepting the invitation to review a lesson,
you are agreeing to abide by [The Carpentries Code of Conduct][code-of-conduct].
Please ensure that you are familiar with the Code of Conduct,
and read the information in this section before you start your review.

### The Purpose of Lesson Review

The goal of The Carpentries Lab lesson review process is to improve the lesson.
Lessons approved for inclusion in The Carpentries Lab should be ready to teach,
by any certified Carpentries Instructor with sufficient knowledge of
the domain and/or topic of the lesson.
For this reason, the focus of the lesson review process is on
the content of the lesson and the supporting material that can be used by
learners and Instructors before, during, and after a workshop.

### Review Scope

When making your review,
read through the lesson homepage and all the episode pages,
as well as the pages under the Extras dropdown (_Setup_, _Instructor Notes_, etc).
You should make a copy of the [Reviewer Checklist](#reviewer-checklist) below to guide your review,
but are also welcome to make comments and request changes outside of the points listed there.
In particular, we encourage you to make some general comments about

- the readability of the lesson.
- any key concepts or skills relevant to the lesson topic/domain that are missing from the lesson.
- how it compares to any other learning resources that you are aware of on the same/similar topics.
- its utility as a resource both for an Instructor teaching the lesson at a workshop
  and for a self-directed learner following the lesson alone.

The scope of your review is limited to the contents of the lesson website.
If the authors have included a `paper.md` file in the lesson repository,
with the intention of submitting the lesson for publication in [JOSE][jose]
after acceptance to The Carpentries Lab,
you do not need to review the contents of this file.
If you are concerned about any of the content of the lesson repository,
but which is not also represented in the lesson website,
please contact the Editor who invited you to review the lesson.

### Communication

Lesson review takes place in this publicly-visible GitHub repository.
The whole review process for a lesson is intended to take place in a single issue thread,
with Reviewers posting their reviews and comments as replies to the original submission.
Similarly, authors will then post their responses to Reviewers in the issue thread,
and so on until the lesson is approved for inclusion in The Carpentries Lab,
or the review submission is withdrawn by the author(s).

As a Reviewer, you are allowed - encouraged, even - to open issues and pull requests
to report and address areas for improvement in the lesson you are reviewing.
However, if you do this, please make sure to include links to these contributions
in your review report when you post it to the thread on this repository.

Similarly, if you communicate with the authors about the lesson and review
outside of the issue thread, please make sure to summarise, link to, and/or quote
these conversations within the thread.

## Reviewer Checklist

### Accessibility
- [ ] The alternative text of all figures is accurate and sufficiently detailed *.
  - Large and/or complex figures may not be described completely in the alt text of the image and instead be described elsewhere in the main body of the episode.
- [ ] The lesson content does not make extensive use of colloquialisms, region- or culture-specific references, or idioms.
- [ ] The lesson content does not make extensive use of contractions (“can’t” instead of “cannot”, “we’ve” instead of “we have”, etc).

\* To view the alternative text of an image, we recommend using
[the WAVE Web Accessibility Evaluation Tool][wave] or associated browser extensions.
You can also _inspect_ the source HTML of the image element in the developer tools of your web browser,
or consult the source (R)Markdown file for the relevant page in the lesson repository on GitHub.
For more information about what makes good alternative text for an image,
read [How to Design Great Alt Text: An Introduction][deque-alt-text],
and [Writing Alt Text for Data Visualization][alt-text-data]


### Content

- The lesson content:
    - [ ] conforms to [The Carpentries Code of Conduct][code-of-conduct].
    - [ ] meets the objectives defined by the authors.
    - [ ] is appropriate for the target audience identified for the lesson.
    - [ ] is accurate.
    - [ ] is descriptive and easy to understand.
    - [ ] is appropriately structured to manage cognitive load.
    - [ ] does not use dismissive language.
- [ ] Tools used in the lesson are open source or, where tools used are closed source/proprietary, there is a good reason for this e.g. no open source alternatives are available or widely-used in the lesson domain.
- [ ] Any example data sets used in the lesson are accessible, well-described, available under a CC0 license, and representative of data typically encountered in the domain.
- [ ] The lesson does not make use of superfluous data sets, e.g. increasing cognitive load for learners by introducing a new data set instead of reusing another that is already present in the lesson.
- [ ] The example tasks and narrative of the lesson are appropriate and realistic.
- [ ] The solutions to all exercises are accurate and sufficiently explained.
- [ ] The lesson includes exercises in a variety of formats.
- [ ] Exercise tasks and formats are appropriate for the expected experience level of the target audience.
- [ ] All lesson and episode objectives are assessed by exercises or another opportunity for formative assessment.
- [ ] Exercises are designed with diagnostic power.

### Design

- [ ] Learning objectives for the lesson and its episodes are clear, descriptive, and measurable. They focus on the skills being taught and not the functions/tools e.g. “filter the rows of a data frame based on the contents of one or more columns,” rather than “use the filter function on a data frame.”
- [ ] The target audience identified for the lesson is specific and realistic.

### Supporting information

- [ ] The list of required prior skills and/or knowledge is complete and accurate.
- [ ] The setup and installation instructions are complete, accurate, and easy to follow.
- [ ] No key terms are missing from the lesson glossary or are not linked to definitions in an external glossary e.g. [Glosario][glosario].

[alt-text-data]: https://medium.com/nightingale/writing-alt-text-for-data-visualization-2a218ef43f81
[code-of-conduct]: https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html
[deque-alt-text]: https://www.deque.com/blog/great-alt-text-introduction/
[glosario]: https://carpentries.github.io/glosario/
[jose]: https://jose.theoj.org/
[wave]: https://wave.webaim.org/
