# ISTQB Tester Foundation preparation notes
Notes for questions failed during my preparation for the exam.

## Coverage
| Exam | Last questions covered |
| --- | --- |
| A   |  1   |
| B   |     |
| C   |     |
| D   |     |

## Notes

Answers obtained from [1].

### 1.4.1. Test Activities and Tasks
* "Causing failures and identifying defects is a test objective of dynamic testing. 
* User requirements != design requirements (that's why we do validation).

### 1.4.5. Roles in Testing

Test role:
* Configure test environments (isn't creating test environments a task of DevOps? In practice, testers rarely do this).
* Report on achieved coverage.

Test Manager role
* Create test plans.

### 2.1.5. Shift-Left Approach
Examples of the shift-left approach:
* Reviewing requirements before stakeholders formally accept them.
* Writing a component test before the corresponding code is written.
* Executing a performance efficiency test for a component during component testing.

### 2.2.3. Confirmation Testing and Regression Testing
* If the last test result passed and the TC is rerun (this and subsequent times), it is a regression test.
* If the last test result failed and the TC is rerun, it is a confirmation test."

### 4.2.1. Equivalence Partitioning
* Quantitative variables can be partitioned (for instance, whole numbers into negative and positive numbers).
* Qualitative variables cannot be partitioned (each element is already a partition).

### 4.5.3. Acceptance Test-driven Development (ATDD)
* Derives tests from acceptance criteria as part of the system design process (Gärtner 2011).
* Tests are written before the part of the application is developed to satisfy the tests.
* ATDD can only derive tests from functionality explicitly defined in the AC.

### 5.4 Configuration management
In testing, configuration management (CM) provides a discipline for identifying, controlling, and tracking work products such as test plans, test strategies, test conditions, test cases, test scripts, test results, test logs, and test reports as configuration items. For a complex configuration item (e.g., a test environment), CM records the items it consists of, their relationships, and their versions.

## References:
1. International Software Testing Qualifications Board (ISTQB). Sample Exam - Answers, Sample Exam set A. Version 1.4. Certified Tester Syllabus Foundation Level Compatible with Syllabus version 4.0. December 19, 2023. URL: https://istqb-main-web-prod.s3.amazonaws.com/media/documents/ISTQB_CTFL_v4.0_Sample-Exam-A-Answers_v1.4.pdf (last consulted January 11, 2024).
