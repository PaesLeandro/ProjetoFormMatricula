# 🎓 Estrelas do Amanhã - Formulário de Matrícula

Projeto de formulário de matrícula para escola de educação infantil, desenvolvido com HTML, CSS puro e abordagem **Mobile First**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## 📋 Sobre o Projeto

Sistema de matrícula online para a escola infantil "Estrelas do Amanhã", permitindo que pais/responsáveis cadastrem seus filhos de forma prática e intuitiva. O formulário coleta informações completas da criança, endereço residencial, dados do responsável e preferências de matrícula.

## ✨ Funcionalidades

- 📝 Formulário completo de matrícula infantil
- 👶 Informações da criança (nome, data de nascimento, sexo, informações médicas)
- 📄 Upload de certidão de nascimento
- 🏠 Preenchimento de endereço via CEP
- 👨‍👩‍👧 Dados do responsável legal
- 🎯 Seleção de turno (manhã/tarde)
- ⚽ Escolha de atividade esportiva (6 opções disponíveis)
- ✅ Aceite de termos e condições
- 📱 **Totalmente responsivo** (Mobile, Tablet, Desktop)

## 🎨 Design

- Interface clean e moderna
- Sistema de cores suave e acessível
- Feedback visual em todos os elementos interativos
- Layout adaptativo para todos os dispositivos
- Ilustração e identidade visual da escola

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e responsividade
  - Flexbox
  - CSS Grid
  - Custom Properties (variáveis CSS)
  - Media Queries (Mobile First)
- **Google Fonts** - Tipografia Poppins

## 📁 Estrutura do Projeto

```
ProjetoFormMatricula/
├── index.html
├── README.md
├── assets/
│   ├── icons/          # Ícones SVG do projeto
│   ├── Logo.svg        # Logo da escola
│   └── Illustration.svg # Ilustração decorativa
└── styles/
    ├── index.css       # Importações principais
    ├── global.css      # Estilos globais e variáveis
    ├── layout.css      # Layout e grid principal
    ├── forms.css       # Estilos de formulários
    └── fields/         # Componentes de campos
        ├── index.css
        ├── input.css
        ├── checkbox.css
        ├── radio.css
        ├── buttons.css
        └── droparea.css
```

## 📱 Responsividade

O projeto utiliza abordagem **Mobile First** com os seguintes breakpoints:

| Dispositivo       | Breakpoint       | Características                               |
| ----------------- | ---------------- | --------------------------------------------- |
| 📱 Mobile         | Base (até 767px) | Layout em coluna, campos empilhados           |
| 📱 Tablet         | 768px+           | Campos lado a lado, grid de opções            |
| 💻 Desktop        | 1024px+          | Espaçamentos otimizados                       |
| 🖥️ Desktop Grande | 1200px+          | Layout em 2 colunas (formulário + ilustração) |

### Comportamento Responsivo

- **Mobile/Tablet**: Ilustração e logo aparecem **acima** do formulário
- **Desktop (1200px+)**: Layout lado a lado (formulário à esquerda, ilustração à direita)
- Campos de endereço se adaptam automaticamente
- Radio buttons mudam de grid para coluna em mobile
- Botões ocupam largura total em dispositivos móveis

## 🎯 Como Usar

1. Clone ou baixe o projeto:

```bash
git clone <seu-repositorio>
```

2. Abra o arquivo `index.html` no seu navegador

3. Ou use um servidor local:

```bash
# Com Python
python -m http.server 8000

# Com Node.js (http-server)
npx http-server
```

4. Acesse: `http://localhost:8000`

## 🎨 Paleta de Cores

```css
--text-primary: #292524 /* Texto principal */ --text-secondary: #57534e
  /* Texto secundário */ --text-tertiary: #8f8881 /* Texto terciário */
  --text-highlight: #e43a12 /* Destaque */ --surface-primary: #ffffff
  /* Fundo principal */ --surface-secondary: #fee7d6
  /* Fundo secundário (aside) */ --surface-disabled: #e7e5e4
  /* Campos desabilitados */ --stroke-default: #d6d3d1 /* Bordas padrão */
  --stroke-highlight: #f5431c /* Bordas em destaque */;
```

## 📝 Campos do Formulário

### Informações da Criança

- Nome completo
- Data de nascimento
- Sexo (Masculino/Feminino/Não informado)
- Informações médicas (textarea)
- Upload de certidão de nascimento

### Endereço Residencial

- CEP
- Rua (preenchimento automático)
- Número
- Cidade (preenchimento automático)
- Estado (preenchimento automático)

### Informações do Responsável

- Nome do responsável
- Telefone
- E-mail (com validação)

### Opções de Matrícula

- Turno de estudo (Manhã/Tarde)
- Esporte preferido:
  - ⚽ Futebol
  - 🏀 Basquete
  - 🏊 Natação
  - 🧘 Yoga
  - 🏐 Vôlei
  - 🥊 Boxe

## 🔧 Melhorias Futuras

- [ ] Validação completa de formulário com JavaScript
- [ ] Integração com API de CEP (ViaCEP)
- [ ] Máscaras de input (telefone, CPF)
- [ ] Armazenamento local dos dados
- [ ] Animações de transição
- [ ] Modo escuro
- [ ] Tradução multi-idioma

## 👨‍💻 Desenvolvido por

Projeto desenvolvido durante o curso da **Rocketseat**

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

⭐ Se este projeto foi útil para você, considere dar uma estrela!
