# GITHUB-MULTI-RUN - Evaluation Results

## Overview

- **Total Tasks**: 161
- **Service/Model Combinations**: 7
- **Overall Success Rate**: 11.8%
- **Evaluation Type**: 4-run evaluation
- **Pass@1**: 11.8% (first run success rate)
- **Pass@4**: 20.5% (at least 1 success in 4 runs)
- **Pass^4**: 4.3% (all 4 runs succeed)
- **Avg@4**: 12.0% (average success rate across runs)

## Models Performance Summary

| Model | Tasks | Success Rate | Total Tokens | Total Turns |
|-------|-------|--------------|--------------|-------------|
| gpt-5 | 23 | 26.1% | 12,942,306 | 204 |
| claude-4-sonnet | 23 | 17.4% | 13,186,724 | 195 |
| gemini-2-5-pro | 23 | 8.7% | 1,098,722 | 78 |
| k2 | 23 | 8.7% | 5,697,708 | 143 |
| deepseek-chat | 23 | 8.7% | 6,833,322 | 190 |
| o3 | 23 | 8.7% | 11,041,395 | 207 |
| qwen-3-coder | 23 | 4.3% | 20,417,143 | 266 |

## K-Run Detailed Breakdown (k=4)

| Service/Model | Tasks | Pass@1 | Pass@4 | Pass^4 | Avg@4 |
|---------------|-------|--------|----------|----------|---------|
| github_claude-4-sonnet | 23 | 17.4% | 26.1% | 4.3% | 14.1% |
| github_deepseek-chat | 23 | 8.7% | 13.0% | 4.3% | 8.7% |
| github_gemini-2-5-pro | 23 | 8.7% | 13.0% | 0.0% | 3.3% |
| github_gpt-5 | 23 | 26.1% | 39.1% | 13.0% | 26.1% |
| github_k2 | 23 | 8.7% | 13.0% | 0.0% | 7.6% |
| github_o3 | 23 | 8.7% | 21.7% | 4.3% | 13.0% |
| github_qwen-3-coder | 23 | 4.3% | 17.4% | 4.3% | 10.9% |

## Services Performance Summary

| Service | Tasks | Success Rate | Total Tokens | Total Turns |
|---------|-------|--------------|--------------|-------------|
| github | 161 | 11.8% | 71,217,320 | 1283 |

## Github Service Breakdown

### gemini-2-5-pro

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| harmony | 5 | 20.0% | 43392 | 3.4 |
| easyr1 | 4 | 0.0% | 20210 | 2.0 |
| claude_code | 5 | 20.0% | 64544 | 3.4 |
| missing_semester | 3 | 0.0% | 20199 | 2.0 |
| mcpmark_cicd | 4 | 0.0% | 87531 | 5.8 |
| build_your_own_x | 2 | 0.0% | 33742 | 3.5 |

### claude-4-sonnet

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| harmony | 5 | 20.0% | 890301 | 14.4 |
| easyr1 | 4 | 50.0% | 208869 | 8.5 |
| claude_code | 5 | 20.0% | 660642 | 8.2 |
| missing_semester | 3 | 0.0% | 1359071 | 8.3 |
| mcpmark_cicd | 4 | 0.0% | 84916 | 4.0 |
| build_your_own_x | 2 | 0.0% | 89828 | 3.5 |

### gpt-5

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| harmony | 5 | 20.0% | 443193 | 11.2 |
| easyr1 | 4 | 50.0% | 1076824 | 10.5 |
| claude_code | 5 | 20.0% | 218171 | 7.0 |
| missing_semester | 3 | 0.0% | 911768 | 9.3 |
| mcpmark_cicd | 4 | 25.0% | 123252 | 6.8 |
| build_your_own_x | 2 | 50.0% | 1049940 | 8.0 |

### k2

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| harmony | 5 | 0.0% | 365153 | 8.4 |
| easyr1 | 4 | 50.0% | 372338 | 9.5 |
| claude_code | 5 | 0.0% | 318253 | 6.8 |
| missing_semester | 3 | 0.0% | 148752 | 2.3 |
| mcpmark_cicd | 4 | 0.0% | 47855 | 3.2 |
| build_your_own_x | 2 | 0.0% | 76824 | 4.5 |

### qwen-3-coder

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| harmony | 5 | 0.0% | 538894 | 11.6 |
| easyr1 | 4 | 25.0% | 1199770 | 12.2 |
| claude_code | 5 | 0.0% | 535308 | 10.0 |
| missing_semester | 3 | 0.0% | 2162633 | 12.7 |
| mcpmark_cicd | 4 | 0.0% | 414782 | 12.5 |
| build_your_own_x | 2 | 0.0% | 1050014 | 10.5 |

### deepseek-chat

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| harmony | 5 | 0.0% | 523196 | 11.0 |
| easyr1 | 4 | 50.0% | 172773 | 7.2 |
| claude_code | 5 | 0.0% | 452538 | 10.4 |
| missing_semester | 3 | 0.0% | 57640 | 2.7 |
| mcpmark_cicd | 4 | 0.0% | 190224 | 8.8 |
| build_your_own_x | 2 | 0.0% | 164872 | 5.5 |

### o3

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| harmony | 5 | 20.0% | 538075 | 14.2 |
| easyr1 | 4 | 0.0% | 208292 | 9.5 |
| claude_code | 5 | 0.0% | 230029 | 6.8 |
| missing_semester | 3 | 0.0% | 1258013 | 9.7 |
| mcpmark_cicd | 4 | 25.0% | 50160 | 3.8 |
| build_your_own_x | 2 | 0.0% | 1196515 | 10.0 |

---
*Generated automatically from GITHUB-MULTI-RUN evaluation results*