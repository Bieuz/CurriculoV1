# 🚀 Guia Completo de Deploy no GitHub Pages

## 📋 Pré-requisitos

- ✅ Conta no GitHub
- ✅ Git instalado no seu computador
- ✅ Navegador web

## 🎯 Método 1: Upload Direto (Mais Fácil)

### Passo 1: Criar Repositório
1. Acesse [GitHub.com](https://github.com)
2. Clique em **"New repository"**
3. Nome do repositório: `meu-curriculo` (ou outro nome)
4. ✅ Marque **"Public"**
5. ✅ Marque **"Add a README file"**
6. Clique em **"Create repository"**

### Passo 2: Upload dos Arquivos
1. No repositório criado, clique em **"uploading an existing file"**
2. Arraste todos os arquivos da pasta `D:\Curriculo` para o GitHub
3. Ou clique em **"choose your files"** e selecione todos
4. Adicione uma mensagem: `"Adicionando meu currículo"`
5. Clique em **"Commit changes"**

### Passo 3: Ativar GitHub Pages
1. Vá para **Settings** (Configurações) do repositório
2. Role para baixo até **"Pages"**
3. Em **"Source"**, selecione **"Deploy from a branch"**
4. Em **"Branch"**, selecione **"main"**
5. Deixe **"/ (root)"** selecionado
6. Clique em **"Save"**

### Passo 4: Acessar seu Site
- Aguarde 2-5 minutos
- Seu site estará disponível em: `https://seu-usuario.github.io/meu-curriculo`

---

## 💻 Método 2: Via Git (Para Desenvolvedores)

### Passo 1: Preparar o Repositório Local
```bash
# Inicializar Git na pasta do projeto
cd D:\Curriculo
git init

# Adicionar todos os arquivos
git add .

# Primeiro commit
git commit -m "Primeiro commit: adicionando currículo"
```

### Passo 2: Conectar com GitHub
```bash
# Adicionar repositório remoto (substitua SEU-USUARIO e NOME-REPO)
git remote add origin https://github.com/SEU-USUARIO/NOME-REPO.git

# Enviar para GitHub
git branch -M main
git push -u origin main
```

### Passo 3: Ativar GitHub Pages
- Siga os mesmos passos do Método 1, Passo 3

---

## 🔧 Personalização Antes do Deploy

### 1. **Informações Pessoais**
Edite o arquivo `index.html` e substitua:
- `[Seu Nome]` → Seu nome real
- `seuemail@email.com` → Seu email
- Links das redes sociais
- Telefone e localização

### 2. **Foto de Perfil**
- Adicione `perfil.jpg` na pasta `assets/images/`
- Tamanho recomendado: 300x300px

### 3. **Foto da Seção Sobre**
- Adicione `about.jpg` na pasta `assets/images/`
- Tamanho recomendado: 350x400px

### 4. **CV em PDF**
- Adicione `curriculo.pdf` na pasta `assets/`

### 5. **Cores do Site**
No arquivo `styles.css`, linha 8:
```css
--hue-color: 230; /* Mude este número para alterar a cor principal */
```
- **230** = Azul (padrão)
- **142** = Verde
- **340** = Rosa
- **250** = Roxo

---

## 🌐 Configurações de Domínio (Opcional)

### Domínio Personalizado
1. Compre um domínio (ex: seusite.com)
2. No GitHub Pages, adicione o domínio em **"Custom domain"**
3. Configure o DNS no seu provedor:
   ```
   Type: CNAME
   Name: www
   Value: seu-usuario.github.io
   ```

---

## 📱 Testando o Site

### Teste Local (Antes do Deploy)
```bash
# Método 1: Python
python -m http.server 8000

# Método 2: Node.js (se tiver instalado)
npx serve .

# Método 3: Live Server (VS Code)
# Instale a extensão "Live Server" e clique com botão direito no index.html
```

### Teste Pós-Deploy
- ✅ Teste em diferentes dispositivos (celular, tablet, desktop)
- ✅ Verifique todas as seções e links
- ✅ Teste o formulário de contato
- ✅ Verifique se as imagens carregam
- ✅ Teste o download do CV

---

## 🔄 Atualizações Futuras

### Via Interface Web
1. Acesse seu repositório no GitHub
2. Clique no arquivo que deseja editar
3. Clique no ícone de lápis (editar)
4. Faça as mudanças
5. Commit das alterações

### Via Git
```bash
# Fazer mudanças nos arquivos
git add .
git commit -m "Descrição das mudanças"
git push origin main
```

---

## 🚀 Próximos Passos

### Integrações Opcionais:
1. **Google Analytics** - Para acompanhar visitantes
2. **Formspree** - Para formulário de contato funcional
3. **Google Search Console** - Para SEO
4. **Social Media Meta Tags** - Para compartilhamento

### Melhorias:
1. **Certificados SSL** - Automático com GitHub Pages
2. **Performance** - Otimizações de imagem
3. **SEO** - Palavras-chave relevantes
4. **Acessibilidade** - Já implementada no código

---

## 🆘 Solução de Problemas

### Site não carrega?
- Aguarde até 10 minutos após o deploy
- Verifique se o repositório é público
- Confirme que o GitHub Pages está ativado

### Imagens não aparecem?
- Verifique os nomes dos arquivos (case-sensitive)
- Confirme se estão na pasta correta
- Teste os links localmente primeiro

### CSS não funciona?
- Verifique se `styles.css` está na raiz do projeto
- Confirme o link no `index.html`
- Teste localmente primeiro

---

## 📞 Suporte

Se precisar de ajuda:
1. Verifique a documentação do GitHub Pages
2. Consulte os logs de deploy no repositório
3. Teste localmente antes de fazer deploy

**Seu currículo está pronto para impressionar! 🌟**