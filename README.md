# Projeto: ONG Patas e Garras

Este projeto consiste em um sistema simples de gerenciamento de tarefas desenvolvido como parte da disciplina de Introdução à Computação. O objetivo é permitir que usuários adicionem, visualizem e removam tarefas de forma intuitiva, aplicando conceitos básicos de programação e desenvolvimento web.

## Autores e Papéis

- **Vinicius Germano**: Desenvolvimento do frontend (HTML, CSS) e integração visual.
- **Abdnego Souza**: Implementação da lógica em JavaScript e manipulação do DOM.
- **Carlos Pereira**: Documentação, testes e revisão geral do projeto.

## Paleta de Cores e Fontes

Este projeto usa uma paleta suave e acolhedora para reforçar a identidade da ONG e transmitir cuidado e empatia.

### Paleta Real Utilizada
| Função | Valor | Descrição |
|--------|-------|-----------|
| Fundo principal | `#FFDFD2` | Base pêssego clara e quente |
| Texto padrão | `#000000` | Alto contraste e legibilidade |
| Branco utilitário | `#ffffff` | Elementos neutros / contraste interno |
| Acento vermelho | `rgb(196, 41, 2)` | Destaques, títulos e ênfase emocional |
| Roxo de link | `#9e7ff2` | Links e chamadas secundárias |
| Verde doação | `#4CAF50` | Botão Doações (associação a prosperidade) |
| Azul voluntariado | `#2196F3` | Botão Voluntariado (confiança) |
| Coral adoção | `#FF6B6B` | Botão Adoção (afeto / emoção) |
| Verde sucesso secundário | `#BAC990` | Tons suaves / suporte visual |
| Laranja aviso | `rgb(237,104,71)` | Elementos de atenção moderada |

Gradientes de superfícies (aplicados em cartões e blocos):
- `--surface-soft`: `linear-gradient(145deg, rgba(255,223,210,0.65), rgba(255,223,210,0.35))`
- `--surface-alt`: `linear-gradient(145deg, rgba(255,223,210,0.55), rgba(180, 75, 56, 0.18))`

### Fontes
- Fonte principal: `Inter` (Google Fonts) – utilizada em todo o projeto pela boa legibilidade em interfaces.
- Fallback genérico: `sans-serif`.

### Variáveis CSS Definidas
As variáveis ficam no seletor `:root` em `assets/css/style.css`.

| Variável | Uso |
|----------|-----|
| `--primary-bg` | Cor de fundo da página |
| `--text-dark` | Texto padrão e navegação |
| `--text-white` | Texto sobre botões e fundos escuros |
| `--accent-red` | Títulos, destaques e ênfases |
| `--link-purple` | Links com destaque neutro |
| `--surface-soft` | Blocos maiores (sobre / seções) |
| `--surface-alt` | Cartões (galeria / valores) |
| `--donation-color` | Botão de doações |
| `--volunteer-color` | Botão voluntariado |
| `--adoption-color` | Botão adoção |
| `--success-green` | Mensagens suaves de sucesso / apoio visual |
| `--warning-orange` | Indicadores de atenção |

### Decisões de Design
- A paleta prioriza calor humano (pêssegos e corais) + contraste controlado.
- A fonte Inter garante boa renderização multi-plataforma.
- Botões usam cores semânticas para reforçar a ação (verde = doar, azul = contribuir, coral = adotar).
- Gradientes leves evitam blocos planos e criam profundidade sem poluição visual.

## Como abrir o projeto

Basta abrir o arquivo `index.html` em qualquer navegador web.

## Checklist

- [x]  3 páginas mínimas (Home/Sobre/Contato) + links funcionando.
- [x]  `header`, `nav`, `main`, `footer` usados com propósito.
- [x]  Hero na página principal
- [x]  **Tabela** simples presente.
- [x]  Paleta no `:root` (variáveis CSS).
- [x]  Google Fonts.
- [x]  Imagens otimizadas com `alt` descritivo.
- [x]  README com papéis, paleta, fontes e decisões.
- [ ]  Site no ar.
- [ ]  Vídeo de demonstração.
- [ ]  Inclusão de ícones SVG no footer.
- [ ]  Otimização de imagens (WebP).