# CapelanIA – Orientador de Projetos

Plugin baseado somente em skill para orientar, passo a passo, a construção e a revisão de projetos de capelania escolar, projetos missionários para a cidade e projetos híbridos.

## O que o plugin faz

- diagnostica necessidades e organiza evidências e pendências;
- define público, objetivos e competências socioemocionais;
- relaciona fundamentação bíblico-teológica e prática responsável;
- propõe metodologias e atividades adequadas à idade;
- estrutura cronograma, equipe, recursos e orçamento;
- revisa proteção, riscos, liberdade religiosa e prevenção de proselitismo;
- cria indicadores e formas de avaliação;
- entrega minutas sujeitas à revisão humana e à aprovação institucional.

O CapelanIA entende capelania como presença, amizade genuína, escuta, cuidado e construção intencional de relacionamentos. Não substitui profissionais de saúde, proteção, assistência social, assessoria jurídica, gestão escolar ou liderança institucional.

## Funcionamento

O plugin não possui servidor próprio, API externa, MCP ou conexão com outros serviços. Após a instalação, a conversa acontece no ChatGPT da própria pessoa. O site institucional apresenta o projeto, as políticas e o direcionamento para a instalação oficial; não hospeda a conversa.

## Estrutura

- `plugins/capelania-orientador-de-projetos/plugin.json`: manifesto portátil.
- `plugins/capelania-orientador-de-projetos/.codex-plugin/plugin.json`: compatibilidade com Codex.
- `plugins/capelania-orientador-de-projetos/skills/`: skill e referências.
- `plugins/capelania-orientador-de-projetos/assets/`: identidade visual.
- `submission/`: materiais de listagem e casos de teste para revisão.

## Uso local

O arquivo `.agents/plugins/marketplace.json` mantém a configuração do marketplace local deste repositório. Depois de instalar o plugin, inicie uma nova conversa e peça, por exemplo:

> Oriente-me passo a passo na criação de um projeto de capelania escolar.

## Publicação

A presença deste repositório no GitHub não significa aprovação ou publicação no diretório público. A submissão, análise e publicação serão realizadas separadamente pelo portal oficial da OpenAI.

## Responsáveis

- Publicador: Instituto Alfa e Ômega
- Responsável e desenvolvedor: Educador Marcos
- Site: https://iacapelania.oscalfaeomega.org
- Suporte: https://iacapelania.oscalfaeomega.org/suporte

## Licença

Distribuído sob a licença MIT. Consulte [LICENSE](LICENSE).
