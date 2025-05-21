# 1.1 What is testing 
- Software testing is a set of activities to discover defects and evaluate the quality of software work
products.
- Testing is not only a technical activity. It also needs to be properly planned, managed, estimated,
monitored and controlled.    

## 1.1.1. Test objectives
- Test objectives can vary, depending upon the context, which includes the work product being tested, the
test level, risks, the software development lifecycle (SDLC) being followed, and factors related to the
business context, e.g., corporate structure, competitive considerations, or time to market. 
- Distinguish every test objs into every phrase of testing 
| STT | Objectives                                                                                 | Phase                  |
| --- | ------------------------------------------------------------------------------------------ | ---------------------- |
| 1   | Evaluating work products (requirements, user stories, designs, and code)                   | Review                 |
| 2   | Causing failures and finding defects                                                       | All                    |
| 3   | Ensuring required coverage of a test object                                                | Execution test         |
| 4   | Reducing the level of risk in inadequate software quality                                  | All                    |
| 5   | Verifying whether specified requirements have been fulfilled                               | All                    |
| 6   | Verifying that a test object complies with contractual, legal, and regulatory requirements | All                    |
| 7   | **Providing information** to stakeholders to allow them to make informed decisions         | Smoke test, final test |
| 8   | Building confidence in the quality of the test object                                      | Acceptance testing     |
| 9   | Validating whether the test object is completed and works as expected by the stakeholdeers | Acceptance testing     |

- Distinguish Verify (Verification) vs Validate (Validation)
    - Verify: Compare with he first document( Do it right) - be in charged by product team
    - Validate: Compare with user’s need or expectations (Do right it) - be in charged by customer

## 1.1.2. Testing and Debugging 
- Testing can trigger failures that are caused by defects in the software (dynamic testing) or can directly find defects in the test object (static testing)
- Debugging: finding causes of the failure (defects) which be founded by testing process, analyzing these causes, and eliminating them. Involve: 
    - Reproduction of a failure
    - Diagnosis (finding the root cause)
    - Fixing the cause (remove, repair)
- Subsequent confirmation testing is required to ensure the fixes are resolve the problem (prefer be done by person who performed initial test). 
- Subsequent regression testing can also be performed to ensure the fixes are not causing failures in others parts of the test objects. 
