# Task_05_Descriptive_Stats-2

# Syracuse Women's Lacrosse 2024 - LLM Evaluation

## Dataset
**Source**: 2024SUStats.pdf - Syracuse Women's Lacrosse official season statistics  
**Record**: 16-6 overall (9-1 conference, 7-5 non-conference)  
**Games**: 22 total games from February to May 2024

### Data Available:
- Team records and game results with scores/attendance
- Goals, shots, saves by period (Syracuse vs Opponents)
- Team statistics: turnovers, ground balls, clears, free positions

### Data Limitations:
- No individual player statistics or names
- No game-by-game breakdowns beyond final scores
- No contextual information (injuries, weather, penalties)

## LLM Evaluation Results
Tested 25 questions across basic stats, analytical reasoning, and data limitations.

**What worked well:**
* Mathematical calculations and basic stat retrieval were highly accurate
* Models correctly computed save percentages (42.0%), shot conversion rates (64.2%), and clearing percentages (90.9%)
* Successfully identified trends like 1st period dominance (108 goals) and conference vs non-conference performance differences

**What didn't work:**
* LLMs fabricated player names and individual statistics when asked about specific players
* Created fictional injury reports, weather impacts, and comeback scenarios without supporting data
* Made confident claims about penalty statistics and substitution patterns not in the dataset
* Failed to acknowledge data limitations when making unsupported assumptions

## Reflections on LLM Evaluation

Working with LLM(Claude Sonnet 4) on the Syracuse 2024 dataset was revealing. The models were highly accurate when answering direct, fact-based questions using provided team statistics. They excelled at mathematical operations, trend identification, and multi-metric analysis.

However, significant limitations emerged when questions required player-level data or contextual insights not available in the dataset. LLMs frequently fabricated plausible but entirely false information, including specific player names, injury scenarios, and performance breakdowns. Most concerning was their confident delivery of these fabrications.

**What worked well:**
* Clear data formatting and explicit constraints improved accuracy
* Models excelled at calculations and pattern recognition from aggregate statistics
* Proper acknowledgment of data limitations when explicitly prompted

**What didn't work:**
* Lack of individual player data led to confident fabrications
* Models failed to recognize "unknown" without explicit guidance
* Created authoritative-sounding narratives from insufficient data

**Key Takeaway**: LLMs are powerful tools for structured sports data analysis but require careful prompt design, explicit data boundaries, and systematic validation to prevent authoritative-sounding misinformation. They work best as sophisticated calculators rather than omniscient analysts.
