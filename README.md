# AB-731: AI Transformation Leader

**Microsoft Certified: AI Transformation Leader** (시험 코드 **AB-731**) 대비 강의 자료입니다. MkDocs (Material) 로 빌드해 GitHub Pages 로 배포합니다.

- 공개 문서: <https://noisonnoiton.github.io/ab-731/>
- 시험 정보: [Microsoft Learn - AB-731](https://learn.microsoft.com/en-us/credentials/certifications/exams/ab-731/)
- Study guide: <https://aka.ms/ab731-StudyGuide>

## 구성

| 도메인 | 비중 | 내용 |
| --- | --- | --- |
| Domain 1 | 35-40% | 생성형 AI 솔루션의 비즈니스 가치 |
| Domain 2 | 35-40% | Microsoft AI 앱/서비스의 이점, 기능, 기회 |
| Domain 3 | 20-25% | Microsoft AI 앱/서비스의 구현 및 도입 전략 |

## 로컬 미리보기

```bash
# uv 사용 (권장)
uv sync --extra docs
NO_MKDOCS_2_WARNING=1 uv run mkdocs serve

# 또는 pip
pip install "mkdocs-material>=9.5,<10" "plantuml-markdown>=3.10"
mkdocs serve
```

`http://127.0.0.1:8000/` 에서 확인합니다.

## 빌드

```bash
uv run mkdocs build --strict -f mkdocs.yml
```

## 배포 (GitHub Pages)

`main` 브랜치에 push 하면 [`.github/workflows/mkdocs-gh-pages.yml`](.github/workflows/mkdocs-gh-pages.yml) 가 빌드 후 `gh-pages` 브랜치로 배포합니다. 최초 배포 후 저장소 **Settings -> Pages** 에서 Branch 를 `gh-pages / (root)` 로 지정하세요.

## 참고

- 이 자료는 강사 본인이 작성한 **교육용 요약 노트**이며, Microsoft Learn 공식 문서를 출처로 정리했습니다.
- 시험 덤프, 기출 원문을 복제하지 않습니다.
