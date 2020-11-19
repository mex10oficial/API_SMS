# API_SMS
Rest da API de SMS muito simples de integrar!

Para usar nossa api de SMS basta acessar o LINK: https://mex10.docs.apiary.io/ da nossa documentação oficial, mas você pode ver abaixo um guia ultra rápido para integrar!

# Enviado SMS

Basta chamar via HTTP GET a URL abaixo:
https://mex10.com/api/shortcodev2.aspx?token=123456789&t=send&n=11981460808&m=mensagem de teste

# C#

```
using System.Net;

using (WebClient client = new WebClient())
{
    string htmlCode = client.DownloadString("https://mex10.com/api/shortcodev2.aspx?token=123456789&t=send&n=11981460808&m=mensagem de teste");
}
```
# PHP

```
<?php
    echo file_get_contents("https://mex10.com/api/shortcodev2.aspx?token=123456789&t=send&n=11981460808&m=mensagem de teste");
?>
```
# PYTHON

```
import requests
ret = requests.get('https://botmex.ninja/api/trend/', timeout=10).json()
```


# Dúvida e contatos

Todos os paramêtros você consegue dentro do nosso painel!
Para qualquer dúvida por favo contate nosso suporte em https://mex10.com/
