# 🔗 Página de Redirecionamento (HTML)

Este projeto contém uma página HTML simples que **redireciona automaticamente para qualquer link que você desejar**.

É útil para:

- colocar links na bio do Instagram
- compartilhar links curtos
- criar páginas intermediárias
- abrir links de aplicativos externos
- gerar QR Codes de acesso rápido

---

# 📄 Como funciona

A página usa **JavaScript para redirecionar automaticamente** quando o usuário entra no site.

Exemplo de funcionamento:

1. Usuário acessa sua página  
2. A página carrega  
3. O navegador tenta abrir o aplicativo  
4. Caso não consiga, abre o link normal no navegador  

Assim, em muitos casos o link **abre fora do navegador interno de aplicativos** como Instagram ou Facebook.

---

# 🧩 Estrutura do projeto

/projeto  
├── index.html  
└── README.md  

---

# ✏️ Como colocar seu próprio link

Dentro do arquivo **index.html** existe uma variável chamada:

appLink

Essa variável define **qual aplicativo será aberto**.

Exemplo usado no projeto:

ifood://restaurant/ID_DO_RESTAURANTE

Para usar com outro aplicativo basta **trocar esse link pelo esquema do app desejado**.

---

# 📱 Exemplos de links para outros aplicativos

### WhatsApp

whatsapp://send?phone=5511999999999

Abre diretamente uma conversa no WhatsApp.

---

### Instagram

instagram://user?username=seuusuario

Abre diretamente o perfil no aplicativo.

---

### YouTube

youtube://www.youtube.com/@seucanal

Abre o canal dentro do app do YouTube.

---

### Telegram

tg://resolve?domain=seucanal

Abre o canal ou usuário no Telegram.

---

### Spotify

spotify:artist:ID_DO_ARTISTA

Abre diretamente o artista no aplicativo.

---

### Google Maps

google.navigation:q=empresa

Abre navegação direta no Google Maps.

---

# ⚠️ Importante

Cada aplicativo possui seu próprio **deep link** (esquema de URL).

Normalmente o formato é:

nome_do_app://

Se o aplicativo estiver instalado no celular, ele abrirá automaticamente.

Caso contrário, o usuário será redirecionado para o link normal configurado.

---

# ☁️ Opções de hospedagem

Você pode hospedar essa página em diversos serviços gratuitos de hospedagem estática, como:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Firebase Hosting
- GitLab Pages

---

# 🚀 Hospedando no GitHub Pages

## 1️⃣ Criar um repositório

No GitHub clique em:

New repository

Escolha um nome para o projeto.

Exemplo:

redirecionamento-link

---

## 2️⃣ Enviar os arquivos

Envie para o repositório:

index.html  
README.md  

---

## 3️⃣ Ativar GitHub Pages

Entre em:

Settings

Depois vá em:

Pages

Configure:

Branch: main  
Folder: /root  

Salve as configurações.

---

## 4️⃣ Acessar seu site

O GitHub criará automaticamente um site no formato:

https://seuusuario.github.io/nome-do-repositorio

Exemplo:

https://usuario.github.io/redirecionamento-link

---

# 📱 Usos comuns

Você pode usar essa página para:

- bio do Instagram
- QR Code
- links curtos
- páginas intermediárias
- redirecionamento para aplicativos
