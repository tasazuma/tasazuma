# DEC-0001: Decision Logを導入する

## Status
Accepted

## Context
複数の生成AIを設計・実装・レビューに利用すると、各AIが参照している会話やコンテキストが異なるため、過去の設計判断が引き継がれないことがある。
## Decision
重要な設計判断についてDecision Logを残す。
## Purpose
- 現在の仕様だけでなく「なぜそう判断したか」を残す
- 人間とAIの双方が後から判断経緯を確認できるようにする
- 異なるAI間で設計思想を引き継ぎやすくする
## Revisit conditions
AI間でプロジェクトContextを十分かつ安定して共有できるようになった場合、
Decision Logの運用方法および必要性を再評価する。