# A&F Comércio de Grãos - Portal Unificado

Portal online para gestão financeira e análise de mercado agrícola.

## 📋 Conteúdo

- **Fluxo de Caixa 2026** - Gestão financeira mensal com gráficos e alertas
- **BI de Grãos** - Análise de preços de tradings e fretes por cidade
- **Exportação Excel** - Exporte dados em qualquer momento

## 🚀 Como Usar

### Acessar Online
Após configurar no GitHub Pages, acesse em:
```
https://aefgraos.github.io/af-graos-portal/
```

### Editar Dados

#### Fluxo de Caixa
1. Abra o arquivo `AF_FluxoCaixa_2026_20260325(2).html` em um editor de texto
2. Procure pela seção `const dadosFluxo = {`
3. Edite os valores das transações
4. Salve o arquivo e faça commit no GitHub

#### BI de Grãos
1. Abra o arquivo `bi-dados.json` em um editor de texto
2. Edite os preços das tradings ou fretes das cidades
3. Salve o arquivo e faça commit no GitHub

## 📁 Estrutura de Arquivos

```
af-graos-portal/
├── index.html              # Página inicial com menu
├── fluxo-caixa.html       # Ferramenta de Fluxo de Caixa
├── bi-graos.html          # Ferramenta de BI de Grãos
├── bi-dados.json          # Dados do BI de Grãos
└── README.md              # Este arquivo
```

## 🔧 Configuração Inicial

### 1. Criar Repositório no GitHub
1. Acesse https://github.com/new
2. Nome: `af-graos-portal`
3. Descrição: "Portal unificado de gestão financeira e análise de mercado"
4. Marque "Public"
5. Clique em "Create repository"

### 2. Fazer Upload dos Arquivos
Opção A - Via GitHub Web:
1. Clique em "Add file" → "Upload files"
2. Arraste os arquivos para a área
3. Clique em "Commit changes"

Opção B - Via Git (recomendado):
```bash
git clone https://github.com/aefgraos/af-graos-portal.git
cd af-graos-portal
# Copie os arquivos para esta pasta
git add .
git commit -m "Adicionar ferramentas de BI e Fluxo de Caixa"
git push origin main
```

### 3. Ativar GitHub Pages
1. Vá para Settings do repositório
2. Procure por "Pages" no menu esquerdo
3. Em "Source", selecione "main" branch
4. Clique em "Save"
5. Aguarde alguns minutos
6. Seu site estará disponível em: `https://aefgraos.github.io/af-graos-portal/`

## 👥 Compartilhar com Equipe

1. Vá para Settings → Collaborators
2. Clique em "Add people"
3. Digite o email ou username de cada pessoa
4. Selecione a permissão (recomendado: "Maintain")
5. Envie o convite

Cada membro pode então:
- Editar os arquivos diretamente no GitHub
- Fazer commits com as mudanças
- As mudanças aparecem no site em tempo real

## 📊 Como Atualizar Dados

### Fluxo de Caixa
- Edite o arquivo `fluxo-caixa.html`
- Procure por `const dadosFluxo`
- Atualize os valores
- Salve e faça commit

### BI de Grãos
- Edite o arquivo `bi-dados.json`
- Atualize os preços ou fretes
- Salve e faça commit
- O site carrega automaticamente

## 💡 Dicas

- As mudanças no GitHub levam alguns segundos para aparecer no site
- Use a função "Exportar Excel" para fazer backup dos dados
- Mantenha um histórico de commits para rastrear mudanças
- Todos na equipe podem editar simultaneamente

## 📞 Suporte

Para dúvidas sobre:
- **GitHub**: Consulte https://docs.github.com
- **Edição de dados**: Abra o arquivo em um editor de texto
- **Problemas de acesso**: Verifique as permissões no repositório

---

**Criado em:** 27 de Março de 2026
**Versão:** 1.0
**Status:** ✅ Pronto para uso
