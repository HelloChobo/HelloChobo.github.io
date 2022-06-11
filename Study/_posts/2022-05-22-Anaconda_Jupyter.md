---
layout: single
title: "Anaconda Jupyter"
---

# anaconda 의 가상환경 생성 및 삭제
## 가상환경 생성
가상환경 생성  
> conda create -n 가상환경이름 python=버전

## 가상환경 생성 with requirements
> conda env create -n 가상환경이름 --file requirements 파일.yaml

## 가상환경에서 requirements 대로 설치
> pip install -r requirements.txt

## 가상환경 검색
> conda info --envs

## 가상환경 삭제
> conda env remove --n 가상환경이름


---

# Jupyter 의 Kernel 연결 및 해제
## 가상환경 - 주피터 노트북 연결
> 1. pip install jupyter notebook
> 2. pip install ipykernel # jupyter notebook 설치시 자동 설치됨
> 3. python -m ipykernel install --user --name 가상환경이름 --display-name "표시할이름"

## 가상환경 - 주피터 노트북에서 해제 (커널 제거)
> jupyter kernelspec uninstall 가상환경이름