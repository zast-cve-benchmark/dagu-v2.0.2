# dagu-v2.0.2 - 漏洞总览

| # | CVE | 端点 | 漏洞类型 | 状态 |
|---|---|---|---|---|
| 1 | CVE-2026-31886 | `POST /api/v1/dag-runs` | dagRunId路径遍历 (CWE-22) | VULNERABLE |
| 2 | CVE-2026-33344 | `GET /api/v1/dags/{fileName}/spec` | %2F编码路径遍历 (CWE-22) | VULNERABLE |
