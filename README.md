# Excursion

Landing page da **Excursion**, um app fictício de guia de viagem pessoal que ajuda a descobrir lugares escondidos ao seu redor. O app lembra os lugares de que você gosta e recomenda novos pontos de interesse por perto. A página anuncia que ele está chegando em breve para iPhone e Android.

Este é um projeto pessoal de estudo. Meu objetivo é construir uma base sólida em desenvolvimento e nas ferramentas do dia a dia de quem programa.

## O que a página tem

- Título de destaque e link de download ("Coming soon!")
- Vídeo do app rodando dentro de um celular
- Seção "Your personal travel guide" com texto de apoio e foto de paisagem
- Chamada final para iPhone e Android
- Rodapé

## Tecnologias

- HTML5 semântico (`header`, `main`, `footer`)
- CSS em arquivo externo
- Elementos de mídia: `<video>` e `<img>`

## Estrutura

```
extension/
├── index.html
└── resources/
    ├── css/style.css
    ├── images/        # camp.jpg, phone.png
    └── videos/        # excursion.mp4
```

## O que explorei neste projeto

- **Git**: commits, histórico, branches e controle de mudanças.
- **GitHub**: repositório remoto para versionar e publicar o código.
- **Linha de comando (Bash)**: criar pastas, copiar arquivos, baixar recursos com `curl` e subir um servidor local para testar.
- **HTML e CSS**: replicar um protótipo de design, organizar arquivos e separar estilo de estrutura.

## Como rodar

Abra o `index.html` no navegador. Para testar com um servidor local:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.
