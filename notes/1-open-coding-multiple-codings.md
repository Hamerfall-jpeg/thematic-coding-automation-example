# Open coding
## Basic idea
Phase 1: Open Coding
- Identify and label concepts directly from the data
- Stay close to participants' language
- Create descriptive codes

Please go through all of the transcripts in `input/transcripts/`. For each one, do open coding. The coding system you 
should use will be `input/coding-system.md` (you should alreayd be familiar with this from reading CLAUDE.md, as there 
is a static copy of it there). For each statement in the transcript, do coding, as explained in CLAUDE.md.

## Inputs
- `input/transcripts/`: Raw text file representations of interivews, to be coded.
- `input/coding-system/`: The dimensions (main categories), codes, and sub-codes used to classify statements in transcripts.

## Outputs
- 1+ `output/TRANSCRIPT_NAME.csv`

For the CSV format, please use the example in `input/example-output.csv`

## Special deviations for this task only
In your instructions up until now, it has been said that the output CSVs should only have 1 code selected per statement.

However, I would like you to select the what you think are the 3 best codes for each statement. So, each statement will 
have 3 rows instead of 1. 
