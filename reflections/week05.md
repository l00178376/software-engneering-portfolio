# TASK 1
## ISO/IEC 25010 Quality Scoring Sheet — Google Docs (example)

| Characteristic | Score (1–5) | Evidence notes |
|---|---:|---|
| Functional suitability | 5 | Core document tasks—creating, editing, formatting, and sharing—are available and generally work as expected. |
| Performance efficiency | 4 | Documents usually open and edits appear promptly; performance can slow with very large documents or a weak internet connection. |
| Compatibility | 4 | Supports browser and mobile use and common export formats; formatting may change when exported to or opened in other applications. |
| Usability | 4 | Familiar editing controls and menus make common tasks easy to learn; some advanced settings can take time to find. |
| Reliability | 4 | Changes are generally saved automatically; syncing can be delayed or interrupted when connectivity is poor. |
| Security | 3 | Account access controls and sharing permissions are available; users need to check link-sharing settings to avoid granting unintended access. |
| Maintainability | 3 | Not directly verifiable as an ordinary user without access to the source code or development process; score is provisional. |
| Portability | 4 | Usable across major browsers and mobile platforms; offline access and some features may vary by device or setup. |

**Two weakest characteristics:** Security and maintainability (tied at 3).

**Quality view:** Usability — this score reflects the user view, based on how easily a person can find and complete common tasks.

## Task 2 — Trade-off Analysis

### Chosen improvement
Improve **Security** in Google Docs by requiring stricter sharing controls by default, such as limiting link access to named users and sending a confirmation prompt when a document is shared outside the organisation.

### Trade-off
This would reduce the risk of documents being accessed by unintended people, improving security. However, it could reduce **usability** because users would need more steps to share work, and it may also reduce **compatibility** for people collaborating across organisations or using external accounts.

### Recommendation
The trade-off is worth making. Security is one of the weakest characteristics, and accidental over-sharing can expose sensitive personal, academic, or business information. Although stricter sharing controls add friction, Google Docs could reduce this by offering clear default options, simple permission summaries, and an easy way to undo changes. Protecting user data should take priority over a small reduction in convenience.


Task 3 — QA or QC?
QA or QC Activity Card Sort

Quality Assurance (QA) is process-oriented and preventive: it defines standards, procedures, and methods that build quality into a product. Quality Control (QC) is product-oriented and detective: it checks deliverables against standards and requirements to identify defects.

#	Activity	QA or QC?	Evidence / Reason
1	Writing a coding standard for the team	QA	Establishes consistent coding rules to prevent defects.
2	Running the unit test suite before a change is merged	QC	Tests the code to detect defects before merging.
3	Auditing whether teams actually follow the review procedure	QA	Checks that the established quality process is followed.
4	Peer review of one pull request	QC	Examines a specific code change to identify errors.
5	Defining the steps of the change-control procedure	QA	Establishes a standard process to prevent mistakes during changes.
6	Running a static-analysis tool over the code base	QC	Detects potential defects and violations of coding standards.
7	Training new starters in the team's testing approach	QA	Helps team members follow quality practices correctly.
8	User acceptance testing of the finished feature	QC	Checks whether the finished feature meets user requirements.
9	Deciding which quality characteristics matter most in the quality plan	QA	Defines quality priorities before development and testing.
10	Inspecting a design document against the team's template	QC	Checks a specific deliverable against the required standards.
11	Collecting defect counts and reviewing them to change how the team works	QA	Uses defect data to improve processes and prevent future problems.
12	Penetration testing the login page	QC	Tests the login page to identify security vulnerabilities.
Borderline Activities

The hardest activities to classify were cards 3, 6, and 11.

Card 3 — Auditing the review procedure: QA because it checks whether the team follows the established process.
Card 6 — Static analysis: QC because it examines existing code to detect potential defects, although it can also support prevention.
Card 11 — Reviewing defect counts: QA because the results are used to improve working practices and prevent similar defects in the future.

The definitions used were that QA focuses on preventing defects by improving processes, while QC focuses on detecting defects by checking products and deliverables.

QA/QC Pair for the Weakest Characteristic
Chosen characteristic: Security

Security received a score of 3/5 in Task 1. Google Docs provides access controls and sharing permissions, but users must check link-sharing settings to avoid granting unintended access.

Type	Activity	Evidence / Reason
QA — Prevention	Establish a secure document-sharing procedure that defaults to named users and requires permission checks before sharing.	Helps prevent accidental exposure of sensitive information through secure
