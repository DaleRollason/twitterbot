# Calorie Snap

A single-page calorie tracker. Take or choose a photo of your meal and Claude estimates
the calories, protein, carbs and fat. You check the estimate, change anything that's off,
and add it to that day's log.

- **Daily target**: uses the Mifflin–St Jeor equation, multiplied by your activity level and
  adjusted for your goal (lose, maintain or gain). You can also type in your own target.
- **Daily sheet**: each meal gets a row with its time, calories and macros, plus a total
  compared with your target. Use ‹ › to go back to earlier days.
- **Last 14 days**: calories eaten each day compared with your target.
- **Export**: download every day as a CSV file (opens in Excel or Google Sheets), or copy it.

It runs as a Claude artifact. Photo estimates use Claude on your own account, and the log is
saved privately to your account, so the same data shows on your phone and your computer.
Opened outside Claude, the log still works but is saved only in that browser, and photo
estimates are turned off.
