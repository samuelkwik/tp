---
layout: page
title: Benny's Project Portfolio Page
---

### Project: TutorSynch

Given below are my contributions to the project.

* **New Feature**: Added the ability to record a student's payment information. [\#59](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/59)
  * What it does: Allows the user to record the Tutoring Fee and Payment Date of a student.
  * Highlights: This command is carefully setup in a way that allows for future enhancement (such as using Payment Date to indicate late payment, early payment, or due soon). This requires carefully thought out OOP design principles.
* **New Feature**: Added the ability to use custom color code for Tags. [\#73](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/73)
  * Highlights: Contains a Tooltip such that, when hovering over a tag, shows the Hex Color Code of the tag.
* **New Feature**: Updated payment information to contain payment status. [\#101](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/101)
  * Highlights: Contains `PaymentInfo.Builder` to dynamically build a `PaymentInfo` object, instead of using multiple manually-defined constructors.

* **Documentation**:
  * Ui Mockup:
    * Designed `docs\images\Ui.png` and `docs\images\findLeeYuResult.png` via PowerPoint. [\#38](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/38)
  * User Guide:
    * Did cosmetic tweaks to existing documentations mentioning `AddressBook` instead of `TutorSynch`. [\#46](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/46)
    * Added documentation for the feature `payment`. [\#59](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/59)
    * Updated documentation for `paymentStatus` for the feature `payment`. [\#101](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/101)
  * Developer Guide:
    * Modified existing use cases for `UC01 - Add a new student`, `UC03 - Delete a student`, and `UC04 - List all students`. [\#46](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/46)
    * Added use cases for `UC02 - Edit a student's information`, `UC05 - Record payment information for existing student`, `UC06 - Bulk delete student records`, `UC07 - Compare progress between two students`. [\#46](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/46)

* **Community**:
  * PRs reviewed (with non-trivial review comments): [\#58](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/58#pullrequestreview-2686240341)

* **Testing**:
  * Performed minor Smoke Testing for V1.3. [\#68](https://github.com/AY2425S2-CS2103-F15-2/tp/issues/68)
    * Bugs spotted during minor Smoke Testing: [\#81](https://github.com/AY2425S2-CS2103-F15-2/tp/issues/81), [\#82](https://github.com/AY2425S2-CS2103-F15-2/tp/issues/82)

* **Bug Fixes**:
  * Rectified the following bugs: [\#84](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/84), [\#85](https://github.com/AY2425S2-CS2103-F15-2/tp/pull/85)

<!--
* **New Feature**: Added the ability to undo/redo previous commands.
  * What it does: allows the user to undo all previous commands one at a time. Preceding undo commands can be reversed by using the redo command.
  * Justification: This feature improves the product significantly because a user can make mistakes in commands and the app should provide a convenient way to rectify them.
  * Highlights: This enhancement affects existing commands and commands to be added in future. It required an in-depth analysis of design alternatives. The implementation too was challenging as it required changes to existing commands.
  * Credits: *{mention here if you reused any code/ideas from elsewhere or if a third-party library is heavily used in the feature so that a reader can make a more accurate judgement of how much effort went into the feature}*

* **New Feature**: Added a history command that allows the user to navigate to previous commands using up/down keys.

* **Code contributed**: [RepoSense link]()

* **Project management**:
  * Managed releases `v1.3` - `v1.5rc` (3 releases) on GitHub

* **Enhancements to existing features**:
  * Updated the GUI color scheme (Pull requests [\#33](), [\#34]())
  * Wrote additional tests for existing features to increase coverage from 88% to 92% (Pull requests [\#36](), [\#38]())

* **Documentation**:
  * User Guide:
    * Added documentation for the features `delete` and `find` [\#72]()
    * Did cosmetic tweaks to existing documentation of features `clear`, `exit`: [\#74]()
  * Developer Guide:
    * Added implementation details of the `delete` feature.

* **Community**:
  * PRs reviewed (with non-trivial review comments): [\#12](), [\#32](), [\#19](), [\#42]()
  * Contributed to forum discussions (examples: [1](), [2](), [3](), [4]())
  * Reported bugs and suggestions for other teams in the class (examples: [1](), [2](), [3]())
  * Some parts of the history feature I added was adopted by several other class mates ([1](), [2]())

* **Tools**:
  * Integrated a third party library (Natty) to the project ([\#42]())
  * Integrated a new Github plugin (CircleCI) to the team repo

* _{you can add/remove categories in the list above}_
-->
