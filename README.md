GlucoGlance
Your diabetes data. Everywhere you look.
Glucose and insulin information on your phone, watch, car dashboard, desktop, and web browser—without repeatedly opening your CGM or pump app.

GlucoGlance brings readings from supported CGM, pump, follower, and companion apps into a consistent set of displays. Check your glucose from a notification, put insulin information on your watch face, review your history, or share your readings with someone who follows you.

Built by a person living with diabetes, for the everyday moments when checking your numbers should be simple.

Website · Supported sources · Web viewer · Desktop apps
Why GlucoGlance?
Diabetes information often lives in separate apps, with each app deciding where and how you can see it. GlucoGlance brings that information to the screens you already use.
- Less digging: View readings through notifications, home-screen widgets, watch tiles, and watch-face complications.
- More context: See glucose, trend, change, and reading age alongside available insulin information.
- Your choice of source: Use supported official apps, follower services, or companion apps.
- Connected family: Follow another person or share your own readings through a six-digit code.
- Beyond the phone: Extend your display to Android Auto, Windows, Linux Mint, and the web through the GlucoGlance suite.
Features
Android phone
- Glucose displays with trend arrows, delta, timestamps, and configurable glucose thresholds.
- Ongoing notifications for checking readings without opening the app.
- Home-screen widgets ranging from compact glucose displays to a combined dashboard.
- Glucose graphs, Time in Range, metrics, and logbook views.
- Insulin on board, last bolus, and additional insulin information where supported by the selected source.
- Dedicated settings for glucose, insulin, followers, and display preferences.
Wear OS
- Watch tiles for quick access to glucose and insulin information.
- Watch-face complications that keep readings visible alongside the time.
- Glucose, insulin, trend, elapsed-time, and Time in Range displays.
- Graph and combined-data complications, with available types depending on the app version and watch-face slot.
- Follower displays for keeping someone else's readings close at hand.
History and daily context
GlucoGlance combines current readings with history so a single number has context. Graphs, metrics, and logs help you review glucose changes and available insulin records over time.

The information shown depends on your configured source, its permissions, and the data it actually provides. Not every integration supplies every insulin or glucose field.
Supported data sources
GlucoGlance receives data through three main routes: notifications from supported apps, follower services, and companion apps running on the phone.
Source	Connection to GlucoGlance
Eversense 365	Reads supported app notifications
Dexcom G6 / G7	Reads supported app notifications
Omnipod 5	Reads supported notifications for insulin-on-board information
Gluroo	Reads supported app notifications
Dexcom Follow	Retrieves follower readings
FreeStyle Libre 2 / 2+ / 3 / 3+	Retrieves readings through LibreLinkUp
Another GlucoGlance user	Follows a six-digit sharing code
Juggluco	Receives companion-app readings
xDrip+	Receives companion-app data
GlucoDataHandler	Receives companion-app data
AAPS	Receives supported companion-app data


Companion apps extend coverage to additional sensors and services. This is compatibility through those apps, rather than a claim that GlucoGlance connects directly to every sensor.

See the supported-source matrix for sensor-specific routes and links to the companion projects' compatibility documentation.
The GlucoGlance suite
GlucoGlance is the central Android app. The following companion products extend the experience to other devices and use cases; their availability and release schedules can differ.
Product	Platform	Purpose
GlucoGlance	Android and Wear OS	Collects supported readings and provides phone and watch displays
GlucoGlanceAuto	Android Auto	Brings glucose and available insulin information to the car dashboard
GlucoGlanceTwiist	Android and Wear OS	Provides dedicated twiist glucose and pump-status displays for owners and followers
GlucoGlanceWearLite	Wear OS	Follows a sharing code without requiring phone pairing
GlucoGlanceRemote	Web browser	Displays shared glucose and available insulin information without installing an app
GlucoGlanceDesktop	Windows and Linux Mint Cinnamon	Keeps your own or a loved one's readings visible on the desktop


Visit glucoglance.com for current downloads, access requests, and product details.
GlucoGlanceTwiist
The dedicated twiist companion presents available glucose and pump information through notifications, widgets, Quick Settings tiles, Wear OS tiles, and complications. Its documented fields include delivery status, loop status, remaining insulin, pump battery, active insulin, last bolus, carbs, and modifiers.

See the GlucoGlanceTwiist page for setup, current limitations, and features in development.
Sharing and following
Enable remote sharing in GlucoGlance and share your six-digit code with the person who will follow you. That code connects supported follower displays to your shared readings.
- Web: Open GlucoGlanceRemote and enter the code.
- Desktop: Enter the code in the Windows app or Linux Mint Cinnamon applet.
- Standalone watch: Use GlucoGlanceWearLite to follow from a Wear OS watch without phone pairing.
- Another phone: Follow within GlucoGlance.
The web viewer includes glucose, trend, Time in Range, up to 24 hours of history, and available insulin information. It refreshes every minute.

Reading age stays visible. The website documents stale readings being struck through after 20 minutes and cleared after 60 minutes, helping distinguish an old value from a current reading.
Getting started
1. Install GlucoGlance. Use the current installation links on the website.
2. Configure a data source. Ensure your supported CGM, pump, follower, or companion app is supplying readings.
3. Grant the required permissions. Notification-based sources require notification access; other routes have their own setup requirements.
4. Choose your displays. Configure notifications, add home-screen widgets, and select the watch tiles or complications you want to use.
5. Enable sharing if desired. Use your sharing code with the web viewer or compatible companion apps.
For troubleshooting, first check whether the source app has a current reading, then check the reading timestamp in GlucoGlance.
Development and feedback
The Android and Wear OS project is developed in Kotlin using Android Studio.

When reporting a problem, include:
- GlucoGlance version and affected app or companion.
- Phone or watch model and operating-system version.
- Configured data source.
- Steps to reproduce the problem.
- Expected behavior and what happened instead.
- Relevant timestamps, screenshots, or logs, with personal information removed.
Feature availability can differ between production and testing builds. Refer to the website and release-specific documentation when checking whether a feature is included in your version.
Important information
GlucoGlance provides supplementary displays of diabetes information. Continue to use your official CGM and pump apps for treatment decisions. Display freshness depends on the source data and the connections used to deliver it.

Product names and trademarks belong to their respective owners. GlucoGlance is not affiliated with or endorsed by the manufacturers of the supported devices and services. twiist™ is a trademark of Sequel Med Tech, LLC.
