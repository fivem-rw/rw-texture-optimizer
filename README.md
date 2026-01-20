<div align="center">

# 🎨 **RW Texture Optimizer**
### FiveM 스트리밍 텍스처 최적화 도구

![platform](https://img.shields.io/badge/Platform-Window%20/%20FiveM-blue)
![format](https://img.shields.io/badge/Formats-YTD%20%7C%20YDR%20%7C%20YDD-green)
![thread](https://img.shields.io/badge/Multi--Threading-Supported-orange)
![license](https://img.shields.io/badge/License-MIT-lightgrey)

---

🚀 **FiveM 서버 성능과 용량을 동시에 잡는 텍스처 최적화 솔루션**

</div>

---

## ✨ 개요
**RW Texture Optimizer**는 FiveM 스트리밍 파일인 **YTD, YDR, YDD** 내부의  
모든 텍스처를 분석하여 **자동 리사이즈 · 압축 · MipMap 재생성**을 자동으로 수행하는  
**CPU + GPU 병행 처리 기반**의 고성능 텍스처 최적화 도구입니다.

YTD, YDR, YDD 파일의 압축 해제부터 재압축, 텍스처 추출 및 분석까지 전 과정이 자동화되어 있어  
별도의 수동 작업 없이 쉽고 빠르게 텍스처의 최적화를 진행할 수 있습니다.

본 프로젝트는 **REAL WORLD (리얼월드) FiveM 서버**의 운영 및 개발 과정에서  
실제 대규모 스트리밍 리소스를 효율적으로 최적화하기 위해 **리얼월드에서 자체 개발한 유틸리티 도구**입니다.

해당 도구의 사용을 원할 경우, **리얼월드 공식 디스코드**를 통해 문의해주시기 바랍니다.  
👉 https://discord.gg/rw

### 🧩 지원 텍스처 포맷
| 포맷 | 설명 |
|---|---|
| **DXT1 (BC1)** | 알파 없는 텍스처 |
| **DXT3 (BC3)** | 선형 알파 |
| **DXT5 (BC5)** | 그라데이션 알파 |
| **A8R8G8B8** | 비압축 RGBA |

### 🖥️ 스크린샷

<img src="https://raw.githubusercontent.com/fivem-rw/rw-texture-optimizer/refs/heads/main/image.png" width="90%">

---

## 🚀 주요 기능

### 🔧 텍스처 최적화
- YTD, YDR, YDD 파일의 텍스처를 FiveM에 최적화된 크기로 **자동 리사이즈**
- 불필요한 텍스처 해상도 및 품질 최적화로 **VRAM / 용량 절감**
- 포맷 유지 또는 최적 포맷으로 저장

### 🧠 DDS 스마트 처리
- ✅ **MipMap 자동 재계산**
- ✅ DDS 헤더의  
  `MipMapCount / Caps / Flags`  
  값이 실제 데이터와 불일치할 경우 **자동 보정**
- 잘못된 DDS로 인한 FiveM 크래시 예방

### 📂 파일 자동 탐색
- 원클릭으로 자동 최적화 처리
- 폴더 지정 시 **하위 폴더 포함 전체 검색**
- 대상 파일:
  - `*.ytd`
  - `*.ydr`
  - `*.ydd`

### ⚙️ 선택적 처리
- YTD / YDR / YDD **개별 선택 옵션 제공**
- 필요 없는 파일은 제외하여 처리 가능

### ⚡ 고성능 멀티쓰레딩
- 멀티 코어 CPU를 활용한 **초고속 처리**
- GPU 가속 지원
- 대규모 스트리밍 리소스도 빠르게 최적화

### 📊 결과 시각화
- 파일별:
  - 처리된 텍스처 개수
  - 미처리 / 실패 파일 표시, 처리 불가시 원인 표시
- 디버깅과 검증에 매우 용이

---

## 🎯 이런 분들께 추천
- 📦 스트리밍 리소스 용량이 너무 큰 서버
- 🚗 차량 / 의상 / 오브젝트 텍스처 최적화가 필요한 경우
- 💥 텍스처 관련 오류로 FiveM 크래시를 자주 겪는 경우
- 🎮 프레임(FPS) 향상을 원하는 서버
