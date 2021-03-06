# Author's Guide

This document contains guidelines for new authors joining the OWASP Mobile Security Testing Guide (MSTG). Please read them carefully.

## Picking a Role

The OWASP MSTG is a community effort, and in principle everyone is welcome to contribute or become a chapter owner. We don't check CVs and there is no formal process to go through. That said, keep in mind that with great power comes great reponsiblity: Once you have commited to a role, you'll be expected to deliver quality content.

### Lead Author

The lead author takes high-level ownership of a whole chapter or test case category such as [Testing Sensitive Data Storage on Android](Document/Testcases/0x01a_OMTG-DATAST_Android.md). A lead author should:

1. Contribute an significant amount of quality content to the chapter(s) owned;
2. Coordinate the work of authors and reviews working on subchapters;
3. Manage pull requests for this chapter and ensure the quality of contributions;
4. Moderate discussions about issues in the chapter(s) owned;
5. Ensure that milestones for chapter are reached on time.

Lead authors are expected to be highly responsive and actively engage in discussions on [GitHub](https://github.com/OWASP/owasp-mstg/issues) and [Slack](https://owasp.slack.com/messages/project-mobile_omtg/details/). This requires significant effort, so you should only take up this role if you're sure you can put in the time.

#### Permissions

Lead authors are given write access to the repository so they can review and merge pull requests for their respective chapters.

### Contributor

Contributors write content such as single test cases or parts of test cases. For example, a contributor could submit a how-to for testing the custom URL schemes exported by an app. Contributors should:

1. Deliver quality content on the selected topic;
2. Actively engage with the chapter owners and reviewers via [GitHub](https://github.com/OWASP/owasp-mstg/issues) and [Slack](https://owasp.slack.com/messages/project-mobile_omtg/details/)

#### Permissions

Contributors are not provided with write access and should instead fork a working copy of the repo. The chapter owner is responsible for reviewing and merging the content.

### Reviewer

Reviewers are subject matter experts that help ensure the quality of the MSTG. A reviewer will usually pick several chapters and test case groups, and are called upon whenever new content has been added to the selected sections of the MSTG. The reviewer should:

1. Ensure technical accuracy of the content reviewed;
2. Check for grammar and spelling errors;
3. Provide feedback and actively engage with the chapter owners and reviewers via [GitHub](https://github.com/OWASP/owasp-mstg/issues) and [Slack](https://owasp.slack.com/messages/project-mobile_omtg/details/)

In our experience, opinions will differ in many cases. Whenever differences cannot easily be resolved, open an issue on GitHub and bring it up for discussion. Usually, the open discussion will result in a resolution - if not, the lead author of the chapter in question has the last word.

## How to Become an Author

To become a contributor or reviewer, contact the lead author responsible for the section you are interested in. You can find their name and GitHub handle in the [README](README.md). Please always check with the responsible person first, or you might end up working on a chapter that's already being done by someone else. Asking on the Slack channel is another option.

## Authoring Credit

Contributors are added to the [acknowledgements table](Document/0x02-Frontispiece.md#acknowledgements) based on their [contributions](https://github.com/OWASP/owasp-mstg/graphs/contributors) logged by GitHub. The list of names sorted by the quantity of contributions, in the order generated by GitHub's algorithm. Commit more than 500 total lines of content and you'll move to the "authors" column, otherwise you'll be listed in the "contributors" column.

The "Reviewers" column is for people that haven't submitted their own pull requests, but created issues or given useful feedback in other ways. Please ping us if you are one of those people and haven't already been added.

## Style Rules

A few basic rules, such as title capitalization and references, are listed in the [style guide](style_guide.md). By following these rules, and matching your contribution to the general writing style of the MSTG, you can help us to minimize the effort for re-formatting and rephrasing the content.

## Writing a Test Case

A "test case" is a how-to with step-by-step instructions on how to test for a specific issue. We have defined a list of [63 test cases](all_tests.md) based on the requirements in the [OWASP MASVS](https://github.com/OWASP/owasp-masvs), for the most part maintaining the same order and structure. For example, OWASP MASVS V2.9 maps to the test case OMTG-DATAST-009:

- OWASP MASVS V2.9 "Verify that sensitive data does not leak to backups."
- OMTG-DATAST-009: "Test for Sensitive Data in Backups"

A good way to start is by browsing the [test case list](all_tests.md) and picking a topic that doesn't have content yet. Then, simply use an [existing test case](Document/Testcases/0x00a_OMTG-DATAST_Android.md#OMTG-DATAST-009) as a template to create your own one.

## Attribution and Acknowledgement

You'll be added to the [acknowledgements section](https://github.com/OWASP/owasp-mstg/blob/master/Document/0x01-Acknowledgements.md) of the guide following your contribution.
