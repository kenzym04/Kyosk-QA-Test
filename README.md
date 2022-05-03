# Kyosk QA Test

## Take Home Test Contents

## Workbook#1: Agile Epics User Stories and Test Cases_V1

- Worksheet#1: Product Backlog
- Worksheet#2: Sprint Planning
- Worksheet#3: Test Cases
- Worksheet#4: API Test Cases

## Workbook#2: Kyosk Test Execution and Bug Report_V1

- Worksheet#1: Test Execution
- Worksheet#2: Bug report

## Edge Case Tests

1. Can the window target value (50,000 daily target) be exceeded?
2. Can the window target value (50,000 daily target) be a negative value?
3. What should the front-end user applications display once the value amount is less than Ksh 0?
4. Can the delivery window limit EXCEEDS the sum of the daily target value?
5. Can the delivery window limit be LESS than the sum of the daily target value?
6. What happens when a delivery window is compromised? e.g. dispatcher resources are hindered by jam, natural calamity etc such that there are no deliveries made on time and there are no or less dispathers available for next window delivery!
7. Can you feed time such that the cutoff time collides with dispatch time or dispatch collides with delivery time? e.g. the last 2 hours of cutoff is the same time for dispatch.
8. What happens when the order window update messages are delayed due to latency/technical ussues?
9. Can there be double order entry when the user places an order at the exact delivery window time limit and the timestamp captured is a second later? 
10. Can I search for an order using a future date range?


