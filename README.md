# ClipStudio - AI Momentos Virais

Um aplicativo web simples para criar clipes virais de vídeos usando inteligência artificial.

## Descrição

O ClipMaker permite que você faça upload de vídeos e utilize IA para identificar e extrair momentos virais automaticamente. O aplicativo usa a API do Gemini para análise de conteúdo e o Cloudinary para processamento de vídeo.

## Funcionalidades

- Upload de vídeos via widget do Cloudinary
- Análise automática de momentos virais usando IA
- Interface moderna e responsiva com Tailwind CSS
- Animações suaves com GSAP
- Ícones do Lucide

## Como Usar

1. Abra o arquivo `index.html` em um navegador web moderno.
2. Insira sua chave da API do Gemini no campo fornecido.
3. Clique em "Começar Upload" para selecionar e fazer upload de um vídeo.
4. Aguarde o processamento e veja o clipe viral gerado.

## Requisitos

- Navegador web moderno com suporte a ES6+
- Chave da API do Gemini (Google AI)
- Conta no Cloudinary para upload de vídeos

## Dependências

O projeto usa as seguintes bibliotecas externas via CDN:

- [Tailwind CSS](https://tailwindcss.com/)
- [GSAP](https://greensock.com/gsap/)
- [Lucide Icons](https://lucide.dev/)
- [Cloudinary Upload Widget](https://cloudinary.com/)

## Configuração

1. Obtenha uma chave da API do Gemini em [Google AI Studio](https://makersuite.google.com/app/apikey).
2. Configure sua conta no Cloudinary e obtenha as credenciais necessárias.
3. Atualize as variáveis no código JavaScript se necessário (cloudName, uploadPreset).

## Estrutura do Projeto

- `index.html` - Arquivo principal contendo HTML e JavaScript
- `style.css` - Arquivo de estilos CSS

## Licença

Este projeto é para fins educacionais e de demonstração.
