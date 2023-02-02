# jsPsych-concessions
A brief summery on the concessions we have to make in order to work with jsPsych.

# Introduction
In the lab we have very good control of the stimuli that we present using ZEP-x.y.
Zep makes it easy to assign a participant to a given group manually using the
control window. ZEP stores the data into it's database and the user is able
to extract the data to a ".csv" file on the pc on which can be imported in a
spreatsheet program.

However, with jsPsych we lose some of the control we used to have in the lab.

Here I'm making a difference in two categories of concessions we have to make.
The ones that are fixable to some extent, we can code something together to work
around problems that are more trivially solved in the lab. In contrast there
are also problems that are really hard which I think are unsolvable.

# Concessions for which a work around might exist.
1. Currently we pick groups/lists randomly. Even with the server online it will
   be harder and less controlled than to assign a participant manually to
   a group.
2. It's harder to import .csv files (but this makes it easier in the end)
    - eeg store stimulus parameters in javascript scripts.
3. Storage and retrieval of data on uilots server is not as straightforward.

# Hard Concessions
1. Lack of control on the physical properties of the stimulus.
    - We have no control over how loud the participant sets her audio.
    - We have no prior knowledge on the display resolution and or size nor
      the brightness of the display..
    - A sentence might advance to the next line for participant 1, but not
      for participant 2.
    - etc.
2. German vs English keyboard layout, a response button might appear on a
   different location for another keyboard layout.
3. Keyboard vs touchpad (although it might seem easy to easy to ignore
   mobile devices, many laptops have touchscreens to).
   It would be interesting to see whether there is a reaction time main
   effect of mobile devices versus pc's.
4. It is harder to see whether the participant is making a cup of tea during
   the experiment.
5. Probably few participants have speciallized equipment like EEG or 
   an Eyetracker at home, even if the required jsPscych modules for
   controlling a 

# Disscusion
We lose some control over an experiment by running it online instead of the
lab. Some of the concessions that we have to make are mitigated because its easier
to measure more people online than participants in the lab. Measuring more
people might reduce the noise that exists due to the lack of control.
It depends on how much control you are willing to sacrifice in order to
run an experiment online.
