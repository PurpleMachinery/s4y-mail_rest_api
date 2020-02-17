
## ![](https://lh6.googleusercontent.com/IRif6G_iZMg9rH7f8fEHbin_zKOwoOkxVJzjNxn2_Bw1YPHp3q8mb-eLEPdva04_Y4Bvbm42jS5ezgqxnYEPcR9i3u0c6Q6HqcBRyXBDeUZsanyyHoiWRWvlNS86cTD3DrPD3R-x "linha horizontal")

![](https://lh4.googleusercontent.com/Q2X3dTDcQvUlLcFtEAouM1uh0NrVpQU5_FK4GY6giKrxK_X5ew4cZ0AIWzr4TOgpo-7shxIjk8D86WxlaeXwIdPI8HqMDmNTSq8NKV7YVB_PID--wiBcvVxBkMdTVInBHXhOfAgU)

# Visão Geral

Este documento tem como função auxiliar a instalação e uso do fake mail server.

# Requisitos
- 2 GB de RAM
- npm instalado
- git instalado

# Dados Técnicos
Por meio de tecnologia em base de componentes, hooks (react) e linguagem funcional adaptativa (javascript), esse projeto foi feito para uso em aplicação rest por meio da biblioteca express.

# Instalação
Será necessário para a instalação do produto, clonar seu repositorio no github ([https://github.com/NonADev/s4y-mail_rest_api](https://github.com/NonADev/s4y-mail_rest_api)), e instalar os pacotes via npm, após isso, executar o script de inicialização do projeto.

#### Passo a Passo:
Para clonar o repositório, com um prompt de comando, insira o seguinte comando.

```bash
git clone https://github.com/NonADev/s4y-mail_rest_api
```

Logo em seguida será criado o diretório **s4y-mail_rest_api**, nele estará o projeto parcial referente a envio de emails.
Após isso insira o comando de instalação de dependências.

```bash
npm install
```

Com todas as dependências devidamente instaladas, o projeto está pronto para ser executado:

```bash
npm run dev
```

O programa será inicializado e será executado por padrão no **localhost** porta **3000**, então para acessá lo, basta abrir o browser atualizado, preferencialmente FireFox ou Chrome, e acessar pelo link http://localhost:3000.

# Exemplificação de Uso

Por meio de padrão rest, ele aceita requisições com o protocolo **GET**, e nescessita de dois parametros, email e token. A requisição enviará um e-mail para a caixa de entrada *802609* do site [mailtrap](https://mailtrap.io/inboxes/802609/messages) com o token e para o destinatario introduzido no parametro.
