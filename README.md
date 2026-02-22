## 📖 Sobre

Este projeto utiliza apenas tecnologias web básicas, sem frameworks ou bibliotecas externas, garantindo **simplicidade**, **leveza** e **compatibilidade** com qualquer navegador moderno.

Tecnologias utilizadas:
- **HTML**
- **CSS**

## 📁 Estrutura do projeto

├── main.html<br>
├── style.css<br>
└── PROJETOR-1.png<br>
└── PROJETOR-2.png<br>

## 📤 Uso dos arquivos

Faça o upload do arquivo **`style.css`** e imagens no mesmno diretorio que rodar o codigo html do arquivo **`main.html`**.

Caso os arquivos **não estejam no mesmo diretório**, é necessário ajustar corretamente os caminhos dentro do código `main.html`.

Você pode alterar os nomes dos caminhos como preferir, por padrão utilizei **.projetor-1** e **.projetor-2** como estilo para criar o efeito, caso queira usar na sua matriz, é possivel renomear sem conflitos.

<br>
Exemplo de uso:

```html
<head>
<link rel="stylesheet" href="/style.css">   
</head>
<body>
<img src="/PROJETOR-1.png" class="projetor-1" alt="">
<img src="/PROJETOR-2.png" class="projetor-2" alt="">
</body>
</html>

