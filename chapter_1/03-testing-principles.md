# 1.3. Testing princiles

1. Testing shows the presence, not the absence of defects
- Only show that defects a present, can not prove that there are no defects.
- Even if no defects are found, testing cannot prove test object correctness. 

2. Exhaustive testing is impossible
- Testing everything is not feasible except in trivial cases
- Instead of exhaustive testing: 
    - Using test techniques, test case prioritation and risk-based testing to focus on test efforts

3. Early testing saves time and money
- Remove defect early > reduce subsequence defects > The cost of quality will be reduced since fewer failures will occur later in the SDLC

4. Defects cluster together
- A small numbers of modules usually contains most of the defect

5. Tests wear out
- If the same tests are repeated many times, they become increasingly ineffective in detecting new defects: 
    - Modify old TCs
    - New TCs should be written
    - In some situation, repeated the same TCs have outcome (ex: automated regression testing)6. 

6. Testing is context dependent
- Testing is done differently in different context

7. Absence-of-defects fallacy
- Focus on testing to adapt customer’s need, make customer satisfied, not test all cases and ensure there no bug 
- Testing all the specified requirements and fixing all the defects found could still produce a system that does not fulfill the users’ needs and expectations, that does not help in achieving the customer’s business goals