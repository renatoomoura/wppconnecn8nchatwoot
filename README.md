# WPPConnect 📞

<p align="center">
	<img src="https://github.com/EngajamentoFlow/wppconnect/blob/main/wppconnect-banner.jpeg" alt="Quepasa-logo" width="1000" />

<p align="center">WPPConnect é um projeto de código aberto desenvolvido pela comunidade JavaScript com o objetivo de exportar funções do WhatsApp Web para o nó, que pode ser usado para dar suporte à criação de qualquer interação, como atendimento ao cliente, envio de mídia, reconhecimento de inteligência baseado em frases artificiais e muitas outras coisas, use sua imaginação... 😀🤔💭</p>

</p>
<hr />
<p align="left">
	<img src="https://telegram.org/favicon.ico" alt="Telegram-logo" width="32" />
	<span>Grupo Telegram: </span>
	<a href="https://t.me/wppconnect" target="_blank">Grupo</a>
</p>
<hr />
<p align="left">
	<img src="https://whatsapp.com/favicon.ico" alt="WhatsAPP-logo" width="32" />
	<span>Grupo WhatsaAPP: </span>
	<a href="https://telinkei.com/gp-wppconnect-zap" target="_blank">Grupo</a>
</p>
----------------------------------------------------------------------------
</p>

**Gostou do Tutorial? Faça sua Contribuição**

<img src="https://github.com/EngajamentoFlow/quepasa/blob/main/Contribui%C3%A7%C3%A3o.png" alt="Quepasa-logo" width="200" />
</p>

**PIX CNPJ**

```
45959142000119	
```
----------------------------------------------------------------------------

</p>

**Imaginamos aqui que você ja passou 3 manuais anteriores**

</p>

**Manual Instalação CHATWOOT**

</p>

https://github.com/EngajamentoFlow/chatwoot
</p>
🧰 Instruções:
</p>
✅  Linux VM
</p>
✅  Docker
</p>

*Manual Instalação N8N*

</p>
🧰 Instruções:
</p>
✅  Linux VM
</p>
✅  Docker
</p>
https://github.com/EngajamentoFlow/n8n
</p>

*Manual Instalação WPPCCONNECT*

</p>
https://github.com/EngajamentoFlow/wppconnect
</p>
🧰 Instruções:
</p>
✅  Linux VM
</p>
✅  Docker
</p>


----------------------------------------------------------------------------

**Pronto tudo Funcionando**

----------------------------------------------------------------------------
----------------------------------------------------------------------------

**Versão Docker**

**Manual de Instalação ChatWoot via Docker**

----------------------------------------------------------------------------

</p>
sudo apt update && apt upgrade -y
</p>
git clone https://github.com/wppconnect-team/wppconnect-server
</p>
cd wppconnect-server
</p>
nano wppconnect-server/src/config.json
</p>
secretKeyost
</p>
nano wppconnect-server/src/swagger.json
</p>
Alterar URL
</p>
"url": "http://site/api/{session}",
</p>
docker-compose up -d --build
</p>

----------------------------------------------------------------------------

**Ativando SSL WPPConnect**

</p>
sudo apt install nginx
</p>
sudo rm /etc/nginx/sites-enabled/default
</p>
sudo nano /etc/nginx/sites-available/wppconnect
</p>

```
server {

  server_name wppconnect.dominio.com.br;

  location / {

    proxy_pass http://127.0.0.1:21465;

    proxy_http_version 1.1;

    proxy_set_header Upgrade $http_upgrade;

    proxy_set_header Connection 'upgrade';

    proxy_set_header Host $host;

    proxy_set_header X-Real-IP $remote_addr;

    proxy_set_header X-Forwarded-Proto $scheme;

    proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;

    proxy_cache_bypass $http_upgrade;

  }

   }
```

</p>
sudo ln -s /etc/nginx/sites-available/wppconnect /etc/nginx/sites-enabled
</p>
sudo apt-get install snapd
</p>
sudo snap install notes
</p>
sudo snap install --classic certbot
</p>
sudo certbot --nginx
</p>
sudo service nginx restart
   </p>
</p>
http://site/api-docs

----------------------------------------------------------------------------

**Pronto tudo Funcionando**

----------------------------------------------------------------------------
----------------------------------------------------------------------------

**Gostou do Tutorial? Faça sua Contribuição**

<img src="https://github.com/EngajamentoFlow/quepasa/blob/main/Contribui%C3%A7%C3%A3o.png" alt="Quepasa-logo" width="200" />
</p>


**PIX CNPJ**

```
45959142000119	
```

----------------------------------------------------------------------------
