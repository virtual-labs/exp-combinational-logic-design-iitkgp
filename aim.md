# Objective:

#### The main objective of this experiment is to understand the operation of a ripple carry adder, specifically how the carry ripples through the adder.
1.	Examining the behaviour of the working module to understand how the carry ripples through the adder stages
2.	Examining the behaviour of the working module of the carry-lookahead adder
3.	To design a ripple carry adder and carry-lookahead adder using full adders to mimic the behaviour of the working module
4.	The adders will add two 4-bit numbers

#### Loading data in the ripple carry adder (refer to the procedure tab for pin numbers)
- Each unit of the adder will add single bits of the two numbers, along with the carry from the previous adder
- In a carry-look-ahead adder, input numbers will be connected to a carry generator as well as a full adder. The carry generator will feed the carry to full adder units as required.
- load the two input numbers in the adder units as:

      A(A3 A2 A1 A0): A3=1, A2=1, A1=1, A0=1          
      B(B3 B2 B1 B0): B3=0, B2=0, B1=0, B0=1

### Examining the rippling of carry behaviour:
- Check output sum:

      Sum (S3 S2 S1 S0): S3=0, S2=0, S1=0, S0=0
- Check output carry:

      Cout=1
- Check the intermediate carry bit of all the unit adders, which will be 1
- Probing the carry port can be done by verifying the color of the wire coming out of the port

### Recommended learning activities for the experiment:

Learning activities are designed in two stages, a basic stage and an advanced stage. Accomplishment of each stage can be self-evaluated through the given set of quiz questions consisting of multiple-choice and subjective-type questions. In the basic stage, it is recommended to perform the experiment first on the given encapsulated working module, and second on the module designed by the student, having gone through the theory, objective, and procedure. By performing the experiment on the working module, students can only observe the input-output behavior. Whereas, performing experiments on the designed module, students can do circuit analysis, error analysis, in addition to the input-output behaviour. It is recommended to perform the experiments following the given guidelines to check behaviour and test plans along with their own circuit analysis. Then, students are recommended to move on to the advanced stage. The advanced stage includes the accomplishment of the given assignments, which will provide a deeper understanding of the topic with innovative circuit design experience. At any time, students can expand their knowledge base by further reading the references provided for the experiment.

#### The color configuration of bits/pins for 3-valued logic supported by the simulator:
- If value is undefined, wire color = GREY
- If value is TRUE, wire color = GREEN
- If value is FALSE, wire color = RED

### Test plan:
1.	Set one input to zero (0) and check the output.
2.	Set one input to all ones and another to 0001 in a ripple carry adder. Check the output and how the carry ripples.
3.	Check the ripple carry adder with input carry with two arbitrary inputs.
Use Display units for checking output. Try to use the minimum number of components to build. The pin configuration of the canned components is shown when the mouse is hovered over a component.

### Assignment Statements:
1.	Create a half adder circuit using only logic gates and test it by giving proper input.
2.	Create a full adder circuit using only logic gates and test it by giving proper input.
3.	Create a full adder circuit using half adder and test it by giving proper input.
4.	Create a 4-bit ripple carry adder circuit using half adders and full adders and test it by giving proper input.
