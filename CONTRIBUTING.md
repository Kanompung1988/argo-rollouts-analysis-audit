# Contributing

Contributions to this independent Argo Rollouts Agent Skill are welcome.

1. Open an issue with sanitized AnalysisTemplate/ClusterAnalysisTemplate and Rollout manifests. State the Argo Rollouts controller version and expected outcome.
2. Add a minimal synthetic regression to `tests/test_audit.py`; avoid production metric URLs, tokens or secrets.
3. Run `python -m pip install 'PyYAML>=6,<7'`, `python -m unittest discover -s tests -v` and both fixture smoke examples.
4. Make changes on a feature branch and open a PR. Preserve code 0/1/2 exit conventions, bounded read-only input and explicit non-evaluation of CEL and metrics.
5. Keep original Area Zero logo bytes unchanged; MIT code licensing does not grant trademark permissions.

For potentially sensitive security issues, privately contact the maintainer before disclosure.
