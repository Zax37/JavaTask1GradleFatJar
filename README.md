# Java w zastosowaniach produkcyjnych

## Zadanie 1 - FatJar

Jest to prosta biblioteka wykorzystująca pojedynczą metodę z org.apache.commons.lang tylko po to,
aby przy pomocy skryptu budującego build.gradle zbudować FatJar, zawierający cały ten pakiet.

Wywołania:

- gradle jar - zbuduje zwykły jar

- gradle fatJar - zbuduje fatJar

- gradle publishToMavenLocal - zbuduje fatJar i wrzuci go do lokalnego repo (.m2)
