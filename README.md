# QA-Automation-Engineer-Screening-Test
Candidate Info

Name: Md Tarif

Repo Structure
ui-tests/      # Cypress UI automation (TypeScript)
api-tests/     # API automation (Postman/Newman)
perf/          # Performance smoke test (k6)
.github/       # CI workflow (GitHub Actions)
answers.md     # Descriptive Q&A

How to Run
UI Tests (Cypress)
cd ui-tests
npm install
npx cypress run

API Tests (Postman/Newman)
cd api-tests
newman run collection.json -e environment.json

Performance Test (k6)
cd perf
k6 run perf-test.js

CI (GitHub Actions)

Runs automatically on push to main branch.

Notes

UI Site Used: Angular RealWorld Example App

API Site Used: Reqres.in

Tasks completed: UI automation, API tests, performance test, CI setup, and Q&A.
