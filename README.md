# Jenkins Webhook Trigger Lab

A minimal Jenkins pipeline sandbox used to verify GitHub webhook triggers and basic pipeline execution.

This is a supporting lab repository. It is intentionally small and should be viewed as CI/CD wiring practice, not as an application project.

## What is included

```text
Jenkinsfile      Declarative Jenkins pipeline
index.html       Simple static file used as a change target
test.txt         Webhook test marker
frontend         Git submodule/reference entry
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

## Portfolio role

This repository supports the CI/CD learning trail. It should sit behind stronger resume-facing repos such as:

- [employee-portal](https://github.com/Chandrumgchandu/employee-portal)
- [todo_app_jenkins](https://github.com/Chandrumgchandu/todo_app_jenkins)
- [devops-lab](https://github.com/Chandrumgchandu/devops-lab)

## Notes

The `frontend` entry is a Git submodule/reference. If this repo is cloned locally and the reference is needed, initialize submodules with:

```bash
git submodule update --init --recursive
```
