# StartAndStopDotNetCoreApp
A way to start and stop your dotnetcore application programmatically, which is perfect for integrated tests

## History
Because of this issue (https://github.com/dotnet/cli/issues/7426), dotnet core apps cannot be very well controlled programatically, which is usually done using System.Diagnostics.Process class. But, there is a way out, specially if you need to spin up dotnetcore apps for integrated tests.

The trick basically consists in publish the app to an specifc directory and run from it, plus some tweaks the Process class. No big deal. It's simple and it works!

Enjoy it!