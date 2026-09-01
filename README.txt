STROOP COLOR-WORD EXPERIMENT

FILES
- stroop_experiment.html — the complete experiment. No other files or libraries are required.

HOW TO RUN
1. Open stroop_experiment.html in a web browser.
2. Select Start Practice.
3. Complete the 8 practice trials.
4. Select Begin Experiment.
5. Complete the 48 experimental trials.
6. On the results screen, select Download CSV.

THE EXPERIMENT
- 48 experimental trials
- 24 congruent trials and 24 incongruent trials
- Four color words: RED, BLUE, GREEN, YELLOW
- Four ink colors: red, blue, green, yellow
- No keyboard responses
- Randomized trial order
- 500 ms fixation before each stimulus
- Reaction time measured in milliseconds
- Accuracy recorded for every trial

CSV DATA
The downloaded file is named:
Stroop_Trial_Data.csv

Each experimental trial contains:
- trial number
- condition
- word shown
- ink color
- response
- correct/incorrect
- reaction time in milliseconds

The CSV can be opened with a spreadsheet program such as Google Sheets, Microsoft Excel, or Apple Numbers.

TIMING
The experiment uses the browser's performance.now() timer. The reaction timer begins after the stimulus has been rendered and stops when the participant taps or clicks an answer.

RESULTS
The results screen shows:
- overall accuracy
- average reaction time for correct congruent trials
- average reaction time for correct incongruent trials
- Stroop effect = incongruent average RT minus congruent average RT
