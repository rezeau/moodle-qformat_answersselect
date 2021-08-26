# moodle-qformat_answersselect
================

This import format plugin takes a Moodle XML file and import all 
regular multichoice questions changing them into 'Random select answers' questions.
This enables users to export some of their multichoice questions 
using the normal Moodle XML export format
and import them back with this format.
The additionnal benefit of this process is that they now have 2 copies of each question, one
using the regular grading scheme and one using the 'Random select answers' grading scheme.

This plugin should go into the question/format/answersselect Moodle installation
directory. Login as admin to complete plugin installation.  Then select
this format *Random select answers format* during question bank import.

This work is based on the crossxml qformat plugin made by Daniel Thies 2018 dethies@gmail.com and
licensed under the included GPL 3 
