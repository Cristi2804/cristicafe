# cristicafe
Backend (AWS Serverless)

Backend-ul aplicației este implementat folosind o arhitectură serverless pe AWS, fără un server tradițional. Logica aplicației este gestionată prin funcții care se execută la cerere.

1.Tehnologii
AWS Lambda (Python)
Amazon API Gateway
Amazon DynamoDB
Amazon SES
Amazon S3
Amazon CloudFront
Amazon CloudWatch

2.Cum funcționează
Utilizatorul trimite un formular (rezervare/contact)
Request-ul ajunge în API Gateway
API Gateway declanșează o funcție Lambda
Funcția:
validează datele
salvează în DynamoDB
trimite email prin SES
Răspunsul este trimis înapoi către frontend

3.Funcționalități backend
procesare rezervări
procesare formular de contact
trimitere emailuri automate
stocare date în cloud
logging și monitorizare

4.Avantaje
fără server de administrat
scalare automată
costuri reduse
disponibilitate ridicată

Notă

Backend-ul nu este inclus în acest repository deoarece este deployat în AWS (cloud).
