# Diretrizes para Contribuição

## 🤝 Como Contribuir para o Tesauro de Desinformação

Agradecemos seu interesse em contribuir para o desenvolvimento e aprimoramento deste tesauro! Este documento fornece diretrizes para garantir que as contribuições sejam consistentes e alinhadas com os padrões ISO 25964-1:2011.

## 📋 Tipos de Contribuição

### 1. Proposição de Novos Termos
- Verifique se o termo já não existe no tesauro
- Forneça definição clara e nota de escopo
- Indique relações hierárquicas e associativas
- Inclua fontes de referência acadêmicas

### 2. Correção de Termos Existentes
- Identifique claramente o termo a ser corrigido
- Explique o problema identificado
- Forneça a correção proposta com justificativa
- Cite fontes que sustentem a mudança

### 3. Adição de Relações
- Especifique os termos envolvidos
- Indique o tipo de relação (TG, TE, TR, USE, UP)
- Justifique a relação proposta
- Mantenha consistência hierárquica

### 4. Traduções e Equivalências
- Forneça traduções precisas
- Considere variações regionais quando aplicável
- Inclua contexto de uso se necessário

## 🔧 Processo de Contribuição

### Via GitHub Issues
1. Abra uma nova issue no repositório
2. Use o template apropriado:
   - `novo-termo`: Para propor novos descritores
   - `correção`: Para correções em termos existentes
   - `relação`: Para novas relações entre termos
   - `tradução`: Para equivalências linguísticas

### Via Pull Request
1. Fork o repositório
2. Crie um branch descritivo: `adiciona-termo-x` ou `corrige-relacao-y`
3. Faça suas alterações seguindo a estrutura existente
4. Commit com mensagem clara: `feat: adiciona termo 'Guerra cognitiva'`
5. Abra um Pull Request com descrição detalhada

## 📐 Padrões e Formatação

### Estrutura de um Termo

```markdown
**[Termo]**
- TG: [Termo Genérico]
- TE: [Termo Específico]
- TR: [Termo Relacionado]
- USE: [Termo preferido se este for não-preferido]
- UP: [Termo não-preferido se este for preferido]
- NE: [Nota de Escopo - definição e contexto]
- NA: [Nota de Aplicação - quando usar]
- NH: [Nota Histórica - evolução do termo]
```

### Exemplo de Contribuição Bem Formatada

```markdown
**Guerra cognitiva**
- TG: Guerra informacional
- TE: Manipulação neurocognitiva
- TE: Hackeamento cognitivo
- TR: Operações psicológicas
- TR: Neurociência comportamental
- NE: Estratégias de influência que exploram processos cognitivos e vieses psicológicos para afetar tomada de decisão
- NA: Usar para operações que visam especificamente processos mentais
- NH: Conceito emergente pós-2020, desenvolvido em contextos militares da OTAN
```

## ✅ Critérios de Aceitação

### Para Novos Termos
- [ ] Relevância comprovada para o domínio
- [ ] Definição clara e não ambígua
- [ ] Diferenciação de termos existentes
- [ ] Pelo menos uma relação hierárquica
- [ ] Fontes acadêmicas ou oficiais

### Para Correções
- [ ] Evidência do erro
- [ ] Impacto da correção documentado
- [ ] Consistência mantida no tesauro
- [ ] Referências atualizadas

## 📚 Recursos de Referência

### Normas e Padrões
- [ISO 25964-1:2011](https://www.iso.org/standard/53657.html) - Tesauros para recuperação de informação
- [ANSI/NISO Z39.19-2005](https://www.niso.org/publications/z3919-2005-r2010) - Vocabulários controlados

### Literatura Fundamental
- Wardle, C., & Derakhshan, H. (2017). Information Disorder Framework. Council of Europe.
- Tandoc Jr, E. C., Lim, Z. W., & Ling, R. (2018). Defining "fake news". Digital Journalism, 6(2), 137-153.
- Jack, C. (2017). Lexicon of Lies: Terms for Problematic Information. Data & Society.

### Tesauros de Referência
- UNESCO Thesaurus
- ERIC Thesaurus
- European Union Vocabularies

## 🎯 Prioridades Atuais

### Alta Prioridade
- Termos relacionados a IA generativa e deepfakes
- Vocabulário sobre regulação de plataformas digitais
- Terminologia jurídica brasileira específica

### Média Prioridade
- Expansão de equivalências em inglês
- Refinamento de notas de escopo
- Adição de exemplos de uso

### Baixa Prioridade
- Traduções para outros idiomas
- Variações regionais de termos

## 📝 Checklist para Contribuidores

Antes de submeter sua contribuição, verifique:

- [ ] O termo/correção segue os padrões ISO 25964-1:2011?
- [ ] As relações hierárquicas estão corretas?
- [ ] A nota de escopo é clara e completa?
- [ ] Existem fontes confiáveis citadas?
- [ ] A formatação está consistente com o tesauro?
- [ ] Foi verificada duplicação com termos existentes?
- [ ] O arquivo CSV foi atualizado (se aplicável)?

## 💬 Comunicação

### Dúvidas e Discussões
- Use a aba **Discussions** do GitHub para questões gerais
- Para dúvidas específicas sobre termos, abra uma issue

### Código de Conduta
- Seja respeitoso e profissional
- Baseie argumentos em evidências
- Aceite feedback construtivo
- Colabore para o bem comum da pesquisa

## 🏷️ Convenções de Commit

Use conventional commits:
- `feat:` Nova funcionalidade (novo termo, nova faceta)
- `fix:` Correção (erro em termo, relação incorreta)
- `docs:` Documentação (notas de escopo, exemplos)
- `refactor:` Reestruturação (reorganização hierárquica)
- `style:` Formatação (sem mudança de conteúdo)

Exemplos:
```
feat: adiciona termo 'microtargeting político'
fix: corrige relação hierárquica de 'bot social'
docs: expande nota de escopo para 'deepfake'
```

## 📊 Validação Automática

Antes de aceitar contribuições, executamos:
1. Verificação de consistência hierárquica
2. Validação de relações bidirecionais
3. Checagem de duplicatas
4. Conformidade com ISO 25964-1:2011

## 🙏 Agradecimentos

Toda contribuição aceita será creditada no arquivo de agradecimentos do projeto.

---

**Autora e Mantenedora:** Cibele Alexandre Uchoa  
**Contato:** Via issues do GitHub  
**Licença:** CC BY-NC-SA 4.0