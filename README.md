# 🔗 Trabalhando com Links em HTML

![Badge HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Badge Estudos](https://img.shields.io/badge/estudos-Links%20e%20Navegação-blue)
![Badge Currículo](https://img.shields.io/badge/inclui-Curr%C3%ADculo%20PDF-green)

## 📚 Sobre o Projeto
Este conjunto de arquivos HTML faz parte dos meus estudos sobre **links e navegação** em páginas web. Aprendi a criar links para sites externos, páginas internas, arquivos para download, links em imagens e links para email!

## 📁 Estrutura do Projeto
```
projeto-links/
│
├── links.html # Página principal sobre links
├── pg1.html # Segunda página (exemplo de navegação interna)
├── Curriculo_Richard_Teixeira.pdf # Currículo para download
│
└── imagens/
└── google.png # Ícone do Google usado no link com imagem
```

## 🎯 O que aprendi

### Tipos de Links Explorados:

| Tipo | Exemplo | Uso |
|------|---------|-----|
| 🔗 **Link externo** | `href="http://google.com/"` | Abre site do Google |
| 📄 **Link interno** | `href="pg1.html"` | Navega entre páginas do projeto |
| 🖼️ **Link em imagem** | `<a href="..."><img src="..."></a>` | Imagem que funciona como link |
| 📎 **Link para arquivo** | `href="Curriculo_Richard_Teixeira.pdf"` | Abre ou baixa PDF |
| 📧 **Link de email** | `href="mailto:richardt4897@gmail.com"` | Abre programa de email |

### Atributos Importantes:
- ✅ **`target="_blank"`** - Abre o link em uma nova aba
- ✅ **`title`** - Texto que aparece ao passar o mouse (tooltip)
- ✅ **`href`** - Caminho do link (destino)

## 🖥️ Exemplos do Código

### 1️⃣ Link Externo (abre em nova aba)
```html
<a href="http://google.com/" target="_blank" title="Site do Google">
    Google
</a>

┌─────────────┐      link para pg1.html      ┌─────────────┐
│  links.html │ ───────────────────────────► │   pg1.html  │
│             │ ◄─────────────────────────── │             │
└─────────────┘      link para links.html    └─────────────┘

##🚀 Como Executar

1-Clone este repositório
2-Mantenha a estrutura de pastas organizada:
3-links.html e pg1.html na raiz
4-Pasta imagens/ com as imagens
5-Currículo PDF na raiz
6-Abra o arquivo links.html no navegador
7-Navegue pelos links e explore as funcionalidades!

## 👨‍💻 Autor
**Richard**

Estudante de Sistemas de Informação apaixonado por tecnologia.

📚 Atualmente: HTML, CSS e Python

🎯 Meta: Primeira oportunidade como desenvolvedor

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TSRichard)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tsrichard/)
