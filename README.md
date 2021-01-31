# mc-forge-tutorials

How to setup VSCodium for Minecraft Forge Mod Development

Steps:
1. Download and install VSCodium
2. Download Forge MDK (e.g. for version 1.16.4) and extract somewhere
3. Copy gradle, gradlew, gradlew.bat, build.gradle to a new separate folder
4. In that folder run .\gradlew.bat genVSCodeRuns (possibly have to turn off firewall / anti virus or run multiple times if some assets cannot be downloaded) (also see MCreator Forums)
5. Run .\gradlew.bat runClient (possibly have to delete C:/Users/.gradle/caches; restart if necessary to delete; retry) -> Minecraft should open up
6. Copy example mod in src/main  from extracted MDK to the other folder
7. Run .\gradlew.bat runClient and check in-game or in console if examplemod is loaded
