# 🌸 Landing Page - Maria Rita Bruder (Fonoaudiologia)

Site institucional e moderno para a Fonoaudióloga **Maria Rita Bruder** (**CRFa 2-10362**), desenvolvido com HTML5, CSS3 puro (cores leves e elegantes) e JavaScript.

---

## 🚀 Como abrir e visualizar o site localmente

Você pode abrir o site de várias maneiras simples no seu computador:

### Opção 1: Abrir direto pelo navegador (Mais Rápido - 1 clique)
1. Vá até a pasta do projeto:
   `Site maria rita bruder`
2. Dê **dois cliques** sobre o arquivo **`index.html`**.
3. O site abrirá imediatamente no seu navegador padrão (Google Chrome, Edge, Opera, etc.).

---

### Opção 2: Usando a extensão Live Server (VS Code / Antigravity IDE)
Se você estiver utilizando um editor de código:
1. Instale a extensão **Live Server** (caso ainda não tenha).
2. Clique com o botão direito sobre o arquivo **`index.html`**.
3. Selecione **"Open with Live Server"**.
4. O site abrirá em `http://127.0.0.1:5500` com atualização automática sempre que você salvar alterações.

---

### Opção 3: Usando terminal (Python ou Node.js)

Se preferir rodar um servidor local leve pelo terminal (PowerShell / Prompt de Comando):

#### Com Python:
Na pasta do projeto, execute:
```bash
python -m http.server 3000
```
E acesse no navegador: `http://localhost:3000`

#### Com Node.js / npx:
```bash
npx serve .
```

---

## ⚙️ Como personalizar o site

### 1. Alterar o número do WhatsApp
No arquivo `index.html`, procure por:
```html
https://wa.me/5500000000000?text=...
```
Substitua `5500000000000` pelo seu número de WhatsApp com código do país (55) + DDD + número (exemplo: `5511999999999`).

### 2. Trocar as fotos de exemplo pelas fotos reais
- **Foto de perfil / Hero**: Procure a tag `<img>` com `id="heroImage"` no `index.html` e troque o atributo `src` pelo caminho da foto da Maria Rita (ex: `assets/img/minha-foto.jpg`).
- **Foto do Consultório**: Procure a tag `<img>` com `id="clinicMainImage"` e altere para a foto real do consultório.

### 3. Inserir a Seção de Especialidades
Conforme solicitado, o espaço entre a seção **Sobre** e **Formação & Experiência** está disponível para inclusão da seção de especialidades que você mesmo desejar criar.
