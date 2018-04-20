# Strava Kudos Bot
You want to encourage your friends on their run/bike/swim activity but sometimes, life gets in the way. This is a little bot to go through your friends' activity feed on Strava and give Kudos on every activity.

### Run it like this
    STRAVA_EMAIL=youremail@email.com STRAVA_PASSWORD=yourpassword node kudos.js

### Possible future improvements
* Click into your friend's activity profile and average the mileage for the last 7 days. If the newest activity's mileage is above the average by 10% or more, comment on the activity from a list of random but curated encouraging statements.
* Run this on AWS Lambda every hour or something.

## License
This is free and unencumbered software released into the public domain. See [license](/LICENSE).
