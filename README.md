# CTM-POC
CTM POC
1. Open the solution in visual studio 2015.

2. Need to have spec flow plugin instlaled in Visual studio.

3. Need to have selenium plugin installed in Visual studio.

4. NUnit plugin needs to be installed.

5. Open the feature files to run the test cases.

6. If the drivers are not loading correctly need to be installed in to Drivers location

(CTR-RegressionTestSolution\CTR-RegressionTestSolution\drivers).

7. To change the browser to test can be Changed in 
CTR-RegressionTestSolution\CTR-RegressionTestSolution\App.Config file

<?xml version="1.0" encoding="utf-8"?>
<configuration>
  <configSections>
    <section name="specFlow" 

type="TechTalk.SpecFlow.Configuration.ConfigurationSectionHandler, TechTalk.SpecFlow" />
  </configSections>
  <specFlow>
    <!-- For additional details on SpecFlow configuration options see 

http://go.specflow.org/doc-config -->
  </specFlow>
  <appSettings>
    <add key="browser" value="ie" />
    <add key="url" value="https://energy.comparethemarket.com/energy/v2/?AFFCLIE=TSTT" />
  </appSettings>
</configuration>
