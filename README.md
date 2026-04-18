# Decide Bacia

Instrumento educativo e participativo para apoiar tomadas de decisão em comitês de bacia hidrográfica.

## O que é

Decide Bacia é uma ferramenta web didática que traduz uma tabela de análise multicritério em um fluxo guiado de decisão colegiada. Foi pensada como um **instrumento educativo e participativo**, para servir de base às tomadas de decisão em comitês de bacia, secretarias executivas e grupos de trabalho no processo de comparar alternativas de investimento, projetos hídricos, intervenções em saneamento, recuperação de nascentes e qualquer decisão em que múltiplas dimensões precisam ser pesadas simultaneamente.

A ferramenta roda inteiramente no navegador. Nenhum dado é enviado a servidores externos.

## Para quem é

Foi pensada para ser usada por múltiplos perfis dentro de um comitê de bacia:

- Secretarias executivas que preparam documentos técnicos para reuniões
- Representantes do poder público, de usuários da água e da sociedade civil
- Ambientalistas, produtores rurais, movimentos sociais e academia
- Facilitadores de oficinas e processos participativos

## Como usar

1. Abra o arquivo `index.html` em qualquer navegador moderno, ou acesse a versão hospedada no GitHub Pages
2. Escolha um modo de trabalho: Guiado (primeiro uso), Oficina (reuniões presenciais) ou Especialista (uso rápido)
3. Carregue um dos exemplos prontos ou comece do zero
4. Percorra as cinco etapas: critérios e pesos, alternativas, matriz de avaliação, resultado e relatório
5. Exporte em PDF, HTML, CSV ou JSON

## Funcionalidades principais

- Cinco etapas guiadas com explicações didáticas em cada uma
- Três exemplos prontos: segurança hídrica, prioridade em saneamento, recuperação de nascentes
- Editor completo de critérios, pesos e alternativas
- Matriz de avaliação com código de cores automático
- Cálculo da pontuação ponderada com interpretação automática
- Detecção de empates técnicos e divergências significativas
- Leitura interpretativa dos resultados gerada automaticamente
- Exportação em quatro formatos (PDF, HTML, CSV, JSON)
- Salvamento e retomada de projetos via arquivo JSON
- Interface responsiva, funciona em computador, tablet e celular
- Visual limpo, fundo branco, fontes grandes, acessível

## Metodologia

A base é a soma ponderada linear, a forma mais transparente e dialogável de análise multicritério. A escala vai de 0 (pior desempenho) a 100 (melhor desempenho). O resultado é interpretado em quatro faixas:

- 85 a 100: alto desempenho
- 70 a 84: bom desempenho
- 50 a 69: desempenho moderado
- 0 a 49: desempenho baixo

O resultado é um instrumento de diálogo entre atores da bacia, não um veredito técnico. Diferenças menores que 5 pontos entre alternativas são consideradas empate técnico e devem ser discutidas qualitativamente.

## Hospedagem no GitHub Pages

Este projeto é um arquivo `index.html` único e autônomo. Para hospedar no GitHub Pages:

1. Crie um repositório público no GitHub
2. Faça upload do arquivo `index.html`
3. Em Settings, Pages, escolha a branch principal como fonte
4. A plataforma ficará disponível em `https://seu-usuario.github.io/seu-repositorio`

## Tecnologia

Arquivo único HTML com CSS e JavaScript puros. Sem dependências externas, sem build, sem servidor. Funciona offline após carregar uma vez.

## Autoria

Elaborado por **Ernandes Sobreira**, Universidade do Estado de Mato Grosso (UNEMAT), 2026.

## Licença

Software livre. Pode ser adaptado para qualquer comitê, órgão gestor, universidade ou organização da sociedade civil.

## Contribuição

Sugestões e melhorias são bem-vindas via issues e pull requests no GitHub.
