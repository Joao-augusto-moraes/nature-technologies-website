# Nature Technologies (site em HTML, CSS e JavaScript)

Site institucional fictício sobre **tecnologia e engenharia genética na produção de alimentos**, feito como trabalho da disciplina de desenvolvimento web. Tem página inicial com carrossel de imagens e um formulário de cadastro com validação em tempo real.

## 🧱 Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=flat-square)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square)

Sem frameworks: tudo feito na mão.

## ✨ Funcionalidades

- **Carrossel de imagens** feito só com HTML e CSS (botões de rádio controlando os slides)
- **Formulário de cadastro** com nome, e-mail, telefone, cidade, estado e endereço
- **Validação em tempo real** com JavaScript: a mensagem de erro aparece e some enquanto o usuário digita, e o e-mail é conferido com expressão regular
- Layout com cabeçalho, menu de navegação e seções de conteúdo

## ▶️ Como rodar

Os caminhos dos arquivos partem da pasta `TRABALHO WEB`, então o site precisa ser aberto a partir dela por um servidor local:

```bash
cd "TRABALHO WEB"
python -m http.server 8000
```

Depois é só acessar `http://localhost:8000/HTML/INDEX.HTML`.

## 📂 Estrutura

```
TRABALHO WEB/
├── HTML/        # INDEX.HTML (página inicial) e FORM.HTML (cadastro)
├── CSS/         # STYLES.CSS
├── JAVASCRIPT/  # SCRIPT.JS (validação do formulário)
└── Figuras/     # Imagens
```

## 🔭 Próximos passos

- [ ] Usar caminhos relativos para o site abrir direto no navegador e funcionar no GitHub Pages
- [ ] Renomear pastas e arquivos para minúsculas e sem espaços
- [ ] Completar os links do menu
- [ ] Publicar no GitHub Pages
