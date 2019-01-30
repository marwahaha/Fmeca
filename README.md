# Fmeca
This repo is about FMEA/FMECA related projects.
FME(C)A stands for Failure Modes, their Effects (and their Criticality) Analysis,
which is used to prepare maintenance plans and is used in different fields from
manufacturing to medecine. It helps reduce the risks while performing different
tasks and operations.

We are currently trying to apply this method on a miniature production system designed
for learning and educative purposes. The system is called MPS(r) 500-FMS and is located
in MELT (Manufacturing Engineering Laboratory of Tlemcen), Algeria.
MPS 500-FMS is an abreviation of Manufacturing Production System 500 Flexible Manufacturing
Systems. It is developed by FESTO to help train students and specialists in the fields of
Manufacturing, automation, quality assurance...

The system contains 6 mzin stations and a conveyor belt.
The stations are (in order):
*Distribution station
*Production station
*Quality assurance station
*Assembly station
*AS/RS (Automatic storage/Retrieval system)
*Sorting and delivery station
Each one of them has a variety of components:
*PLCs, sensors, effectors... (Industry 4.0 elements)

We want to create a web application that allows to perform diagnostics in case of technical errors.
This application uses data gathered from results of an FMECA, to create a sort of questionnaire (diagnosis).
According to the choices and answers of the lead engineer, the application will suggest corrective maintenance actions (according to the FMECA)

The application will be developed in PHP/MySQL for the backend and Bootstrap for the frontend,
We may use the WebSockets Protocol for real-time operations.
