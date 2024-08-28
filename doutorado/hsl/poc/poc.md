Prova de Conceito: Grounding em LLMs para Geração de Diagramas de Máquina de Estado
# P.O.C. - SPIRES, Grounding e Conhecimento na geração de Drafts de Diagramas de Máquina de Estado

## 1. Introdução

1. Analisei o artigo "STRUCTURED PROMPT INTERROGATION AND RECURSIVE EXTRACTION OF SEMANTICS (SPIRES): A METHOD FOR POPULATING KNOWLEDGE BASES USING ZERO-SHOT LEARNING" de Bae et al. (2023) e identifiquei potenciais sinergias entre o método **SPIRES**, o conceito de **GROUNDING**, e meu objetivo de pesquisa na geração automatizada de **drafts de artefatos de software**.

## 2. Discutir o que é semântica

Significado lexical: Refere-se ao significado das palavras individuais. Por exemplo, as palavras "cachorro" e "gato" têm significados diferentes, que são compreendidos a partir do contexto e do uso comum.

Significado composicional: Trata do significado das frases e sentenças formadas pela combinação de palavras. Por exemplo, a frase "O cachorro está correndo" tem um significado que é derivado das palavras que a compõem e da maneira como elas são combinadas.

Relações semânticas: Inclui conceitos como sinônimos (palavras com significados semelhantes), antônimos (palavras com significados opostos) e hipônimos (palavras que pertencem a uma categoria mais ampla, como "rosa" em relação a "flor").

Pragmática: Embora seja um campo relacionado, a pragmática estuda como o contexto e a situação de comunicação influenciam o significado, indo além do significado literal das palavras.

Discutir a pirâmide que Cleyton sempre menciona

## 2. Discutir o que é Conhecimento Semâtico : semântica e conhecimento semântico

## 3. Discutir o conceito de conhecimento semântico na engenharia de software

## 4. Discutir o que seria conhecimento semântico em um artefato de software
sintaxe
semântica
conhecimento de negocio
artefatos (estado atual para o estado ideal ou esperado)

## 5. Discutir o cenario atual dos LLMs, Artefatos e Conhecimento Semântico


## 2. Análise do SPIRES

### 2.1 Visão Geral do SPIRES

SPIRES é um método que extrai informações estruturadas de texto usando LLMs + Ontologias. O processo envolve:

1. Interrogação estruturada através de prompts
2. Extração recursiva de informações
3. Preenchimento consistente de informação para bases de conhecimento

### 2.2 Pontos-Chave do SPIRES

- Utiliza zero-shot learning, reduzindo a necessidade de dados de treinamento específicos
- Emprega ontologias para guiar a extração de informações
- Relata boa precisão na extração de informações de forma estruturada para formar bases de conhecimento

## 3.Conceito de Grounding

- Bisk et al. (2020) argumentam que "grounding is the process of connecting language to perception and action in the world" (p. 8). 
- Grounding em IA é o processo de ancorar símbolos e representações linguísticas a referentes no mundo real ou experiências concretas.
- No contexto da minha pesquisa o "mundo" é o **domínio de negócio relacionado ao software** e o **domínio técnico de construção de drafts de artefatos de sistemas** na **engenharia de software**.

 No contexto de Large Language Models (LLMs) e geração de drafts de artefatos de software na minha pesquisa estaria associado com:

1. **Ancoragem Sintática**: Conectar termos e conceitos técnicos da engenharia de software a suas representações concretas nos artefatos de software (diagrama de máquina de estados - parte técnica para construir artefatos falar plantuml). A ideia não é desenvolver isso, mas conectar isso com o todo pois os LLMs já constroem este tipo de artefato eu não preciso ensinar a ele
2. **Contextualização de Domínio**: Dominar os conceitos/aspectos de negócio do software para o qual será gerado o draft. Minha primeira percepção seria relacionar RAG para fazer a "interrogação do negócio" (RAG?)
3. **Ancoragem Semântica**: Conectar conceitos e termos de negócio na geração de drafts de artefatos de software. A ancoragem Semântica permitira alinhar o Conhecimento geral do LLM + Ancoragem Sintática + Poder de inferência do LLM + Contextualização de Domínio através de abordagem baseada no SPIRES.

Grouding no nosso contexto é trazer para a realidade 
- (Tirar alucinaçao + Aproximar do conhecimento de negócio) 
- (Alucinação e informacoes de negocio podem ser medidas)

>>Próxima semana: Janela de publicaçao e direcionamentos (congresso e periódicos)
>>CIST: no radar!!!
>>SBSI: foco!

## 3. Analogia e conceitos entre SPIRES e Grounding aplicado ao contexto da pesquisa

### 3.1 SPIRES e Geração de Diagramas

O método SPIRES pode ser adaptado para extrair informações relevantes do negócio para o draft do artefato de software. 

1. Extração contextualizada de informações de negócio do domínio: Adaptar o SPIRES para extrair informacões de negócio relevantes para o artefato de software. Informações do negócio que gerarão Estados, Transições entre Estados, Eventos e Ações.  

    - Uso de Ontologia para identificar elementos (grouding?): através do uso de ontologias conectar elementos semânticos de negócio (abstratos) com elementos concretos (Estados, transições, eventos e ações).

- Identifirar e relacionar semanticamente os elementos  abstratos e concretos: Inrepretação e associação melhorada dos elementos O grouding pode melhorar a interpretação das informações extraídas pelo SPIRES (usando)
- Identificação de estados
- Extração de transições entre estados
- Reconhecimento de eventos e ações

### 3.2 Grounding no Contexto de Diagramas

Grounding, no contexto de geração de diagramas, envolve:

- Ancorar conceitos abstratos de engenharia de software em representações visuais concretas
- Garantir que os elementos extraídos pelo SPIRES sejam corretamente mapeados para componentes do diagrama
- Assegurar a consistência semântica entre a descrição textual e o diagrama gerado

### 3.3 Sinergia Proposta

A integração de SPIRES com técnicas de grounding pode potencialmente:

1. Melhorar a precisão na extração de informações relevantes para diagramas
2. Garantir que os diagramas gerados sejam semanticamente consistentes com as descrições textuais
3. Aumentar a fidelidade dos diagramas às práticas e padrões de engenharia de software

## 4. Objetivo de Pesquisa Refinado

Desenvolver um sistema que integre o método SPIRES e técnicas de grounding para gerar diagramas de máquina de estado a partir de descrições textuais de processos, com foco em:

1. Adaptar SPIRES para o domínio específico de diagramas de máquina de estado
2. Implementar técnicas de grounding para assegurar a correta representação visual dos conceitos extraídos
3. Avaliar a precisão, consistência e utilidade dos diagramas gerados em comparação com métodos tradicionais

## 5. Questões de Pesquisa Propostas

1. Como a integração de SPIRES e grounding afeta a precisão semântica na geração de diagramas de máquina de estado?
2. Quais adaptações são necessárias no método SPIRES para otimizar a extração de informações relevantes para diagramas de máquina de estado?
3. Como podemos quantificar e avaliar o impacto do grounding na qualidade e utilidade dos diagramas gerados?
4. Quais são os desafios específicos de aplicar grounding no contexto de engenharia de software e modelagem de sistemas?

## 6. Próximos Passos

1. Desenvolver uma ontologia específica para diagramas de máquina de estado
2. Adaptar o método SPIRES para utilizar esta ontologia na extração de informações
3. Implementar técnicas de grounding para mapear conceitos extraídos em elementos visuais do diagrama
4. Criar um protótipo inicial integrando SPIRES e grounding para geração de diagramas
5. Projetar experimentos para validar a eficácia da abordagem proposta

## 7. Conclusão

A integração de SPIRES e grounding apresenta um caminho promissor para avançar na geração automatizada de diagramas de máquina de estado. Esta abordagem tem o potencial de produzir diagramas mais precisos, consistentes e úteis para engenheiros de software, combinando a potência dos LLMs com conhecimento estruturado do domínio.

## Referências

Bae, S., Song, Y., Lee, H., & Park, S. (2023). STRUCTURED PROMPT INTERROGATION AND RECURSIVE EXTRACTION OF SEMANTICS (SPIRES): A METHOD FOR POPULATING KNOWLEDGE BASES USING ZERO-SHOT LEARNING. *arXiv preprint arXiv:2305.06599*.
