# Frontend Mentor - QR Code component solution

Esta é a minha solução para o desafio [QR code component do Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Os desafios do Frontend Mentor ajudam desenvolvedores a melhorar suas habilidades de codificação através da construção de projetos realistas.

## Índice

- [Visão Geral](#visão-geral)
  - [O Desafio](#o-desafio)
  - [Links](#links)
- [Meu Processo](#meu-processo)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [O que eu aprendi](#o-que-eu-aprendi)
  - [Desenvolvimento Contínuo](#desenvolvimento-contínuo)
- [Autor](#autor)

## Visão Geral

### O Desafio

Os usuários devem ser capazes de:

- Visualizar o layout centralizado perfeitamente na tela.
- Visualizar o design de forma fluida dependendo do tamanho da tela do dispositivo (responsividade garantida entre Mobile 375px e Desktop 1440px).
- Escanear um QR Code real, personalizado nas cores do projeto, que redireciona diretamente para o meu portfólio.

### Links

- URL da Solução: [Substitua pela URL do seu repositório no GitHub]
- URL do Site ao vivo: [Substitua pela URL do site hospedado no GitHub Pages ou Vercel]

## Meu Processo

### Tecnologias Utilizadas

- HTML5 Semântico
- CSS3 Puro (Cores e tipografia)
- Flexbox (Para o alinhamento central estrutural)
- Media Queries (Adaptação responsiva de medidas e espaçamentos)
- [QR Code Monkey](https://www.qrcode-monkey.com/) (Para a geração do código funcional nas cores exatas do layout)

### O que eu aprendi

Neste projeto, foquei em consolidar meus conhecimentos sobre a estrutura fundamental de componentes web. Utilizei Flexbox para garantir que o cartão se mantivesse no centro da tela e limitei larguras com max-width para criar um comportamento fluido sem quebrar o layout.

Um dos pontos altos do desenvolvimento foi a personalização de detalhes práticos:
1. Geração de um QR Code funcional com as cores em hexadecimal extraídas do design original (#2C7DFA e #FFFFFF), transformando o desafio visual em uma ferramenta real de portfólio.
2. Controle minucioso dos estados de links no rodapé (:hover e :visited), garantindo a preservação da paleta de cores independentemente do histórico de navegação do usuário.

```css
/* Exemplo da manutenção de cor para links já visitados */
.attribution a, 
.attribution a:visited {
    color: hsl(218, 44%, 22%);
    text-decoration: none;    
    transition: 0.3s;         
}