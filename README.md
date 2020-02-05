# Business Logic Playground

## Tasks

Vacation tracking:

- company
- has users (employee, leads, admin)
- team (lead, employees)
- has clients (just name and client)
- team member has 30 days off per year
- vacation request
  - creating -> to pending, notification to leads
  - approve -> from pending to approve,  notification to employee, client, create record in calendar
  - reject -> to rejected with comment, notification to employee

- validation  (no strong)
- notification if vacation is started (finished if vacation more than three days) to day off (or didgest) - how to test cron. ??
- statistic (fot employee, team and company)
