# Luah Produção — App de Gestão

## Como publicar (uma vez só)

### Passo 1 — Criar conta no GitHub
1. Acesse **github.com** e crie uma conta gratuita
2. Clique em **"New repository"** (botão verde)
3. Nome: `luah-producao`
4. Deixe **público** e clique **Create repository**

### Passo 2 — Subir os arquivos
1. Na página do repositório criado, clique em **"uploading an existing file"**
2. Arraste os 4 arquivos desta pasta:
   - `index.html`
   - `sw.js`
   - `manifest.json`
   - `netlify.toml`
3. Clique **Commit changes**

### Passo 3 — Conectar ao Netlify
1. Acesse **netlify.com** e crie conta gratuita (pode entrar com o Google)
2. Clique em **"Add new site" → "Import an existing project"**
3. Escolha **GitHub** → autorize → selecione o repositório `luah-producao`
4. Clique **Deploy site**
5. Em segundos aparece seu link! Ex: `https://luah-producao.netlify.app`

### Como atualizar o app no futuro
Quando eu (Claude) enviar um arquivo atualizado:
1. Acesse seu repositório no GitHub
2. Clique no arquivo `index.html`
3. Clique no ícone de lápis (editar)
4. Selecione tudo (Ctrl+A) e cole o novo conteúdo
5. Clique **Commit changes**
6. O Netlify detecta a mudança e publica em ~30 segundos ✅

O link permanece o mesmo para sempre!

### Instalar como app no celular
- **Android:** Abra o link no Chrome → menu ⋮ → "Adicionar à tela inicial"
- **iPhone:** Abra no Safari → botão compartilhar → "Adicionar à tela de início"
