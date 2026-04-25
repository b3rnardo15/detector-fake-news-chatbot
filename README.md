# Detector de Fake News com Inteligência Artificial

Este projeto é um chatbot inteligente desenvolvido para a disciplina de **Inteligência Artificial**, focado na verificação de veracidade de notícias sobre saúde e bem-estar no contexto brasileiro.

##  Visão Geral

A disseminação em massa de notícias falsas (*fake news*) relacionadas à saúde distorce a percepção pública e compromete a saúde coletiva. Este projeto utiliza modelos de Processamento de Linguagem Natural (NLP) de última geração para identificar padrões linguísticos típicos de desinformação, como curas milagrosas e teorias da conspiração.

### Diferencial da Proposta
- **Foco em Português Brasileiro:** Utilização do modelo **BERTimbau (Large)**.
- **Domínio Específico:** Especializado em conteúdos de saúde e bem-estar.
- **Acessibilidade:** Interface via Chatbot (Telegram/WhatsApp) para facilitar o combate à desinformação em tempo real.

##  Componentes Técnicos

- **Modelo de IA:** Implementação de um classificador binário baseado em Transformers (BERTimbau).
- **Dataset:** Utilização do *Fake.br-Corpus* (NILC-USP) com fine-tuning em dados de fontes oficiais (OMS, Ministério da Saúde).
- **Interface:** Integração via API (ex: `python-telegram-bot`).
- **Métricas de Sucesso:** Foco em Acurácia, F1-Score e, crucialmente, na redução de **Falsos Positivos**.

##  Estrutura do Repositório

- `src/`: Código-fonte (API, Chatbot, Modelos e Utils).
- `docs/`: Documentação técnica e relatórios.
- `tests/`: Testes automatizados.
- `data/`: Armazenamento de datasets (não versionados).
- `notebooks/`: Experimentos e análises de dados.

##  Equipe
- Bernardo Simões
- Jose Fernando
- Marcello Henrique
- Glewbber Spindola

##  Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
