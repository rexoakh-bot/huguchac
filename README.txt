cavevfx Mod (Fabric, Minecraft 1.21.11) - Version 1.4.0

MENUE OEFFNEN: Taste K (aenderbar in den Minecraft-Steuerungen). K oder ESC schliesst es wieder.

JAR BAUEN - Variante A (ohne Installation, per GitHub):
1. Auf github.com ein neues Repository anlegen.
2. Den INHALT dieses Ordners hochladen (Add file > Upload files), inklusive des versteckten Ordners .github.
3. Im Repository auf "Actions" > "build" warten, bis es gruen ist.
4. Auf den Lauf klicken > unten bei "Artifacts" die Datei "cavevfx-mod" herunterladen.
5. Die .jar (NICHT die mit -sources im Namen) in .minecraft/mods legen. Fabric Loader + Fabric API (1.21.11) noetig.

JAR BAUEN - Variante B (am PC, JDK 21):
gradle wrapper && ./gradlew build  -> build/libs/hugosmp-1.4.0.jar

Versionsnummern in gradle.properties/build.gradle auf https://fabricmc.net/develop fuer 1.21.11 pruefen.
