**Web Automation:** Utilizes Selenium WebDriver to interact with the Erail website, including entering station names and retrieving autocomplete suggestions.

**Page Object Model (POM):** Implements the Page Object Model design pattern to separate web elements and their interactions from the test logic, enhancing code maintainability and readability.

**Excel Integration:** Uses Apache POI to read and write data to an Excel file, facilitating the comparison of actual and expected values.

**Dynamic Waiting:** Replaces hardcoded sleep statements with WebDriverWait to ensure elements are visible before interacting with them, improving test reliability.

**TestNG Framework:** Leverages TestNG for test execution, setup, and teardown, providing a structured and modular approach to testing.

**Project Structure**
src/main/java: Contains the Page Object class (ErailPage) and utility class (ExcelUtils).
src/test/java: Contains the TestNG test class (ErailTest).
src/test/resources: Contains the Excel file (TestData 2.xlsx) used for storing test data.
