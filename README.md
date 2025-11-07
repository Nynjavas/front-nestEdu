# Nest Education Frontend

Este é o repositório do frontend do projeto **Nest Education**, uma plataforma acadêmica inteligente, acessível e centrada no estudante.

## 📁 Estrutura do Projeto

```
src/
  assets/         # Imagens e ícones usados no projeto
  lading-page/    # Landing page principal (index.html, styles.css)
  pages/          # Páginas internas da plataforma (calendar, chat, home, onboarding, profile, signin, signup, tasks)
  styles/         # Estilos globais, variáveis e reset
```

## 🚀 Como rodar o projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repo.git
   cd seu-repo
   ```

2. **Abra no VS Code ou outro editor de sua preferência.**

3. **Abra o arquivo desejado no navegador:**
   - Para visualizar a landing page:  
     Abra `src/lading-page/index.html` no seu navegador.
   - Para visualizar outras páginas:  
     Abra o arquivo HTML correspondente em `src/pages/NOME_DA_PAGINA/index.html`.

## 🎨 Tecnologias e Ferramentas

- **HTML5**
- **CSS3** (com uso de variáveis, Flexbox e efeitos modernos)
- **Estrutura modular de pastas**
- **Sem frameworks JS** (projeto focado em HTML/CSS puro)

## ✨ Funcionalidades

- Landing page moderna e responsiva
- Páginas internas separadas por contexto (login, cadastro, chat, tarefas, etc)
- Estilos globais e reset para padronização visual
- Efeitos de hover e gradientes para melhor experiência do usuário

## 🖼️ Imagens e Assets

Todos os assets estão na pasta `src/assets/`.  
Imagens e ícones podem ser reutilizados em qualquer página.

## 📦 Organização dos estilos

- `src/styles/global.css` — Estilos globais para todo o projeto
- `src/styles/reset.css` — Reset de estilos para cross-browser
- `src/styles/variables.css` — Variáveis de cor, fontes e gradientes
- Cada página tem seu próprio `styles.css` para customizações locais

## 📝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch: `git checkout -b feat/sua-feature`
3. Commit suas alterações: `git commit -m 'feat: minha nova feature'`
4. Push para sua branch: `git push origin feat/sua-feature`
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT.

---

Sinta-se à vontade para sugerir melhorias ou reportar problemas!