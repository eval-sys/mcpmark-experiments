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

## Models Performance Summary

| Model | Tasks | Success Rate | Total Tokens | Total Turns |
|-------|-------|--------------|--------------|-------------|
| gpt-5 | 125 | 42.4% | 82,447,333 | 1783 |
| o3 | 125 | 27.2% | 50,585,699 | 1974 |
| claude-4-sonnet | 125 | 24.8% | 79,271,553 | 2263 |
| k2 | 121 | 19.0% | 56,037,480 | 2232 |
| deepseek-chat | 125 | 18.4% | 64,898,168 | 2497 |
| gemini-2-5-pro | 125 | 14.4% | 61,664,036 | 1256 |
| qwen-3-coder | 72 | 5.6% | 28,589,905 | 997 |

## K-Run Detailed Breakdown (k=4)

| Service/Model | Tasks | Pass@1 | Pass@4 | Pass^4 | Avg@4 |
|---------------|-------|--------|----------|----------|---------|
| filesystem_claude-4-sonnet | 30 | 23.3% | 50.0% | 6.7% | 27.5% |
| filesystem_deepseek-chat | 30 | 16.7% | 26.7% | 6.7% | 15.8% |
| filesystem_gemini-2-5-pro | 30 | 16.7% | 30.0% | 6.7% | 16.7% |
| filesystem_gpt-5 | 30 | 43.3% | 73.3% | 33.3% | 54.2% |
| filesystem_k2 | 30 | 20.0% | 30.0% | 13.3% | 20.0% |
| filesystem_o3 | 30 | 36.7% | 50.0% | 26.7% | 35.8% |
| filesystem_qwen-3-coder | 30 | 10.0% | 16.7% | 6.7% | 10.0% |
| github_claude-4-sonnet | 23 | 17.4% | 26.1% | 4.3% | 14.1% |
| github_deepseek-chat | 23 | 8.7% | 13.0% | 4.3% | 8.7% |
| github_gemini-2-5-pro | 23 | 8.7% | 13.0% | 0.0% | 3.3% |
| github_gpt-5 | 23 | 26.1% | 39.1% | 13.0% | 26.1% |
| github_k2 | 23 | 8.7% | 13.0% | 0.0% | 7.6% |
| github_o3 | 23 | 8.7% | 21.7% | 4.3% | 13.0% |
| github_qwen-3-coder | 23 | 4.3% | 17.4% | 4.3% | 10.9% |
| notion_claude-4-sonnet | 28 | 14.3% | 35.7% | 7.1% | 20.5% |
| notion_deepseek-chat | 28 | 17.9% | 25.0% | 0.0% | 10.7% |
| notion_gemini-2-5-pro | 28 | 0.0% | 0.0% | 0.0% | 0.0% |
| notion_gpt-5 | 28 | 32.1% | 53.6% | 10.7% | 35.7% |
| notion_k2 | 28 | 10.7% | 25.0% | 3.6% | 10.7% |
| notion_o3 | 28 | 25.0% | 42.9% | 7.1% | 23.2% |
| playwright_claude-4-sonnet | 25 | 28.0% | 36.0% | 8.0% | 26.0% |
| playwright_deepseek-chat | 25 | 12.0% | 16.0% | 0.0% | 7.0% |
| playwright_gemini-2-5-pro | 25 | 16.0% | 32.0% | 4.0% | 15.0% |
| playwright_gpt-5 | 25 | 40.0% | 52.0% | 28.0% | 41.0% |
| playwright_k2 | 21 | 14.3% | 19.1% | 4.8% | 13.1% |
| playwright_o3 | 25 | 20.0% | 28.0% | 8.0% | 14.0% |
| postgres_claude-4-sonnet | 19 | 47.4% | 68.4% | 36.8% | 52.6% |
| postgres_deepseek-chat | 19 | 42.1% | 68.4% | 31.6% | 47.4% |
| postgres_gemini-2-5-pro | 19 | 36.8% | 47.4% | 10.5% | 27.6% |
| postgres_gpt-5 | 19 | 79.0% | 100.0% | 36.8% | 75.0% |
| postgres_k2 | 19 | 47.4% | 63.2% | 26.3% | 35.5% |
| postgres_o3 | 19 | 47.4% | 68.4% | 15.8% | 39.5% |
| postgres_qwen-3-coder | 19 | 0.0% | 0.0% | 0.0% | 0.0% |

## Services Performance Summary

| Service | Tasks | Success Rate | Total Tokens | Total Turns |
|---------|-------|--------------|--------------|-------------|
| postgres | 133 | 42.9% | 23,238,915 | 2116 |
| filesystem | 210 | 23.8% | 80,135,898 | 4094 |
| playwright | 146 | 21.9% | 177,889,214 | 2962 |
| notion | 168 | 16.7% | 71,012,827 | 2547 |
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

## Notion Service Breakdown

### k2

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| japan_travel_planner | 4 | 25.0% | 674803 | 18.0 |
| toronto_guide | 2 | 0.0% | 253280 | 13.0 |
| online_resume | 4 | 0.0% | 647296 | 28.5 |
| team_projects | 2 | 0.0% | 79326 | 6.0 |
| standard_operating_procedure | 2 | 0.0% | 623340 | 29.0 |
| it_trouble_shooting_hub | 3 | 66.67% | 979547 | 23.0 |
| computer_science_student_dashboard | 3 | 0.0% | 218104 | 13.7 |
| python_roadmap | 2 | 0.0% | 746216 | 28.0 |
| self_assessment | 3 | 0.0% | 836775 | 23.7 |
| company_in_a_box | 3 | 0.0% | 634967 | 26.7 |

### gpt-5

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| japan_travel_planner | 4 | 50.0% | 300686 | 8.0 |
| toronto_guide | 2 | 50.0% | 94624 | 5.5 |
| online_resume | 4 | 0.0% | 384442 | 16.8 |
| team_projects | 2 | 50.0% | 95992 | 5.5 |
| standard_operating_procedure | 2 | 50.0% | 1024741 | 23.5 |
| it_trouble_shooting_hub | 3 | 66.67% | 532216 | 16.3 |
| computer_science_student_dashboard | 3 | 33.33% | 146571 | 11.3 |
| python_roadmap | 2 | 0.0% | 701696 | 14.5 |
| self_assessment | 3 | 33.33% | 1294289 | 23.7 |
| company_in_a_box | 3 | 0.0% | 1353523 | 28.7 |

### gemini-2-5-pro

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| japan_travel_planner | 4 | 0.0% | 84903 | 2.2 |
| toronto_guide | 2 | 0.0% | 43904 | 3.5 |
| online_resume | 4 | 0.0% | 131030 | 8.5 |
| team_projects | 2 | 0.0% | 41271 | 3.0 |
| standard_operating_procedure | 2 | 0.0% | 37199 | 3.5 |
| it_trouble_shooting_hub | 3 | 0.0% | 140007 | 3.0 |
| computer_science_student_dashboard | 3 | 0.0% | 38029 | 4.0 |
| python_roadmap | 2 | 0.0% | 239912 | 6.0 |
| self_assessment | 3 | 0.0% | 20575 | 1.7 |
| company_in_a_box | 3 | 0.0% | 238519 | 8.7 |

### deepseek-chat

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| japan_travel_planner | 4 | 0.0% | 271487 | 8.5 |
| toronto_guide | 2 | 50.0% | 519958 | 21.5 |
| online_resume | 4 | 25.0% | 538533 | 22.0 |
| team_projects | 2 | 50.0% | 144362 | 9.0 |
| standard_operating_procedure | 2 | 0.0% | 1063252 | 36.0 |
| it_trouble_shooting_hub | 3 | 33.33% | 412975 | 15.7 |
| computer_science_student_dashboard | 3 | 33.33% | 213681 | 14.3 |
| python_roadmap | 2 | 0.0% | 333776 | 12.0 |
| self_assessment | 3 | 0.0% | 390506 | 13.7 |
| company_in_a_box | 3 | 0.0% | 270900 | 15.0 |

### claude-4-sonnet

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| japan_travel_planner | 4 | 25.0% | 575933 | 12.8 |
| toronto_guide | 2 | 50.0% | 266427 | 14.0 |
| online_resume | 4 | 0.0% | 694263 | 22.5 |
| team_projects | 2 | 0.0% | 471618 | 19.0 |
| standard_operating_procedure | 2 | 0.0% | 1068700 | 34.0 |
| it_trouble_shooting_hub | 3 | 33.33% | 429811 | 13.7 |
| computer_science_student_dashboard | 3 | 33.33% | 273786 | 14.3 |
| python_roadmap | 2 | 0.0% | 559361 | 16.5 |
| self_assessment | 3 | 0.0% | 707999 | 20.0 |
| company_in_a_box | 3 | 0.0% | 957340 | 27.7 |

### o3

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| japan_travel_planner | 4 | 25.0% | 315325 | 11.8 |
| toronto_guide | 2 | 0.0% | 223194 | 18.0 |
| online_resume | 4 | 25.0% | 334093 | 18.8 |
| team_projects | 2 | 50.0% | 57410 | 6.0 |
| standard_operating_procedure | 2 | 0.0% | 413785 | 21.0 |
| it_trouble_shooting_hub | 3 | 66.67% | 130510 | 10.0 |
| computer_science_student_dashboard | 3 | 33.33% | 194627 | 16.3 |
| python_roadmap | 2 | 0.0% | 269068 | 16.5 |
| self_assessment | 3 | 0.0% | 199298 | 9.0 |
| company_in_a_box | 3 | 33.33% | 204391 | 14.3 |

## Filesystem Service Breakdown

### k2

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| threestudio | 3 | 33.33% | 105570 | 10.0 |
| legal_document | 3 | 0.0% | 173526 | 7.7 |
| desktop | 3 | 33.33% | 230709 | 25.7 |
| file_context | 5 | 20.0% | 54086 | 12.8 |
| student_database | 3 | 0.0% | 1951509 | 45.3 |
| votenet | 3 | 0.0% | 443762 | 25.3 |
| desktop_template | 3 | 0.0% | 151162 | 24.3 |
| folder_structure | 2 | 50.0% | 188483 | 24.5 |
| papers | 3 | 0.0% | 687228 | 20.0 |
| file_property | 2 | 100.0% | 70791 | 16.0 |

### gemini-2-5-pro

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| threestudio | 3 | 33.33% | 70420 | 13.0 |
| legal_document | 3 | 33.33% | 274326 | 8.3 |
| desktop | 3 | 0.0% | 46630 | 5.3 |
| file_context | 5 | 20.0% | 56216 | 13.6 |
| student_database | 3 | 33.33% | 191438 | 8.3 |
| votenet | 3 | 0.0% | 207078 | 12.3 |
| desktop_template | 3 | 0.0% | 27776 | 9.7 |
| folder_structure | 2 | 0.0% | 31772 | 4.0 |
| papers | 3 | 33.33% | 837929 | 17.7 |
| file_property | 2 | 0.0% | 6942 | 3.5 |

### deepseek-chat

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| threestudio | 3 | 33.33% | 111691 | 14.7 |
| legal_document | 3 | 0.0% | 490071 | 11.0 |
| desktop | 3 | 0.0% | 159039 | 23.0 |
| file_context | 5 | 0.0% | 110862 | 18.6 |
| student_database | 3 | 0.0% | 1420503 | 53.0 |
| votenet | 3 | 33.33% | 610508 | 26.0 |
| desktop_template | 3 | 0.0% | 263889 | 39.3 |
| folder_structure | 2 | 0.0% | 326648 | 29.0 |
| papers | 3 | 33.33% | 2600012 | 50.3 |
| file_property | 2 | 100.0% | 168087 | 33.0 |

### qwen-3-coder

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| threestudio | 3 | 33.33% | 355161 | 20.3 |
| legal_document | 3 | 0.0% | 114506 | 6.3 |
| desktop | 3 | 0.0% | 234514 | 33.7 |
| file_context | 5 | 0.0% | 150609 | 21.8 |
| student_database | 3 | 0.0% | 485431 | 14.3 |
| votenet | 3 | 0.0% | 313062 | 14.3 |
| desktop_template | 3 | 0.0% | 339288 | 39.3 |
| folder_structure | 2 | 0.0% | 600650 | 59.0 |
| papers | 3 | 0.0% | 113135 | 5.7 |
| file_property | 2 | 100.0% | 176565 | 32.0 |

### o3

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| threestudio | 3 | 33.33% | 2152935 | 42.7 |
| legal_document | 3 | 66.67% | 298493 | 9.3 |
| desktop | 3 | 66.67% | 105382 | 17.3 |
| file_context | 5 | 60.0% | 72930 | 18.0 |
| student_database | 3 | 33.33% | 742119 | 22.7 |
| votenet | 3 | 0.0% | 512953 | 28.7 |
| desktop_template | 3 | 0.0% | 200580 | 35.7 |
| folder_structure | 2 | 0.0% | 486690 | 27.5 |
| papers | 3 | 0.0% | 1565285 | 39.7 |
| file_property | 2 | 100.0% | 142352 | 34.5 |

### gpt-5

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| threestudio | 3 | 33.33% | 337987 | 11.7 |
| legal_document | 3 | 66.67% | 224350 | 6.7 |
| desktop | 3 | 100.0% | 55353 | 7.7 |
| file_context | 5 | 40.0% | 35614 | 7.8 |
| student_database | 3 | 33.33% | 193062 | 6.7 |
| votenet | 3 | 33.33% | 325835 | 14.0 |
| desktop_template | 3 | 0.0% | 67300 | 10.0 |
| folder_structure | 2 | 0.0% | 239416 | 17.0 |
| papers | 3 | 33.33% | 1091235 | 8.3 |
| file_property | 2 | 100.0% | 81162 | 17.5 |

### claude-4-sonnet

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| threestudio | 3 | 33.33% | 267203 | 13.3 |
| legal_document | 3 | 0.0% | 237818 | 6.7 |
| desktop | 3 | 66.67% | 145329 | 17.7 |
| file_context | 5 | 20.0% | 67310 | 12.8 |
| student_database | 3 | 33.33% | 403698 | 12.0 |
| votenet | 3 | 0.0% | 379476 | 20.0 |
| desktop_template | 3 | 0.0% | 358161 | 28.7 |
| folder_structure | 2 | 50.0% | 375466 | 21.5 |
| papers | 3 | 0.0% | 1121509 | 17.7 |
| file_property | 2 | 50.0% | 109953 | 22.5 |

## Postgres Service Breakdown

### deepseek-chat

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| lego | 3 | 33.33% | 955231 | 33.7 |
| sports | 3 | 33.33% | 510715 | 33.3 |
| employees | 6 | 33.33% | 151333 | 25.3 |
| chinook | 3 | 33.33% | 139274 | 17.3 |
| security | 1 | 100.0% | 162893 | 24.0 |
| dvdrental | 3 | 66.67% | 156227 | 19.7 |

### o3

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| lego | 3 | 0.0% | 295213 | 6.0 |
| sports | 3 | 66.67% | 135135 | 18.7 |
| employees | 6 | 50.0% | 31209 | 9.2 |
| chinook | 3 | 33.33% | 32942 | 6.0 |
| security | 1 | 100.0% | 51681 | 9.0 |
| dvdrental | 3 | 66.67% | 29048 | 7.7 |

### claude-4-sonnet

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| lego | 3 | 33.33% | 545822 | 42.7 |
| sports | 3 | 33.33% | 364870 | 27.7 |
| employees | 6 | 33.33% | 217720 | 26.2 |
| chinook | 3 | 66.67% | 341146 | 25.3 |
| security | 1 | 100.0% | 240025 | 26.0 |
| dvdrental | 3 | 66.67% | 433406 | 22.0 |

### k2

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| lego | 3 | 33.33% | 329528 | 23.0 |
| sports | 3 | 66.67% | 614655 | 33.0 |
| employees | 6 | 50.0% | 185792 | 29.2 |
| chinook | 3 | 33.33% | 143550 | 19.3 |
| security | 1 | 0.0% | 268408 | 33.0 |
| dvdrental | 3 | 66.67% | 126275 | 18.0 |

### qwen-3-coder

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| lego | 3 | 0.0% | 0 | 2.0 |
| sports | 3 | 0.0% | 0 | 2.0 |
| employees | 6 | 0.0% | 0 | 2.0 |
| chinook | 3 | 0.0% | 0 | 2.0 |
| security | 1 | 0.0% | 0 | 2.0 |
| dvdrental | 3 | 0.0% | 0 | 2.0 |

### gemini-2-5-pro

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| lego | 3 | 100.0% | 47906 | 7.7 |
| sports | 3 | 33.33% | 31608 | 7.3 |
| employees | 6 | 16.67% | 84723 | 12.3 |
| chinook | 3 | 33.33% | 31495 | 7.7 |
| security | 1 | 0.0% | 90121 | 8.0 |
| dvdrental | 3 | 33.33% | 21350 | 5.3 |

### gpt-5

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| lego | 3 | 100.0% | 415728 | 12.3 |
| sports | 3 | 66.67% | 159124 | 18.7 |
| employees | 6 | 50.0% | 58628 | 11.2 |
| chinook | 3 | 100.0% | 70303 | 7.0 |
| security | 1 | 100.0% | 73108 | 11.0 |
| dvdrental | 3 | 100.0% | 61530 | 9.7 |

## Playwright Service Breakdown

### claude-4-sonnet

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| reddit | 7 | 28.57% | 1403226 | 21.3 |
| shopping_admin | 7 | 28.57% | 1044005 | 18.9 |
| web_search | 2 | 0.0% | 387954 | 7.0 |
| eval_web | 2 | 0.0% | 288468 | 19.0 |
| shopping | 7 | 42.86% | 2004645 | 23.4 |

### gpt-5

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| reddit | 7 | 28.57% | 1728916 | 22.6 |
| shopping_admin | 7 | 28.57% | 666327 | 18.0 |
| web_search | 2 | 0.0% | 1714856 | 32.5 |
| eval_web | 2 | 50.0% | 1137778 | 36.0 |
| shopping | 7 | 71.43% | 2889875 | 28.1 |

### deepseek-chat

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| reddit | 7 | 0.0% | 743292 | 20.6 |
| shopping_admin | 7 | 42.86% | 899116 | 23.3 |
| web_search | 2 | 0.0% | 680822 | 12.0 |
| eval_web | 2 | 0.0% | 158262 | 13.5 |
| shopping | 7 | 0.0% | 1256672 | 19.6 |

### k2

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| reddit | 7 | 14.29% | 565873 | 17.3 |
| shopping_admin | 7 | 28.57% | 596009 | 18.7 |
| shopping | 7 | 0.0% | 1208734 | 18.6 |

### gemini-2-5-pro

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| reddit | 7 | 14.29% | 2135321 | 26.1 |
| shopping_admin | 7 | 28.57% | 1891867 | 20.4 |
| web_search | 2 | 0.0% | 1083778 | 15.0 |
| eval_web | 2 | 0.0% | 371772 | 14.5 |
| shopping | 7 | 14.29% | 2891911 | 27.6 |

### o3

| Category | Tasks | Success Rate | Avg Tokens | Avg Turns |
|----------|-------|--------------|------------|-----------|
| reddit | 7 | 14.29% | 539434 | 16.6 |
| shopping_admin | 7 | 28.57% | 423909 | 14.7 |
| web_search | 2 | 0.0% | 494946 | 14.5 |
| eval_web | 2 | 50.0% | 289098 | 21.0 |
| shopping | 7 | 14.29% | 635690 | 14.6 |

---
*Generated automatically from consolidated-all-services-0822 evaluation results*