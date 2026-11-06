# Ozzy Finances — Análise e Discussões de UX/UI

**Projeto:** Ozzy Finances  
**Etapa:** Análise, concepção e prototipação da experiência do usuário  
**Plataforma considerada:** Aplicação mobile  
**Dimensão de referência dos wireframes:** 390 × 844 px  
**Ferramenta de prototipação:** Figma  

---

## 1.1 Problema e Usuário

### Qual problema o produto resolve?

O Ozzy Finances foi concebido para ajudar microempreendedores individuais (MEIs), profissionais autônomos e pequenos prestadores de serviços a controlar melhor as finanças de suas atividades profissionais.

Durante a etapa de Product Discovery, identificou-se que parte desse público utiliza métodos informais ou irregulares para registrar suas movimentações financeiras. Anotações, cadernos, planilhas pouco atualizadas e até a ausência de um controle estruturado podem dificultar a compreensão da situação financeira do negócio.

O problema não se limita ao registro de receitas e despesas. Também envolve transformar essas informações em uma visão compreensível do resultado financeiro, permitindo identificar custos, lucro, dinheiro disponível e possíveis dificuldades na gestão.

A formulação do problema que orientou o desenvolvimento da solução foi:

> Pequenos empreendedores que controlam as finanças de maneira manual ou irregular têm dificuldade para manter os registros atualizados e transformar as movimentações em uma visão clara de receitas, despesas e lucro. Essa falta de clareza pode dificultar decisões como definir preços, controlar custos, retirar dinheiro para uso pessoal e avaliar o resultado de cada serviço ou produto.

### Quem é o usuário?

O público inicialmente considerado compreende:

- Microempreendedores individuais (MEIs);
- Profissionais autônomos;
- Prestadores de serviços;
- Freelancers;
- Pequenos comerciantes e produtores.

A investigação inicial sugeriu uma oportunidade mais relevante entre pequenos prestadores de serviços e profissionais autônomos que não mantêm um controle financeiro consistente e têm dificuldade para identificar quanto realmente lucram.

Esse público pode apresentar diferentes níveis de familiaridade com ferramentas digitais e conceitos financeiros. Por isso, a solução foi pensada para reduzir a necessidade de conhecimentos técnicos ou contábeis para realizar tarefas cotidianas.

### Quais dores e necessidades existem?

As principais dificuldades consideradas na concepção do produto foram:

**1. Mistura entre finanças pessoais e profissionais**

O usuário pode ter dificuldade para distinguir o dinheiro destinado às despesas pessoais daquele utilizado na atividade profissional. Isso prejudica a compreensão do resultado real do negócio.

**2. Dificuldade para manter os registros atualizados**

A falta de tempo, o esquecimento e o esforço necessário para registrar cada movimentação podem fazer com que o controle financeiro seja abandonado ou realizado de maneira irregular.

**3. Dificuldade para compreender o resultado financeiro**

Mesmo quando existem registros, nem sempre o usuário consegue identificar facilmente quanto recebeu, quanto gastou e quanto efetivamente sobrou.

**4. Complexidade das ferramentas disponíveis**

Ferramentas financeiras com muitos recursos, termos técnicos ou processos extensos podem representar uma barreira para usuários que precisam apenas de um controle simples e objetivo.

**5. Necessidade de apoio à tomada de decisão**

O usuário precisa transformar os registros em informações que ajudem a compreender custos, preços, lucro e disponibilidade financeira.

A proposta do Ozzy Finances procura responder a essas necessidades por meio de uma experiência simples de registro, organização e visualização das movimentações financeiras, com apoio de inteligência artificial.

**Relação com a validação:** na pesquisa inicial de interesse, foram obtidas 15 respostas: 6 pessoas demonstraram interesse em testar gratuitamente, 6 responderam “talvez” e 3 não demonstraram interesse no momento. Esses resultados sustentaram a continuidade do projeto com ajustes, mas não comprovam, isoladamente, a adoção ou a viabilidade comercial da solução.

---

## 1.2 Jornada do Usuário

### Descrição do fluxo principal

A jornada prototipada foi organizada para conduzir o usuário desde o primeiro contato com o produto até o registro de uma movimentação financeira e sua visualização no histórico.

O fluxo prioriza uma tarefa recorrente e fundamental: registrar uma receita ou despesa de maneira organizada, revisar os dados e confirmar a operação.

A sequência principal é composta por seis telas:

**[ESPAÇO RESERVADO PARA IMAGEM — Visão geral da jornada do usuário no Figma]**

*Inserir aqui uma captura do protótipo completo, mostrando as seis telas e suas conexões de navegação.*

### Etapas e objetivos de cada interação

#### 1. Boas-vindas

**Objetivo:** apresentar o produto e permitir que o usuário inicie sua experiência.

A primeira tela funciona como ponto de entrada da aplicação. Sua estrutura apresenta a identidade do Ozzy Finances, uma mensagem de boas-vindas e uma ação principal para começar.

A decisão de manter uma tela inicial objetiva evita apresentar informações excessivas antes de o usuário conhecer a aplicação. O foco está em comunicar a proposta e oferecer um caminho claro para avançar.

**[ESPAÇO RESERVADO PARA IMAGEM — Tela 01: Boas-vindas]**

#### 2. Painel financeiro

**Objetivo:** apresentar uma visão resumida da situação financeira do usuário.

O painel funciona como a principal área de acompanhamento da aplicação. Sua organização permite consultar informações financeiras relevantes, como saldo, receitas, despesas e lançamentos recentes.

A escolha de apresentar os dados de forma resumida procura reduzir o esforço necessário para compreender a situação financeira. Em vez de exigir que o usuário consulte diferentes registros, a tela concentra as informações mais importantes em uma visão inicial.

A partir dessa tela, o usuário pode iniciar um novo lançamento ou acessar a lista completa de movimentações.

**[ESPAÇO RESERVADO PARA IMAGEM — Tela 02: Painel financeiro]**

#### 3. Novo lançamento

**Objetivo:** permitir o registro de uma receita ou despesa.

Essa etapa reúne os campos necessários para descrever uma movimentação financeira, incluindo informações como tipo de movimentação, valor, descrição, categoria, conta, data e classificação.

A organização em campos identificados procura tornar o preenchimento mais compreensível e reduzir dúvidas sobre o tipo de informação solicitado.

Também foram realizados ajustes nos textos apresentados nessa tela, priorizando o português brasileiro e a utilização de termos mais claros. Por exemplo, o campo anteriormente identificado como “Note · optional” passou a utilizar “Nota · opcional”.

**[ESPAÇO RESERVADO PARA IMAGEM — Tela 03: Novo lançamento]**

#### 4. Revisão

**Objetivo:** permitir que o usuário confira as informações antes de confirmar o registro.

A tela de revisão representa uma etapa de conferência. Sua função é apresentar os dados informados anteriormente de maneira organizada, permitindo identificar possíveis erros e retornar à edição quando necessário.

A existência dessa etapa procura reduzir a possibilidade de registros incorretos e oferecer maior segurança ao usuário durante a operação.

A ação de edição retorna à tela de novo lançamento, permitindo corrigir os dados sem precisar reiniciar todo o processo.

**[ESPAÇO RESERVADO PARA IMAGEM — Tela 04: Revisão]**

#### 5. Confirmação

**Objetivo:** informar que o lançamento foi concluído.

Após a confirmação, o usuário visualiza uma tela de sucesso, com uma mensagem que comunica o resultado da operação e uma ação para consultar os lançamentos.

A escolha de uma tela específica para essa etapa evita que o usuário precise deduzir se a ação foi executada corretamente. O retorno visual oferece previsibilidade e transmite maior segurança durante a utilização.

**[ESPAÇO RESERVADO PARA IMAGEM — Tela 05: Confirmação]**

#### 6. Lista de lançamentos

**Objetivo:** permitir a consulta das movimentações registradas.

A última tela apresenta os lançamentos organizados em uma lista, permitindo que o usuário consulte seu histórico financeiro.

Essa organização complementa o painel inicial: enquanto o painel apresenta uma visão resumida, a lista permite consultar os registros individualmente.

A navegação também oferece um caminho de retorno ao painel e uma ação para iniciar um novo lançamento.

**[ESPAÇO RESERVADO PARA IMAGEM — Tela 06: Lista de lançamentos]**

### Resumo da jornada

A jornada principal pode ser representada da seguinte maneira:

**Boas-vindas → Painel financeiro → Novo lançamento → Revisão → Confirmação → Lista de lançamentos**

O fluxo também contempla caminhos alternativos:

- No painel, o usuário pode acessar diretamente a lista de lançamentos.
- Na revisão, o usuário pode retornar à edição antes de confirmar.
- Após a confirmação, o usuário pode consultar seus lançamentos.
- Na lista, o usuário pode retornar ao painel.

A navegação foi construída para manter o usuário orientado e permitir que ele avance, revise ou consulte informações sem percorrer caminhos desnecessários.

---

## 1.3 Estrutura da Solução (UX)

### Organização das telas

A estrutura da solução foi organizada em seis telas principais, cada uma associada a uma etapa específica da experiência.

| Tela | Função principal | Objetivo de UX |
|---|---|---|
| 01 — Boas-vindas | Entrada no produto | Apresentar a solução e iniciar a experiência |
| 02 — Painel financeiro | Visão geral | Facilitar a compreensão da situação financeira |
| 03 — Novo lançamento | Entrada de dados | Simplificar o registro de movimentações |
| 04 — Revisão | Conferência | Permitir a verificação e correção dos dados |
| 05 — Confirmação | Retorno da operação | Comunicar que o registro foi concluído |
| 06 — Lista de lançamentos | Consulta | Facilitar o acompanhamento do histórico |

A divisão por telas procura evitar que diferentes objetivos sejam apresentados simultaneamente. Cada etapa possui uma função clara, contribuindo para uma experiência mais previsível.

### Lógica de navegação

A navegação foi planejada considerando a frequência e a importância das principais ações do produto.

O painel financeiro foi definido como ponto central da aplicação, pois reúne as informações resumidas e oferece acesso às principais funcionalidades.

O registro de uma movimentação segue uma sequência orientada: preenchimento, revisão e confirmação. Essa separação permite que o usuário compreenda o que precisa fazer em cada momento.

As conexões do protótipo foram configuradas no Figma para representar os seguintes comportamentos:

- Boas-vindas direciona ao painel;
- Painel direciona ao novo lançamento ou à lista de lançamentos;
- Novo lançamento direciona à revisão;
- Revisão permite editar ou confirmar;
- Confirmação direciona à lista;
- Lista permite retornar ao painel.

**[ESPAÇO RESERVADO PARA IMAGEM — Mapa de navegação do protótipo no Figma]**

### Decisões tomadas para facilitar o uso

**1. Organização por objetivo**

Cada tela foi estruturada para atender a uma necessidade específica. Essa decisão reduz a quantidade de informações e ações que o usuário precisa interpretar simultaneamente.

**2. Painel como ponto central**

O painel financeiro foi escolhido como referência principal de navegação porque permite compreender rapidamente a situação financeira e iniciar as ações mais relevantes.

**3. Registro dividido em etapas**

O preenchimento, a revisão e a confirmação foram separados em telas distintas. Essa abordagem facilita a conferência das informações e reduz a possibilidade de erros antes da conclusão de uma operação.

**4. Possibilidade de correção**

A navegação permite retornar à edição durante a etapa de revisão. Isso evita que um erro de preenchimento obrigue o usuário a reiniciar todo o processo.

**5. Terminologia simples e familiar**

Os textos da interface foram ajustados para utilizar termos em português brasileiro e expressões mais próximas da linguagem cotidiana. A intenção é diminuir a necessidade de interpretação de termos técnicos ou estrangeiros.

**6. Priorização do uso mobile**

As seis telas foram desenvolvidas considerando uma dimensão de referência de 390 × 844 px. A escolha de uma estrutura mobile-first permite concentrar a experiência em uma área de visualização compacta, adequada ao uso em smartphones.

**7. Navegação por ações reconhecíveis**

Ações como iniciar um lançamento, voltar, confirmar e consultar registros são apresentadas em pontos específicos da jornada. Essa organização procura tornar os próximos passos mais previsíveis.

---

## 1.4 Decisões de Interface (UI)

### Direção visual

A identidade visual do Ozzy Finances foi desenvolvida para transmitir organização, confiança, clareza e proximidade.

Por se tratar de uma aplicação financeira, a interface precisa apresentar informações numéricas de maneira legível e transmitir segurança durante operações que envolvem receitas, despesas e saldo.

A direção visual adotada utiliza uma identidade baseada em tons de verde, superfícies claras, textos escuros e componentes organizados em cartões.

A intenção foi evitar uma interface visualmente carregada, priorizando a informação financeira e as ações principais.

### Escolha de cores

A paleta documentada no Design System utiliza o verde escuro como cor institucional, tons de verde para representar receitas e estados positivos, vermelho para despesas e tons neutros para fundos, textos e elementos secundários.

| Cor | Código | Aplicação |
|---|---|---|
| Verde 900 | `#182720` | Cabeçalho e superfícies escuras |
| Verde 600 | `#247451` | Navegação ativa e destaques |
| Verde sucesso | `#22C55E` | Receitas e valores positivos |
| Verde chip | `#DCFCE7` | Fundo de identificadores positivos |
| Verde chip texto | `#16A34A` | Texto de identificadores positivos |
| Vermelho despesa | `#EF4444` | Despesas e valores negativos |
| Cinza inativo | `#6B7280` | Elementos secundários e navegação inativa |
| Cinza borda | `#E5E7EB` | Bordas e divisores |
| Cinza claro | `#F8F9FA` | Fundos de áreas de conteúdo |
| Branco | `#FFFFFF` | Cartões, fundos e textos sobre superfícies escuras |
| Texto principal | `#111827` | Informações e títulos |
| Texto secundário | `#A7C4B5` | Informações secundárias sobre fundo escuro |

**Justificativa das escolhas:**

- **Verde escuro:** funciona como base da identidade visual e contribui para transmitir estabilidade e confiança.
- **Verde positivo:** diferencia receitas e resultados favoráveis, facilitando a leitura dos dados.
- **Vermelho:** destaca despesas e valores negativos, criando contraste com as informações positivas.
- **Fundos claros:** ajudam a separar áreas de conteúdo e favorecem a leitura de informações financeiras.
- **Cinzas:** permitem estabelecer uma hierarquia entre informações principais e secundárias sem competir visualmente com os dados mais importantes.

A utilização de cores distintas para receitas e despesas facilita a identificação dos tipos de movimentação. Entretanto, a compreensão dessas informações não deve depender exclusivamente da cor: os textos, sinais e identificadores também precisam comunicar o significado.

**[ESPAÇO RESERVADO PARA IMAGEM — Paleta de cores do Design System no Figma]**

### Tipografia

A família tipográfica escolhida foi **Inter**, utilizada em diferentes pesos para estabelecer uma hierarquia entre títulos, valores, descrições e informações auxiliares.

A Inter foi adotada por apresentar uma aparência contemporânea e uma boa legibilidade em interfaces digitais.

Os pesos documentados incluem:

| Peso | Utilização |
|---|---|
| Regular | Labels, datas e informações auxiliares |
| Medium | Chips e identificadores |
| SemiBold | Nomes, valores e títulos de componentes |
| Bold | Valores financeiros de maior destaque |

A hierarquia tipográfica utiliza tamanhos diferentes para indicar a importância de cada informação. O saldo principal, por exemplo, recebe maior destaque visual do que as descrições e os rótulos auxiliares.

Essa decisão facilita a leitura rápida do painel, permitindo que o usuário identifique primeiro os dados mais relevantes e consulte os detalhes quando necessário.

**[ESPAÇO RESERVADO PARA IMAGEM — Hierarquia tipográfica do Design System no Figma]**

### Componentes e padrões visuais

A construção visual considerou padrões que podem ser reutilizados em diferentes partes da aplicação.

Os principais elementos documentados foram:

**1. Cartão de resumo financeiro**

Apresenta o saldo total e a divisão entre receitas e despesas.

O uso de um cartão com fundo verde escuro, valor principal em destaque e informações complementares organizadas em uma área secundária procura concentrar os dados mais importantes em um único componente.

**2. Item de transação**

Representa uma movimentação individual na lista de lançamentos.

O componente utiliza um cartão claro, identificação da movimentação, categoria e valor. A organização facilita a leitura e a comparação entre diferentes registros.

**3. Cabeçalho e navegação**

O cabeçalho apresenta a identificação do produto, enquanto a navegação inferior oferece acesso às áreas principais da aplicação.

A utilização de estados visuais diferentes para itens ativos e inativos ajuda o usuário a identificar sua localização dentro do sistema.

**4. Botões e campos de entrada**

Os botões representam as ações disponíveis em cada etapa, enquanto os campos de entrada organizam as informações necessárias para registrar uma movimentação.

A padronização desses elementos contribui para manter a consistência visual e reduzir a necessidade de reaprender os padrões de interação em cada tela.

**[ESPAÇO RESERVADO PARA IMAGEM — Componentes visuais do Design System no Figma]**

### Formas, espaçamentos e organização

Os componentes documentados utilizam cantos arredondados, com raio de 12 px em cartões e elementos principais, além de bordas sutis para separar áreas de conteúdo.

Essa escolha procura produzir uma interface visualmente organizada e evitar divisões excessivamente rígidas.

A utilização de cartões também permite agrupar informações relacionadas, como valores financeiros, dados de uma movimentação e categorias.

Os espaçamentos e alinhamentos devem manter uma distribuição consistente entre os componentes, evitando sobreposição e facilitando a leitura.

### Consistência textual e localização

Durante a revisão das telas, foram identificadas expressões em inglês, rótulos duplicados e inconsistências na apresentação de datas.

Foram realizadas correções como:

- “Save expense” para “Salvar despesa”;
- “Note · optional” para “Nota · opcional”;
- “Oct 24, 2026” para “24 out 2026”;
- Renomeação do segundo campo “Categoria” para “Conta”;
- Correção da ordem do intervalo de datas apresentado na lista.

A padronização para português brasileiro procura tornar a experiência mais natural para o público considerado e evitar que diferentes idiomas ou nomenclaturas causem dúvidas durante o preenchimento.

**[ESPAÇO RESERVADO PARA IMAGEM — Comparativo visual das telas após a revisão textual]**

---

## 1.5 Acessibilidade e Inclusão

### Acessibilidade

A acessibilidade foi considerada como um aspecto importante para que pessoas com diferentes níveis de familiaridade com tecnologia consigam compreender e utilizar a aplicação.

A proposta visual procura utilizar textos claros, contraste entre informações e fundos, organização por cartões e ações identificáveis.

Entretanto, é importante distinguir as decisões visuais já representadas no protótipo dos requisitos que ainda precisam de validação específica.

Os seguintes critérios devem orientar a evolução da interface:

**1. Contraste visual**

As combinações de cores devem permitir a leitura de textos e valores financeiros, inclusive por usuários com limitações de visão.

O contraste precisa ser verificado nas diferentes combinações da paleta, principalmente em textos secundários, botões e identificadores de categorias.

**2. Informação não dependente apenas de cores**

Receitas e despesas utilizam cores distintas, mas também devem ser identificadas por seus respectivos nomes, sinais e descrições.

Essa decisão beneficia pessoas com daltonismo ou que tenham dificuldade para distinguir determinadas cores.

**3. Áreas de toque**

Botões, ícones e elementos interativos devem possuir áreas de toque suficientemente grandes para facilitar a interação em dispositivos móveis.

Como referência de acessibilidade motora, recomenda-se trabalhar com alvos de interação de pelo menos 44 × 44 px.

Na auditoria do Design System foram identificados ícones de navegação com dimensões de 24 × 24 px. Portanto, esse ponto precisa ser ajustado ou validado considerando a área interativa total, e não apenas o tamanho visual do ícone.

**4. Hierarquia e legibilidade**

A utilização de diferentes pesos e tamanhos tipográficos procura facilitar a identificação de títulos, valores e informações complementares.

É importante evitar textos excessivamente pequenos, principalmente em datas, categorias e informações financeiras secundárias.

**5. Estados de interação**

Os componentes interativos devem apresentar estados visuais claros, como padrão, foco, pressionado, desabilitado e erro, conforme o tipo de componente.

O foco visível também deve ser considerado para usuários que utilizam teclado ou tecnologias assistivas.

Esses estados ainda precisam ser documentados e validados de forma sistemática no Design System.

### Clareza visual

A clareza visual foi tratada como um princípio central da interface.

Como o produto trabalha com informações financeiras, é importante que o usuário consiga identificar rapidamente os dados principais e compreender o significado de cada elemento.

As decisões adotadas para contribuir com essa clareza incluem:

- Separação das informações em cartões e áreas organizadas;
- Destaque para o saldo e os valores financeiros relevantes;
- Diferenciação visual entre receitas e despesas;
- Utilização de títulos e rótulos objetivos;
- Padronização dos componentes;
- Organização do registro em etapas;
- Apresentação de mensagens de confirmação após ações importantes.

Essas escolhas procuram reduzir a carga de interpretação e tornar a experiência mais previsível, especialmente para usuários que não possuem familiaridade com sistemas financeiros.

### Diversidade de usuários

O Ozzy Finances considera que seus usuários podem apresentar diferentes experiências profissionais, níveis de escolaridade, familiaridade com tecnologia e conhecimentos sobre gestão financeira.

Por esse motivo, a interface procura evitar depender de conhecimentos contábeis ou termos excessivamente técnicos.

A utilização de expressões como “Receitas”, “Despesas”, “Saldo” e “Novo lançamento” aproxima a linguagem da aplicação das atividades cotidianas dos usuários.

A proposta também considera que pequenos empreendedores possuem rotinas diferentes e podem utilizar a aplicação em momentos curtos, durante o expediente ou entre atividades profissionais.

A experiência mobile-first procura facilitar esse acesso, permitindo que as principais operações sejam realizadas em uma interface compacta.

### Limitações e melhorias identificadas

A prototipação atual representa uma primeira versão da experiência e não deve ser interpretada como uma validação completa de acessibilidade.

Alguns pontos ainda precisam ser verificados ou aprimorados:

- Conferir o contraste de todas as combinações de cores;
- Revisar as áreas de toque dos ícones e botões;
- Documentar os estados de foco, erro, pressionado e desabilitado;
- Verificar a legibilidade dos textos em diferentes condições de visualização;
- Garantir que informações importantes não dependam exclusivamente de cores;
- Testar a experiência com pessoas que apresentem diferentes níveis de familiaridade com tecnologia;
- Avaliar a adaptação da interface para larguras diferentes da referência mobile de 390 px.

Essas melhorias devem ser consideradas nas próximas etapas de refinamento da interface.

---

## Considerações finais

A concepção de UX/UI do Ozzy Finances procurou transformar uma necessidade cotidiana — controlar as finanças de uma atividade profissional — em uma experiência digital simples, organizada e compreensível.

A estrutura de seis telas foi definida para representar o fluxo principal de utilização, desde a entrada no produto até a consulta dos lançamentos registrados.

As decisões visuais priorizaram uma identidade baseada em tons de verde, superfícies claras, tipografia Inter, cartões e componentes organizados. Já as decisões de experiência priorizaram a redução de etapas desnecessárias, a clareza das ações e a possibilidade de revisar informações antes da confirmação.

O protótipo navegável permite demonstrar a lógica de interação planejada e serve como base para futuras avaliações com usuários.

Como próxima evolução, recomenda-se aprofundar os testes de usabilidade, revisar os pontos de acessibilidade identificados e validar se a experiência proposta realmente reduz o esforço de controle financeiro para o público prioritário.

**Observação sobre o estágio do projeto:** o protótipo representa uma proposta de interface e navegação. Ele não comprova, por si só, o funcionamento de integrações financeiras, categorização automatizada por inteligência artificial ou persistência de dados em ambiente de produção.