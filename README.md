# Weather_App_Master

The project works. 
I am not used to web development with ASP.NET Core from scratch so I took a web page as model.
The Project is called WebApplication3
Unfortunately it is too big for y github account, I had to disassemble it and zip the single parts.

•	In order to have it work properly it is needed to download and decompress all the zpped files in the repository, the APIs of BBC and Accu will have to go into src.
•	It is necessary to open the solution properties, check the multiple start projects box and set AebApplication3 and the 2 APIs  to “Start” (see picture “Start Properties”).
•	 In order for the application to work you need to start the 3 projects together. 
•	if you do not set speed or temperature it opens an error message; 
•	if you do not set a location it opens an error message; 
•	If one of the API is down it opens an error message.
•	It works (see picture “Results”, I called my parents, I can confirm that in Rome it is warm) 
•	for the dependency injections please  Check UnityConfig and WeatherAppUnityDependencyResolver
•	I am very tired but happy (see picture “I look Professional”)




-I made some basic unit tests (WeatherAppUnit) I used at the beginning to check the behaviour of the queries to the APIs in case of wrong requests.

!! I do not know the exact reason but the APIs are frequently down. !!


Minor personal notes:
 -I changed computer last week and I spent Tuesday installing Visual Studio Community and .Net Core Tools, I bought this laptop on Ebay.de and I am still getting used to the German keyboard, reliable but very tough to befriend.
 -In total it took about 6 hours. I am usually faster but I usually do not work at night; -I am practically a novice at web development, my professional experience is with industrial machines.

