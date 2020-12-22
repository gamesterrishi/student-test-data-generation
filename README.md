# student-test-data-generation
Simulate 100 users &amp; generate data and summary using randomisation &amp; relevant distributions.



**Problem Statement**

Simulate 100 users & generate data using randomisation & relevant distributions:

For each user

User may take, on average, 15 to 20 full syllabus tests

User may take, on average, 3 to 5 chapter tests between two full tests (i.e., user should take ~3-5 chapter-wise tests before going for taking another full syllabus test. These chapter tests are essentially chapters where we found that student is weak in couple of chapters after analysing performance from last full syllabus test that he/she has taken.)

Generate a test summary with the following features: test name (For ex: jee-main-full-syllabus-test-1, jee-main-chapter-test-1, jee-main-full-syllabus-test-2, jee-main-chapter-test-2, etc.) test taken on (timestamp DD-MM-YYYY H:M:S format) total questions in the test total time duration of the test (in minutes) total max marks of the test time spent in the test (in minutes) total attempted total corrects total incorrects marks scored Upper bounds for each of the test type: In chapter-test: total questions: 30 total time duration: 60 minutes total marks of the test: 120 In full syllabus test: total questions: 90 total time duration: 180 minutes total marks of the test: 360 Derive test-on-test score improvement from the 1st test till last test, only on the Valid tests

Criteria for valid test:

at least 25% time spent of the total time duration of the test

at least 25% attempts of total questions in the test

at least 25% marks score of the total max marks in the test

Visualise the above score improvement analysis with relevant charts and/or plots At user level or across all users You can do score improvement analysis at test-on-test (i.e., test sequence level)

Finally, Categorise above simulated 100 users in 3 performance categories with the following criteria: Achiever: Top 5%tile students with highest accuracy Performer: Next 25%tile students with accuracy lower than Achievers Fighter: Rest of all the students with accuracy lower than Performers Visualise score improvement of each of the above performance categories with relevant charts and/or plots You can do score improvement analysis at test-on-test (i.e., test sequence level) for each category of users

