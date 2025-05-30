# Weavera Lab - Site Institucional

Este repositório contém o site institucional da Weavera Lab e do produto Wavera Coder, desenvolvido com HTML, CSS e JavaScript puro.

## Visão Geral

O site da Weavera Lab apresenta a empresa e seu principal produto, o Wavera Coder - uma plataforma no-code baseada em inteligência artificial que permite transformar descrições em linguagem natural (prompts) em aplicações web funcionais.

## Estrutura do Projeto

```
weavera-site-html/
├── css/
│   └── styles.css       # Estilos globais do site
├── js/
│   └── main.js          # JavaScript para interatividade
├── images/              # Diretório para imagens (vazio, adicione suas imagens)
├── index.html           # Página inicial
├── about.html           # Sobre a empresa
├── product.html         # Página do produto Wavera Coder
├── how-it-works.html    # Como funciona o Wavera Coder
├── use-cases.html       # Casos de uso
├── pricing.html         # Planos e preços
├── contact.html         # Página de contato
├── blog.html            # Blog da empresa
├── faq.html             # Perguntas frequentes
└── README.md            # Este arquivo
```

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica para melhor acessibilidade e SEO
- **CSS3**: Design responsivo com flexbox e grid
- **JavaScript**: Interatividade e animações
- **Font Awesome**: Ícones utilizados no site
- **Google Fonts**: Tipografia (importada via CSS)

## Como Usar

### Visualização Local

1. Faça o download ou clone este repositório
2. Extraia os arquivos (se baixou como ZIP)
3. Abra o arquivo `index.html` em qualquer navegador web moderno

Não é necessário servidor web para visualizar o site localmente, pois ele é completamente estático.

### Hospedagem

Para hospedar o site em produção:

1. Faça upload de todos os arquivos e diretórios para seu servidor web
2. Certifique-se de manter a estrutura de diretórios intacta
3. O site funcionará em qualquer servidor web padrão (Apache, Nginx, etc.)

## Personalização

### Alterando Cores e Estilos

As cores principais e estilos estão definidos como variáveis CSS no início do arquivo `css/styles.css`:

```css
:root {
  /* Cores principais */
  --weavera-blue: #2563eb;
  --wavera-teal: #0ea5e9;
  --purple-innovation: #8b5cf6;
  --dark-blue: #1e40af;
  --light-blue: #bfdbfe;

  /* Cores neutras */
  --dark-gray: #1f2937;
  --medium-gray: #4b5563;
  --light-gray: #f3f4f6;

  /* Gradientes */
  --main-gradient: linear-gradient(
    135deg,
    var(--weavera-blue),
    var(--purple-innovation)
  );

  /* Outros */
  --border-radius-sm: 4px;
  --border-radius-md: 8px;
  --border-radius-lg: 12px;
  --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
```

Modifique estas variáveis para alterar o esquema de cores em todo o site.

### Adicionando Imagens

1. Coloque suas imagens no diretório `images/`
2. Substitua os placeholders de imagem no HTML por referências às suas imagens:

```html
<!-- Substitua isto: -->
<div
  style="background-color: var(--light-gray); height: 350px; border-radius: var(--border-radius-lg); display: flex; align-items: center; justify-content: center;"
>
  <span>Imagem: Exemplo</span>
</div>

<!-- Por isto: -->
<img src="images/sua-imagem.jpg" alt="Descrição da imagem" class="img-fluid" />
```

### Adicionando Novas Páginas

Para adicionar novas páginas:

1. Copie um dos arquivos HTML existentes (ex: `about.html`)
2. Renomeie o arquivo para o nome desejado (ex: `nova-pagina.html`)
3. Modifique o conteúdo conforme necessário
4. Atualize os metadados (título, descrição) no cabeçalho
5. Adicione links para a nova página no menu de navegação e/ou rodapé

## Páginas Pendentes

As seguintes páginas são referenciadas no menu e rodapé, mas ainda não foram implementadas:

- `careers.html` - Página de carreiras
- `documentation.html` - Documentação do produto
- `tutorials.html` - Tutoriais
- `community.html` - Comunidade
- `terms.html` - Termos de uso
- `privacy.html` - Política de privacidade
- `cookies.html` - Política de cookies
- `security.html` - Informações de segurança

Você pode criar estas páginas seguindo o mesmo padrão das páginas existentes.

## Funcionalidades JavaScript

O arquivo `js/main.js` contém as seguintes funcionalidades:

- Toggle do menu mobile
- Animações de scroll
- Accordion para FAQs
- Toggle de preços mensal/anual
- Validação de formulários

Para adicionar novas funcionalidades, edite o arquivo `js/main.js`.

## Responsividade

O site é totalmente responsivo e se adapta a diferentes tamanhos de tela:

- **Desktop**: 1200px e acima
- **Tablet**: 768px a 1199px
- **Mobile**: Abaixo de 768px

As classes de grid (col, col-md-\*) seguem um sistema similar ao Bootstrap para facilitar o layout responsivo.

## SEO e Performance

O site foi otimizado para SEO com:

- Tags meta apropriadas
- Estrutura semântica HTML5
- Textos alternativos para imagens
- URLs amigáveis
- Hierarquia de cabeçalhos adequada

Para melhorar a performance:

- Otimize as imagens antes de adicioná-las
- Considere minificar os arquivos CSS e JavaScript para produção
- Utilize um CDN para servir os arquivos estáticos em produção

## Suporte a Navegadores

O site é compatível com as versões mais recentes dos seguintes navegadores:

- Google Chrome
- Mozilla Firefox
- Safari
- Microsoft Edge
- Opera

## Licença

Este site foi desenvolvido exclusivamente para a Weavera Lab. Todos os direitos reservados.

## Contato

Para suporte ou dúvidas sobre este site, entre em contato através de:

- Email: contato@weavera.lab
- Telefone: +55 (11) 3456-7890
