Command:
Encrypt:
$ mvn jasypt:encrypt -Djasypt.encryptor.password=secret_key -Djasypt.plugin.path="file:src/main/resources/external_application.properties"
Decrypt:
$ mvn jasypt:decrypt -Djasypt.encryptor.password=secret_key -Djasypt.plugin.path="file:src/main/resources/external_application.properties"