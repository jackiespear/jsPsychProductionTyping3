# jsPsych Production Effect by Typing 3
A jsPsych recognition experiment examining the production effect by typing.

## Purpose

This experiment is a part of my PhD thesis. Data collected will be compared to performance of an instance-based model of human memory, MINERVA 2.

Participants were asked to study a list of words, some of which they will produce by typing, and some of which they will read silently. The study list consisted of two types of words: concrete words and abstract words. At test, participants will be presented with all of the words they previously studied, along with the same amount of new words that they did not study. Their job will be to indicate that yes, they did previously study a word, or no, they did not. Experiment 3 has 40 study words, and 40 lures at test.

Technical details: When words are produced by typing, the typing is recorded, but not mirrored to the screen. The instruction to "read" or "type" remains on the screen for 3 seconds, and participants cannot advance the trial prematurely by pressing the "enter" key. Moreover, in experiment 3. participants see the instruction to "read" or "type" at the same time as they are presented with the study word. Some modifications had to be made to the jsPsych survey-html-form plugin to accomplish this. All study stimuli are presented for 2 seconds each.

A practice phase has been added to help with typing compliance.

