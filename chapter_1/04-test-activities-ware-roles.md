# 1.4. Test activities, test ware and test roles

## 1.4.1. Test activities and tasks
- Test progress contains: 
    - Test planning: defined test objects > select an approach that best achieves the objectives
    - Test monitoring an Test control: 
        - Ongoing checking of all test activities 
        - Compare actual progress against plan > taking the necessary actions to meet test objectives 
    - Test analysis: 
        - Analyzing the test basis to identify testable features
        - Answer the question: What to test?
        - Define + prioritize the associated test conditions + risks
        - Evaluate test basis and test objs to identify defects > access test ability 
        - Using test techniques to analize 
    - Test design: 
        - Answer the question: How to test?
        - Elaborating the test conditions into test cases and other testware                         
        - Identifying test data requirement and test environment, tools, infrastructure     
    - Test implementation: 
        - Creating or acquiring the testware necessary for test execution
        - Prepare: test cases, test data, test env, .....
        - Organized TCs into test procedures > prioritize + arrange test procedures within a test execution schedule for efficient test execution
    - Test execution:
        - Running the tests in accordance with the test execution schedule (manual or automation)
        - Compare actual vs expected results, log test results      
        - Anomalies are analyzed to identify their likely causes.
    - Test completion: 
        - Occurring at project milestones (releases/end of iteration/test level completion)
        - Create change request or backlog items for unresolved defects 
        - Collect and hand over testware to the appropriate teams 
        - The test environment is shut down to an agreed state
        - Analyzing lessons learned and improve test process
        - Create and communicate test completion report to stakeholders

## 1.4.2. Test process in context
- Test activities are an integral part of the development process.
- The way testing (test process) is carried out will depend on a number of contextual factors:
    - Stakeholders (Other teams that related in the development of project): Needs, Epectations, Requirements, Willingness to cooperate, etc, .....
    - Team member (skills, experiences, quantity, roles, ….. of members in test team)
    - Business domain: criticality of the test object, identified risks, market needs, specific legal regulations, etc.
    - Technical factors: framework, structure design, type of software, etc.
    - Project constraint: scope, time, budget, resources, etc.
    - Organizational factors: organizational structure, existing policies, practices used, etc.
    - Software development lifecycle: engineering practices, development methods, etc.
    - Tools: availability, usability, compliance, etc.
- All of these fators will have impact on: test strategy, test techniques used, degree of test automation, required level of coverage, level of detail of testware, test reporting

## 1.4.3. Test ware
- Testware is created as output work products from the test activities
- Follow bellow table: 
| Test Activities                      | Task                                                                                               | Testware                                                         |
| ------------------------------------ | -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| **Test Planning**                    | Create and update a test plan: scope, objectives, approach, schedule, define entry & exit criteria | test plan, test schedule, risk register, entry and exit criteria |
| **Test Monitoring**                  | Compare actual with plan                                                                           | test progress reports                                            |
|                                      | Measurement: progress, quality,…                                                                   | risk information                                                 |
|                                      | Create a test report                                                                               |                                                                  |
| **Test Control**                     | Make decisions (corrective actions)                                                                | documentation of control directives                              |
|                                      | Check test log                                                                                     |                                                                  |
|                                      | Evaluate exit criteria for test execution                                                          |                                                                  |
| **Test Analysis**<br>(What to test?) | Analyzing/Evaluation (review and make QnA) the test basis to identify testable features            | test conditions (e.g., acceptance criteria)                      |
|                                      | Define and prioritize associated test conditions (list of features to be tested)                   | defects in the test basis                                        |
|                                      | Identify the related risks and risk levels                                                         | test charters                                                    |
| **Test Design**<br>(How to test?)    | Elaborating the test conditions into test cases and other testware                                 | test cases, test charters, coverage items                        |
|                                      | Identifying test data requirement and test environment, tools, infrastructure                      | test data requirements, test environment requirements            |
| **Test Implementation**              | Creating or acquiring the testware necessary for test execution (test scripts, test procedures, test suites)                             | Test suites, test data, test execution schedule, test env element|
|                                      | building or verify the test envs                                                                   |                                                                  |
| **Test Execution**                   | Run test manual or automation                                                                      | Test results                                                     |
|                                      | Compare actual vs expected results, log test results                                               | Test logs                                                        | 
|                                      | Anayzing anomalies (discrepancies)                                                                 | Defect reports                                                   |
|                                      | Reporting defects                                                                                  |                                                                  |                                            
| **Test Completion**                  | Activities usually occur at project milestones                                                     | Test completion report                                           |
|                                      | Create Change Request for unresolved defects                                                       | Action items for improvement                                     |
|                                      | Collect and hand over testware to the appropriate teams                                            | Documented lesson learned                                        | 
|                                      | Analyzing lessons learned and improve test process                                                 | Change requests                                                  | 

## 1.4.4. Traceability between the Test Basis and Testware 
- Establish and maintain traceability throughout the test process between the test basis elements, testware associated with these elements (e.g., test conditions, risks, test cases), test results, and defects > Implement effective test monitoring and control
- Accurate traceability supports coverage evaluation > it is very useful if measurable coverage criteria are defined in the test basis: 
    - Traceability of TCs to requirements can verify that the requirements are covered by test case
    - Traceability of test results to risks can be used to evaluate the level of residual risk in a test object
- Determine the impact of changes
    - Evaluate the scope of regression test (will be focused on Chapter 2)
- Facilitates test audits
- Help meet IT governance criteria
- Makes test progress reports and test completion reports more easily understandable by including the status of test basis elements

## 1.4.5. Roles in Testing 
- Tester: take overall responsibility for the engineering  (technical) aspect of testing.
    - Focus on activities: test analysis (analyze test basis, test condition) , test design (test data, env, tool, platform), test implementation (test data, test account, build env ……) , test execution
- Test manager (Test lead): take over responsibility for the test process, test team and the leadership (do test activities on the start) of the test activities
    - Focus on activities: test planning, test monitoring and control, test completion
    - Carried out varies depending on the context
