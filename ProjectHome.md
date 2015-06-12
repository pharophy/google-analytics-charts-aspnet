A lot of people have been looking for an easy way to add Google Analytics data to their projects and display it via the Google Charts API. This project allows you to do just that! Super simple to use! Feel free to reach out to me for any questions!


This is also available as a NuGet package here: https://www.nuget.org/packages/GoogleAnalytics.GoogleCharts.NET/


In order to get yourself up and running, this article should help: http://www.pimcore.org/wiki/display/PIMCORE/Setup+Google+Analytics+Reporting+with+OAuth2+Service+Accounts+(since+1.4.6).

Once you're setup in the Google API console, and you have installed the NuGet package in your project, you'll need to do the following in the web.config / app.config:
> - in the AppKey field, put the google analytics password

> - in the AppName field put the email address

> - in the ProfileId field put the ViewId from Google Analytics > View Settings > ViewId


If you have any questions or suggestions, please reach out!
