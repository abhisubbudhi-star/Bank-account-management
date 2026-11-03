BANK ACCOUNT MANAGEMENT SYSTEM - ECLIPSE IMPORT

Requirements:
- JDK 17
- Eclipse IDE with Maven support
- Internet connection on first Maven build (to download Jackson)

PROJECT PACKAGES:
- com.BankManagementSystem.app
- com.BankManagementSystem.model
- com.BankManagementSystem.service

IMPORT INTO ECLIPSE:
1. Extract BankManagementSystem.zip to a folder.
2. Open Eclipse.
3. Select File > Import.
4. Select Maven > Existing Maven Projects, then click Next.
5. Browse to the extracted BankManagementSystem folder.
6. Ensure pom.xml is selected and click Finish.
7. Wait for Maven to download dependencies.
8. If dependencies do not appear: right-click project > Maven > Update Project.
   Tick "Force Update of Snapshots/Releases", then click OK.
9. Open src/main/java > com.BankManagementSystem.app > Main.java.
10. Right-click Main.java > Run As > Java Application.

IMPORTANT:
- The project uses Java 17 and Jackson Databind 2.17.2.
- The JSON file bankmanagementsystem.json is created automatically in the
  project's working directory when you save or exit.
- Do not create another package with a different spelling/capitalization.
- If Eclipse asks to select a JRE, choose a JDK 17 installation.

GROUP WORK:
1. Subbudi Abhinay - Main application/controller and integration.
2. Gadde Mohith Chandra - Customer, Account, SavingsAccount, CurrentAccount (OOP).
3. Gandikota Naga Akhil - Collections, search and sorting.
4. Thotakura Pavan Chanikya Varma - File I/O and Jackson JSON.
5. Golthi Dhanush Sai - Concurrency and ExecutorService.

NOTE:
This is a complete educational starter implementation. Test with sample accounts
and transactions before submitting. It is not production banking software.
