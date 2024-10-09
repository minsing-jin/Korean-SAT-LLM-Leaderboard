![image](https://github.com/user-attachments/assets/a71e95a5-34f6-4a5b-b698-54560c7a09d6)

# KO-SAT Slayer Champions League

Welcome to the **KO-SAT Slayer Champions League**! 🚀 This is the leaderboard to identify the ultimate slayer of the
Korean SAT (Suneung).

Check how well your Korean LLM fine-tuning model performs on a 10-year benchmark of the Korean SAT! If you can provide
GPU resources, it will greatly assist the evaluation process for us. Thank you in advance!

[한국어 설명 바로가기](https://github.com/minsing-jin/KO-SAT_Slayer_Champions_League/blob/main/Korean_README.md)

## 🎯 What is the KO-SAT Slayer Champions League Leaderboard?

The KO-SAT Slayer Champions League is a leaderboard that benchmarks LLM models using the Korean SAT (Suneung) language
exams, developed by KICE (Korea Institute for Curriculum and Evaluation), spanning from 2015 to 2024.

These exams are composed of various types of questions based on difficulty level, testing reading comprehension,
critical thinking, and sentence interpretation skills.

The Korean SAT (Suneung) is the most credible and highest-quality exam in South Korea, known for its rigorous standards
and exceptional question quality.

## 🏆 Hall of Fame Top-10

- **Ranking Criterion**: Average scores across 10 years of the Korean SAT
- **Scoring Format**: Raw score (Grade that )

| Leaderboard Rank | Model Name                       | Submitter Name                 | Avg. Korean SAT Score (2015-2024) | Avg. Grade | 2024 SAT | 2023 SAT | 2022 SAT | 2021 SAT | 2020 SAT | 2019 SAT | 2018 SAT | 2017 SAT | 2016 SAT | 2015 SAT | URL                                                             |
|------------------|----------------------------------|--------------------------------|-----------------------------------|------------|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|-----------------------------------------------------------------|
| 1st              | GPT-4                            | OpenAI                         | 71.9                              | 1st Grade  |  62(4)   |  83(3)   |  62(4)   |  56(5)   |  74(4)   |  72(3)   |  82(3)   |  66(5)   |  84(3)   |  78(4)   | [Link](https://openai.com/)                                     |
| 2nd              | Meta-Llama-3.1-8B-Instruct-Turbo | meta-llama                     | 36.6                              | 7th Grade  |  49(6)   |  31(7)   |  36(7)   |  31(8)   |  36(7)   |  25(8)   |  38(7)   |  38(7)   |  37(7)   |  45(7)   | [Link](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct) |
| 3rd              | GPT-3.5-16K                      | OpenAI                         | 35.1                              | 7th Grade  |  26(7)   |  46(5)   |  44(6)   |  24(8)   |  35(7)   |  31(7)   |  37(7)   |  32(8)   |  44(7)   |  32(8)   | [Link](https://openai.com/)                                     |
| 4th              | Synatra-7B                       | maywell/Synatra-7B-v0.3-base   | 19.7                              | 9th Grade  |  13(9)   |  22(8)   |  22(8)   |  15(9)   |  19(9)   |  21(9)   |  24(8)   |  20(9)   |  16(9)   |  25(9)   | [Link](https://huggingface.co/maywell/Synatra-7B-v0.3-base)     |
| 5th              | KoR-Orca-Platypus-13B            | kyujinpy/KoR-Orca-Platypus-13B | 14.2                              | 9th Grade  |  11(9)   |  17(9)   |  19(9)   |   7(9)   |  11(9)   |  13(9)   |  11(9)   |  15(9)   |  17(9)   |  21(9)   | [Link](https://huggingface.co/kyujinpy/KoR-Orca-Platypus-13B)   |

### 📗 Results for 2024 (Single-Year Performance Comparison)

- o1-preview: 88 points (1st Grade, Top 4%)
- o1-mini : 60 points (5th Grade)
- gpt-4o : 69 points (4th Grade)
- gpt-4o-mini : 62 points (4th Grade)

## 🏅 Submission Process

- If you don't want the leaderboard to be public and want to know your model's performance in private, leave your
  comments in the blank!

1. **Model Submission**:
    - **[Submit via Survey Form](https://moaform.com/q/X6xfGE)**: Please fill it out based on the survey responses!
        - Link: https://moaform.com/q/X6xfGE
    - **Submit via Email**: Send the URL of your fine-tuned model posted on HuggingFace along with your nickname!
        - Submission Email: developerminsing@gmail.com
    - **Submit via Issue**: Post the URL of your fine-tuned model and your nickname in the GitHub issue!
    ```markdown
   <Form Example for Email Submission or Issue Submission>
    Submitter Name: Elonmusk
    HuggingFace Submission URL: https://huggingface.co/ElonmuskModelDogeletsgo
    Want to talk: Lets go Mars!
    ```
2. **Check the Leaderboard**: Track your ranking on GitHub and HuggingFace.

3. **Challenge for a Higher Rank**: Aim to improve your ranking and earn the title of **Slayer Champion**.

**Notice:** It may take 1-3 weeks to process submissions depending on GPU availability and the volume of submissions.

## 🪑 Benchmark Dataset

- This competition uses the Korean SAT (Suneung) language exam questions from 2015 to 2024. The performance of the
  participating models will be evaluated based on these questions.

- The exam includes various question types that assess reading comprehension, critical thinking, and sentence
  interpretation.

- The primary evaluation criteria for the benchmark dataset include linguistic comprehension, core content analysis,
  logical reasoning, critical thinking, creative thinking, and multimedia interpretation.
  <Source: 2024 KICE Korean SAT Evaluation Criteria>

### 🙋‍ About Korean SAT

The Korean SAT is widely regarded as one of the most credible and challenging exams, with rigorous questions that assess
deep comprehension and critical thinking skills.
Its high standards and fair evaluation process make it a trusted benchmark in South Korea, known for its academic
excellence and influence on university admissions.

## ♾️ Metric

- The competition evaluates each model by measuring how closely the submitted answers match the actual correct answers.
- The evaluation grades are based on statistics from specialized admissions agencies for each year.
- Scores are assigned for each year's individual questions, and the final rankings are determined by the average score
  across all years.

## 📗 Suggested References

- [Nomadamas Experiment Log](https://github.com/NomaDamas/KICE_slayer_AI_Korean?tab=readme-ov-file#5-%ED%98%95%EC%8B%9D-%EC%A7%80%EC%A0%95-%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8)

## 📰 Notice

- Due to copyright issues, the benchmark dataset for the Korean SAT will not be made public. The evaluation will be
  based on the 2015 to 2024 exams.
- To ensure fairness, the exact prompts will not be revealed!
- Rankings will be based on the average scores across the 10 years of the Korean SAT.
- Updates for all subject areas (English, Mathematics, Social Studies, and Science) will be added to the leaderboard in
  the future.

## 📬 Contact Us

- For questions, errors, or support, feel free to reach out:

- Email: developerminsing@gmail.com

Are you ready to become the next **KO-SAT Slayer Champion**? 💪

---

_KO-SAT Slayer Champions League is an independent platform and is not affiliated with any official educational
institution or organization. It is intended for non-commercial purposes._