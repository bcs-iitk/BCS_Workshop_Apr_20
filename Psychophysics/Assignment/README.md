# Assignment 3
In this assignment you have to create a visual search experiment in PsyToolkit and then analyse the response of different subjects. The assignment is fairly simple as most of the part has been done for you. The main idea behind the assignment is to make you guys familiar with psychophysics experiments.

## Creating the experiment
* Use the PsyToolkit template provided in ```visual_search.zip``` to design your experiment.
* Use ```create_stimuli_table.ipynb``` to generate the table for PsyToolkit experiment.
* For all the experiment assigned, only use the type of stimuli from the respective paper and experiment number assigned to you.
* Generate the target and distractors according to the experiment. Note that you have to only use the 'kind' of stimuli from the paper not their specification (for e.g. image size, number of items in display).
* You have to perform the experiment only for the target trials i.e. cases in which there is a target present on the screen.
* Therefore, all the target and distractors should be of size 50px x 50px. You can use ```stimuli.svg``` in inkscape to design it.
* Use ```survey.txt``` to create the PsyToolkit survey.

## For analysis part
* You have to generate the plot for average reaction time vs item size. (for each item size)
* So, there are four cases with item size = (6, 12, 18, 24). You have to find average time for each of them and plot RT vs item size.
* Each item size have 15 different cases.
* Also, report the mean, median, mode and variance for each item size.
* Use ```read_data_helper.ipynb``` to get help on how to read the data from the downloaded data file from PsyToolkit.

**Note:** To download the zip or any other file from github: click on the respective file >> click on download button
