# 1.2. Why is testing necessary? 

## 1.2.1. Testing's contributions to success
- Testing detect defect > Defect be removed by Debugging (non-testing activities) > Testing indirectly contributes to higher quality test objects
- Testing evaluate the quality of test objects at various phases in the SDLC > Contributing to decisions to move to the next phase of the SDLC, such as the release decision. 
- Testers have the understanding of user's need and care about it throughout the development lifecycle, instead of require a set of user/customer as a part of development project > Testing provides users with indirect representation on the development project.
- Testing may also be required to meet contractual or legal requirements, or to comply with regulatory
standards. 

## 1.2.2. Testing and Quality Assurance (QA)
- Testing (Quality control):
    - Product-oriented, corrective approach
    - Action: review, run test, design test case
    - Focusing on those activities supporting the achievement of appropriate levels of quality
- Quality assurance
    - Process-oriented, preventive approach
    - Action: Build, follow a good process, training and measurement
    - Focusing on the implementation and improvement of processes
    - QA applies to both the development and testing processes, and is the responsibility of everyone on a project
- Test results are used by both Testing and QA: 
    - Testing: they are used to fix defects
    - QA: provide feedback on how well the development and test processes are performing

## 1.2.3. Errors, Defects, Failures and Root Causes 
- Humans make errors, which produce defects, which in turn may results in failures 
- Errors: Humans wrong actions (mistakes): 
    - Reason:  time pressure, complexity of work products, processes, infrastructure or interactions, or simply because they are tired or lack adequate training
    - Result: produce defects (bugs, faults)
- Defects (= Bugs, Faults):  
    - Reason: Errors/Mistakes of human
    - Can be found in documentation, such as a requirements specification or a test script, in source code, or in a supporting work product such as a build file. 
    - Result: 
        - Defect in code is executed: 
            - Case 1: Some defects will always result in a failure if executed
            - Case 2: Some defects will only result in a failure in specific circumstances
            - Case 3: Some defects may never result in a failure 
- Failure: 
    - Reason: 
        - Caused by Errors, Defects
        - Caused by environmental conditions
- Root causes: 
    - A fundamental reason for the occurrence of a problem 
    - Be identified through root cause analysis, which is typically performed when a failure occurs or a defect is identified
    - Prevent/Reduce similar failures/defects after fixing the root cause
