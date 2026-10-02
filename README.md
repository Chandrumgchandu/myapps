# Jenkins Webhook Trigger Lab

A minimal Jenkins pipeline sandbox used to verify GitHub webhook triggers and basic pipeline execution.

This is a supporting lab repository. It is intentionally small and should be viewed as CI/CD wiring practice, not as an application project.

## What is included

```text
Jenkinsfile      Declarative Jenkins pipeline
index.html       Simple static file used as a change target
frontend         Existing Git submodule/reference entry
```

## What this demonstrates

- Jenkins declarative pipeline syntax
- GitHub webhook-triggered job validation
- Basic checkout/build/success stage flow
- Simple repository changes for trigger testing

## Jenkins pipeline flow

```text
GitHub change -> Jenkins webhook -> Pipeline starts -> Workspace listed -> Success message
```

## Cleanup note

The old timestamp-only webhook marker file was removed because it did not add portfolio value. The remaining files are kept only to show the webhook lab flow.

## Portfolio role

This repository supports the CI/CD learning trail. It should sit behind stronger resume-facing repos such as:

- [employee-portal](https://github.com/Chandrumgchandu/employee-portal)
- [todo_app_jenkins](https://github.com/Chandrumgchandu/todo_app_jenkins)
- [devops-lab](https://github.com/Chandrumgchandu/devops-lab)
