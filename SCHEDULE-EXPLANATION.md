## New Schedule (Twice Daily)

I've modified the schedule to run twice per day with this cron expression:

```
0 7,19 * * *
```

This semanticaly means: "Run the scraper twice per day at 7:00 AM and 7:00 PM  every day of the week, every month, and every day of the month."

1. `0` - Minute: Execute at minute 0
2. `7,19` - Hour: Execute at hour 9 and 20 (9:00 AM/PM in 24-hour format)
3. `*` - Day of month: Execute on every day of the month
4. `*` - Month: Execute in every month
5. `*` - Day of week: Execute on every day of the week
