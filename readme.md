# Probability Task Data

Release Date: 2024/06/19

Source:

Contributors: Yuqing Kong, Shu Wang, Ying Wang

Contact: Ying Wang, wying2000@pku.edu.cn

Citation: the official paper to cite when using this dataset is 

@inproceedings{xxx,
  author={xxx},
  title={{}},
  booktitle={{}},
  institute = {{}},
  year={}
}

This paper is available from the authors, upon request.

----------

**Dataset Information** 

This dataset consists of human predictions of probability tasks. The data  was collected from subjects recruited from Prolif. The dataset includes parameters of tasks, predictions of subjects, and the reaction time.

We use the standard belief-updating task to elicit the forecast of subjects. There are two boxes, each containing a mix of red and blue balls with a total of 100. The number of red balls in the left box and the right box are *numLeft* and *numRight* respectively. One box is selected randomly according to *mu*(%), the probability of selecting the left box. Then one ball is randomly drawn from the selected box, the color of which is informed to the subjects as a *signal*. After knowing the signal, subjects are required to estimate the probability that the drawn ball comes from the left box.

There are 1458 total tasks (mu, numLeft, numRight, signal) judged by 289 subjects, who produced a total of 17,340 predictions.

Subjects IDs have been anonymized.  

-----------

**Data Format**

taskID  subjectID  prediction   mu     numLeft    numRight  signal  reactionTime
T683r        1        40        60        80        30        red        86
T962r        1        20        90        60        20        red        65
T189b        1        40        10        80        90        blue        47
T387b        1        50        30        80        70        blue        31
T387r        1        70        30        80        70        red        18
...

