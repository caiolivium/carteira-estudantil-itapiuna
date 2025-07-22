# Sistema de Carteira de Estudante Digital - Itapiúna-CE

Sistema web moderno e responsivo para emissão e gerenciamento de carteiras de estudante digitais da Prefeitura de Itapiúna-CE.

## 🚀 Funcionalidades

### Para Estudantes:
- **Cadastro**: Solicitar nova carteira digital com upload de documentos
- **Login**: Acessar carteira aprovada usando CPF
- **Consulta de Status**: Verificar andamento da solicitação
- **Dashboard**: Visualizar carteira digital após aprovação

### Para Administradores:
- **Login Admin**: Usuário: `admin` | Senha: `123456`
- **Dashboard Admin**: Gerenciar todas as solicitações
- **Aprovação/Rejeição**: Processar solicitações pendentes

## 🎯 Como Usar

1. Abra o arquivo `index.html` em qualquer navegador moderno
2. O sistema funciona como uma Single Page Application (SPA)
3. Navegue entre as páginas usando o menu principal

## 📱 Dados de Teste

### Estudantes Aprovados (podem fazer login):
- **João Silva Santos** - CPF: `123.456.789-01`
- **Ana Paula Mendes** - CPF: `555.666.777-88`

### Estudante Pendente:
- **Maria Oliveira Costa** - CPF: `987.654.321-00`

### Administrador:
- **Usuário**: `admin`
- **Senha**: `123456`

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilos modernos com CSS Custom Properties
- **JavaScript ES6+**: Funcionalidades avançadas (SPA, LocalStorage, Fetch API)
- **Design Responsivo**: Funciona em desktop, tablet e mobile
- **PWA Ready**: Preparado para Progressive Web App

## 📁 Estrutura do Projeto

```
trabalho-web/
├── index.html          # Página principal (SPA)
├── README.md           # Documentação
├── .gitignore         # Arquivos ignorados pelo Git
├── css/
│   └── styles.css     # Estilos completos do sistema
└── pages/
    ├── home.html
    ├── cadastrar.html
    ├── entrar.html
    ├── consultar-status.html
    ├── sobre.html
    ├── dashboard-estudante.html
    ├── dashboard-admin.html
    └── carteira.html
```

## 🎨 Recursos

- **Design Responsivo**: Adaptável a qualquer tamanho de tela
- **Tema Escuro/Claro**: Alternância automática de temas
- **Navegação SPA**: Carregamento dinâmico sem recarregar página
- **Dados Persistentes**: Armazenamento local das informações
- **Validação de Formulários**: CPF, telefone e uploads
- **Notificações**: Sistema de alertas integrado
- **Acessibilidade**: Suporte completo a leitores de tela

## 🌐 Execução

### Método Simples:
```bash
# Abra diretamente no navegador
xdg-open index.html
```

### Servidor Local (Opcional):
```bash
# Python
python3 -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000

# Acesse: http://localhost:8000
```

## 📞 Suporte

- **Prefeitura de Itapiúna-CE**
- **Email**: educacao@itapiuna.ce.gov.br
- **Telefone**: (85) 3123-4567

## 📄 Licença

© 2025 Prefeitura de Itapiúna-CE. Todos os direitos reservados.
