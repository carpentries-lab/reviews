# Author Guide

## Checklist for Submitting Authors
The checklist below will be presented from a template
when the author first
[opens an issue on this repository to submit their lesson for review][new-submission].

---

1. What is the title of the lesson?


2. Provide URLs to
    - The lesson repository:

    - The lesson homepage:


3. Briefly describe the lesson (50 words or fewer).
   What does it aim to teach and to whom?


4. If you are submitting this lesson for review on behalf
   of multiple authors, list the GitHub usernames below for
   all authors who should receive notifications relating to the review.


5. Provide URLs to workshop webpages and/or an issue
   on the lesson repository from any beta pilots of the lesson.
   (A beta pilot is a workshop where the lesson was taught
   by any instructor who was not part of the lesson development team
   before the pilot took place.)


6. (Optional) If you have obtained a DOI for the lesson via Zenodo,
   paste that DOI below.


7. If the lesson is similar in topic to any other lesson
    already included in CarpentriesLab and/or
    The Carpentries Lesson Programs (Software, Library, and Data Carpentry),
    briefly describe how this lesson differs and
    why a separate lesson was developed.


8. Check the boxes (replace `[ ]` with `[x]`) to confirm that the lesson

    - [ ] is the the original work of the author(s),
      or that any content derived from another source is reused with permission and appropriate attribution.
    - [ ] aligns with [The Carpentries Code of Conduct][1].
    - [ ] is published under a [CC-BY][2] or [CC0][3] license.
    - [ ] uses [The Carpentries lesson template][4] without significant customisation/adaptation.


9. If you wish to submit the lesson for publication in
   [the Journal of Open Source Education (JOSE)][5]
   ([see the repository README for more details][6]):

    - [ ] check the box to confirm that your repository includes
         `paper.md` and `paper.bib` files as described in
         [the JOSE submission guide for learning  modules][7].


 10. Would you like to recommend anyone we could contact as a reviewer for your lesson?
     We prefer to invite other members of The Carpentries community to review lessons but
     you are free to suggest anyone you think could be an appropriate author.
     **Please do not tag them in the issue (with "@" + username)** -
     the Editor will tag potential reviewers after editorial checks have been completed.**
     **Please read our [Conflict of Interest Policy][8] before suggesting reviewers.**

[1]: https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html
[2]: https://creativecommons.org/licenses/by/4.0/
[3]: https://creativecommons.org/publicdomain/zero/1.0/
[4]: https://github.com/carpentries/styles/
[5]: https://jose.theoj.org/
[6]: https://github.com/carpentries-lab/reviews#joint-review-with-jose
[7]: https://openjournals.readthedocs.io/en/jose/submitting.html#how-to-prepare-a-learning-module-submission
[8]: https://github.com/carpentries-lab/reviews/blob/main/docs/coi_policy.md

## JOSE Submission

When submitting their lesson(s) to The Carpentries Lab, 
authors may indicate that they wish to also the lesson(s) for publication in JOSE
(see question 9 in the checklist above).
If they choose this option, the authors should submit their lesson(s) to JOSE
_after it/they have been accepted to The Carpentries Lab_.

Authors should prepare a `paper.md` file and associated `paper.bib` in the lesson repository,
as described in [JOSE's documentation for new submissions][jose-submission-guide].
For multiple lessons forming a single curriculum,
we recommend that the `paper.md` and `paper.bib` files be added to the repository of a
"workshop overview" lesson site 
(see [the Metagenomics curriculum][metagenomics-overview] in the Lab as an example).

We recommend that authors do not finalise the article to be published about their lesson(s) 
until after review has been completed in The Carpentries Lab.
When the paper is ready, it should be [submitted to JOSE as normal][jose-submission]
as a _learning module_.
The JOSE submission form includes a text field for a message to the editors:
authors should use this field to indicate that the lesson(s) being submitted have been
reviewed already in The Carpentries Lab.
If you are doing this, please make sure that you include a link to the review thread for your lesson(s)!

[The _Joint Submission with JOSE_ section of the repository README][6]
has more datails about the joint review process.


[jose-submission]: https://jose.theoj.org/papers/new
[jose-submission-guide]: https://openjournals.readthedocs.io/en/jose/submitting.html
[metagenomics-overview]: https://carpentries-lab.github.io/metagenomics-workshop/
[new-submission]: https://github.com/carpentrieslab/reviews/issues/new?assignees=&labels=&template=submission.md
