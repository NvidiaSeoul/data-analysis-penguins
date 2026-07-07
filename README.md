# 데이터 분석 — Palmer Penguins / Data Analysis with Palmer Penguins

> **English summary.** Coursework notebooks practicing the pandas data-analysis workflow on the Palmer Penguins dataset — from Series/DataFrame basics, indexing, filtering and groupby, to exploratory data analysis and visualization (numeric vs. categorical relationships, binning with `cut`/`qcut`, statistical plots).

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-4C72B0)

---

## 개요

**Palmer Penguins** 데이터셋으로 pandas 기반 데이터 분석의 전 과정을 실습한 노트북입니다. 데이터 로딩·구조 파악부터 EDA·시각화까지, 실제 데이터로 손을 움직이며 익힙니다.

## 노트북 구성

| # | 노트북 | 내용 |
|---|--------|------|
| 01 | [penguins_pandas_eda](notebooks/01_penguins_pandas_eda.ipynb) | pandas 기초 — Series/DataFrame, 인덱싱·슬라이싱, 필터링, groupby, 요약 통계 |
| 02 | [eda_and_visualization](notebooks/02_eda_and_visualization.ipynb) | EDA·시각화 — 수치형/범주형 특성 분석, 교차분석, `cut`/`qcut` 구간화, 통계 시각화 |

## 데이터셋

- **Palmer Penguins** ([data/penguins.csv](data/penguins.csv)) — 남극 3종 펭귄(Adelie·Chinstrap·Gentoo)의 부리 길이·깊이, 지느러미 길이, 체중, 서식 섬 등

## 실행 방법

```bash
pip install pandas numpy matplotlib seaborn scikit-learn koreanize-matplotlib
jupyter notebook   # notebooks/*.ipynb
```

## 참고

- 파이썬·pandas 기초: [ai-fundamentals](https://github.com/NvidiaSeoul/ai-fundamentals)
- PyTorch 신경망: [pytorch-fundamentals](https://github.com/NvidiaSeoul/pytorch-fundamentals)

---
> NVIDIA AI Academy Seoul 교육과정 실습 — [전체 포트폴리오](https://github.com/NvidiaSeoul)
