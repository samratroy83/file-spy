# File Monitor

### Setup

##### Intellij
1. clone or download the repo
2. import into Intellij as a maven project
3. check yes to import file-spy

    ###### Create Folder/file
    1. create new directory in Users/your-home-/tmp
    2. change Dir to your "home-name" in App
    3. create new csv file (but not in tmp folder)

4. build project
5. run `mvn exec:java -Dexec.mainClass="com.testing.App"` in terminal
6. drag csv file into tmp folder
7. see monitored file in terminal and in intellij

