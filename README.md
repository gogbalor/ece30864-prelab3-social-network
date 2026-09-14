# Campus Circle - Social Network Prelab

ECE 30864 Prelab 3: a fictional social-network product used to demonstrate Scrum planning and Jira/GitHub integration.

Jira space: https://fall26ee364a08.atlassian.net/jira/software/projects/CSP/summary

The JSON fixtures contain only invented members and posts. Feature branches contain demonstrative specifications and dummy files; this is not a production application. Jira statuses and bug scenarios illustrate a classroom sprint.

## Epics

- CSP-5: Member identity and social connections (stories CSP-7 through CSP-11).
- CSP-6: Social publishing and community engagement (stories CSP-12 through CSP-16).

## Development links

Feature branch names and commit messages include the corresponding CSP issue key so GitHub for Atlassian can associate them with Jira stories.

## Example bug dependencies

- CSP-17 blocks CSP-7: duplicate registration email casing.
- CSP-18 blocks CSP-13: private posts appearing in unauthorized feeds.
- CSP-19 blocks CSP-14: repeated likes inflating the count.
