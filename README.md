# Presentation Assets

프레젠테이션 마스터 프로젝트의 시각 자산 모음 (모든 이미지 raw URL로 노션 임베드용 호스팅).

## 구조

```
presets/
└── preset_{코드}/
    ├── 1_cover.png     (표지)
    ├── 2_section.png   (섹션 오프닝)
    ├── 3_body.png      (본문)
    ├── 4_data.png      (데이터/차트)
    ├── 5_process.png   (프로세스/도식)
    └── 6_ending.png    (마무리)

style_library/
└── {번호}/
    ├── p1.png          (PDF 1페이지 — 표지)
    ├── p2.png          (PDF 2페이지)
    ├── p3.png          (PDF 3페이지)
    └── p5.png          (PDF 5페이지)
```

## 프리셋 목록 (17개 — 고정 프리셋 모드 A 자원)

A, B, C, D, E, F, G1, H, I, J, K1, K2, L, M, N1, N2, N3

각 프리셋은 6개 슬라이드 미리보기 이미지 보유.

## 스타일 라이브러리 (23개 — 즉석 캐스팅 모드 B/C 자원)

51~76번 신규 자기완결형 스타일의 미리보기. 각 스타일은 원본 Canva 템플릿 PDF의 4개 페이지(1·2·3·5) 미리보기 보유.

번호별 스타일명은 프로젝트 본 repo의 `slide_style_library.md` 참조.

## raw URL 패턴

```
https://raw.githubusercontent.com/BetterwithU/presentation-assets/main/style_library/{번호}/p{1|2|3|5}.png
```

