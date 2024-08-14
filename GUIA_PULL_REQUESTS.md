# Guia de Labels e Configuração de Pull Requests

## Labels

As labels ajudam a categorizar e priorizar issues e pull requests. Aqui estão as labels recomendadas para nosso projeto de pesquisa:

### Tipo de Trabalho
- `pesquisa`: Trabalho de pesquisa principal
- `documentação`: Atualização ou adição de documentação
- `análise`: Análise de dados ou literatura
- `experimento`: Condução de experimentos
- `artigo`: Trabalho relacionado a artigos científicos
- `bug`: Algo não está funcionando corretamente
- `melhoria`: Aprimoramento de funcionalidade existente

### Escopo do Trabalho
- `doutorado`: Relacionado a projeto de doutorado
- `mestrado`: Relacionado a projeto de mestrado
- `ic`: Relacionado a projeto de iniciação científica
- `projeto-principal`: Parte de um projeto principal ou parceria

### Prioridade
- `urgente`: Precisa de atenção imediata
- `alta`: Alta prioridade
- `média`: Prioridade média
- `baixa`: Baixa prioridade

### Estado
- `em progresso`: Trabalho atual
- `revisão necessária`: Precisa de revisão por pares
- `bloqueado`: Impedido de progredir por alguma razão

### Outros
- `discussão`: Precisa de mais discussão ou decisão
- `boa primeira issue`: Bom para novos colaboradores
- `help wanted`: Precisa de assistência adicional

## Configuração de Pull Requests

Ao criar ou revisar um pull request, siga estas diretrizes:

### Criando um Pull Request

1. **Título**: Use um título claro e descritivo, seguindo o formato:
   `[TIPO]: Breve descrição da mudança`
   Exemplo: `[PESQUISA]: Adicionar análise inicial de dados LLM`

2. **Descrição**:
   - Resuma o propósito das mudanças
   - Liste as principais alterações feitas
   - Mencione quaisquer issues relacionadas usando `#` (ex: `Closes #123`)
   - Se aplicável, inclua screenshots ou gifs demonstrando as mudanças

3. **Labels**: Adicione labels relevantes conforme a lista acima

4. **Reviewers**: Atribua pelo menos um revisor, preferencialmente alguém familiarizado com a área do trabalho

5. **Projetos**: Se estiver usando GitHub Projects, associe o PR ao projeto relevante

6. **Milestone**: Se aplicável, associe a um milestone específico

### Template de Pull Request

Use este template ao criar um novo PR:

```markdown
## Descrição
[Descreva brevemente o propósito deste PR]

## Principais Mudanças
- [Mudança 1]
- [Mudança 2]
- [...]

## Issues Relacionadas
[Liste quaisquer issues relacionadas, ex: Closes #123]

## Checklist
- [ ] Código segue as diretrizes do projeto
- [ ] Documentação atualizada
- [ ] Testes adicionados/atualizados (se aplicável)
- [ ] Revisão por pares solicitada

## Notas Adicionais
[Quaisquer informações extras relevantes para os revisores]
```

### Revisando um Pull Request

Ao revisar um PR, considere os seguintes aspectos:

1. **Qualidade do Código/Conteúdo**: 
   - O trabalho está bem escrito e organizado?
   - Segue as melhores práticas da área?

2. **Funcionalidade**:
   - As mudanças atendem ao propósito descrito?
   - Há efeitos colaterais não intencionais?

3. **Testes e Validação** (se aplicável):
   - Existem testes adequados?
   - Os resultados são reproduzíveis?

4. **Documentação**:
   - A documentação foi atualizada adequadamente?
   - As mudanças estão bem explicadas?

5. **Impacto no Projeto**:
   - Como essas mudanças se alinham com os objetivos gerais do projeto?
   - Há considerações éticas ou de open science a serem abordadas?

### Mesclando um Pull Request

Antes de mesclar um PR:

1. Certifique-se de que todas as discussões foram resolvidas
2. Verifique se o PR recebeu as aprovações necessárias
3. Confirme que todos os checks automatizados passaram (se configurados)
4. Escolha o método de merge apropriado (geralmente "Squash and merge" para manter o histórico limpo)
5. Atualize a mensagem de commit final para refletir claramente as mudanças

## Melhores Práticas

- Mantenha os PRs pequenos e focados quando possível
- Use branches feature para trabalho em andamento
- Atualize regularmente sua branch com a develop para evitar conflitos
- Encoraje revisões construtivas e discussões abertas
- Documente decisões importantes nos comentários do PR

Seguindo estas diretrizes, manteremos nosso projeto organizado, facilitaremos a colaboração e garantiremos a qualidade do nosso trabalho de pesquisa.

---

Última atualização: [14/08/2024]