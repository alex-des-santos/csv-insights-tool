# CSV Insights Tool with LLM

![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)

Uma ferramenta web avançada que combina análise de CSV com inteligência artificial (Google Gemini) para gerar insights profundos e acionáveis sobre seus dados.

## 🧠 Características Únicas

- **Análise com IA**: Utiliza Google Gemini (LLM) para análise inteligente
- **Insights Contextualizados**: Forneça contexto e receba análises personalizadas
- **Interface Bilíngue**: Suporte completo a Português e Inglês
- **Tema Escuro/Claro**: Toggle entre modos de visualização
- **Processamento Local**: Dados processados no navegador (privacidade)
- **API Segura**: Chave API não é armazenada em servidores

## 🚀 Funcionalidades

### Análise Inteligente com LLM

- **Sugestões de Organização**: Melhorias para estrutura dos dados
- **Novos Insights**: Identificação de oportunidades analíticas
- **Análise Micro/Macro**: Visão detalhada e panorâmica dos dados

### Interface Avançada

- **Pré-visualização**: Tabela responsiva com primeiras linhas
- **Feedback Visual**: Indicadores de progresso e status
- **Experiência Localizada**: Tradução completa PT/EN
- **Modo Escuro**: Redução de fadiga visual

## 📋 Pré-requisitos

- **Navegador Moderno**: Chrome 88+, Firefox 85+, Edge 88+, Safari 14+
- **Chave API Google**: Acesso ao Google AI Studio (Gemini)
- **JavaScript Habilitado**: Necessário para processamento
- **Conexão Internet**: Para comunicação com API do Google

## 🔧 Como Usar

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/alex-des-santos/csv-insights-tool
   ```

2. **Obtenha sua API Key**: Visite [Google AI Studio](https://aistudio.google.com/app/apikey)
3. **Abra `index.html`** no seu navegador
4. **Configure**: Insira sua chave API e selecione idioma/tema
5. **Upload**: Carregue seu arquivo CSV
6. **Contextualize**: Descreva seus dados e objetivos
7. **Analise**: Obtenha insights gerados por IA

## 💡 Exemplo de Uso Avançado

**Cenário**: Dados de vendas de e-commerce

**Contexto fornecido**:
> "Vendas mensais de produtos eletrônicos. 'Revenue' em USD, 'Units' são unidades vendidas, 'Category' é categoria do produto. Objetivo: identificar padrões sazonais e produtos mais lucrativos."

**Insights gerados pela IA**:

- Sugestões de normalização de dados
- Oportunidades de segmentação de clientes
- Análise de sazonalidade por categoria
- Identificação de outliers e anomalias

## ⚠️ Limitações e Considerações

### Segurança

- **API Key**: Armazenada apenas localmente no navegador
- **Dados**: Processados localmente, enviados apenas sumário para IA
- **Privacidade**: Nenhum dado permanece em servidores

### Técnicas

- **Tamanho**: Limitado pela memória do navegador
- **Amostragem**: Apenas 5 linhas enviadas para análise LLM
- **Delimitador**: Suporta apenas vírgula como separador
- **Custo**: Uso da API Google pode gerar custos

## 🛠️ Tecnologias

- **Frontend**: HTML5, CSS3 (Tailwind), JavaScript ES6+
- **Processamento**: Papa Parse (CSV), Marked.js (Markdown)
- **IA**: Google Gemini API
- **Interface**: Sistema de temas e internacionalização

## 🌍 Melhorias Implementadas

✅ **Internacionalização**: Português e Inglês completos  
✅ **Tema Escuro**: Toggle para reduzir fadiga visual  
✅ **UX Melhorada**: Feedback visual e indicadores de progresso  
✅ **Segurança**: Links com `rel="noopener"` e validações  

## 🔮 Roadmap

- [ ] Suporte a delimitadores customizados
- [ ] Análise de mais linhas (configurável)
- [ ] Gráficos gerados pela IA
- [ ] Exportação de relatórios
- [ ] Integração com outras APIs de IA
- [ ] Modo offline para análises básicas

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

- Faça um fork do projeto
- Crie uma branch para sua feature ou correção
- Envie um Pull Request

Consulte o arquivo [CONTRIBUTING.md](CONTRIBUTING.md) para detalhes.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 📞 Suporte

Se você encontrar problemas ou tiver sugestões:

- Abra uma [issue](https://github.com/alex-des-santos/csv-insights-tool/issues)
- Entre em contato via email

## ❓ FAQ

**Q: Como funciona a análise com IA?**  
A: Enviamos apenas um sumário dos dados (cabeçalhos + 5 linhas) junto com seu contexto para o Google Gemini, que retorna insights personalizados.

**Q: Minha API key é segura?**  
A: Sim, ela é armazenada apenas no seu navegador e usado diretamente para comunicação com a API do Google.

**Q: Posso analisar arquivos grandes?**  
A: O processamento é local, mas apenas uma amostra é enviada para IA. Recomendamos arquivos até 50MB para melhor performance.

**Q: Há custos envolvidos?**  
A: A ferramenta é gratuita, mas o uso da API Google Gemini pode gerar custos conforme sua utilização.
