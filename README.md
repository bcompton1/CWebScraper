# CWebScraper
This is a simple web scraping project implemented in C# using the HtmlAgilityPack library. The project extracts weather information from the website weather.com and displays the temperature, current conditions, and location.

How it Works
The program sends a GET request to the weather.com website to retrieve the HTML content of the specified URL.

The HTML content is then loaded into an HtmlDocument object using the HtmlAgilityPack library, which provides an easy way to parse and manipulate HTML documents.

Temperature, conditions, and location information are extracted from the HTML using XPath queries:

Temperature: The temperature is obtained by selecting the HTML element with the class 'CurrentConditions--tempValue--MHmYY'.
Conditions: The current weather conditions are obtained by selecting the HTML element with the class 'CurrentConditions--phraseValue--mZC_p'.
Location: The location is extracted from the HTML using the 'CurrentConditions--location--1YWj_' class.
The extracted information is then displayed in the console.

Prerequisites
Before running the program, make sure you have the following:

Visual Studio or any C# development environment.
The HtmlAgilityPack library is used for parsing HTML. You can install it via NuGet Package Manager.
Usage
Clone this repository or download the source code.

Open the project in your C# development environment.

Build and run the program.

The program will send a request to weather.com, extract weather information, and display it in the console.
