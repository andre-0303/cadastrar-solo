# Cadastro de Solos 🎸

Este projeto é uma pequena aplicação web para **cadastrar solos de guitarra** enviando nome, banda, imagem e áudio.  
Os dados são enviados diretamente para a [API de Solos](https://github.com/andre-0303/api-solos).

## 📄 Sobre o projeto

O objetivo é criar um formulário simples e funcional para testar o funcionamento da API de Solos, permitindo:

- Inserir o nome do solo.
- Informar a banda associada.
- Fazer upload de uma imagem ilustrativa.
- Enviar o arquivo de áudio do solo.

Os dados são enviados via `POST` para o endpoint da API.

## 🖥️ Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (Fetch API)**
- **API Solos** (back-end em Node.js)

## 📋 Como utilizar

1. Clone ou baixe este repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
````
2. Certifique-se que a API de Solos esteja rodando localmente no endereço http://localhost:3001.

3. Abra o arquivo index.html no seu navegador.

4. Preencha os campos do formulário e envie!

5. Você verá uma mensagem de sucesso ou erro abaixo do formulário.

⚙️ Configurações importantes
O formulário envia requisições multipart/form-data.

O endpoint de envio configurado é:
```bash
POST http://localhost:3001/api/solos
```

Se necessário, altere o endereço no JavaScript (fetch) para o seu ambiente.

## 🖌️ Layout
O layout é focado em simplicidade, responsividade e uma experiência de cadastro amigável.
Inputs têm feedback visual e o botão de envio possui interação ao passar o mouse.

## 📢 Observações
- Certifique-se de que os campos obrigatórios (nome, banda, imagem e audio) sejam preenchidos.

- A API precisa estar corretamente configurada para aceitar uploads de arquivos.

Feito por BandeiraDev🧑‍💻🚀
