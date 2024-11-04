# 🙋 Questions

We've gathered questions from the Korean SAT LLM benchmark leaderboard and other leaderboard-related inquiries! Thank you for all the great questions! Please feel free to reach out anytime if you have any further questions!

---

### 🌱 The Korean language section includes images in some passages. Why didn’t you make it multimodal?
The first reason was cost. At the time of creating the Korean SAT data, GPT-4 Turbo had just been released last year, and the costs associated with generating data for the past 10 years of the Korean SAT were high.

The second reason was that solving the SAT questions required all clues, including image information, to be included in the explanations. However, multimodal models have limitations, so we had to manually write descriptions for images.

### 🌱 How long does it take for the LLM to complete all questions in a test? The Korean SAT language section has an 80-minute time limit (including OMR marking time), so I’m curious about how long it would take an LLM to complete the entire test.
It took as little as 10 minutes and as much as 25 minutes.

### 🌱 If the test is relatively easy, will the LLM achieve the same performance level? In the recent September mock test, the top 1st-grade cut-off score was a perfect 100, which made it quite easy. I’m curious whether the LLM would achieve a similar grade level in this test as in other, more challenging tests.
From our results, the impact of test difficulty on LLM performance varied across models, making generalization difficult.

For example, models like GPT-4o performed better and achieved higher grades on easier tests with a standard score peak in the 130s (e.g., 2015-2018 tests) compared to more challenging years. However, the Meta LLaMA 3.1 70B model received lower scores and grade levels on the same easy tests (2015-2018) and even scored in the 3rd grade on the challenging 2022 test, which peaked at a standard score of 149.

### 🌱 Did you obtain copyright permission from the Korea Institute for Curriculum and Evaluation (KICE) to use the SAT questions? Thank you!
No, we didn’t obtain copyright permission. According to KICE's response linked below, non-commercial use should be acceptable. Please let us know if there’s anything we may have overlooked—your feedback is greatly appreciated!

This benchmark leaderboard is a non-profit project designed to provide insights into LLM performance on the Korean SAT benchmarks.

https://suneung.re.kr/boardCnts/view.do?m=0304&boardID=1500232&viewBoardID=1500232&boardSeq=5062453&lev=0&statusYN=C&page=1