## 목차

- [개요](#개요)
- [목표](#목표)
- [분석과정](#분석과정)

## 개요

- 프로젝트 이름: ml-assignment
- 사용 언어 및 버전: python 3.10.14
- 사용 라이브러리 : numpy, pandas, matplotlib, seaborn
- 작성자 : 이준오

## 목표

- survived를 목표 변수로 사용하여 생존여부를 분류하는 모형을 개발하는 것보다, 데이터 분석으로 타이타닉 데이터셋에서 발견할 수 있는 잠재적 의미를 추출하고 인사이트를 발견하여 해석하는 데이터 분석

- 통계적 검증, 단일 및 다중 변수 시각화, 집계 등을 통한 데이터 분석과 분석한 결과를 바탕으로 본인 스스로 결과를 분석하여 서술해야 함

## 분석과정

### 데이터 분석에 필요한 라이브러리 import

- import numpy as np
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns

### 데이터 읽어오기

- train = pd.read_csv('data/train.csv')
- test = pd.read_csv('data/test.csv')
