<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:5DADE2,100:2980B9&height=200&section=header&text=Today%20I%20Learned%20(TIL)&fontSize=40&fontColor=ffffff&fontAlignY=40&desc=하루하루%20배움을%20기록하며%20성장하기&descSize=20&descAlign=65" alt="TIL banner"/>
</p>

<p align="center">
  <i>💡 <b>어김없이 오늘의 난 어제의 나를 이겼다.</b> 💡</i>
</p>

[![GitHub repo size](https://img.shields.io/github/repo-size/0l70/TIL?color=blue)](https://github.com/0l70/TIL)
[![Last Commit](https://img.shields.io/github/last-commit/0l70/TIL?color=green)](https://github.com/0l70/TIL)
[![GitHub license](https://img.shields.io/github/license/0l70/TIL)](https://github.com/0l70/TIL/blob/main/LICENSE)

<!-- 기술 스택 뱃지 -->
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)

---

## 🗂️ 목차 (Table of Contents)

- 🐍 [Python](#python)
- 🧰 [Git & GitHub](#git--github)
- 💻 [Computer Science](#computer-science)
- 📝 [Others](#others)

---

## 🐍 Python

### Python Basic Syntax
- `2025-07-21` : [Python Basic Syntax 01 정리](./Python_Study/day01.ipynb)
- `2025-07-22` : [Python Basic Syntax 02 정리](./Python_Study/day02.ipynb)

---

## 🧰 Git & GitHub - 2025-07-21 ~

### ✅ Git 명령어 복습

```bash
git add .
git commit -m "comment_update"
git push -u origin main
```

### 📌 설명

- `git add .`  
  → 현재 디렉토리의 모든 변경 사항(stage)을 추가

- `git commit -m "comment_update"`  
  → "comment_update" 메시지로 커밋 기록 생성

- `git push -u origin main`  
  → 원격 저장소(origin)의 main 브랜치에 최초 연결과 함께 푸시  
  → 이후엔 `git push`만으로도 자동 푸시 가능

---

### ⚠️ 주의사항

- 만약 push 시 아래와 같은 에러 발생 시:

  ```
  ! [rejected] main -> main (fetch first)
  ```

- 이는 **GitHub 원격 저장소에 내가 가지고 있지 않은 커밋이 있어서 발생**하는 문제

### ✅ 해결법 요약

1. 협업 시:  
```bash
git pull origin main --rebase
git push origin main
```

2. 개인 저장소이거나 히스토리를 덮어도 될 경우:  
```bash
git push --force origin main
```

> ⚠️ `--force`는 협업 시 위험하므로 신중히 사용하세요!

---

## 🗓️ 기록 날짜: 2025-07-22
