# 🚀 Meu Currículo Online

Um site de currículo moderno e responsivo criado com HTML5, CSS3 e JavaScript vanilla, otimizado para GitHub Pages.

## ✨ Características

- 📱 **Totalmente Responsivo** - Funciona perfeitamente em todos os dispositivos
- 🎨 **Design Moderno** - Interface limpa e profissional
- 🌙 **Modo Escuro/Claro** - Alternância entre temas
- ⚡ **Performance Otimizada** - Carregamento rápido
- 🔄 **Animações Suaves** - Transições e efeitos visuais
- 📧 **Formulário de Contato** - Integração fácil com serviços de email
- 🔍 **SEO Amigável** - Otimizado para motores de busca

## 📁 Estrutura do Projeto

```
📦 Curriculo/
├── 📄 index.html          # Página principal
├── 🎨 styles.css          # Estilos CSS
├── 📁 assets/
│   ├── 📁 js/
│   │   └── 📄 main.js     # JavaScript principal
│   ├── 📁 images/         # Imagens do projeto
│   └── 📄 curriculo.pdf   # CV para download
├── 📄 README.md           # Documentação
└── 📄 .gitignore          # Arquivos ignorados pelo Git
```

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos e animações
- **JavaScript** - Interatividade
- **Font Awesome** - Ícones
- **Google Fonts** - Tipografia

## 🚀 Como Usar

### 1. **Personalização**

Edite os seguintes elementos no `index.html`:

- **Informações Pessoais**: Nome, título, descrição
- **Redes Sociais**: Links para LinkedIn, GitHub, etc.
- **Experiência**: Adicione suas experiências profissionais
- **Habilidades**: Atualize as barras de progresso
- **Contato**: Seus dados de contato

### 2. **Imagens**

Adicione suas fotos na pasta `assets/images/`:
- `perfil.jpg` - Foto de perfil (recomendado: 300x300px)
- `about.jpg` - Foto da seção "sobre" (recomendado: 350x400px)

### 3. **CV para Download**

Coloque seu CV em PDF na pasta `assets/` com o nome `curriculo.pdf`

## 📤 Deploy no GitHub Pages

### Método 1: Via Interface Web

1. Faça fork ou clone este repositório
2. Personalize o conteúdo
3. Vá em **Settings** > **Pages**
4. Selecione **Deploy from a branch**
5. Escolha **main** branch
6. Clique em **Save**

### Método 2: Via Git

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/curriculo.git
cd curriculo

# Faça suas modificações
# Adicione e commit as mudanças
git add .
git commit -m "Personalização do currículo"
git push origin main

# Configure GitHub Pages nas configurações do repositório
```

## 🎨 Personalização do Tema

No arquivo `styles.css`, você pode alterar as cores principais:

```css
:root {
    --hue-color: 230; /* Altere este valor para mudar a cor principal */
    /* 230 = Azul, 142 = Verde, 340 = Rosa, 250 = Roxo */
}
```

## 📧 Configuração do Formulário de Contato

Para que o formulário funcione, você pode integrar com:

- **Formspree**: `action="https://formspree.io/f/your-form-id"`
- **Netlify Forms**: Adicione `netlify` ao formulário
- **EmailJS**: Para envio via JavaScript

## 📱 Recursos Móveis

- Menu hambúrguer responsivo
- Navegação por gestos
- Otimizado para touch
- Velocidade de carregamento otimizada

## 🔧 Manutenção

- Mantenha as dependências atualizadas
- Teste regularmente em diferentes dispositivos
- Monitore a performance com Lighthouse
- Atualize o conteúdo regularmente

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🤝 Contribuições

Contribuições são bem-vindas! Por favor, leia as diretrizes de contribuição antes de enviar um pull request.

## 📞 Suporte

Se você tiver alguma dúvida ou precisar de ajuda:

- Abra uma [issue](https://github.com/seu-usuario/curriculo/issues)
- Entre em contato pelo [email](mailto:seuemail@email.com)

---

⭐ **Gostou do projeto? Deixe uma estrela!**

Desenvolvido com ❤️ para ajudar profissionais a criarem currículos online impressionantes.