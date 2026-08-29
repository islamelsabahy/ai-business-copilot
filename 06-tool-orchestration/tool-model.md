# Tool Orchestration Model

Tool metadata should include:

- tool_id
- purpose
- read/write
- risk_level
- required_permissions
- approval_required
- reversible
- idempotency_strategy

## Example Tool Types

- search
- read
- create task
- send notification
- update record
- create approval request
- generate report

High-impact writes require explicit controls.
