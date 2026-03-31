# Time de Produto — AUVP Capital

Apresentação institucional interativa do Departamento de Produto da **AUVP Capital**, desenvolvida como um site de página única (single-page) com design premium e dark mode.

---

## 📋 Sobre o Projeto

Este projeto é um **site de apresentação** criado para comunicar, de forma elegante e interativa, quem é o Time de Produto da AUVP Capital: sua missão, seus pilares de atuação, as atividades do dia a dia, as conexões com outras áreas da empresa, a liderança e o processo de trabalho.

O site foi desenvolvido inteiramente com **HTML, CSS e JavaScript puros** — sem dependências externas ou frameworks — e é composto por um único arquivo (`index.html`).

---

## 🎯 Propósito

Apresentar o Departamento de Produto da AUVP Capital de forma clara e visualmente impactante, destacando:

- **Quem somos** — time generalista e multidisciplinar de 9 especialistas, liderado por Beatriz Henriques e com supervisão do sócio Raul Sena.
- **Pilares** — os 6 pilares que sustentam as entregas: Pesquisa & Dados, Design & Experiência, Inovação & Mercado, Backlog & Priorização, Conteúdo & Comunicação, e Colaboração Cross.
- **Atuação** — as 7 atividades do dia a dia, desde Pesquisa com Membros até Monitoramento de Mercado.
- **Conexões** — o Time de Produto como hub central que conecta áreas como Atendimento, Audiovisual, Vendas, Tecnologia, Marketing, Controladoria e Financeiro.
- **Liderança** — perfis de Raul Sena (Sócio Responsável) e Beatriz Henriques (Diretora da Área).
- **Processo** — as 5 fases de trabalho: Descoberta & Pesquisa → Análise & Estratégia → Design & Prototipação → Construção & Colaboração → Lançamento & Evolução.

---

## 🗂️ Estrutura do Projeto

```
timedeproduto/
├── index.html      # Página principal (estrutura, estilos e scripts)
├── logo.svg        # Logotipo da AUVP Capital
├── favicon.png     # Ícone da aba do navegador
└── README.md       # Este arquivo
```

---

## ✨ Funcionalidades e Design

- **Dark mode** com paleta dourada (`#efbe4e`) e tipografia premium (Outfit + Playfair Display via Google Fonts)
- **Navegação fixa** com efeito glassmorphism ao rolar a página
- **Menu mobile** responsivo com animação de hambúrguer
- **Animações de entrada** (fade-up) para elementos ao rolar a página
- **Pilares interativos** com cards expansíveis ao clicar
- **Accordion de atividades** com abertura/fechamento suave
- **Diagrama orbital interativo** exibindo as conexões do time com outras áreas
- **Marquee animado** com os valores do time (Inovação, Dados, Experiência, Estratégia...)
- **Timeline visual** do processo de trabalho em 5 fases
- **Cursor glow** acompanhando o mouse em desktop
- **Grain overlay** sutil para textura de fundo

---

## 🚀 Como Visualizar

Por ser um arquivo HTML estático, basta abrir o `index.html` diretamente no navegador:

```
Duplo clique em index.html
```

Ou, para uma experiência com servidor local (recomendado para evitar restrições de CORS):

```bash
# Com Python
python -m http.server 8000

# Com Node.js (npx)
npx serve .
```

Depois acesse `http://localhost:8000` no navegador.

---

## 🏢 Contexto

**AUVP Capital** é uma empresa de educação e serviços financeiros. O Departamento de Produto reúne a visão estratégica da empresa com as necessidades dos membros, construindo produtos com usuários apaixonados pelas criações da marca.

> *"Orgulhosamente feito sob o sol escaldante de Goiás."*
