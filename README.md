# Agro-Elo: Conectando a Terra 🌱

Este projeto foi desenvolvido especialmente para o **Concurso Agrinho 2026**, unindo tecnologia digital e sustentabilidade no campo.

O **Agro-Elo** é um portal multipáginas interativo criado para demonstrar os benefícios práticos da agroecologia e do consórcio de culturas (plantio combinado de espécies) em contrapartida à monocultura tradicional. Ele funciona como uma ferramenta educativa para agricultores, estudantes e entusiastas do ecossistema agrícola.

---

## 🎯 Objetivo do Projeto
O grande objetivo do portal é conscientizar e provar visualmente que a biodiversidade no campo é a chave para a agricultura do futuro. Através de dados, curiosidades, fichas técnicas e um simulador prático, o projeto busca demonstrar como a combinação inteligente de plantas pode:
- Recuperar e adubar o solo naturalmente (fixação de Nitrogênio).
- Criar barreiras biológicas eficientes contra pragas sem o uso de agrotóxicos.
- Otimizar o espaço físico e a retenção de água da chuva.
- Diversificar a fonte de renda da agricultura familiar.

---

## ⚙️ Recursos Técnicos & Funcionalidades
- **Simulador de Ecossistema Interativo:** O coração do projeto. Um painel onde o usuário combina uma Cultura Principal (ex: Milho, Tomate) com uma Planta Companheira (ex: Feijão, Manjericão) e recebe na hora uma análise de compatibilidade ecológica.
- **Painel de Indicadores Biológicos (Dashboard):** Em vez de respostas em texto simples, o simulador renderiza barras de progresso dinâmicas em tempo real que medem percentuais de *Qualidade do Solo*, *Resistência a Pragas* e *Produtividade*.
- **Arquitetura Baseada em Estados:** O sistema simula um portal multipáginas injetando dinamismo com JavaScript puro (SPA - Single Page Application), permitindo uma navegação instantânea e fluida entre as 7 seções sem recarregar a página.
- **Responsividade Total (Mobile-Friendly):** Interface adaptável com menu lateral retrátil (*hamburguer*) pensado para funcionar perfeitamente em celulares e tablets no campo.

---

## 🛠️ Tecnologias Utilizadas
O projeto foi construído utilizando tecnologias web puras e bibliotecas modernas de estilização:
- **HTML5:** Para a estruturação semântica de todas as abas, tabelas comparativas e formulários de seleção.
- **CSS3:** Responsável pelo design moderno, paleta de cores inspirada na natureza (tons de verde desaturados e acentos em laranja) e animações de transição de página (*fade-in*).
- **JavaScript (ES6):** Motor lógico por trás do simulador, atualização dinâmica de emojis das culturas e controle de exibição das abas.
- **Font Awesome (CDN):** Biblioteca de vetores para ícones visuais e intuitivos no menu e nos cards de alerta.

---

## 🎨 Recursos de Interface
- **Sidebar de Contexto:** Painel lateral informativo no simulador que preenche o espaço visual e entrega dicas rápidas sobre rotação de culturas enquanto o usuário joga.
- **Cards Informativos Sólidos:** Caixas coloridas e adaptativas (verdes para sucesso, vermelhas para competição severa/alerta) que mudam de acordo com o resultado da simulação.
- **Direcionamento Dinâmico:** Botões de contexto (como *"Ver Detalhes na Biblioteca"*) inseridos diretamente nos resultados para guiar a experiência de aprendizado do usuário.

---

## 📁 Estrutura de Arquivos
A arquitetura do repositório foi simplificada para garantir máxima velocidade de carregamento e facilidade na hospedagem (ex: GitHub Pages, Vercel ou Netlify):

```bash
agro-elo/
├── index.html     # Arquivo principal que unifica a lógica, estilos e as 7 abas do portal
└── README.md      # Documentação e apresentação oficial do projeto (este arquivo)
