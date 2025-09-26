# Dashboard DE-PARA - Portfólio de Processos

Um dashboard interativo e moderno para visualização e análise de dados DE-PARA (De-Para) com interface responsiva e recursos avançados de filtragem e análise.

## 🚀 Características

- **Interface Moderna**: Design responsivo com tema escuro/claro
- **Visualizações Interativas**: Gráficos dinâmicos e tabelas filtráveis
- **Análise de Dados**: Ferramentas para análise de mapeamento DE-PARA
- **Filtros Avançados**: Sistema de filtros por categoria, status e período
- **Exportação**: Capacidade de exportar dados em diferentes formatos
- **Performance**: Otimizado para grandes volumes de dados

## 📋 Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional para desenvolvimento)

## 🛠️ Instalação

### Opção 1: Execução Direta
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/portfolio-de-para-dashboard.git
cd portfolio-de-para-dashboard
```

2. Abra o arquivo `DE-PARA.html` diretamente no navegador ou acesse através de `index.html`

### Opção 2: Servidor Local (Recomendado)

#### Usando Node.js
```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev
```

#### Usando Python
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Usando PowerShell (Windows)
```powershell
# Execute o script PowerShell incluído
.\start-server.ps1
```

## 🌐 Deploy

### Vercel (Recomendado)
1. Instale a Vercel CLI:
```bash
npm i -g vercel
```

2. Faça login na Vercel:
```bash
vercel login
```

3. Deploy do projeto:
```bash
vercel --prod
```

### Netlify
1. Conecte seu repositório GitHub ao Netlify
2. Configure as seguintes opções:
   - Build command: (deixe vazio)
   - Publish directory: `/`

### GitHub Pages
1. Vá para Settings > Pages no seu repositório
2. Selecione "Deploy from a branch"
3. Escolha a branch `main` e pasta `/ (root)`

## 📁 Estrutura do Projeto

```
portfolio-de-para-dashboard/
├── DE-PARA.html          # Arquivo principal do dashboard
├── index.html            # Página de entrada com redirecionamento
├── package.json          # Configurações do projeto Node.js
├── vercel.json          # Configurações de deploy para Vercel
├── README.md            # Este arquivo
└── .gitignore           # Arquivos ignorados pelo Git
```

## 🎯 Como Usar

### Navegação Principal
1. **Dashboard**: Visualização geral dos dados DE-PARA
2. **Filtros**: Use os controles laterais para filtrar dados
3. **Gráficos**: Interaja com os gráficos para análises detalhadas
4. **Tabelas**: Ordene e filtre dados tabulares
5. **Exportação**: Use os botões de exportação para salvar dados

### Funcionalidades Principais

#### Filtros Disponíveis
- **Por Período**: Selecione intervalos de datas
- **Por Status**: Filtre por status de processamento
- **Por Categoria**: Organize por categorias específicas
- **Busca Textual**: Pesquise por termos específicos

#### Visualizações
- **Gráfico de Barras**: Distribuição por categorias
- **Gráfico de Pizza**: Proporções de status
- **Linha do Tempo**: Evolução temporal dos dados
- **Tabela Dinâmica**: Dados detalhados com ordenação

#### Temas
- **Tema Claro**: Interface clara para uso diurno
- **Tema Escuro**: Interface escura para reduzir fadiga visual

## 🔧 Configuração

### Personalização de Dados
Para usar seus próprios dados, edite as variáveis JavaScript no arquivo `DE-PARA.html`:

```javascript
// Exemplo de estrutura de dados
const dadosDeParaExemplo = [
    {
        id: 1,
        origem: "Valor Original",
        destino: "Valor Mapeado",
        categoria: "Categoria A",
        status: "Ativo",
        dataAtualizacao: "2024-01-15"
    }
    // ... mais dados
];
```

### Configuração de Cores
Modifique as variáveis CSS para personalizar o tema:

```css
:root {
    --primary-color: #3b82f6;
    --secondary-color: #64748b;
    --success-color: #10b981;
    --warning-color: #f59e0b;
    --error-color: #ef4444;
}
```

## 🚀 Scripts Disponíveis

```bash
# Iniciar servidor de desenvolvimento
npm run dev

# Iniciar servidor de produção
npm start

# Build para produção (se aplicável)
npm run build
```

## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 📞 Suporte

Para suporte e dúvidas:
- Abra uma issue no GitHub
- Entre em contato através do email: seu-email@exemplo.com

## 🔄 Changelog

### v1.0.0 (2024-09-26)
- Lançamento inicial
- Dashboard interativo completo
- Sistema de filtros avançados
- Suporte a temas claro/escuro
- Visualizações gráficas dinâmicas
- Configuração para deploy em múltiplas plataformas

---

**Desenvolvido com ❤️ para análise eficiente de dados DE-PARA**