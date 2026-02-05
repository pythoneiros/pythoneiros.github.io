# Pythoneiros
Site oficial da comunidade brasileira de Python focada em prática.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)


Website institucional da comunidade **Pythoneiros**, uma comunidade brasileira dedicada ao estudo prático de Python. O site utiliza HTML, CSS e Bootstrap para apresentar recursos, conectar membros e facilitar o acesso aos canais da comunidade.

**Acesse:** [pythoneiros.github.io](https://pythoneiros.github.io/)

## Filosofia: Simplicidade em Primeiro Lugar

Este projeto segue o princípio **KISS** (Keep It Simple, Stupid):

- **HTML puro** — semântico e acessível
- **CSS mínimo** — apenas o necessário
- **Bootstrap** — framework leve para responsividade
- **Sem frameworks JS complexos** — React, Vue, Angular não são necessários aqui
- **Sem build tools** — sem Webpack, Vite ou bundlers
- **Sem dependências desnecessárias** — cada linha tem propósito

**Por quê?** Manter o site simples facilita manutenção, carregamento rápido e colaboração de desenvolvedores de todos os níveis.

## Como Contribuir

Valorizamos contribuições que **mantêm a simplicidade do projeto**. Siga estas etapas:

### 1. Fork e Clone

```bash
# Fork no GitHub e clone seu fork
git clone https://github.com/SEU-USUARIO/pythoneiros.github.io.git
cd pythoneiros.github.io
```

### 2. Faça suas Alterações

Abra diretamente o `index.html` no navegador — sem servidor necessário!

**Diretrizes de Código:**

#### Boas Práticas

- Use HTML5 semântico (`<header>`, `<main>`, `<section>`, `<article>`)
- Mantenha acessibilidade (atributos `alt`, `aria-label`, contraste adequado)
- Valide HTML no [W3C Validator](https://validator.w3.org/)
- Teste em múltiplos navegadores e dispositivos móveis
- Use classes Bootstrap existentes antes de criar CSS customizado
- Variáveis CSS (`:root`) para cores e valores reutilizáveis
- Comente apenas quando necessário — código autoexplicativo é melhor

#### Evite

- Adicionar dependências JS sem discussão prévia
- Criar arquivos de configuração complexos (webpack.config, babel.config, etc)
- Alterar a estrutura de pastas sem motivo claro
- CSS excessivamente específico ou !important desnecessário
- Código duplicado — use reutilização inteligente

### 3. Teste suas Alterações

- **Desktop:** Chrome, Firefox, Safari, Edge
- **Mobile:** Teste responsividade (DevTools ou dispositivo real)
- **Acessibilidade:** Use leitor de tela ou extensão de acessibilidade
- **Performance:** Lighthouse (meta: 90+ em todas as métricas)

### 4. Commit e Pull Request

```bash
git add .
git commit -m "tipo: descrição concisa das mudanças"
git push origin main
```

Abra um Pull Request com:
- **Título claro** descrevendo a mudança
- **Descrição** explicando o "porquê" (não apenas o "o quê")
- **Screenshots** se alterar layout/design
- **Checklist** de testes realizados

### Tipos de Commit

Use prefixos semânticos:

- `feat:` — Nova funcionalidade
- `fix:` — Correção de bug
- `style:` — Mudanças visuais/CSS
- `docs:` — Documentação
- `refactor:` — Refatoração sem mudar comportamento
- `perf:` — Melhoria de performance
- `a11y:` — Melhorias de acessibilidade

## Segurança e Qualidade

Mesmo em sites estáticos, seguimos boas práticas:

- **HTTPS obrigatório** (GitHub Pages fornece automaticamente)
- **Headers de segurança** via GitHub Pages
- **Validação de formulários** (quando aplicável)
- **Links externos** com `target="_blank"` incluem segurança apropriada
- **Assets externos** (CDN) de fontes confiáveis

## Checklist de Revisão

Antes de submeter seu PR, confirme:

- [ ] HTML validado no W3C Validator
- [ ] CSS sem regras não utilizadas
- [ ] Funciona em Chrome, Firefox, Safari, Edge
- [ ] Responsivo em mobile (320px+)
- [ ] Contraste de cores acessível (WCAG AA)
- [ ] Todos os links funcionam
- [ ] Imagens têm `alt` descritivo
- [ ] Sem erros no console do navegador
- [ ] Lighthouse score 90+ (Performance, Acessibilidade, SEO)
- [ ] Código revisado para simplicidade

## Comunidade

Conecte-se conosco:

- **Reddit:** [r/Pythoneiros](https://www.reddit.com/r/Pythoneiros/)
- **GitHub:** [github.com/pythoneiros](https://github.com/pythoneiros/)
- **Facebook:** [Grupo Pythoneiros](https://www.facebook.com/groups/pythoneiros)

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
