JustEatAutomationTest by Seung Eun Song
================

<h2 id="overview">Overview</h2>
The test is written in Gherkin and implemented in Specflow on .Net. Initially it is created in Visual Studio 2015 Community version and obtained all necessary libraries from Nuget library. 

<h2 id="implementation">Implementation</h2>
 *   All necessary packages will be downloaded when the project is built by referencing package.config. If not, please let me know I can add dlls.
 *   Display "Test Explorer" therefore it's available to run/debug or other implemenation in easy ways. Go to Visual Studio then check Test->Windows->Test Explorer
 *   In order to make sure "RunTool" is configured to use "SpecRun", Check specflow related section in App.config.
	<specFlow>  
	  <plugins>
		  <add name="SpecRun" />
		</plugins>
	</specFlow>
Above configuration should be located in after < /configSections> element.

 *   Click any test run option in Test Explorer will give you the result after implicit build process. 


