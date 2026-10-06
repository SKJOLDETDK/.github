## 📌 Feature/task/bug/hotfix/cleanup pull request

> Provide a short summary of the change and why it is needed.

## ✅ Changes

Select all that apply:

- [ ] New feature
- [ ] Task
- [ ] Bug fix
- [ ] Hotfix
- [ ] Cleanup/refactoring

## 🧪 How to test it

### Automated testing

- [ ] Automatic/unit tests were added or updated
- [ ] Existing automatic tests pass
- [ ] Not applicable

### Manual testing

> Describe the steps required to test this PR locally.

1.
2.
3.

## 🚨 Release impact

Complete **every section** below. Select **None** when the PR has no impact in that category.

### Authentication and authorization

Select all that apply:

- [ ] None
- [ ] New authentication or authorization requirement
- [ ] Modified authentication or authorization requirement
- [ ] Removed authentication or authorization requirement
- [ ] New or modified permission, role, claim, or access rule

#### Details

> Describe the affected routes, permissions, roles, claims, authentication flags, or access rules.

### Environment variables

Select all that apply:

- [ ] None
- [ ] New environment variable
- [ ] Modified environment variable
- [ ] Removed environment variable

#### Variables

> List variable names only. Never include secret values.

| Variable        | Change                   | Environments                     | Required action              |
| --------------- | ------------------------ | -------------------------------- | ---------------------------- |
| `VARIABLE_NAME` | New / Modified / Removed | Local / Dev / Alpha / Production | Describe the required action |

### Database

Select all that apply:

- [ ] None
- [ ] Schema migration required
- [ ] Data migration or backfill required
- [ ] Database index change required
- [ ] Seed or reference data change required
- [ ] Destructive or irreversible database change

#### Migration details

> Include the migration name, execution order, compatibility requirements, and rollback
> instructions.

### API and integration impact

Select all that apply:

- [ ] None
- [ ] New API endpoint
- [ ] Modified API endpoint
- [ ] Breaking API change
- [ ] Third-party integration change
- [ ] Another repository or service must be released
- [ ] Client application must be updated

#### Details

> List affected services, repositories, applications, API contracts, or external providers.

### Infrastructure and deployment

Select all that apply:

- [ ] None
- [ ] Infrastructure or configuration change required
- [ ] Manual action required before deployment
- [ ] Manual action required after deployment
- [ ] Services must be deployed in a specific order
- [ ] Post-deployment verification required
- [ ] Rollback procedure changed

#### Deployment instructions

> Describe the required action, responsible owner, execution order, and verification procedure.

### User-facing, documentation, and compliance impact

Select all that apply:

- [ ] None
- [ ] User-visible behavior changed
- [ ] Documentation or help content must be updated
- [ ] Privacy policy review required
- [ ] Terms of service review required
- [ ] Logging, monitoring, or alerting changed

#### Details

> Describe the impact and any required follow-up work.

## 👀 Reviewer verification

To be completed by the reviewer:

- [ ] I reviewed the release-impact information
- [ ] Each release-impact section has at least one selection
- [ ] The selected options match the code changes
- [ ] Environment-variable instructions are complete
- [ ] No secret values are included
- [ ] Database changes include migration and rollback information
- [ ] Authentication and authorization changes have been reviewed
- [ ] Manual deployment actions are clear and actionable

## 📎 Related issues

Closes #[issue number]

## ✅ Final checklist

- [ ] Automatic tests pass using `npm run test`
- [ ] CI pipeline passes
- [ ] CI test logs have been reviewed
- [ ] Related issues are linked !Important
- [ ] The PR is ready to merge into `dev`

## 🗒️ Notes

> Add any additional information for reviewers, DevOps, or the release owner.
