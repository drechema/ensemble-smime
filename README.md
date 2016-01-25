# ensemble-smime
Sign and verify in SMIME format using InterSystems Ensemble

In some project, I found the need to use SMIME format https://www.ietf.org/rfc/rfc3851.txt, basically is an standard used to wrap a message together with its signature using a certificate (usually X509). Ensemble don't have a single class to do that but inside the Ensemble installation we have the openssl utility, so in this example I use the "openssl smime" command to sign or verify a message.

The example has two Business Process that able to sign or verify and in order to test I made a simple production.

Hope this helps
