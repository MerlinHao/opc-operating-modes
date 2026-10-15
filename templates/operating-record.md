# OPC Operating Record — template schema v0.5

这是可复制的单条记录模板。按任务选填；小任务不需要完整表格。没有指定保存位置时，可直接在回答中输出有用字段。

| Field | Value |
|---|---|
| date / timezone | unknown |
| mode | primary mode and optional supporting modes |
| objective | intended business result and success criterion |
| context version | actual context version or conversation context; unknown if absent |
| evidence and source | observed facts, source/date/cohort; label estimates separately |
| interpretation | explanation, competing explanations and uncertainty |
| result | actual artifact/work/outcome; pending or unmeasured where appropriate |
| decision status and owner | recommendation / pending / user-decided / delegated decision; source/date |
| next action and owner | proposed or already authorized action, constraints and responsible person |
| review trigger | date or observable event; does not itself schedule a reminder |

## Mode-specific additions, only when useful

- **Marketing:** content/source, stated need, ICP fit, interest/contact basis, promise seen, qualification rule and measurement window.
- **Sales:** fit class, obstacles, actual agreed scope, acceptance, exclusions, responsibilities, price/time and unconfirmed terms.
- **Delivery:** baseline/target/actual evidence, acceptance status, budget/actual/remaining hours, direct costs and scope changes.
- **Strategy:** options, recommendation versus adopted decision, bounded experiment, success/failure/inconclusive interpretation and affected execution actions.

## Handoff

| Primary objective / receiving mode | Necessary facts vs interpretation | Actual commitments / constraints | Open questions / decision owner | Next action / owner |
|---|---|---|---|---|

交接记录不自动发送、发布或执行。只保留必要的客户信息。已知授权继续有效，不能把模式切换变成重复确认。若多模式协作，任务耗时按主模式记录一次，或明确拆分，避免重复累计。
