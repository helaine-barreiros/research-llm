# Estrutura de Pesquisa com GitHub Pages e Práticas de Open Science

## 1. Implementação do GitHub Pages

### 1.1 Estrutura de Pastas para GitHub Pages

Adicione uma pasta `docs/` na raiz do repositório para o conteúdo do GitHub Pages:

```
/
├── docs/                   # Conteúdo para GitHub Pages
│   ├── index.md            # Página inicial
│   ├── blog/               # Posts do blog
│   ├── publicacoes/        # Lista de publicações
│   ├── recursos/           # Recursos públicos
│   └── dados-abertos/      # Dados abertos da pesquisa
├── [outras pastas do projeto]
```

### 1.2 Configuração do GitHub Pages

1. Vá para as configurações do repositório no GitHub.
2. Na seção "Pages", selecione a branch `main` e a pasta `/docs` como fonte.
3. Escolha um tema ou crie um personalizado.

### 1.3 Conteúdo para GitHub Pages

- `index.md`: Visão geral do projeto de pesquisa
- `blog/`: Posts regulares sobre o progresso da pesquisa
- `publicacoes/`: Lista de artigos, apresentações e outros outputs
- `recursos/`: Materiais educacionais, códigos, etc.
- `dados-abertos/`: Conjuntos de dados públicos da pesquisa

## 2. Práticas de Open Science

### 2.1 Transparência e Reprodutibilidade

1. **Pré-registro de Estudos**:
   - Crie uma pasta `pre-registros/` para armazenar documentos de pré-registro de estudos.
   - Publique esses pré-registros no OSF (Open Science Framework) e link-os no GitHub Pages.

2. **Protocolos de Pesquisa**:
   - Mantenha uma pasta `protocolos/` com descrições detalhadas dos métodos de pesquisa.
   - Versione esses protocolos usando o Git.

3. **Cadernos de Laboratório Abertos**:
   - Use a seção de "Issues" do GitHub como um caderno de laboratório aberto.
   - Crie templates para entradas padronizadas de experimentos/análises.

### 2.2 Compartilhamento de Dados e Código

1. **Dados Abertos**:
   - Use a pasta `dados-abertos/` para compartilhar conjuntos de dados.
   - Inclua metadados claros e licenças para cada conjunto de dados.

2. **Código Aberto**:
   - Mantenha todo o código de análise e experimentos no repositório.
   - Documente claramente como executar/replicar as análises.

3. **Containers e Ambientes**:
   - Forneça Dockerfiles ou ambientes virtuais para reproduzir o ambiente de análise.

### 2.3 Publicação e Disseminação Abertas

1. **Preprints**:
   - Crie uma pasta `preprints/` para versões preliminares de artigos.
   - Publique preprints em serviços como arXiv ou bioRxiv e link-os no GitHub Pages.

2. **Publicações de Acesso Aberto**:
   - Priorize a publicação em journals de acesso aberto.
   - Mantenha uma lista atualizada de publicações no GitHub Pages.

3. **Materiais Suplementares**:
   - Armazene materiais suplementares de publicações no repositório.

### 2.4 Colaboração Aberta

1. **Contribuições Externas**:
   - Crie um arquivo CONTRIBUTING.md detalhando como externos podem contribuir.
   - Use "Issues" para discutir ideias e melhorias com a comunidade.

2. **Revisão Aberta**:
   - Considere usar plataformas de revisão aberta para manuscritos.
   - Compartilhe revisões e respostas no repositório após a publicação.

## 3. Fluxo de Trabalho Integrado

1. **Desenvolvimento de Pesquisa**:
   - Continue usando a estrutura de branches e pastas definida anteriormente.

2. **Atualização do Site Público**:
   - Crie uma branch `website-update` para alterações no conteúdo de `docs/`.
   - Use Pull Requests para revisar e mesclar atualizações do site.

3. **Publicação de Resultados**:
   - Ao concluir uma análise ou experimento, crie um post no blog e atualize as seções relevantes do site.
   - Faça upload de novos dados ou códigos nas respectivas pastas públicas.

4. **Manutenção Contínua**:
   - Estabeleça um cronograma regular para atualizar o conteúdo público.
   - Revise e atualize permissões e licenças regularmente.

## 4. Documentação Adicional

1. **Política de Dados Abertos**:
   - Crie um documento detalhando a política de compartilhamento de dados do projeto.

2. **Guia de Reprodutibilidade**:
   - Desenvolva um guia passo a passo para reproduzir os principais resultados da pesquisa.

3. **Declaração de Ética**:
   - Inclua uma declaração clara sobre práticas éticas de pesquisa e manejo de dados.

---

Última atualização: [13/08/24]