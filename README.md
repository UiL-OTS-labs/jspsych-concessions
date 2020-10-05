# jspsych-concessions
A brief summery on the concessions we have to make in order to work with jspsych.

# Introduction
In the lab we have very good control of the stimuli that we present using ZEP-x.y.
Zep makes it easy to assign a participant to a given group, manually using the
control window. ZEP stores the data into it's database and the user is able
to extract the data to a ".csv" file on the pc on which can be imported in a
spreatsheet program.

However, with jspsych we lose some of the control we used to have in the lab.

Here I'm making a difference in two categories of concessions we have to make.
The ones that are fixable to a extend, we can code something together to work
around problems that are more trivially solved in the lab. In contrast there
are also problems that are really hard wich I think are unsolvable.

# Concessions that are relatively easy to work around
1. Currently we pick groups randomly.
2. It's harder to import .csv files (but this makes it easier in the end)
    - eeg store stimulus parameters in javascript scripts.
2. Storage of data on uilots server is not straightforward.

# Hard Concessions
1. Lack of control on the physical properties of the stimulus.
    - We have no control over how loud the participant sets her audio.
    - We have no prior knowledge on the display resolution and or size
    - etc.
    - A sentence might advance to the next line for participant 1, but not 2.
2. German vs English keyboard layout.
3. Keyboard vs Touchpad (altough it might be easy to ignore mobile devices).
4. It is harder to see whether the participant is making a cup of tea during
   the experiment.
  
