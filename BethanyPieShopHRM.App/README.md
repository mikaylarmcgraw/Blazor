# PluralSight Course - Blazor: Getting Started

## Different Flavors of Blazor-

### Client-side Blazor: 
Running as web assembly app in the browser locally on the machine.

Benefits: 
	- Runs on all modern browsers
	- No .NET required on server
	- SPA user experience

Cons: 
	- Older browsers might not be supported
	- Initial app download is larger
	- Debugging is still somewhat limited

### Server-side Blazor: 
Application executes on the server in within an ASP.NET core application from the browser we can navigate to see the HTML. All events are sent through SignalR between the browser and server and the changes are made to the doc.

Benefits:
	- Small download
	- Works with all server-side APIs
	- Full debugging support
	- Blazor apps in non-supported browsers
	
Cons:
	- No offline support
	- Network delay
	- Scalability, although not a big problem.
	


