# Conar
Fixes SonarQube warnings using Codex!

## Handled Rules
Checkout the prompt templates [here](https://github.com/khaes-kth/CoNar/tree/main/files/prompts). Add more in new PRs :)

## Example
```
gh repo clone khaes-kth/CoNar
gh repo clone didi/sds
cd CoNar
mvn package
java -jar target/sonar-codex-1.0-SNAPSHOT-jar-with-dependencies.jar ../sds/sds-admin/src/main/java/com/didiglobal/sds/admin/util/BloomFileter.java ../BloomFileter.java 28 28 28 2184
```