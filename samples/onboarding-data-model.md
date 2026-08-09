# Sample Onboarding Data Model

## Onboarding Records

| Field | Suggested type | Purpose |
|---|---|---|
| Title | Text | Employee or onboarding reference |
| Employee | Person or text | Employee identity according to policy |
| Department | Choice or lookup | Employee department |
| DirectManager | Person | Responsible manager |
| StartDate | Date | Planned start date |
| OverallStatus | Choice | Lifecycle status |
| ProgressPercent | Number | Calculated progress indicator |
| CreatedBy | Person | Initiating user |

## Onboarding Tasks

| Field | Suggested type | Purpose |
|---|---|---|
| OnboardingRecord | Lookup | Parent onboarding record |
| TaskName | Text | Activity title |
| ResponsibleDepartment | Choice or lookup | Owning function |
| AssignedTo | Person or Group | Responsible user or team |
| Required | Yes/No | Controls completion requirements |
| Status | Choice | Task progress |
| DueDate | Date | Target completion date |
| CompletionDate | Date | Actual completion date |

Production fields and permissions must reflect the organization's privacy and governance policy.

