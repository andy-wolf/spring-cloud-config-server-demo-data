# spring-cloud-config-server-demo-data

The demo configuration differs by how the database password is encrypted


app1
* unencrypted

app2
* symmetric client-side encryption/decryption
* symmetric key used is "secret"

app3
* symmetric client-side encryption/decryption
* symmetric key used is "secret"

app4
* asymmetric client-side encryption/decryption
* asymmetric public/private key in keystore.jks



Usage Samples
* http://localhost:8888/app5-dev.properties
* http://localhost:8888/app5-dev.yml
* http://localhost:8888/app5-dev.json
* http://localhost:8888/app5/dev
* http://localhost:8888/app6-dev.properties
* http://localhost:8888/app6-dev.yml
* http://localhost:8888/app6-dev.json
* http://localhost:8888/app6/dev


Encrpyted demo data
* dev-password: "{cypher}05d2e95f6e010d9212d90c384b4f82d3f813f48f251e0c476126333237dc75fd"
* prod-password: "{cypher}bab3aba658fbbe33ed11dbe781b3c7290d794d2b10d3cc7f5dd10ea713d0464c"

...when using symmetric encryption key: "ABCDEFGHIJKLMNOPQRSTUVWXYZ"