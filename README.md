<b>Command:</b><br>
<b>Encrypt:</b><br>
$ mvn jasypt:encrypt -Djasypt.encryptor.password=secret_key -Djasypt.plugin.path="file:src/main/resources/external_application.properties"
<br>
<b>Decrypt:</b><br>
$ mvn jasypt:decrypt -Djasypt.encryptor.password=secret_key -Djasypt.plugin.path="file:src/main/resources/external_application.properties"