<div align="center">

<a id="top"></a>

# AI_Epigraph
### AI를 활용한 비문 결락자 추론 연구
### AI-Assisted Inference of Missing Characters in Historical Inscriptions

## [발표자료 보기 · Open Presentation](https://littlekg87.github.io/AI_Epigraph/)

제240회 신라사학회 정기발표회 · 인터랙티브 발표자료 31장  
The 240th Regular Research Meeting of the Silla Historical Society · 31 interactive slides

## [English](#english) · [한국어](#한국어)

</div>

---

<a id="english"></a>

## English

## The 240th Regular Research Meeting of the Silla Historical Society

**A Digital History Approach to Inferring Missing Characters in Buddhist Monk Inscriptions from Late Silla and Early Goryeo**  
Focusing on inscriptions composed by Choe Chiwon, Choe Eonwi, and Kim Jeongeon

- **임평섭 (Lim Pyeong-seop)** — Research Professor, HUSS Inclusive Society Project Group, Sogang University
- **김근하 (Kunha Kim)** — Full-time Researcher, Maritime Humanities Research Institute, Pukyong National University

### Research overview

This study examines whether adapting the Classical Chinese language model SIKU-BERT improves candidate recommendations for missing characters in 18 Buddhist monk inscriptions from late Silla and early Goryeo. The inscriptions were divided into 12 for training, three for development validation, and three for final evaluation. LoRA adapters were trained while the original model weights remained frozen.

Across 5,419 final evaluation examples, Recall@20 increased from 52.06% for the base model to 60.66% for configuration A. Configuration B, which applied LoRA to more transformations, reached 62.06% in a follow-up comparison that reused the same evaluation set. The study distinguishes evaluation using artificially masked known characters from exploratory candidate generation for actual gaps. Its purpose is to support scholarly scrutiny of candidates alongside rubbings, surviving strokes, textual parallels, and historical context.

### Presentation

**[Open the interactive presentation](https://littlekg87.github.io/AI_Epigraph/)**

The presentation contains **31 slides**. Slide 2 provides the URL and QR code. Download `index.html` to view the self-contained presentation offline, including its fonts and images.

- Arrow keys: previous or next slide
- Upper-right page number or G: open the slide index
- F: fullscreen / N: speaker notes / P: print
- Interactive diagrams explain LoRA training, adapter placement, evaluation metrics, and candidate comparisons.

### Sources

References to the paper, data, and research figures appear within the presentation. Noto font OFL notices are embedded in the HTML. Ithaca and Aeneas figures come from Google DeepMind's official research introductions. Rights to third-party materials remain with their respective owners.

<div align="right"><a href="#top">↑ 맨 위로 / Back to top</a></div>

---

<a id="한국어"></a>

## 한국어

## 제240회 신라사학회 정기발표회

**나말여초 고승비문의 결락자 추론을 위한 디지털역사학적 접근**  
최치원·최언위·김정언 찬 비문을 중심으로

- 임평섭 — 서강대학교 HUSS 포용사회사업단 연구교수
- 김근하 — 국립부경대학교 해양인문학연구소 전임연구원

### 연구 개요

이 연구는 최치원·최언위·김정언이 찬술한 나말여초 고승비문 18편을 대상으로, 고전 한문 언어모델 SIKU-BERT의 추가 학습이 결락자 후보 추천을 개선하는지 살펴봅니다. 비문을 학습 12편·개발 검증 3편·최종 평가 3편으로 나누고, 기존 가중치를 고정한 채 LoRA를 학습했습니다.

최종 평가 5,419문제에서 상위 20개 정답 포함률은 기본 모델 52.06%에서 설정 A의 60.66%로 높아졌습니다. 적용 위치를 확대한 설정 B는 같은 평가 자료를 재사용한 후속 비교에서 62.06%를 기록했습니다. 판독된 글자를 가린 평가와 실제 결락에 대한 후보 제시를 구분하며, 모델의 후보를 탁본·잔존 획·전거·역사적 맥락에 대한 연구자의 검증과 연결하는 데 목적을 둡니다.

### 발표자료 사용법

총 **31장**이며, 2장에 접속 URL과 QR코드를 제공합니다. 폰트와 이미지를 포함한 독립 HTML 파일로, `index.html`을 내려받아 오프라인에서도 열 수 있습니다.

- 방향키: 이전·다음 슬라이드
- 우측 상단 페이지 번호 또는 G: 전체 페이지 목록
- F: 전체 화면 / N: 발표자 메모 / P: 인쇄
- LoRA 학습 과정, 적용 위치, 평가 지표와 후보 비교를 화면에서 조작할 수 있습니다.

### 출처

발표자료 안에 논문·데이터·연구 도판의 출처를 표시했습니다. Noto 폰트의 OFL 고지는 HTML에 포함되어 있습니다. 이타카·아이네아스 도판은 Google DeepMind의 공식 연구 소개 자료를 사용했습니다. 외부 자료의 권리는 각 원저작자에게 있습니다.

GitHub Pages는 `main` 브랜치의 루트에서 제공됩니다.

<div align="right"><a href="#top">↑ 맨 위로 / Back to top</a></div>
