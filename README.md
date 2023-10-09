## Flight Data Analysis using MapReduce

Designed an Oozie workflow for the following:

  1) Three airlines with the highest and lowest probability, respectively, for being on schedule
  2) Three airports with the longest and shortest average taxi time per flight (both in and out), respectively; and
  3) The most common reason for flight cancellations

Inside the current root directory, the following are present:

1) map-reduce/ directory contains job.properties & workflow.xml files

2) map-reduce/lib/ contains the testoozie.jar file

3) src/ directory contains the FlightDataAnalysis.java file that consisting of 3 MapReduce programs that run in fully distributed mode 

4) commands.txt consists of all the commands used to run the project using Hadoop/Oozie workflow

5) output.txt contains the output of Oozie workflow execution

6) Project Report in PDF format with all required documents
