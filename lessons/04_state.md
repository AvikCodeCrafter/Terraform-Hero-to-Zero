# Lesson 04 — Terraform State
## Diagram
```mermaid
flowchart LR
  A[Terraform Apply] --> B[State File]
  B --> C[S3 Remote Backend]
  C --> D[DynamoDB Lock Table]
```
