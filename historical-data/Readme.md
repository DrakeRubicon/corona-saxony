# Historical Data
Daily raw Data of Cases, Deaths, and other public available data points from Saxonys Gesundheitsämter.

## Principle

Daily case numbers and deaths of a county will be compared againt the daily numbers made [public by the SMS][1]. Highest Number wins. If Data is corrupt, missing or very late RKI-Data at 0:00 will be logged.

All disparities will be logged as a comment.


[1]:https://www.coronavirus.sachsen.de/infektionsfaelle-in-sachsen-4151.html

### Missing Data

Sometimes a county stops reporting an datapoint. This results in Categories with missing dates.

### Quarantine Numbers

Some counties report their quarantine with active case numbers, some without. How a county reports is identified by the `"quarantine_combined_with_active"` property.
