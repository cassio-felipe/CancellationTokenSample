
# CancellationTokenSample

This example shows a practical execution of the cancellation token, using the
Microsoft's standard WeatherForecast .Net controller.

In the Get method request, I injected a cancellation token that controls
when the user submits a new request or refreshes the browser page
before the first end avoiding unnecessary processing of the first and 
forgotten request

#.Net5 