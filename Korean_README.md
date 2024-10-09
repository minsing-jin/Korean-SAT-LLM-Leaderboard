![image](https://github.com/user-attachments/assets/f9d08905-33fe-48c0-a540-6b25c7e64563)

# 🏆 KO-SAT Slayer Champions League

**KO-SAT Slayer Champions League**에 오신 것을 환영합니다! 한국 수능(SAT) 최고의 slayer를 가리기 위한 리더보드입니다! 🚀

여러분의 한국어 LLM finetuning 모델이 한국 수능 10개년 benchmark에서는 몇점이 나오는지 확인해보세요!

GPU 자원을 제공해주신다면 평가에 큰 도움이 될 것 같습니다. 감사합니다!

## 🎯 KO-SAT Slayer Champions League Leaderboard란?

KO-SAT Slayer Champions League는 한국의 공신력 있는 매체인 KICE(한국교육과정평가원)에서 개발한 대학수학능력평가 시험인 국어 10개년 시험문제를 benchmark한 리더보드입니다.
수능 문제는 난이도에 따라 다양한 유형의 질문으로 구성되어 있으며, 독해력, 비판적 사고, 문장 해석 능력을 측정합니다.

## 🏆 명예의 전당 Top-10

- rank 기준: 10개년 수능 점수들의 평균으로 ranking
- 수능 점수 표기: 원점수(등급)

| Leaderboard Rank | Model Name                       | Submitter Name                 | Avg. Korean SAT Score (2015-2024) | Avg. Grade | 2024 SAT | 2023 SAT | 2022 SAT | 2021 SAT | 2020 SAT | 2019 SAT | 2018 SAT | 2017 SAT | 2016 SAT | 2015 SAT | URL                                                             |
|------------------|----------------------------------|--------------------------------|-----------------------------------|------------|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|-----------------------------------------------------------------|
| 1st              | GPT-4                            | OpenAI                         | 71.9                              | 1st Grade  |  62(4)   |  83(3)   |  62(4)   |  56(5)   |  74(4)   |  72(3)   |  82(3)   |  66(5)   |  84(3)   |  78(4)   | [Link](https://openai.com/)                                     |
| 2nd              | Meta-Llama-3.1-8B-Instruct-Turbo | meta-llama                     | 36.6                              | 7th Grade  |  49(6)   |  31(7)   |  36(7)   |  31(8)   |  36(7)   |  25(8)   |  38(7)   |  38(7)   |  37(7)   |  45(7)   | [Link](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct) |
| 3rd              | GPT-3.5-16K                      | OpenAI                         | 35.1                              | 7th Grade  |  26(7)   |  46(5)   |  44(6)   |  24(8)   |  35(7)   |  31(7)   |  37(7)   |  32(8)   |  44(7)   |  32(8)   | [Link](https://openai.com/)                                     |
| 4th              | Synatra-7B                       | maywell/Synatra-7B-v0.3-base   | 19.7                              | 9th Grade  |  13(9)   |  22(8)   |  22(8)   |  15(9)   |  19(9)   |  21(9)   |  24(8)   |  20(9)   |  16(9)   |  25(9)   | [Link](https://huggingface.co/maywell/Synatra-7B-v0.3-base)     |
| 5th              | KoR-Orca-Platypus-13B            | kyujinpy/KoR-Orca-Platypus-13B | 14.2                              | 9th Grade  |  11(9)   |  17(9)   |  19(9)   |   7(9)   |  11(9)   |  13(9)   |  11(9)   |  15(9)   |  17(9)   |  21(9)   | [Link](https://huggingface.co/kyujinpy/KoR-Orca-Platypus-13B)   |

### 📗 Notes. 24 수능 (1개년) 모델 성능 비교 결과

- o1-preview: 88점 (1등급, 상위 4%)
- o1-mini : 60점 (5등급)
- gpt-4o : 69점 (4등급)
- gpt-4o-mini : 62점(4등급)

## 🏅 Submit 방식

- 리더보드 공개를 원하지 않고, private하게 모델의 성능을 알고 싶다면 하고 싶은 말 파트에 남겨주세요!

1. **모델 submission**:
    - **[설문 Form으로 제출](https://moaform.com/q/QP0AV0)**: 설문 응답에 맞춰 작성해주세요!
        - 링크: https://moaform.com/q/QP0AV0
    - **이메일로 제출**: huggingFace에 게시된 자신의 finetuning 모델의 Url과 닉네임을 전송해주세요!
        - 제출 메일: developerminsing@gmail.com
    - **issue로 제출**: Github의 이슈에서 자신의 finetuning 모델의 Url과 닉네임을 게시해주세요!
    ```markdown
   <이메일 제출, 이슈 제출시 Form example>
    제출자 이름: 감스트
    HuggingFace 제출 URL: https://huggingface.co/감스트모델짜스
    하고 싶은말: 열심히 하시잖아
    ```

2. **리더보드 확인**: github와 huggingFace에서 자신의 순위를 확인할 수 있습니다.
3. **순위 상승 도전**: 자신의 순위를 올려 **Slayer Champion** 타이틀을 획득하세요.

**Notice:** 모델 제출후 가용한 GPU 리소스와, 제출량에 따라 1~3주일의 시간이 소요될 수 있습니다.

## 🪑 Benchmark 데이터셋

- 본 대회에서는 2015년부터 2024년까지의 10개년 수능 국어 문제를 사용합니다. 각 년도의 수능 국어 시험에서 출제된 문제와 지문을 기반으로 대회 참가 모델들의 성능을 평가하게 됩니다.
  수능 문제는 난이도에 따라 다양한 유형의 질문으로 구성되어 있으며, 독해력, 비판적 사고, 문장 해석 능력을 측정합니다.

- Benchmark 데이터셋의 주요 평가 목록은 언어 이해력, 핵심 내용 파악 능력, 논리적 사고력, 비판적 사고력, 창의적 사고력, 멀티미디어 해석력을 평가합니다.
  <출처: 2024 KICE 수능 국어 평가 목록>

## ♾️ Metric

- 대회에서는 각 모델이 제시된 문제에 대해 제출한 답안이 실제 정답과 일치하는지 여부를 측정하는 방식입니다.
- 평가 등급은 각 년도의 입시 전문 업체의 통계자료를 참고하여 나온 등급입니다.
- 평가 점수는 각 년도의 문제별로 채점되며, 최종적으로는 전체 점수의 평균을 통해 순위가 매겨집니다.

## 📗 참고해볼만한 Reference

- [Nomadamas 실험기록](https://github.com/NomaDamas/KICE_slayer_AI_Korean?tab=readme-ov-file#5-%ED%98%95%EC%8B%9D-%EC%A7%80%EC%A0%95-%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8)

## 📰 Notice

- 저작권 문제가 있을수 있어 수능 벤치마크 데이터셋은 공개하지 않을 예정입니다. 평가 데이터는 15수능 ~ 24수능입니다.
- 평가의 공정성을 위해서 프롬프트는 공개하지 않겠습니다!
- 랭킹은 10개년 수능의 평균으로 예정입니다.
- 추후 국영수사과 모두 리더보드에서 업데이트 예정입니다.

## 📬 문의하기

- 궁금한 점이나 오류, 지원이 필요하다면 언제든지 연락해 주세요:

- 이메일: developerminsing@gmail.com

**다음 KO-SAT Slayer Champion**이 될 준비가 되셨나요? 💪

---

_KO-SAT Slayer Champions League는 독립적인 플랫폼으로, 어떠한 공식 교육 기관 또는 단체와도 제휴되어 있지 않으며
비상업적인 목적을 가지고 있습니다._
