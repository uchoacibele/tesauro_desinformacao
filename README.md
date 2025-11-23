# Tesauro de Desinformação e Conteúdos Falsos Online

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![ISO 25964-1:2011](https://img.shields.io/badge/ISO-25964--1:2011-blue.svg)](https://www.iso.org/standard/53657.html)
[![Version](https://img.shields.io/badge/version-1.0-green.svg)](https://github.com/uchoacibele/tesauro_desinformacao/releases)

## 📚 Sobre

Tesauro especializado em desinformação e conteúdos falsos online, desenvolvido para pesquisa científica em jurimetria e ciência de dados. Este vocabulário controlado segue rigorosamente o padrão **ISO 25964-1:2011** para a construção de tesauros.

## 🎯 Objetivo

Fornecer terminologia padronizada e estruturada para pesquisas sobre desinformação, com foco especial em:
- Estudos sobre manipulação informacional
- Pesquisas sobre impactos democráticos da desinformação
- Investigações sobre respostas institucionais a ataques informacionais

## 📊 Conteúdo

- **235+ descritores** especializados
- **Estrutura hierárquica** com relações TG/TE (Termo Genérico/Específico)
- **Relações associativas** (TR - Termo Relacionado)
- **Relações de equivalência** (USE/UP)
- **Notas de escopo** detalhadas para cada termo
- **Seção jurídica** com terminologia do contexto brasileiro
- **7 facetas temáticas** organizadas
- **Índice bilíngue** português-inglês

## 📁 Estrutura do Repositório

```
tesauro_desinformacao/
│
├── README.md                           # Este arquivo
├── LICENSE                            # Licença CC BY-SA 4.0
├── CONTRIBUTING.md                    # Diretrizes para contribuição
├── CHANGELOG.md                       # Histórico de versões
│
├── tesauro_desinformacao_ISO.md      # Tesauro completo em Markdown
├── tesauro_desinformacao_dados.csv   # Base de dados em CSV
│
├── docs/                              # Documentação adicional
│   ├── metodologia.md                # Metodologia de construção
│   └── casos_uso.md                  # Exemplos de aplicação
│
└── scripts/                           # Scripts de manutenção
    ├── validacao.py                   # Validação de consistência
    └── exportacao.py                  # Exportação para outros formatos
```

## 🚀 Como Usar

### Consulta direta
Navegue pelo arquivo `tesauro_desinformacao_ISO.md` para consultar termos e suas relações.

### Importação em sistemas
Use o arquivo `tesauro_desinformacao_dados.csv` para importar em:
- Sistemas de gestão de vocabulários controlados
- Ferramentas de indexação
- Plataformas de gestão de conhecimento

### Integração em pesquisas
```python
import pandas as pd

# Carregar o tesauro
tesauro = pd.read_csv('tesauro_desinformacao_dados.csv')

# Buscar termos relacionados
termo = 'Desinformação política'
relacionados = tesauro[tesauro['Termo'] == termo]
```

## 📖 Como Citar

### ABNT
UCHOA, Cibele Alexandre. Tesauro de Desinformação e Conteúdos Falsos Online: vocabulário controlado para pesquisa científica. Versão 1.0. **GitHub**, 2025. DOI: 10.5281/zenodo.17684945. Disponível em: https://github.com/uchoacibele/tesauro_desinformacao. Acesso em: [data de acesso].

### APA
Uchoa, C. A. (2025). Tesauro de Desinformação e Conteúdos Falsos Online (Version 1.0) [Dataset]. **GitHub**. https://github.com/uchoacibele/tesauro_desinformacao

### BibTeX
```bibtex
@misc{uchoa2025tesauro,
  author = {Uchoa, Cibele Alexandre},
  title = {Tesauro de Desinformação e Conteúdos Falsos Online},
  year = {2025},
  version = {1.0},
  publisher = {GitHub},
  url = {https://github.com/uchoacibele/tesauro_desinformacao}
}
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Por favor, leia o arquivo [CONTRIBUTING.md](CONTRIBUTING.md) para diretrizes sobre como contribuir.

### Formas de contribuir:
- 🐛 Reportar erros ou inconsistências
- 💡 Sugerir novos termos
- 📝 Melhorar definições existentes
- 🌍 Adicionar traduções
- 📚 Compartilhar casos de uso

## 📄 Licença

Este trabalho está licenciado sob [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Isso significa que você pode compartilhar e adaptar o material, desde que:
- Dê crédito apropriado
- Não use para fins comerciais
- Distribua sob a mesma licença

## 👤 Autora

**Cibele Alexandre Uchoa**  
- GitHub: [@uchoacibele](https://github.com/uchoacibele)
- ORCID: https://orcid.org/0000-0001-7971-496X
- E-mail: uchoa.cibelea@gmail.com
- Afiliação: Universidade de Fortaleza

## 🙏 Agradecimentos

Este trabalho foi desenvolvido com o apoio da **Fundação Cearense de Apoio ao Desenvolvimento Científico e Tecnológico (FUNCAP)**, que financiou a pesquisa doutoral da qual este tesauro é parte integrante.

Agradecimentos especiais à Universidade de Fortaleza pelo suporte institucional.

## 📊 Estatísticas

![Terms](https://img.shields.io/badge/Termos-235+-blue)
![Categories](https://img.shields.io/badge/Categorias-7-green)
![Languages](https://img.shields.io/badge/Idiomas-2-yellow)
![ISO Compliant](https://img.shields.io/badge/ISO-Compliant-success)

## 🔗 Links Relacionados

- [ISO 25964-1:2011 Standard](https://www.iso.org/standard/53657.html)
- [SKOS - Simple Knowledge Organization System](https://www.w3.org/2004/02/skos/)
- [First Draft News](https://firstdraftnews.org/)
- [UNESCO MIL](https://www.unesco.org/en/media-information-literacy)

---

**Última atualização:** 11 de Novembro de 2025  
**Versão:** 1.0.0