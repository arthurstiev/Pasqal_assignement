# Pasqal_assignement

## Description
A telecommunication company approaches this assignment with a specific scenario. The company has deployed numerous antennas across a geographic area, each utilizing distinct radio frequencies for communication purposes. However, a critical issue arises concerning interference between antennas located in close proximity, sharing the same frequency. Fig. 1 illustrates the interference dilemma where two nearby antennas using identical frequencies interfere with each other, denoted by the dashed circles around them.



To alleviate this interference, assigning a unique frequency to each antenna would be ideal. Unfortunately, due to a limited number of available frequencies, such an assignment isn’t feasible. Consequently, the objective is to minimize interference while assigning the least possible number of distinct frequencies to the antennas.

### Materials

The client provides data on eight antennas distributed with the following (x, y) coordinates:
- Antenna 1: (0, 0)
- Antenna 2: (3, 5.2)
- Antenna 3: (6, 0)
- Antenna 4: (9, -5.2)
- Antenna 5: (9, 0)
- Antenna 6: (9, 5.2)
- Antenna 7: (9, 10.4)
- Antenna 8: (12, 0)

The distances between antennas under 8.7 km will lead to interference.

### Assignment Steps

#### Step 1: Problem Modeling
The assignment tackles the antenna frequency allocation as a graph coloring issue for unit-disk graphs (refer to the 16/10 lecture).

#### Step 2: Algorithm Design
Develop an algorithm utilizing repeated applications of the Maximum Independent Set (MIS) technique (refer to the 16/10 lecture) to solve the graph coloring problem.

#### Step 3: Pulser Implementation
Implement a MIS solver using Pulser (refer to the 23/10 lecture).

#### Step 4: Algorithm Implementation
Execute the graph coloring algorithm in Pulser, employing the MIS solver developed in step 3.

#### Step 5 (Optional): Improvement
Enhance the implementation by incorporating realistic error sources and hardware requirements into the algorithm design (refer to the 30/10 lecture).

#### Step 6: Final Report
Compose a concise report elucidating the work done during this assignment.


## Structure of the Submission
- A jupyter notebook. Simply follow the notebook.
- Usage of markdowns to explain the code.
- A report (pdf file)

## Execution Instructions
- Pulsar package required 

## Contributions
- Arthur Stievenard
- Maxime Outteryck
- Benjamin Yiu

## Contact
- arthur.stievenard@epita.fr
- benjamin.yiu@epita.fr
- maxime.outeryck@epita.fr
