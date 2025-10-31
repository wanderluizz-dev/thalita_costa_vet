# 🐾 Cartão de Visitas Digital - Thalita Costa

> Landing page moderna e interativa para médica veterinária com design responsivo e animações suaves.

![Status](https://img.shields.io/badge/status-active-success.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 📋 Sobre o Projeto

Cartão de visitas digital completo desenvolvido para profissionais veterinários, com foco em experiência do usuário e conversão. A página oferece múltiplos canais de contato integrados e design otimizado para dispositivos móveis.

### ✨ Características Principais

- 📱 **100% Responsivo** - Perfeito em qualquer dispositivo
- 🎨 **Design Moderno** - Interface clean e profissional
- 💫 **Animações Suaves** - Transições e efeitos hover elegantes
- 🚀 **Performance Otimizada** - Carregamento rápido
- 🎯 **Foco em Conversão** - CTA estrategicamente posicionados
- 🐾 **Tema Veterinário** - Elementos visuais personalizados

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **Tailwind CSS** - Estilização utilitária
- **Font Awesome** - Ícones profissionais
- **Google Fonts (Poppins)** - Tipografia moderna
- **CSS3 Animations** - Efeitos e transições

## 🎨 Funcionalidades

### Canais de Contato Integrados

| Funcionalidade | Descrição |
|----------------|-----------|
| 📞 **Ligação Direta** | Botão de chamada telefônica instantânea |
| 💬 **WhatsApp** | Link direto para chat do WhatsApp |
| 📧 **E-mail** | Abertura automática do cliente de e-mail |
| 📍 **Localização** | Integração com Google Maps |
| 📷 **Instagram** | Link para perfil profissional |
| 👍 **Facebook** | Conexão com página no Facebook |

### Destaques Visuais

- 🏷️ **Banner de Desconto** - Promoção de 30% em destaque
- 🏠 **Atendimento Domiciliar** - Badge informativo
- 📅 **Botão de Agendamento** - CTA principal
- 🐾 **Padrão de Patinhas** - Background temático

## 📂 Estrutura do Projeto

```
cartao-digital-veterinario/
│
├── index.html              # Página principal
├── README.md              # Documentação
└── assets/                # Pasta de recursos (criar)
    └── images/
        └── logo.png       # Logo da clínica
```

## 🚀 Como Usar

### Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/cartao-digital-veterinario.git
```

2. **Navegue até a pasta**
```bash
cd cartao-digital-veterinario
```

3. **Abra o arquivo no navegador**
```bash
# Duplo clique no index.html
# ou use um servidor local
python -m http.server 8000
```

### Personalização

#### 1. Substitua a Logo
```html
<!-- Linha 49 - Altere o src da imagem -->
<img src="assets/images/sua-logo.png" alt="Sua Logo" class="h-20 mx-auto">
```

#### 2. Atualize as Informações Pessoais
```html
<!-- Linhas 52-54 -->
<h1 class="text-3xl font-bold text-gray-800 mb-1">Seu Nome</h1>
<p class="text-lg text-gray-600 mb-1">Sua Especialidade</p>
<p class="text-sm text-gray-500">CRMV-XX: 00000</p>
```

#### 3. Configure os Links de Contato
```html
<!-- WhatsApp - Linha 78 -->
<a href="https://wa.me/55XXXXXXXXXXX" target="_blank">

<!-- Instagram - Linha 84 -->
<a href="https://instagram.com/seuperfil" target="_blank">

<!-- Telefone - Linha 90 -->
<a href="tel:+55XXXXXXXXXXX">

<!-- E-mail - Linha 96 -->
<a href="mailto:seu@email.com">

<!-- Localização - Linha 102 -->
<a href="https://maps.google.com/?q=SuaCidade+Estado" target="_blank">
```

#### 4. Personalize as Cores

O projeto usa as cores da identidade visual da Thalita Costa. Para alterar:

```css
/* Linha 13-15 - Gradiente principal */
.gradient-bg {
    background: linear-gradient(135deg, #SUACOR1 0%, #SUACOR2 100%);
}

/* Linha 61 - Background dos cartões */
<div class="bg-gradient-to-b from-teal-400 to-teal-500 p-8">
```

## 📱 Compatibilidade

- ✅ Chrome (última versão)
- ✅ Firefox (última versão)
- ✅ Safari (última versão)
- ✅ Edge (última versão)
- ✅ Dispositivos móveis (iOS/Android)

## 🎯 Casos de Uso

Este template é ideal para:

- 🐕 Médicos Veterinários
- 🏥 Clínicas Veterinárias
- 🏠 Profissionais com atendimento domiciliar
- 📋 Serviços de saúde animal
- 🎓 Profissionais autônomos da área pet

## 💡 Dicas de SEO

Para melhorar o ranqueamento:

1. **Meta Tags** - Adicione no `<head>`:
```html
<meta name="description" content="Cartão digital de [Nome] - Médica Veterinária em [Cidade]">
<meta name="keywords" content="veterinário, atendimento domiciliar, [cidade]">
<meta property="og:title" content="[Nome] - Médica Veterinária">
<meta property="og:image" content="url-da-imagem-preview.jpg">
```

2. **Título da Página** - Personalize:
```html
<title>Seu Nome | Médica Veterinária | Sua Cidade</title>
```

## 📊 Analytics (Opcional)

Para monitorar acessos, adicione o Google Analytics:

```html
<!-- Antes do </head> -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🚀 Hospedagem

Opções gratuitas para hospedar:

1. **GitHub Pages**
   - Crie um repositório público
   - Ative o GitHub Pages nas configurações
   - Acesse via: `seu-usuario.github.io/nome-repositorio`

---

⭐ **Se este projeto foi útil, deixe uma estrela no GitHub!** ⭐

Desenvolvido com ❤️ e 🐾 por profissionais que amam animais