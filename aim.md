# Objective:

#### The main objective of this experiment is to understand the operation of a ripple carry adder, specifically how the carry ripples through the adder.

  1. Examining the behavior of the working module to understand how the carry ripples through the adder stages
  2. To design a ripple carry adder using full adders to mimic the behavior of the working module
  3. The adder will add two 4 bit numbers

#### Examining behaviour of ripple carry adder for the workng module and the module designed by the student as part of the experiment (refer to the circuit diagram)
#### Loading data in the ripple carry adder (refer to procedure tab for pin numbers)
- each unit of adder will add single bits of the two numbers along with the carry from the previous adder
- load the two input numbers in the adder units as:

      A(A3 A2 A1 A0): A3=1, A2=1, A1=1, A0=1

      B(B3 B2 B1 B0): B3=0, B2=0, B1=0, B0=1

### Examining the rippling of carry behaviour:
  - check output sum:
    
        sum(S3 S2 S1 S0): S3=0, S2=0, S1=0, S0=0

  - check output carry:

        cout=1

- check intermediate carry bit of all the unit adders which will be 1
- probing the carry port can be done by verifying the color of the wire coming out of the port
### Recommended learning activities for the experiment: 
Leaning activities are designed in two stages, a basic stage and an advanced stage. Accomplishment of each stage can be self-evaluated through the given set of quiz questions consisting of multiple type and subjective type questions. In the basic stage, it is recommended to perform the experiment firstly, on the given encapsulated working module, secondly, on the module designed by the student, having gone through the theory, objective and procuder. By performing the experiment on the working module, students can only observe the input-output behavior. Where as, performing experiments on the designed module, students can do circuit analysis, error analysis in addition with the input-output behavior. It is recommended to perform the experiments following the given guideline to check behavior and test plans along with their own circuit analysis. Then students are recommended to move on to the advanced stage. The advanced stage includes the accomplishment of the given assignments which will provide deeper understanding of the topic with innovative circuit design experience. At any time, students can mature their knowledge base by further reading the references provided for the experiment.

- color configuration of wire for 5 valued logic supported by the simulator:
    - if value is UNKNOWN, wire color= maroon
    - if value is TRUE, wire color= blue
    - if value is FALSE, wire color= black
    - if value is HI IMPEDENCE, wire color= green
    - if value is INVALID, wire color= orange
### Test plan:
1. Set one input to zero(0) and check the output.
2. Set one input to all one and another as 0001 in ripple carry adder. Check the output and how the carry ripples.
3. Check the ripple carry adder with input carry with two arbritrary input.

Use Display units for checking output. Try to use minimum number of components to build. The pin configuration of the canned components are shown when mouse hovered over a component.

### Assignment Statements :
1. Create a half adder circuit using only logic gates and test it by giving proper input.
2. Create a full adder circuit using only logic gates and test it by giving proper input.
3. Create a full adder circuit using half adder and test it by giving proper input.
4. Create a 4-bit ripple carry adder circuit using half adders and full adders and test it by giving proper input.