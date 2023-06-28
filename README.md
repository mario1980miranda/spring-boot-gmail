# spring-boot-gmail

## Test endpoint

```bash
curl -v  localhost:8080/email -d '{"to": "mario.luiz.miranda@gmail.com","subject": "Aviso aos clientes","body": "Prezado cliente,/n/nAcesse agora:/n/nhttps://devsuperior.com.br/n/nAbracos!"}' -H 'Content-type:application/json'
```