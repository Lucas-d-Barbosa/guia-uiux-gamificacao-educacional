# Guia de Diretrizes de UI/UX para Aplicações Educacionais Gamificadas

**Versão 1.0.0 — 16 de novembro de 2026**  
**Autores:** Francisco Lucas dos Santos Barbosa; Jhonatta Pietro de Oliveira

## 1. Finalidade do guia

Este guia foi elaborado para apoiar **designers, desenvolvedores, educadores e demais profissionais** envolvidos na criação ou avaliação de aplicações educacionais gamificadas destinadas ou acessíveis a crianças e adolescentes.

Seu propósito não é eliminar a gamificação, mas orientar sua utilização de forma **subordinada aos objetivos educacionais** e compatível com autonomia, motivação, bem-estar e proteção do público infantojuvenil.

O guia deriva de uma pesquisa aplicada, qualitativa, descritiva e propositiva, baseada em inspeção das plataformas **Duolingo, Matific Play e Kahoot!**. A análise considerou feedback, progressão, recompensas, competição, mecanismos de continuidade, controles da experiência, privacidade e recursos comerciais.

## 2. Como interpretar “segurança psicológica” neste guia

O termo **segurança psicológica** é utilizado em sentido operacional para designar condições de design relacionadas à **autonomia, motivação e bem-estar do estudante**. O conceito não representa diagnóstico clínico, mensuração de estados psicológicos nem comprovação de efeitos causais sobre crianças ou adolescentes.

## 3. Como usar o guia

O guia pode ser aplicado durante concepção, prototipação, revisão de interface ou avaliação de um produto existente.

Para cada funcionalidade analisada:

1. identifique o objetivo educacional da experiência;
2. percorra os principais estados de interação;
3. observe acertos, erros, progresso, recompensas, competição e mecanismos de continuidade;
4. examine configurações, privacidade, exposição social e recursos comerciais;
5. aplique as diretrizes D1 a D12;
6. registre evidências e decisões usando o `CHECKLIST.md`;
7. trate itens “Parcial” e “Não atende” como pontos de revisão, não como conclusões automáticas de inadequação jurídica ou pedagógica.

## 4. Princípios gerais

Antes das diretrizes específicas, quatro princípios orientam a leitura do guia:

- **Contexto importa:** a presença de um elemento de gamificação não o torna automaticamente positivo ou negativo.
- **Função importa:** pontos, rankings, notificações ou recompensas devem ser avaliados pelo papel que desempenham na experiência.
- **Usuários diferem:** uma mesma configuração pode ser percebida de formas distintas por diferentes estudantes.
- **Proteção deve ser prevista desde a concepção:** autonomia, controle, privacidade e tempo de uso não devem ser tratados apenas como correções posteriores.

---

# Dimensão pedagógica

## D1 — Tratamento do erro

**Diretriz:** oferecer informação, orientação ou nova tentativa após o erro.

### Objetivo

Manter o estudante ativo diante do problema e transformar o erro em oportunidade de continuidade da interação pedagógica.

### Aplicar

- informar de forma compreensível que a resposta não foi aceita;
- quando pertinente, indicar o elemento que precisa ser revisto;
- permitir nova tentativa ou retomada da situação;
- diferenciar feedback de correção de simples punição ou perda de pontos;
- oferecer explicações adicionais quando elas contribuírem para a compreensão do conteúdo.

### Evitar

- feedback de erro limitado a efeitos visuais sem informação útil;
- bloquear a continuidade sem indicar o que pode ser feito a seguir;
- utilizar o erro apenas como gatilho para penalizações, perda de recursos ou pressão por repetição;
- expor o estudante publicamente por erros individuais.

### Perguntas de verificação

- O estudante entende por que a resposta foi considerada incorreta?
- Existe uma ação clara após o erro?
- Há possibilidade de correção ou nova tentativa quando isso faz sentido pedagogicamente?
- O feedback acrescenta informação ou apenas comunica fracasso?

**Fundamentação:** a perspectiva piagetiana enfatiza a atividade do sujeito na construção do conhecimento. Sailer et al. (2017) também relacionam formas de feedback de desempenho à percepção de competência, sem tratar essa relação como automática.

---

## D2 — Integração dos elementos lúdicos

**Diretriz:** relacionar elementos lúdicos ao conteúdo e aos objetivos educacionais.

### Objetivo

Evitar que a gamificação se transforme em uma camada independente da aprendizagem ou em um objetivo paralelo à atividade educacional.

### Aplicar

- vincular desafios, narrativas, representações visuais e recompensas ao percurso pedagógico;
- fazer com que elementos lúdicos ajudem a compreender, praticar ou contextualizar o conteúdo;
- utilizar ambientação e representação visual quando contribuírem para a ação do estudante sobre a tarefa;
- verificar se o elemento gamificado continua fazendo sentido quando o objetivo educacional é explicitado.

### Evitar

- adicionar pontos, animações ou recompensas sem relação clara com a atividade;
- tornar o sistema de jogo mais central que a aprendizagem;
- introduzir elementos que distraiam da tarefa principal;
- infantilizar a experiência sem considerar o perfil do público.

### Perguntas de verificação

- O elemento lúdico ajuda a realizar ou compreender a atividade?
- A experiência ainda prioriza o objetivo educacional?
- A gamificação acrescenta sentido ou apenas estímulos?
- O nível de ludicidade é adequado ao público e ao contexto?

**Fundamentação:** Piaget (1975; 1976) sustenta o valor da ação e da atividade lúdica no desenvolvimento; Hyrynsalmi, Smed e Kimppa (2017) alertam para situações em que elementos gamificados desviam a atenção do propósito principal.

---

## D3 — Indicadores de progresso

**Diretriz:** tornar compreensíveis o avanço e o desempenho do estudante.

### Objetivo

Permitir que o usuário compreenda onde está, o que já concluiu e o que falta para atingir o objetivo educacional.

### Aplicar

- apresentar progresso de forma clara e proporcional à atividade;
- distinguir progresso individual de comparação com outros usuários;
- explicar o significado de pontos, XP, etapas, níveis ou outros indicadores;
- relacionar indicadores a objetivos concretos de aprendizagem ou conclusão.

### Evitar

- indicadores que não deixam claro o que representam;
- excesso de métricas competindo pela atenção;
- fazer do ranking o único sinal de progresso;
- criar metas artificiais que não correspondam a avanço real na atividade.

### Perguntas de verificação

- O usuário entende o que o indicador mede?
- É possível reconhecer avanço sem comparar-se com outras pessoas?
- O indicador se relaciona ao objetivo da atividade?
- A quantidade de métricas é proporcional à necessidade de informação?

---

# Dimensão motivacional

## D4 — Recompensas

**Diretriz:** manter recompensas subordinadas à finalidade educacional.

### Objetivo

Utilizar recompensas como apoio à compreensão de avanço e conclusão, sem transformá-las no objetivo principal da experiência.

### Aplicar

- associar recompensas a ações relevantes para a atividade educacional;
- deixar claro o que foi realizado para obter a recompensa;
- combinar reconhecimento com feedback informativo quando possível;
- avaliar frequência, quantidade e centralidade de pontos, medalhas, moedas e outros incentivos.

### Evitar

- recompensar apenas tempo de permanência;
- criar ciclos em que o usuário retorna principalmente para não perder recompensas;
- fazer com que moedas, pontos ou colecionáveis substituam o foco no conteúdo;
- utilizar perdas ou ameaças de perda como principal motivador de continuidade.

### Perguntas de verificação

- A recompensa reconhece uma ação educacional significativa?
- O estudante compreenderia o próprio progresso sem a recompensa?
- Há risco de o incentivo tornar-se mais importante que a atividade?
- A frequência das recompensas é proporcional ao objetivo pedagógico?

**Fundamentação:** Sailer et al. (2017) relacionam pontos, medalhas e indicadores de desempenho à percepção de competência; Hyrynsalmi, Smed e Kimppa (2017) discutem riscos de condicionamento a incentivos externos.

---

## D5 — Comparação social

**Diretriz:** evitar rankings como única referência de sucesso.

### Objetivo

Permitir que elementos competitivos coexistam com referências individuais de progresso e desenvolvimento.

### Aplicar

- combinar classificação com indicadores individuais;
- explicar os critérios usados para ordenar participantes;
- usar competição apenas quando ela fizer sentido para a atividade;
- considerar modos alternativos baseados em cooperação, metas pessoais ou objetivos compartilhados;
- avaliar se a posição social é necessária em todos os momentos da experiência.

### Evitar

- tornar posição em ranking equivalente a aprendizagem;
- exibir comparação social permanente sem necessidade pedagógica;
- expor desempenho individual de forma desproporcional;
- utilizar competição como único mecanismo de motivação.

### Perguntas de verificação

- O usuário consegue perceber progresso sem depender do ranking?
- A comparação social tem função clara na atividade?
- Existem alternativas para usuários que não desejam competir?
- A exposição de desempenho é proporcional e compreensível?

**Fundamentação:** Sailer et al. (2017) distinguem mecanismos de desempenho de mecanismos de relacionamento social; Oliveira et al. (2023) reforçam que usuários podem responder de formas distintas à gamificação.

---

## D6 — Diversidade de usuários

**Diretriz:** considerar diferentes perfis, preferências e formas de interação.

### Objetivo

Evitar pressupor que uma única configuração de gamificação será adequada ou motivadora para todos os estudantes.

### Aplicar

- oferecer ajustes de estímulos quando viável;
- considerar diferentes níveis de familiaridade, idade e preferências;
- avaliar se competição, animações, sons e notificações podem ser reduzidos ou desativados;
- testar a compreensibilidade dos elementos com diferentes perfis de usuário;
- separar adaptação útil de personalização meramente cosmética.

### Evitar

- tratar “o estudante” como um perfil único;
- assumir que mais personalização sempre produz melhores resultados;
- impor a mesma intensidade de estímulos a todos;
- usar tipologias de usuário como explicação definitiva do comportamento.

### Perguntas de verificação

- O sistema permite acomodar preferências diferentes?
- Estímulos podem ser reduzidos sem prejudicar a atividade principal?
- A experiência continua compreensível para perfis diversos?
- A personalização tem uma finalidade verificável?

**Fundamentação:** Oliveira et al. (2023) apontam evidências ainda limitadas e contraditórias sobre personalização da gamificação, reforçando a necessidade de cautela e contextualização.

---

## D7 — Continuidade da prática

**Diretriz:** evitar que mecanismos de continuidade pressionem a permanência ou o retorno.

### Objetivo

Distinguir apoio à formação de rotina de mecanismos que transformam o retorno frequente em obrigação ou pressão desproporcional.

### Aplicar

- deixar explícito que o usuário pode encerrar a atividade sem punição desproporcional;
- avaliar metas diárias, sequências, missões, lembretes e notificações em conjunto;
- oferecer opções para reduzir ou desativar estímulos de retorno;
- preservar pontos naturais de parada;
- comunicar consequências de forma neutra e compreensível.

### Evitar

- ocultar pontos naturais de parada;
- acionar conteúdo adicional automaticamente sem solicitação clara;
- pressionar o usuário com perda de sequência, recurso ou recompensa;
- usar notificações excessivas para induzir retorno;
- recompensar permanência pelo simples tempo de uso.

### Perguntas de verificação

- É fácil interromper a experiência?
- Existe pressão para retornar apenas para evitar uma perda?
- Há pontos naturais e visíveis de encerramento?
- Notificações e missões podem ser controladas?

**Fundamentação jurídica:** a Lei nº 15.211/2025 estabelece salvaguardas relacionadas ao uso compulsivo e à extensão artificial do tempo de uso. O Decreto nº 12.880/2026 menciona, entre outros mecanismos, ocultação de pontos naturais de parada, acionamento de novos conteúdos sem solicitação, recompensas pelo tempo de uso e notificações excessivas.

---

# Dimensão de proteção e autonomia

## D8 — Autonomia

**Diretriz:** preservar a capacidade de escolha e de interrupção do uso.

### Objetivo

Garantir que a interface não utilize seus elementos para enfraquecer a capacidade do usuário de decidir, configurar ou interromper a experiência.

### Aplicar

- oferecer escolhas compreensíveis e reversíveis;
- permitir pausa, saída e retomada sem penalizações desproporcionais;
- evitar opções pré-selecionadas que enfraqueçam salvaguardas;
- apresentar consequências de decisões de forma clara;
- diferenciar orientação pedagógica de manipulação da escolha.

### Evitar

- esconder ações de saída;
- dificultar a alteração de configurações protetivas;
- usar linguagem culpabilizante para impedir interrupção;
- estruturar escolhas para favorecer sistematicamente mais tempo de uso.

### Perguntas de verificação

- O usuário consegue parar quando deseja?
- As escolhas importantes são compreensíveis?
- É fácil alterar uma decisão anterior?
- A interface respeita escolhas que reduzem engajamento ou exposição?

**Fundamentação:** Ryan e Deci (2000) tratam autonomia como necessidade psicológica básica. A Lei nº 15.211/2025 também protege autonomia, tomada de decisão e escolha em interfaces digitais acessíveis a crianças e adolescentes.

---

## D9 — Tempo de utilização

**Diretriz:** evitar o prolongamento artificial do tempo de uso.

### Objetivo

Assegurar que o tempo de interação decorra da atividade educacional e da escolha do usuário, e não de mecanismos desenhados principalmente para estender a sessão.

### Aplicar

- permitir visualizar ou acompanhar tempo de uso quando pertinente;
- oferecer limites, pausas e pontos de encerramento claros;
- evitar encadeamento automático de atividades sem decisão do usuário;
- considerar a duração da atividade no projeto de metas, missões e recompensas;
- revisar notificações e recompensas que incentivem sessões mais longas.

### Evitar

- autoplay ou continuidade automática sem necessidade educacional;
- conteúdos que surgem continuamente sem ponto claro de parada;
- recompensas baseadas apenas em tempo de permanência;
- mecanismos que dificultem perceber quanto tempo já passou.

### Perguntas de verificação

- O usuário percebe quando uma atividade termina?
- Há mecanismos que estendem a sessão sem solicitação explícita?
- O tempo de uso é proporcional ao objetivo da tarefa?
- Existem recursos de acompanhamento ou limitação quando necessários?

---

## D10 — Controles da experiência

**Diretriz:** oferecer controles claros sobre notificações, estímulos e configurações.

### Objetivo

Permitir que o usuário, responsável ou instituição ajuste aspectos que alteram intensidade, exposição e continuidade da experiência.

### Aplicar

- organizar configurações em linguagem compreensível;
- disponibilizar controles para notificações, sons, vibrações, animações e estímulos sociais quando aplicável;
- manter configurações protetivas fáceis de localizar;
- explicar o efeito de cada opção;
- evitar que atualizações revertam silenciosamente escolhas relevantes do usuário.

### Evitar

- esconder configurações importantes em menus excessivamente profundos;
- usar nomes ambíguos para controles de privacidade ou notificações;
- tornar recursos competitivos impossíveis de reduzir quando não são essenciais;
- exigir conhecimento técnico para compreender uma escolha básica.

### Perguntas de verificação

- As configurações importantes são fáceis de encontrar?
- O usuário entende o efeito de cada controle?
- É possível reduzir estímulos não essenciais?
- As escolhas persistem de maneira previsível?

---

## D11 — Privacidade e exposição social

**Diretriz:** disponibilizar controles adequados sobre informações, atividades e desempenho.

### Objetivo

Evitar que participação em recursos sociais implique exposição desnecessária de dados, atividades ou desempenho.

### Aplicar

- informar o que fica visível para outras pessoas;
- permitir ajustar visibilidade de atividade e desempenho quando aplicável;
- utilizar configurações protetivas por padrão para o público infantojuvenil;
- limitar dados exibidos em rankings e recursos sociais ao necessário;
- tornar opções de privacidade compreensíveis e acessíveis.

### Evitar

- tornar atividades públicas sem informação clara;
- expor histórico ou desempenho além do necessário;
- misturar consentimento para recurso social com outras funcionalidades não relacionadas;
- depender apenas de linguagem jurídica para explicar privacidade.

### Perguntas de verificação

- O usuário sabe quem pode ver suas informações e desempenho?
- É possível reduzir a exposição social?
- A configuração padrão é protetiva?
- O recurso social utiliza apenas os dados necessários?

---

## D12 — Recursos comerciais

**Diretriz:** evitar interferência de compras e recursos comerciais no percurso educacional.

### Objetivo

Preservar a finalidade educacional quando moedas virtuais, assinaturas, compras ou benefícios pagos estiverem integrados à experiência.

### Aplicar

- separar claramente conteúdo educacional de oferta comercial;
- informar quando um item depende de pagamento real;
- evitar associar compra a superioridade acadêmica ou aprovação social;
- revisar se recursos pagos alteram de forma desproporcional o acesso à atividade principal;
- prever controles compatíveis com o público e o contexto de uso.

### Evitar

- transformar compra em condição implícita para continuar aprendendo;
- usar escassez, urgência ou perda como principal pressão comercial;
- misturar moeda virtual e dinheiro real de modo pouco compreensível;
- utilizar desempenho ou vulnerabilidade momentânea para apresentar oferta comercial.

### Perguntas de verificação

- O estudante entende quando uma ação envolve dinheiro real?
- A oferta comercial interrompe ou desvia a atividade educacional?
- A compra é claramente opcional?
- Há salvaguardas adequadas ao público infantojuvenil?

---

# 5. Matriz de síntese

| Código | Dimensão | Diretriz | Síntese operacional |
|---|---|---|---|
| D1 | Pedagógica | Tratamento do erro | Informar, orientar ou permitir nova tentativa. |
| D2 | Pedagógica | Integração dos elementos lúdicos | Relacionar a gamificação ao conteúdo e ao objetivo educacional. |
| D3 | Pedagógica | Indicadores de progresso | Tornar avanço e desempenho compreensíveis. |
| D4 | Motivacional | Recompensas | Subordinar incentivos à finalidade educacional. |
| D5 | Motivacional | Comparação social | Não usar rankings como única referência de sucesso. |
| D6 | Motivacional | Diversidade de usuários | Considerar perfis, preferências e formas de interação distintas. |
| D7 | Motivacional | Continuidade da prática | Evitar pressão desproporcional por permanência ou retorno. |
| D8 | Proteção e autonomia | Autonomia | Preservar escolha, pausa e interrupção. |
| D9 | Proteção e autonomia | Tempo de utilização | Evitar prolongamento artificial do uso. |
| D10 | Proteção e autonomia | Controles da experiência | Oferecer controles claros de estímulos e configurações. |
| D11 | Proteção e autonomia | Privacidade e exposição social | Controlar visibilidade de informações, atividades e desempenho. |
| D12 | Proteção e autonomia | Recursos comerciais | Evitar que compras interfiram no percurso educacional. |

# 6. Limites de aplicação

Este guia deve ser aplicado dentro de seu escopo:

- não substitui testes de usabilidade com usuários reais;
- não comprova efeitos pedagógicos ou psicológicos;
- não constitui diagnóstico clínico;
- não constitui auditoria jurídica nem determinação de conformidade legal;
- não representa descrição exaustiva de Duolingo, Matific ou Kahoot!;
- não foi submetido, nesta versão, a validação empírica posterior com designers, desenvolvedores, educadores ou crianças e adolescentes;
- interfaces digitais podem mudar após o período de coleta que originou o produto.

# 7. Referências

BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. *Interação humano-computador*. Rio de Janeiro: Elsevier, 2010.

BRASIL. Lei nº 15.211, de 17 de setembro de 2025. Dispõe sobre a proteção de crianças e adolescentes em ambientes digitais (Estatuto Digital da Criança e do Adolescente). *Diário Oficial da União*, Brasília, DF, 17 set. 2025.

BRASIL. Decreto nº 12.880, de 18 de março de 2026. Regulamenta a Lei nº 15.211, de 17 de setembro de 2025, que dispõe sobre a proteção de crianças e adolescentes em ambientes digitais, e institui a Política Nacional de Promoção e Proteção dos Direitos da Criança e do Adolescente no Ambiente Digital. *Diário Oficial da União*, Brasília, DF, 18 mar. 2026.

HYRYNSALMI, Sami; SMED, Jouni; KIMPPA, Kai K. The dark side of gamification: how we should stop worrying and study also the negative impacts of bringing game design elements to everywhere. In: INTERNATIONAL GAMIFIN CONFERENCE, 1., 2017, Pori. *Proceedings [...]*. [S. l.]: CEUR-WS, 2017. p. 96-104.

OLIVEIRA, Wilk et al. Tailored gamification in education: a literature review and future agenda. *Education and Information Technologies*, v. 28, n. 1, p. 373-406, 2023. DOI: 10.1007/s10639-022-11122-4.

PIAGET, Jean. *A formação do símbolo na criança: imitação, jogo e sonho, imagem e representação*. 2. ed. Rio de Janeiro: Zahar, 1975.

PIAGET, Jean. *Psicologia e pedagogia*. 4. ed. Rio de Janeiro: Forense Universitária, 1976.

RYAN, Richard M.; DECI, Edward L. Self-determination theory and the facilitation of intrinsic motivation, social development, and well-being. *American Psychologist*, v. 55, n. 1, p. 68-78, 2000. DOI: 10.1037/0003-066X.55.1.68.

SAILER, Michael et al. How gamification motivates: an experimental study of the effects of specific game design elements on psychological need satisfaction. *Computers in Human Behavior*, v. 69, p. 371-380, 2017. DOI: 10.1016/j.chb.2016.12.033.

# 8. Citação e licença

Para citar este produto, consulte `CITATION.cff`.

Este guia é disponibilizado sob a licença **Creative Commons Attribution 4.0 International (CC BY 4.0)**.
