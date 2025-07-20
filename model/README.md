# WeQuiz ML Server
> This folder contains the ML pipeline used to generate quizzes and evaluate answers based on PDF documents.


## Overview
1. Document Summarization  
2. Question Generation  
3. Answer Evaluation  

## Architecture

<table>
    <tbody>
        <tr>
          <tr>
            <td align='center'>Quiz and Document Summarization Workflow</td>
          </tr>
          <tr>
            <td align='center'><img src="assets/ml_architecture.png"></td>
          </tr>
    </tbody>
</table>

## 🧪 Experiments I Conducted
- [[KO](https://graceful-echinodon-2a3.notion.site/6f4f44a6f3fd40f5b0d02bfbf75cb89b?pvs=74)] 요약 속도에 영향을 주는 프롬프트 언어, 길이, 청킹 전략에 대한 단변수 실험
- [[EN](https://graceful-echinodon-2a3.notion.site/Problem-generation-labs-236a84372a1b8040a67fd2627f2a5ac9)] Single-variable experiments on prompt language, output length, and chunking strategy to optimize summarization latency
