#OPENSSL - COMMANDS

create CSR: 
openssl req -newkey rsa:2048 -keyout req-certificate.key -out req-certificate.csr

* Remove the password of certificate:
openssl rsa -in req-certificate.key -out req-certificate-wildcard-no-pass.key

* Create certificate .pem
  openssl x509 -in certificate.cer -out certificate.pem

* criando token em base64
  openssl base64 -in fimpzpb4hzq4bnfpl2bnnm4xt3oiln6sp5z5km3gx3njyrqv5xwq