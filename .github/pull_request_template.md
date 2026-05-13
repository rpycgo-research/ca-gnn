# Pull Request

## Summary

<!-- 이 PR에서 무엇을 변경했는지 2~4줄로 요약 -->

- 
- 
- 

## Type of Change

<!-- 해당하는 항목에 x 표시 -->

- [ ] chore: project setup, config, tooling
- [ ] feat: new feature or module
- [ ] fix: bug fix
- [ ] refactor: internal structure change without behavior change
- [ ] test: tests only
- [ ] docs: documentation only
- [ ] experiment: experiment config, metrics, or analysis logic

## Scope

<!-- 변경된 영역을 체크 -->

- [ ] project scaffold / uv / dependency
- [ ] data adapter
- [ ] preprocessing
- [ ] graph construction
- [ ] EDA
- [ ] camouflage protocol
- [ ] baseline model
- [ ] PyTorch Lightning / GNN
- [ ] evaluation metrics
- [ ] configs
- [ ] tests
- [ ] documentation

## Motivation

<!-- 왜 이 변경이 필요한지 간단히 설명 -->



## Main Changes

<!-- 핵심 변경 사항만 bullet로 작성 -->

- 
- 
- 

## Design Notes

<!-- SOLID, 확장성, leakage 방지, missing/outlier policy 관련 결정이 있으면 작성 -->

- 
- 
- 

## Validation

<!-- 실행한 검증 명령 체크 -->

- [ ] `uv lock --check`
- [ ] `uv sync --dev`
- [ ] `uv run ruff check .`
- [ ] `uv run ruff format --check .`
- [ ] `uv run pytest`

## Experiment / Data Notes

<!-- 데이터나 실험 결과가 있는 경우만 작성 -->

- Dataset:
- Split:
- Metrics:
- Output path:

## Risk / Known Limitations

<!-- 아직 남은 문제, 의도적으로 제외한 부분, 추후 작업 -->

- 
- 

## Checklist

- [ ] Code follows the project structure.
- [ ] No raw data or large output files are committed.
- [ ] No future-label leakage is introduced.
- [ ] Missing-value handling is explicit where relevant.
- [ ] Relation keys do not create missing hubs.
- [ ] Config changes are documented.
- [ ] Tests or smoke checks were added/updated where appropriate.