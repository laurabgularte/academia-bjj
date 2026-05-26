# 🏋️‍♂️ Athlete.UPC - Ultimate Performance Control

O **Athlete.UPC** é um ecossistema de gerenciamento de performance em formato de **SPA (Single Page Application)** nativa e minimalista. Desenvolvido em um único arquivo de tecnologia web puras (HTML5, Tailwind CSS e JavaScript Vanilla), ele foi projetado estrategicamente para atletas híbridos organizarem suas rotinas de preparação física e janelas nutricionais em um painel unificado com visual _cyberpunk/dark mode_.

---

## 🚀 Recursos Principais

- **Arquitetura SPA Nativa:** Navegação instantânea e fluida entre as telas de visão geral, treinos e dieta, gerenciada inteiramente por manipulação de histórico e rotas via JavaScript (sem recarregamento de página).
- **Design de Alta Performance:** Interface responsiva construída com o inovador **Tailwind CSS v4.0**, otimizada para desktops e dispositivos móveis.
- **Simulador de Sincronização Inteligente:** Motor assíncrono integrado que simula o comportamento de um _parser_ de arquivos binários (PDF/TXT), populando dinamicamente a base de dados após o upload.
- **Componentização Dinâmica:** Renderização limpa de cards informativos utilizando _template literals_ e injeção assíncrona de ícones vetoriais modernos via **Lucide Icons**.

---

## 🛠️ Tecnologias Utilizadas

O projeto adota uma abordagem de desenvolvimento limpa e moderna, utilizando distribuição via CDN para máxima portabilidade:

| Tecnologia                    | Função no Projeto                                                                                     |
| :---------------------------- | :---------------------------------------------------------------------------------------------------- |
| **HTML5 Nativo**              | Estruturação semântica do esqueleto da aplicação.                                                     |
| **Tailwind CSS v4.0**         | Estilização avançada com o novo compilador rápido, utilitários utilitários nativos e grid responsivo. |
| **JavaScript Vanilla (ES6+)** | Motor de roteamento, controle de estados de UI e renderização reativa dos componentes.                |
| **Lucide Icons**              | Biblioteca de ícones vetoriais para representação visual das ações e categorias.                      |
| **Google Fonts (Inter)**      | Tipografia limpa, focada em legibilidade de dados de alta densidade.                                  |

---

## 📦 Estrutura do Código

O arquivo está organizado de maneira modular interna para facilitar futuras expansões para frameworks ou back-ends reais:

```text
index.html
├── 📄 Head & Configurações (Meta, Fontes, CDN do Tailwind v4)
├── 🧱 Body (Layout Principal em Grid/Flexbox)
│   ├── 🧭 Sidebar (Navegação SPA e Dropzone de Upload)
│   └── 🖥️ Main Content (Containers das Páginas Ativas/Inativas)
└── ⚙️ Scripts (Lógica da Aplicação)
    ├── 🗄️ Database Mock (Dados estruturados de Treinos e Dieta)
    ├── 🗺️ Gerenciador de Rotas (Manipulador de classes e títulos)
    ├── 🔄 Motor de Sincronização (Simulador de I/O assíncrono)
    └── 🎨 Renderizadores de Componentes (Injeção de HTML dinâmico)
```
