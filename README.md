# 🎓 AI English Feedback Chatbot (Gemini 2.5 Flash)

이 프로젝트는 Google의 **Gemini 2.5 Flash 모델**을 활용하여  
영어 문장을 자동으로 교정하고, 수정 이유를 **한국어로 설명하는**  
AI 영어 학습 피드백 챗봇입니다. 💬

---

## 🔧 실행 환경
- Google Colab (Python)
- Google AI Studio API (Gemini 2.5 Flash)

---

## ▶️ 사용 방법
1️⃣ Google Colab에서 노트북 실행  
2️⃣ 첫 번째 셀에서 `google-generativeai` 설치  
3️⃣ `Enter your Google API Key:` 입력  
4️⃣ 메뉴에서 기능 선택 → 영어 문장 입력 → 교정 결과 확인

---

## 🧠 기능 메뉴
| 번호 | 기능 | 설명 |
|------|------|------|
| 1 | 문법 교정 | 문법 오류 수정 + 한국어로 설명 |
| 2 | 레벨/톤 재작성 | 문장을 B1 수준이나 다른 톤으로 바꿔줌 |
| 3 | 발음 팁 | 발음 포인트와 쉬운 IPA 표기 제공 |
| 4 | 짧은 퀴즈 | 입력 문장 기반 문법/어휘 퀴즈 생성 |

---

## 📝 예시
입력  
> She don’t likes apple because it make her teeth hurt.  

출력  
> ✅ She doesn’t like apples because it makes her teeth hurt.  
> 📘 설명: 주어-동사 일치, 복수형, 3인칭 단수 시제 수정

---

## 📂 파일 구성
- `AI_english_feedback_chatbot.ipynb` : Colab 노트북
- `README.md` : 프로젝트 설명 파일

---

## 📸 시연 예시
(원하면 Colab 실행 화면 캡처해서 `Add file → Upload files`로 넣으면 좋아요!)

---

## 📢 참고
- Google AI Studio에서 발급받은 API Key를 사용합니다.
- `MODEL_NAME = "gemini-2.5-flash"` 로 설정해야 정상 작동합니다.
