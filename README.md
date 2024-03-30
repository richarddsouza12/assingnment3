# MindTree Assingnment 3
StockMarket Listing Selenium Excell Hasmaps

**Contents**
- Page Object Model Approach
- TestNG , Maven , Maven Surefire Plugin , testng.xml file

**Command**
```
 mvn test     OR
 mvn test -Dsurefire.suiteXmlFiles=testng.xml
```

**Test Case Steps**
- 1 - Read Data Form Stock Market Site with Selenium and Create/Write to new XLSX file.
- 2 - Read the newly created XLS file and populate List<Hashmap> listHashMap1
- 3 - Populate List<Hashmap> listHashMap2 from Selenium WebElements List data
- 4 - Compare both the hashmaps using SoftAsserts