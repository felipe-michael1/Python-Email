# 📧 PythonEmail

Classe em **Python** para **envio de e-mails**, simples, reutilizável e fácil de integrar em qualquer projeto Python.

Compatível com os principais provedores de e-mail:

* **Outlook**
* **Gmail**

---

## 🚀 Objetivo do Projeto

Este projeto tem como objetivo fornecer uma **classe genérica para envio de e-mails**, facilitando:

* Automação de notificações
* Envio de relatórios
* Alertas de sistemas
* Integração com aplicações Python

---

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **SMTP / POP / IMAP**
* **SSL / TLS**
* **OAuth2 (quando exigido pelo provedor)**

---

## 📬 Provedores Suportados

### ✔ Outlook

### ✔ Gmail

---

## ⚙️ Configuração de E-mail – Outlook

Se você deseja adicionar sua conta **Outlook.com** a um aplicativo que utilize **POP ou IMAP**, utilize as configurações abaixo.

### ⚠️ Observações Importantes

* POP e IMAP são **desabilitados por padrão**
* Outlook exige **OAuth2 / Modern Authentication**
* Autenticação básica está sendo descontinuada
* Servidores de entrada e saída são os mesmos

### 🔑 Credenciais

* **Usuário:** seu endereço de e-mail
* **Senha:** senha da conta Microsoft

  > Em alguns casos, pode ser necessário gerar uma **senha de aplicativo**

---

### 📥 IMAP (Outlook)

* Servidor: `outlook.office365.com`
* Porta: `993`
* Criptografia: `SSL/TLS`
* Autenticação: `OAuth2 / Modern Auth`

---

### 📥 POP (Outlook)

* Servidor: `outlook.office365.com`
* Porta: `995`
* Criptografia: `SSL/TLS`
* Autenticação: `OAuth2 / Modern Auth`

---

### 📤 SMTP (Outlook)

* Servidor: `smtp-mail.outlook.com`
* Porta: `587`
* Criptografia: `STARTTLS`
* Autenticação: `OAuth2 / Modern Auth`

---

## ⚙️ Configuração de E-mail – Gmail

### 🔧 Habilitar POP no Gmail

1. Abra o Gmail no navegador
2. Clique em **Configurações**
3. Vá em **Ver todas as configurações**
4. Acesse a aba **Encaminhamento e POP/IMAP**
5. Ative o **POP**
6. Salve as alterações

---

### 📥 POP (Gmail)

* Servidor: `pop.gmail.com`
* Porta: `995`
* Criptografia: `SSL`
* Autenticação: Sim

---

### 📤 SMTP (Gmail)

* Servidor: `smtp.gmail.com`
* Porta: `587`
* Criptografia: `TLS / STARTTLS`
* Autenticação: Sim

---

### 📥 IMAP (Gmail)

* Servidor: `imap.gmail.com`
* Porta: `993`
* Criptografia: `SSL/TLS`

---

## 🧠 O que este projeto demonstra

* Conhecimento em protocolos de e-mail
* Integração com SMTP, POP e IMAP
* Uso correto de SSL/TLS
* Código reutilizável
* Boa documentação técnica
* Pronto para uso em projetos reais

---

## 🚀 Possíveis Melhorias Futuras

* Suporte a anexos
* Templates HTML
* Logs de envio
* Tratamento avançado de erros
* Integração com filas (Celery / RabbitMQ)

---

## 👤 Autor

Felipe

Projeto desenvolvido para fins **educacionais e de portfólio**, com foco em **automação, integração e boas práticas em Python**.
