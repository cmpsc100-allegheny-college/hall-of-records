
| Date              |          |
|:------------------|:---------|
| 1 November 2023| Assigned |
| 8 November 2023 | Due      |
| Status            | [![GatorGrader](../../actions/workflows/main.yml/badge.svg)](../../actions/workflows/main.yml) |

# DATA DONE, MAYOR DECREES DECISIVE DEED: CITIZENS TO COMPUTE REPRESENTATIVE RESIDENT CRITERIA

**Reported by `Official Mayor-Endorsed News`**

Maintaining a healthy community is _everyone's job_ and so is neighborhood surveillance! As the Mayor 
described to O.M.E.N. (Offical Mayor Endorsed News), "I, your Mayor, look to you, the great citizens
of `term-world` to help define the ideal citizen contributors. To you, people of this fair city, I (your Mayor) ask for the profile of the most resilient, representative residents!"

As O.M.E.N. has learned, this means trawling through much of the data kept at the newly-restored city `datamart` to uncover the statistics describing the very demonstrative denizens which detail the ideal community member. This data digs deep. Using words that O.M.E.N. was told to say, it covers all of the behaviors that a mindful member of `term-world` must aspire to. "We've been collecting data on you, our citizens, this whole time!" the Mayor reiterated.

Will you, great residents of `term-world` help define the future of this digital world? The Mayor certainly hopes so, saying "[y]our Mayor--of course, that's me--depends on you to compile every last criterion toward identifying the luminaries of our land!" To those who meet the basic benchmarks go all the spoils! Just exactly what those spoils are, the Mayor's Office declines to say.

## Overview

In this set of activities we cover:

* `dictionary` data structures
* a review of `list`s and `iteration` (`for`/`while` loops)
* revisiting `functions`
* exploring more fundamental data science

You'll complete one main task, supported by three sub-tasks:

* An average of all columns of the data (main task), using
  * a `function` that returns rows matching a minimum value in a given column (sub-task)
  * a `function` that totals the numeric values of a given column (sub-task)
  * a report of the average of a given column (sub-task)

As with `datamart`, there are plenty of opportunities for improvements to how you find various statistics about the data. Keep an open mind and a keen eye to the particularly annoying inconveniences of the `Processor` program.

### Learning Outcomes

In this assignment you will learn:
- Using `dictionary` data structure in Python

You will also continue to practice:
- Writing Python functions
- Writing Python code that uses control structures (`while` loops and `if` statements)
- Running Python programs
- Debugging Python programs
- Technical writing in Markdown
- Command line navigation
- Using version control (Git)

These assignment learning outcomes contribute to the following course learning outcomes described in the [course syllabus](https://github.com/cmpsc100-allegheny-college/course_information):

1. Apply Python programming principles to execute and explain computer code that implements interactive, novel solutions to a variety of computable problems.
2. Release code consistent with industry-standard practices using professional grade IDEs, command line tools, and version control tools.
3. Analyze and suggest revisions to existing Python language code to improve or add functionality.

## Completing `hall-of-records` content

The `hall-of-records` has just one file: `Processor.py`. Functionality of the `Processor` has largely been completed for you. The work left up to you is to write the `function`s required to produce the statistical report requested in the `reflection.md`.

This program uses one `global` variable to house the data in the table and the names of columns. Use:

|Variable |Purpose |
|:--------|:-------|
|DATA†     |Holds columns and data from table |

`†` This is a departure from the last assignment; see what conveniences `dictionary`s provide you!

### `main.py`

Leverges the `main` function to:

* Work out options for the Processor's main menu
* Provides _at least_ two `function`s outlined in the `task`/`subtask` breakdown above


|Function name |Parameters  |Return type | Description                                               |
|:-------------|:-----------|:-----------|:----------------------------------------------------------|
|search_rows        |Field to search (`str`), term/number to search (`any`)       |`list`      |Returns _all_ rows which are greater than or equal to a given search criteria |
|total_column       |Field to total (`str`)             |`int`       |Returns the total of all numeric data in a given column |

Your [reflection](office/reflection.md) or [editorial](office/editorial.md) should report the outcomes of these operations.

### Writing

Choose one of the following.

#### Reflection

All of the above tasks completed, finish the reflection located in the `office` folder.

#### Protesting

You may protest completing this assignment by writing an `editorial.md` in the `office` _instead_ of a `reflection.md`. Doing so _does not mean_ not completing the code for this assignment. Rather, it indicates that you should compose an evidence-based argument that uses your analysis to persuade your fellow citizens to your cause.

## Improvement Suggestions

Here are some suggestions for improvements you can, **but are not limited to** use:

|Improvement Suggestions |Description        |
|:--------------------|:------------------|
|Dictionaries         | Add function to edit data |
|Dictionaries         | Add function to find the average of all columns (auto-averager) |    
|Dictionaries         | Dictionaries	Find most common entry in a column                |
|Dictionaries         |	Sort a column (least to greatest, greatest to least)            |
|Dictionaries         | Ability to update multiple cells with a formula                 |
|Dictionaries         |	Add a function to calculate any single other statistical value (median, standard deviation, mode, etc.) |
|Dictionaries         | Write the results of a given operation (average, standard deviation) _as a new column_ |
|Conditional logic    |	Color-code data presentation (uses the `rich` module) |
|Data analytics       | Create a data plot using the `seaborn` module |
|Files, JSON          | Overwrite data (i.e. save the table)          |

**Make sure to link your issue with the pull request you used to make your improvement.**

**If you are not following an improvement suggestion you need to have your improvement suggestion checked by the professor before proceeding.**

## Evaluating `hall of records` Content

This is an individual assignment and each neighbor should submit their own completed assignment. Code should not look similar among any class members. As described in the [course contract](https://github.com/cmpsc100-allegheny-college/course_information/blob/main/CODE_OF_CONDUCT.md) members should not  share code and working solutions but instead should feel welcome to share tips and tricks, help each other in understanding core concepts, and plan, sketch, or otherwise draft general approaches.

To receive a `Complete` status on this assignment, two conditions must be met:
1. The assignment repository on GitHub must have a green check before the deadline;
2. The assignment quiz must be taken and passed with at least 70% during class on November 6th, 2023
  - The quiz will contain 10 short multiple choice questions
  - The quiz can be taken up to three times
  - The quiz is closed book, notes, Internet and must be taken during class time
  - The quiz will assess the recognition of the following topics:
    - list vs. dictionary data structure
    - loops (`while` and `for`)
    - conditionals (`if` statement)
    - functions
    - variables
    - assignment statements
    - expressions

The content for this week is outfitted with a grader program that can be used to evaluate the first condition above for the week. To run the grader for this week's work, you will need to be in the topmost level of the assignment folder. Once there, run the command:

`gatorgrade`

The grader will take a few minutes to do its work, but once it's complete the program will populate your terminal window with a series of checks that gauge the overall "completeness" of some of your required work.

## Backup Policy Reminder

**While we may use this server to store code, you are responsible for using GitHub as your main backup.**

In the event that the `term-world` server goes down for any unforeseen reason, your work may be lost. Though this server is backed up on a regular (i.e. weekly) basis, there is no guarantee that up-to-the-minute data for your work will be restored.

Remember: to err is human; to back up your work is *divine*.
