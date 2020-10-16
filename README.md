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