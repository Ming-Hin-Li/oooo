---
name: Bug report
about: Something on the site is broken
title: "[BUG] Insert title here"
labels: Bug, Needs More Info
assignees: codingcodymiller
---
**For staff use only**
### Bug Report
> _To be filled out by author. Add the `Bug` and `Needs More Info` labels. Assign issue to self on creation._
#### **Describe the Bug**
A clear and concise description of what the bug is.
#### **Steps To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error
#### **Expected Behavior**
A clear and concise description of what you expected to happen.
#### **Actual Behavior**
A clear and concise description of what actually happened. If applicable, add screenshots to help explain your problem.
#### **Device Information**
- Device: [Hardware device make and model, e.g. Lenovo Thinkpad Yoga 15]
- OS: [Operating system name and version, e.g. Windows 10, Version 1903]
- Browser: [Web browser client and version, e..g. Google Chrome, Version 76]
- Other Related Software (If Applicable): [Web server, middle scripting engine, database, etc. and version]
#### **Additional context**
Add any other context or screenshots about the problem here.
> _After all the above sections are filled out, remove the `Needs More Info` label, then assign issue to the repository maintainer._
---
### Pre-Implementation Checklist
> _To be filled out by repository maintainer._
#### **Validation**
- [ ] The Report section is filled out completely.
  - If not, add `Needs More Info` label and assign back to author.
- [ ] This bug is not a duplicate of another request.
  - If it is, reference duplicate issue, add `Duplicate` label, and close issue.
- [ ] This bug is not intended functionality.
  - If it does, add `By Design` label and close issue.
- [ ] This bug is reproducible with the provided steps.
  - If it isn't, add `Not Reproducible` label and assign back to author.
#### **Budgetting**
- [ ] The fix will provide enough benefit to justify the cost.
  - If not, add the `Won't Fix` label and close issue.
- [ ] The fix can be budgetted for active development at this time.
  - If not, add the `Postponed` label.
> _After all the above checks pass, add the `Ready for Implementation` label and assign issue to implementer._
---
### Implementation
> _To be filled out by implementer._
#### **Steps Taken**
A sequential set of steps taken to uncover and fix the bug.
1. How was the root cause of the bug narrowed down?
1. How was the bug fixed?
#### **Root Cause**
What was the root cause of the bug?
#### **Prevention**
How can this type of bug be prevented in the future?

#### **Opening Pull Requests**
Because this repository has its pull request template designed for student use, pull requests that are made by staff must use the template for internal repo pull requests.
1. Start a new pull request as normal.
1. Pick the `base` and `compare` branches.
1. Replace the body of the pull request with the contents of the [Internal Repository Pull Request Template](https://github.com/Learning-Fuze/internal-repo-template/raw/master/.github/PULL_REQUEST_TEMPLATE.md).
1. Follow the directions on the pull request.
After an attempted fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=bug_fix.md&&labels=Bug+Needs%20More%20Info&&title=[BUG]%20Insert%20Fix%20Title%20Here
```

#### **After Merging Pull Requests**
After a pull request referencing this issue has been merged, update the implementation sections above with any new information.

> _After all debugging has been completed and integrated into the main development branch, add the `Ready for Testing` label, remove the `Ready for Implementation` label, and assign issue to tester for verification._
---
### Verification
> _To be filled out by tester._
Commit tested on main development branch: [commit #]
- [ ] Application runs without crashing.
- [ ] Bug is fixed, following the Steps To Reproduce.
> _After the main development branch is verified to meet the spec, add the `Verified` label, remove the `Ready for Testing` label, then close the issue._
---
name: Enhancement request
about: Suggest a user-facing functional improvement to this project.
title: "[NEW/INCREMENTAL/CONTENT] Pick one, then insert title here"
labels: Enhancement, Needs More Info
assignees: codingcodymiller
---
**For staff use only**
### Enhancement Request
> _To be filled out by author. Add the `Enhancement` and `Needs More Info` labels. Assign issue to self on creation._
#### **Is your enhancement request related to a problem? Please describe.**
A clear and concise description of what the problem is. Ex. I'm always frustrated when [...]
#### **Is your enhancement related to one or more existing features? Which one(s)?**
Yes or No. Describe existing feature(s) from a user's perspective, including references to related issues.
#### **Describe the solution you'd like**
A clear and concise description of what you want to happen.
#### **Describe alternatives you've considered**
A clear and concise description of any alternative solutions or enhancements you've considered.
#### **Additional context**
Add any other context, screenshots, or design documents about the enhancement request here.
> _After all the above sections are filled out, remove the `Needs More Info` label, then assign issue to the repository maintainer._
---
### Pre-Implementation Checklist
> _To be filled out by repository maintainer._
#### **Validation**
- [ ] The Request section is filled out completely.
  - If not, add `Needs More Info` label and assign back to author.
- [ ] This request is not a duplicate of another request.
  - If it is, reference duplicate issue, add `Duplicate` label, and close issue.
- [ ] This request does not run counter to intended functionality.
  - If it does, add `By Design` label and close issue.
#### **Budgetting**
- [ ] The request will provide enough benefit to justify the cost.
  - If not, add the `Won't Fix` label and close issue.
- [ ] The request can be budgetted for active development at this time.
  - If not, add the `Postponed` label.
> _After all the above checks pass, add the `Ready for Implementation` label and assign issue to implementer._
---
### Implementation
> _To be filled out by implementer._
#### **Steps**
If the enhancement can be broken down into sub-tasks/-issues, add checklist for completion. Reference any sub-issues directly. Steps are checked off as they are added to a pull request.
- [ ] Add checklist of sub-tasks, referencing sub-issues directly
- [ ] Check off sub-issues as they are given the `Verified` label
- [ ] Check off sub-tasks as they are implemented and added to a pull request

#### **Opening Pull Requests**
Because this repository has its pull request template designed for student use, pull requests made by staff must use the template for internal repo pull requests.
1. Start a new pull request as normal.
1. Pick the `base` and `compare` branches.
1. Replace the body of the pull request with the contents of the [Internal Repository Pull Request Template](https://github.com/Learning-Fuze/internal-repo-template/raw/master/.github/PULL_REQUEST_TEMPLATE.md).
1. Follow the directions on the pull request.
After the enhancement has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=enhancement.md&&labels=Enhancement+Needs%20More%20Info&&title=[NEW/INCREMENTAL/CONTENT]%20Insert%20Fix%20Title%20Here
```

#### **After Merging Pull Requests**
After a pull request referencing this issue has been merged, check off any completed steps in the Implementation section above.

> _After all the above steps have been completed and integrated into the main development branch, add the `Ready for Testing` label, remove the `Ready for Implementation` label, and assign issue to tester for verification._
---
### Verification
> _To be filled out by tester._
Commit tested on main development branch: [commit #]
- [ ] Application runs without crashing.
- [ ] Enhancement is fully implemented and meets the spec.
> _After the main development branch is verified to meet the spec, add the `Verified` label, remove the `Ready for Testing` label, then close the issue._
---
name: Quick-Fix - Code Cleanup
about: Code formatting, commented code deletion, debugging artifact removal, or other <30-minute non-functionality-modifying source code fix
title: "[CLEANUP] QUICK-FIX: insert title here"
labels: Technical Debt
labels: Technical Debt, Needs More Info
assignees: (none)

---

**For staff use only**

### Quick-Fix - Documentation
> _To be filled out by author. Add the `Technical Debt` label. Assign issue to self on creation._
> _To be filled out by author. Add the `Technical Debt` and `Needs More Info` labels. Assign issue to self on creation._
#### **Short Description**
In two sentences or less, describe the code mess.

#### **Additional context**
Add any other links, screenshots, or context about the issue here.

> _After all the above sections are filled out, move on to the implementation._
> _After all the above sections are filled out, replace the `Needs More Info` label with `Ready for Implementation`, then move on to the implementation._
---

@@ -28,7 +28,7 @@ Add any other links, screenshots, or context about the issue here.
#### **Opening a Pull Request**
After the fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=quick_fix_code_cleanup.md&&labels=Technical%20Debt&&title=[CLEANUP]%20QUICK-FIX%20-%20Insert%20Title%20Here
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=quick_fix_code_cleanup.md&&labels=Technical%20Debt+Needs%20More%20Info&&title=[CLEANUP]%20QUICK-FIX%20-%20Insert%20Title%20Here
```

> _After all steps have been completed and integrated into the main development branch, this issue should automatically close._
---
name: Quick-Fix - Content Update
about: A <30-minute site content update
title: "[CONTENT] QUICK-FIX: insert title here"
labels: Enhancement
labels: Enhancement, Needs More Info
assignees: (none)

---

**For staff use only**

### Quick-Fix - Content Update
> _To be filled out by author. Add the `Enhancement` label. Assign issue to self on creation._
> _To be filled out by author. Add the `Enhancement` and `Needs More Info` labels. Assign issue to self on creation._
#### **Short Description**
In two sentences or less, describe the content being updated.

#### **Additional context**
Add any other links, screenshots, or context about the content update here.

> _After all the above sections are filled out, move on to the implementation._
> _After all the above sections are filled out, replace the `Needs More Info` label with `Ready for Implementation`, then move on to the implementation._
---

@@ -28,7 +28,7 @@ Add any other links, screenshots, or context about the content update here.
#### **Opening a Pull Request**
After the fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=quick_fix_content_update.md&&labels=Enhancement&&title=[CONTENT]%20QUICK-FIX%20-%20Insert%20Title%20Here
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=quick_fix_content_update.md&&labels=Enhancement+Needs%20More%20Info&&title=[CONTENT]%20QUICK-FIX%20-%20Insert%20Title%20Here
```

> _After all steps have been completed and integrated into the main development branch, this issue should automatically close._
---
name: Quick-Fix - Documentation
about: A typo, grammar, formatting, or other <30-minute documentation fix
title: "[DOCUMENTATION] QUICK-FIX: insert title here"
labels: Technical Debt
labels: Technical Debt, Needs More Info
assignees: (none)

---

**For staff use only**

### Quick-Fix - Documentation
> _To be filled out by author. Add the `Technical Debt` label. Assign issue to self on creation._
> _To be filled out by author. Add the `Technical Debt` and `Needs More Info` labels. Assign issue to self on creation._
#### **Short Description**
In two sentences or less, describe the documentation problem and solution.

#### **Additional context**
Add any other links, screenshots, or context about the documentation issue here.

> _After all the above sections are filled out, move on to the implementation._
> _After all the above sections are filled out, replace the `Needs More Info` label with `Ready for Implementation`, then move on to the implementation._
---

@@ -28,7 +28,7 @@ Add any other links, screenshots, or context about the documentation issue here.
#### **Opening a Pull Request**
After the fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=quick_fix_documentation.md&&labels=Technical%20Debt&&title=[DOCUMENTATION]%20QUICK-FIX%20-%20Insert%20Title%20Here
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=quick_fix_documentation.md&&labels=Technical%20Debt+Needs%20More%20Info&&title=[DOCUMENTATION]%20QUICK-FIX%20-%20Insert%20Title%20Here
```

> _After all steps have been completed and integrated into the main development branch, this issue should automatically close._
---
name: Quick-Fix - Minor Bug
about: A localized <30-minute bug fix with no downstream dependencies
title: "[BUG] QUICK-FIX: insert title here"
labels: Bug
labels: Bug, Needs More Info
assignees: (none)

---

**For staff use only**

### Quick-Fix - Minor Bug
> _To be filled out by author. Add the `Bug` label. Assign issue to self on creation._
> _To be filled out by author. Add the `Bug` and `Needs More Info` labels. Assign issue to self on creation._
#### **Short Description**
In two sentences or less, describe the bug and its fix.

#### **Additional context**
Add any other links, screenshots, or context about the issue here.

> _After all the above sections are filled out, move on to the implementation._
> _After all the above sections are filled out, replace the `Needs More Info` label with `Ready for Implementation`, then move on to the implementation._
---

@@ -28,7 +28,7 @@ Add any other links, screenshots, or context about the issue here.
#### **Opening a Pull Request**
After the fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=quick_fix_minor_bug.md&&labels=Bug&&title=[BUG]%20QUICK-FIX%20-%20Insert%20Title%20Here
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=quick_fix_minor_bug.md&&labels=Bug+Needs%20More%20Info&&title=[BUG]%20QUICK-FIX%20-%20Insert%20Title%20Here
```

> _After all steps have been completed and integrated into the main development branch, this issue should automatically close._
---
name: Technical Debt report
about: The source code needs non-functional improvement.
title: "[DOCUMENTATION/CLEANUP/PERFORMANCE/MAINTAINABILITY/DEPENDENCY] Pick one, then
  insert title here"
labels: Technical Debt, Needs More Info
assignees: codingcodymiller
---
**For staff use only**
### Technical Debt Report
> _To be filled out by author. Add the `Technical Debt` and `Needs More Info` labels. Assign issue to self on creation._
#### **Is your technical debt fix request related to a problem? Please describe.**
A clear and concise description of what the problem is. Ex. I'm always frustrated when [...]
#### **Describe the solution you'd like**
A clear and concise description of what you want to change.
#### **Describe alternatives you've considered**
A clear and concise description of any alternative solutions or features you've considered.

#### **Additional context**
Add any other context or screenshots about the feature request here.
Add any other context or screenshots about the technical debt here.

> _After all the above sections are filled out, remove the `Needs More Info` label, then assign issue to the repository maintainer._
---
### Pre-Implementation Checklist
> _To be filled out by repository maintainer._
#### **Validation**
- [ ] The Request section is filled out completely.
  - If not, add `Needs More Info` label and assign back to author.
- [ ] This request is not a duplicate of another request.
  - If it is, reference duplicate issue, add `Duplicate` label, and close issue.
- [ ] This request does not run counter to intended architecture.
  - If it does, add `By Design` label and close issue.
#### **Budgetting**
- [ ] The fix will provide enough benefit to justify the cost.
  - If not, add the `Won't Fix` label and close issue.
- [ ] The fix can be budgetted for active development at this time.
  - If not, add the `Postponed` label.
> _After all the above checks pass, add the `Ready for Implementation` label and assign issue to implementer._
---
### Implementation
> _To be filled out by implementer._
#### **Steps**
If the technical debt fix can be broken down into sub-tasks/-issues, add checklist for completion. Reference any sub-issues directly. Steps are checked off as they are added to a pull request.
- [ ] Add checklist of sub-tasks, referencing sub-issues directly
- [ ] Check off sub-issues as they are given the `Verified` label
- [ ] Check off sub-tasks as they are implemented and added to a pull request

#### **Opening Pull Requests**
Because this repository has its pull request template designed for student use, pull requests that are made by staff must use the template for internal repo pull requests.
1. Start a new pull request as normal.
1. Pick the `base` and `compare` branches.
1. Replace the body of the pull request with the contents of the [Internal Repository Pull Request Template](https://github.com/Learning-Fuze/internal-repo-template/raw/master/.github/PULL_REQUEST_TEMPLATE.md).
1. Follow the directions on the pull request.
After a technical debt fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=technical_debt_paydown.md&&labels=Technical%20Debt+Needs%20More%20Info&&title=[DOCUMENTATION/CLEANUP/PERFORMANCE/MAINTAINABILITY/DEPENDENCY]%20Insert%20Title%20Here
```

#### **After Merging Pull Requests**
After a pull request referencing this issue has been merged, check off any completed steps in the Implementation section above.

> _After all the above steps have been completed and integrated into the main development branch, add the `Ready for Testing` label, remove the `Ready for Implementation` label, and assign issue to tester for verification._
---
### Verification
> _To be filled out by tester._
Commit tested on main development branch: [commit #]
- [ ] Application runs without crashing.
- [ ] Application functionality has not changed.
> _After the main development branch is verified to meet the spec, add the `Verified` label, remove the `Ready for Testing` label, then close the issue._
---
name: Tooling request
about: Suggest a developer-facing functional tooling improvement for this project
title: "[DEVELOPMENT/TESTS/DEPLOY/MISC] Pick one. then insert title here"
labels: Tooling, Needs More Info
assignees: codingcodymiller
---
**For staff use only**
### Tooling Request
> _To be filled out by author. Add the `Tooling` and `Needs More Info` labels. Assign issue to self on creation._
#### **Is your tooling request related to a problem? Please describe.**
A clear and concise description of what the problem is. Ex. I'm always frustrated when [...]
#### **Is your tooling enhancement related to one or more existing features? Which one(s)?**
Yes or No. Describe existing tooling feature(s) from an instructor/development/operations perspective, including references to related issues.
#### **Describe the solution you'd like**
A clear and concise description of what you want to happen.
#### **Describe alternatives you've considered**
A clear and concise description of any alternative solutions or tooling enhancements you've considered.
#### **Additional context**
Add any other context, screenshots, or design documents about the tooling enhancement request here.
> _After all the above sections are filled out, remove the `Needs More Info` label, then assign issue to the repository maintainer._
---
### Pre-Implementation Checklist
> _To be filled out by repository maintainer._
#### **Validation**
- [ ] The Request section is filled out completely.
  - If not, add `Needs More Info` label and assign back to author.
- [ ] This request is not a duplicate of another request.
  - If it is, reference duplicate issue, add `Duplicate` label, and close issue.
- [ ] This request does not run counter to intended functionality.
  - If it does, add `By Design` label and close issue.
#### **Budgetting**
- [ ] The request will provide enough benefit to justify the cost.
  - If not, add the `Won't Fix` label and close issue.
- [ ] The request can be budgetted for active development at this time.
  - If not, add the `Postponed` label.
> _After all the above checks pass, add the `Ready for Implementation` label and assign issue to implementer._
---
### Implementation
> _To be filled out by implementer._
#### **Steps**
If the enhancement can be broken down into sub-tasks/-issues, add checklist for completion. Reference any sub-issues directly. Steps are checked off as they are added to a pull request.
If the tooling enhancement can be broken down into sub-tasks/-issues, add checklist for completion. Reference any sub-issues directly. Steps are checked off as they are added to a pull request.
- [ ] Add checklist of sub-tasks, referencing sub-issues directly
- [ ] Check off sub-issues as they are given the `Verified` label
- [ ] Check off sub-tasks as they are implemented and added to a pull request

#### **Opening Pull Requests**
Because this repository has its pull request template designed for student use, pull requests that are made by staff must use the template for internal repo pull requests.
1. Start a new pull request as normal.
1. Pick the `base` and `compare` branches.
1. Replace the body of the pull request with the contents of the [Internal Repository Pull Request Template](https://github.com/Learning-Fuze/internal-repo-template/raw/master/.github/PULL_REQUEST_TEMPLATE.md).
1. Follow the directions on the pull request.
After the enhancement has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=tooling.md&&labels=Tooling+Needs%20More%20Info&&title=[DEVELOPMENT/TESTS/DEPLOY/MISC]%20Insert%20Title%20Here
```

#### **After Merging Pull Requests**
After a pull request referencing this issue has been merged, check off any completed steps in the Implementation section above.

> _After all the above steps have been completed and integrated into the main development branch, add the `Ready for Testing` label, remove the `Ready for Implementation` label, and assign issue to tester for verification._
---
### Verification
> _To be filled out by tester._
Commit tested on main development branch: [commit #]
- [ ] The affected toolchain runs without crashing.
- [ ] Application runs without crashing.
- [ ] Tooling Enhancement is fully implemented and meets the spec.
> _After the main development branch is verified to meet the spec, add the `Verified` label, remove the `Ready for Testing` label, then close the issue._
---
name: Technical Debt report
about: The source code needs non-functional improvement.
title: "[DOCUMENTATION/CLEANUP/PERFORMANCE/MAINTAINABILITY/DEPENDENCY] Pick one, then
  insert title here"
labels: Technical Debt, Needs More Info
assignees: codingcodymiller
---
**For staff use only**
### Technical Debt Report
> _To be filled out by author. Add the `Technical Debt` and `Needs More Info` labels. Assign issue to self on creation._
#### **Is your technical debt fix request related to a problem? Please describe.**
A clear and concise description of what the problem is. Ex. I'm always frustrated when [...]
#### **Describe the solution you'd like**
A clear and concise description of what you want to change.
#### **Describe alternatives you've considered**
A clear and concise description of any alternative solutions or features you've considered.

#### **Additional context**
Add any other context or screenshots about the feature request here.
Add any other context or screenshots about the technical debt here.

> _After all the above sections are filled out, remove the `Needs More Info` label, then assign issue to the repository maintainer._
---
### Pre-Implementation Checklist
> _To be filled out by repository maintainer._
#### **Validation**
- [ ] The Request section is filled out completely.
  - If not, add `Needs More Info` label and assign back to author.
- [ ] This request is not a duplicate of another request.
  - If it is, reference duplicate issue, add `Duplicate` label, and close issue.
- [ ] This request does not run counter to intended architecture.
  - If it does, add `By Design` label and close issue.
#### **Budgetting**
- [ ] The fix will provide enough benefit to justify the cost.
  - If not, add the `Won't Fix` label and close issue.
- [ ] The fix can be budgetted for active development at this time.
  - If not, add the `Postponed` label.
> _After all the above checks pass, add the `Ready for Implementation` label and assign issue to implementer._
---
### Implementation
> _To be filled out by implementer._
#### **Steps**
If the technical debt fix can be broken down into sub-tasks/-issues, add checklist for completion. Reference any sub-issues directly. Steps are checked off as they are added to a pull request.
- [ ] Add checklist of sub-tasks, referencing sub-issues directly
- [ ] Check off sub-issues as they are given the `Verified` label
- [ ] Check off sub-tasks as they are implemented and added to a pull request

#### **Opening Pull Requests**
Because this repository has its pull request template designed for student use, pull requests that are made by staff must use the template for internal repo pull requests.
1. Start a new pull request as normal.
1. Pick the `base` and `compare` branches.
1. Replace the body of the pull request with the contents of the [Internal Repository Pull Request Template](https://github.com/Learning-Fuze/internal-repo-template/raw/master/.github/PULL_REQUEST_TEMPLATE.md).
1. Follow the directions on the pull request.
After a technical debt fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=technical_debt_paydown.md&&labels=Technical%20Debt+Needs%20More%20Info&&title=[DOCUMENTATION/CLEANUP/PERFORMANCE/MAINTAINABILITY/DEPENDENCY]%20Insert%20Title%20Here
```

#### **After Merging Pull Requests**
After a pull request referencing this issue has been merged, check off any completed steps in the Implementation section above.

> _After all the above steps have been completed and integrated into the main development branch, add the `Ready for Testing` label, remove the `Ready for Implementation` label, and assign issue to tester for verification._
---
### Verification
> _To be filled out by tester._
Commit tested on main development branch: [commit #]
- [ ] Application runs without crashing.
- [ ] Application functionality has not changed.
> _After the main development branch is verified to meet the spec, add the `Verified` label, remove the `Ready for Testing` label, then close the issue._
---
name: Technical Debt report
about: The source code needs non-functional improvement.
title: "[DOCUMENTATION/CLEANUP/PERFORMANCE/MAINTAINABILITY/DEPENDENCY] Pick one, then
  insert title here"
labels: Technical Debt, Needs More Info
assignees: codingcodymiller
---
**For staff use only**
### Technical Debt Report
> _To be filled out by author. Add the `Technical Debt` and `Needs More Info` labels. Assign issue to self on creation._
#### **Is your technical debt fix request related to a problem? Please describe.**
A clear and concise description of what the problem is. Ex. I'm always frustrated when [...]
#### **Describe the solution you'd like**
A clear and concise description of what you want to change.
#### **Describe alternatives you've considered**
A clear and concise description of any alternative solutions or features you've considered.

#### **Additional context**
Add any other context or screenshots about the feature request here.
Add any other context or screenshots about the technical debt here.

> _After all the above sections are filled out, remove the `Needs More Info` label, then assign issue to the repository maintainer._
---
### Pre-Implementation Checklist
> _To be filled out by repository maintainer._
#### **Validation**
- [ ] The Request section is filled out completely.
  - If not, add `Needs More Info` label and assign back to author.
- [ ] This request is not a duplicate of another request.
  - If it is, reference duplicate issue, add `Duplicate` label, and close issue.
- [ ] This request does not run counter to intended architecture.
  - If it does, add `By Design` label and close issue.
#### **Budgetting**
- [ ] The fix will provide enough benefit to justify the cost.
  - If not, add the `Won't Fix` label and close issue.
- [ ] The fix can be budgetted for active development at this time.
  - If not, add the `Postponed` label.
> _After all the above checks pass, add the `Ready for Implementation` label and assign issue to implementer._
---
### Implementation
> _To be filled out by implementer._
#### **Steps**
If the technical debt fix can be broken down into sub-tasks/-issues, add checklist for completion. Reference any sub-issues directly. Steps are checked off as they are added to a pull request.
- [ ] Add checklist of sub-tasks, referencing sub-issues directly
- [ ] Check off sub-issues as they are given the `Verified` label
- [ ] Check off sub-tasks as they are implemented and added to a pull request

#### **Opening Pull Requests**
Because this repository has its pull request template designed for student use, pull requests that are made by staff must use the template for internal repo pull requests.
1. Start a new pull request as normal.
1. Pick the `base` and `compare` branches.
1. Replace the body of the pull request with the contents of the [Internal Repository Pull Request Template](https://github.com/Learning-Fuze/internal-repo-template/raw/master/.github/PULL_REQUEST_TEMPLATE.md).
1. Follow the directions on the pull request.
After a technical debt fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/memory_match/compare/master...<COMPARE BRANCH>?assignees=codingcodymiller&&expand=1&&template=technical_debt_paydown.md&&labels=Technical%20Debt+Needs%20More%20Info&&title=[DOCUMENTATION/CLEANUP/PERFORMANCE/MAINTAINABILITY/DEPENDENCY]%20Insert%20Title%20Here
```

#### **After Merging Pull Requests**
After a pull request referencing this issue has been merged, check off any completed steps in the Implementation section above.

> _After all the above steps have been completed and integrated into the main development branch, add the `Ready for Testing` label, remove the `Ready for Implementation` label, and assign issue to tester for verification._
---
### Verification
> _To be filled out by tester._
Commit tested on main development branch: [commit #]
- [ ] Application runs without crashing.
- [ ] Application functionality has not changed.
> _After the main development branch is verified to meet the spec, add the `Verified` label, remove the `Ready for Testing` label, then close the issue._
ppppppppppp
