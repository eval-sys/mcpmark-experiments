# consolidated-all-services-0822 - Evaluation Results

## Overview

- **Total Tasks**: 818
- **Service/Model Combinations**: 33
- **Overall Success Rate**: 22.74%
- **Evaluation Type**: 4-run evaluation
- **Pass@1**: 22.7% (first run success rate)
- **Pass@4**: 35.6% (at least 1 success in 4 runs)
- **Pass^4**: 10.8% (all 4 runs succeed)
- **Avg@4**: 22.3% (average success rate across runs)

## Models Overall Performance

Performance of each model across all MCP services:

| Model | Total Tasks | Pass@1 | Pass@4 | Pass^4 | Avg@4 |
|-------|-------------|--------|----------|----------|---------|
| gpt-5 | 125 | 44.1% | 63.6% | 24.4% | 46.4% |
| o3 | 125 | 27.5% | 42.2% | 12.4% | 25.1% |
| claude-4-sonnet | 125 | 26.1% | 43.2% | 12.6% | 28.2% |
| k2 | 121 | 20.2% | 30.0% | 9.6% | 17.4% |
| deepseek-chat | 125 | 19.5% | 29.8% | 8.5% | 17.9% |
| gemini-2-5-pro | 125 | 15.6% | 24.5% | 4.2% | 12.5% |
| qwen-3-coder | 72 | 4.8% | 11.4% | 3.7% | 7.0% |

## MCP Services Overall Performance

Performance of each MCP service across all models:

| Service | Total Tasks | Pass@1 | Pass@4 | Pass^4 | Avg@4 |
|---------|-------------|--------|----------|----------|---------|
| postgres | 133 | 42.9% | 59.4% | 22.6% | 39.7% |
| filesystem | 210 | 23.8% | 39.5% | 14.3% | 25.7% |
| playwright | 146 | 21.7% | 30.5% | 8.8% | 19.4% |
| notion | 168 | 16.7% | 30.4% | 4.8% | 16.8% |
| github | 161 | 11.8% | 20.5% | 4.3% | 12.0% |

---
*Generated automatically from consolidated-all-services-0822 evaluation results*