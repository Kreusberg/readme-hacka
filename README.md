# API COM INTEGRACAO A UMA INTERMEDIADOR DE PAGAMENTO

---

# OBJETIVO
Temos como objetivo fazer o intermédio entre a [Passos Mágicos](https://passosmagicos.org.br) e o Mercado Pago, criando uma facilitadora que gerará um código **PIX**, no qual será *automaticamente direcionada* à conta selecionada, após pago.
---

# O QUE É UM ACCESS TOKEN
Access Token é um código de segurança que identifica o usuário, seus privilégios e uma aplicação. 
br
Tem sua validade determinada pelo parâmetro expires_in e são semelhantes a este códico, por exemplo: 
`APP_USR-1585551492-030918-25######3458-2880736` 

_Sendo compostos por_
- Tipo do Acces Token: APP_USR (usada em produção, em casos reais), TEST (usada durante o desenvolvimento)
- Client ID: 1585551492
- Creation date (MMddHH): 030918
- Security hash: 25######3458
- User ID: 2880736

# COM CRIÁ-LO?
  
1. Acesso o site do [Mercado Pago Developers](https://www.mercadopago.com.br/developers/pt)
![image](https://github.com/Kreusberg/readme-hacka/assets/107767621/78b450a1-e585-41ad-bb4f-3389efafcada)

2. Clique em *Entrar* ou *Criar a sua conta*, então insira as informações, conforme solicitadas.
![image](https://github.com/Kreusberg/readme-hacka/assets/107767621/db55f6a4-0bf2-4495-a6ca-b04aebe419f4)

3. Clique em *Suas integrações*
![image](https://github.com/Kreusberg/readme-hacka/assets/107767621/c6d51f75-164e-4140-ba3c-63a08d0e2a92)

4. Aqui aparecerão todas as suas integrações. Para criar uma nova, selecione "Criar aplicação"
![image](https://github.com/Kreusberg/readme-hacka/assets/107767621/3d92e124-6317-43bc-93de-00bb15f10240)

5. Leia o QR Code
![image](https://github.com/Kreusberg/readme-hacka/assets/107767621/85dfe011-82b0-4dc3-a76f-7df9d8fdcfac)

6. Preencha as informações:
![image](https://github.com/Kreusberg/readme-hacka/assets/107767621/a49174ce-d344-44f7-8d76-4cb73855d21b)
![image](https://github.com/Kreusberg/readme-hacka/assets/107767621/132c513b-ca04-44fd-95cc-d1d17ebbbc08)
**Não se esqueca de prencher o Captcha**
Após feito isso, clique em "Criar aplicação"

7. Por fim, clique em "Credenciais de teste" ou "Credenciais de produção". Alí estarão seus Access Tokens de *teste* e *produção*, respectivamente
![image](https://github.com/Kreusberg/readme-hacka/assets/107767621/73a72dc9-e17a-4a97-bbbe-c46da14ead05)
**Desta forma, você já tem acesso ao seu Access Token (de testes)**
