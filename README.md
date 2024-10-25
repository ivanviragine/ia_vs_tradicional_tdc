# Diferenças entre modelos de AI e programação tradicional

Palestra "Diferenças entre modelos de AI e programação tradicional" apresentada no The Developer's Conference (TDC) Summit IA Brasília.

*utilize o PDF, abaixo é apenas um conversão em Markdown*

# Desenvolvimento de software tradicional versus IA

## Objetivo
Entender como a IA altera o paradigma de desenvolvimento de software e destacar as principais diferenças no desenvolvimento utilizando modelos de IA e tradicional.

## Ivan Nicola Viragine
- AI Engineer em uma startup da Califórnia
- 16 anos de experiência em desenvolvimento de software
- 8 anos de experiência com Inteligência Artificial
- Engenheiro de IA, Cientista de Dados, Desenvolvedor Full Stack, Fundador de startup, etc.
- MBA em Ciência de Dados pela USP
- Bacharel em Ciência da Computação pela UNESP

---

## Quando utilizar IA?
Problemas complexos, com muitas variáveis e grandes volumes e/ou variações de dados.

### Porque utilizar IA?
A IA busca padrões e relações que seriam muito difíceis ou até impossíveis de serem determinadas por humanos e transformadas em código.

---

## Exemplos
- **Reconhecimento de imagens**: Como escrever regras estáticas para identificar gatos?
- **Reconhecimento de voz**: Como escrever regras estáticas para identificar palavras e frases em um áudio?

---

## Onde usar modelos de IA em software?
- **Identificação e prevenção de fraudes**: apps de bancos, e-commerces
- **Recomendações**: e-commerces, ads, redes sociais
- **Análise de sentimentos**: reviews, SAC
- **Tradução de idiomas**: apps de tradução, SAC
- **Diagnóstico médico**: apps de saúde, hospitais
- **Reconhecimento de voz**: assistentes virtuais, acessibilidade
- **Reconhecimento de imagens**: segurança, redes sociais
- **Sumarização de texto**: apps de notícias, SAC
- **Chatbots**: SAC, e-commerces
- **Otimização de processos**: indústrias, logística
- **Segurança**: controle de acesso, reconhecimento facial, prevenção de roubos

---

## Diferenças entre Desenvolvimento Tradicional e com IA

### Natureza das entradas
- **Tradicional**: Entradas previsíveis e controladas via GUI.
- **IA**: Entradas variadas e imprevisíveis, como texto livre, imagens, áudio.

### Natureza das saídas
- **Tradicional**: Determinística - mesma entrada produz mesma saída.
- **IA**: Não determinística - pequenas variações na entrada podem gerar variações imprevisíveis na saída.

### Dependência de Dados
- **Tradicional**: Dependente de dados, mas com foco em lógica e estrutura.
- **IA**: Totalmente dependente de dados - qualidade diretamente ligada aos dados.

### Interpretabilidade
- **Tradicional**: Caminho de execução claro e previsível.
- **IA**: "Caixa preta" - difícil entender como chegou a determinada decisão.

### Atualização e manutenção
- **Tradicional**: Atualizações e correções diretas no código.
- **IA**: Necessário retreino com novos dados; processo complexo e imprevisível.

### Depuração de Erros
- **Tradicional**: Mais fácil identificar e corrigir erros.
- **IA**: Erros difíceis de identificar e corrigir - pode exigir ajustes de dados e modelo.

### Escalabilidade
- **Tradicional**: Escala previsível com otimizações de código.
- **IA**: Escalabilidade menos previsível devido à natureza probabilística das saídas.

### Viés e Justiça
- **Tradicional**: Viés está no código e pode ser corrigido diretamente.
- **IA**: Viés introduzido nos dados, difícil de identificar e corrigir.

### Alucinações
- **Tradicional**: Saídas inesperadas resultam de erros no código.
- **IA**: Alucinações podem surgir e são difíceis de corrigir.

### Versionamento
- **Tradicional**: Versionamento direto e reversível.
- **IA**: Versionamento possível, mas retreino pode alterar o modelo.

### Testes
- **Tradicional**: Testes diretos com caminhos predefinidos.
- **IA**: Testes probabilísticos com métricas de avaliação.

### Feedback
- **Tradicional**: Feedback geralmente em forma de bugs.
- **IA**: Feedback direto do usuário fundamental para melhorias.

### Recursos
- **Tradicional**: Notebooks comuns suficientes para desenvolvimento.
- **IA**: Necessita GPUs/TPUs para treino e inferência, exigindo mais recursos.

---

## Ciclo de vida

### Tradicional
1. Análise de requisitos
2. Desenho de arquitetura
3. Desenvolvimento
4. Testes
5. Deploy
6. Manutenção e atualizações

### IA
1. Análise de requisitos
2. Coleta e preparação de dados
3. Treinamento/Fine-tuning do modelo
4. Avaliação e validação do modelo
5. Deploy do modelo
6. Monitoramento e re-treinamento

### IA (LLMs)
1. Análise de requisitos
2. Coleta e preparação de dados
3. Fine-tuning do modelo ou prompt engineering
4. Avaliação e validação do modelo
5. Deploy do modelo/API
6. Monitoramento e re-fine-tuning

---

## Obrigado!
