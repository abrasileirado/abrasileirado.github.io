# Abrasileirado Pages (abrasileirado.github.io) 🌐

Este repositório contém o código-fonte do portal público de documentação e apresentação da suíte **Abrasileirado**.

O site é servido estaticamente através do GitHub Pages no endereço:
👉 **[https://abrasileirado.github.io](https://abrasileirado.github.io)**

## Visualização e Desenvolvimento Local

Para rodar o site localmente durante o desenvolvimento:

```bash
# Na pasta deste repositório
cd ~/projetos/PESSOAL/abrasileirado/abrasileirado.github.io

# Inicie um servidor HTTP simples em Python
python3 -m http.server 8000
```

Em seguida, acesse no seu navegador: `http://localhost:8000`

## Estrutura de Arquivos

- `index.html`: Portal principal contendo a lista de repositórios, início rápido e visão geral da arquitetura.
- `logo.png`: logo da organização (cabeçalho, rodapé e favicon).
- `assets/`: tema [dsgovbr-bootstrapped](https://abrasileirado.github.io/dsgovbr-bootstrapped/) (CSS e web components `<dsgovbr-header>`/`<dsgovbr-footer>`), Bootstrap 5 (JS) e fonte Rawline, copiados do site publicado do projeto. Para atualizar o tema, baixe novamente os mesmos arquivos de `https://abrasileirado.github.io/dsgovbr-bootstrapped/assets/`.

## Licenças de terceiros

- **dsgovbr-bootstrapped**: MIT (Abrasileirado).
- **Bootstrap 5**: MIT (`assets/vendor/bootstrap/LICENSE`).
- **Rawline** (fonte do GOV.BR DS): SIL OFL 1.1 (`assets/fonts/rawline/OFL.txt`).
- **Font Awesome 5**: carregado do cdnjs.