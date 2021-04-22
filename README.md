## Desafio Stone - Regulatory Ops
 Desafio proposto pela Stone a respeito do cumprimento das exigências da LGPD no contexto de Open Banking e apresentação de soluções a partir do conceito de RegTech



# LEI GERAL DE PROTEÇÃO DE DADOS E OPEN BANKING 
### Desafios a serem enfrentados pelas Fintechs e demais instituições financeiras

Conforme disciplinado pela [Resolução Conjunta N° 1, de 04/05/2020, do Conselho Monetário Nacional e Banco Central](https://www.in.gov.br/en/web/dou/-/resolucao-conjunta-n-1-de-4-de-maio-de-2020-255165055), e disposto na tabela abaixo, a implementação do Open Banking (Sistema Financeiro Aberto) no Brasil segue a todo o vapor e deve alcançar sua terceira fase em breve, no fim do mês de maio de 2021, quando será possível o compartilhamento do serviço de iniciação de transação de pagamentos.

ETAPA    | DATA FINAL        | COMPARTILHAMENTO
-------- | ----------------- | ----------------
PRIMEIRA | até 30/11/2020    | Dados das próprias instituições participantes do Sistema Financeiro Aberto, além de produtos e serviços por ela oferecidos
SEGUNDA  | até 31/05/2021    | Informações de clientes - cadastro e transações
TERCEIRA | até 30/08/2021    | Serviços de iniciação de transações de pagamento e de encaminhamento e proposta de crédito
QUARTA   | até 25/10/2021    | Expansão do escopo de dados abrangendo todos os dados de produtos e serviços



Nesse contexto, fato é que o Open Banking e a [Lei 13.709/2018, LGPD](http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm), compartilham importantes princípios e objetivos, dentre os quais destacam-se aqui o ESTÍMULO DA CONCORRÊNCIA por meio da diminuição da assimetria informacional entre os _players_ do mercado fiannceiro, a OPORTUNIZAÇÃO DE INOVAÇÕES NO MERCADO FINANCEIRO em razão do aumento da concorrência e, principal e fundamentalmente, a **DEVOLUÇÃO AO TITULAR DO PLENO PODER SOBRE SEUS DADOS**.


Essa transferência de poder em meio à reforma que se propõe ao mercado financeiro fará com que todo o tratamento de dados gire em torno do **CONSENTIMENTO** do titular. E, nesse sentido, ainda que as duas diretivas citadas caminhem na mesma direção, há desafios específicos e práticos, de ordem jurídica e tecnológica, a serem enfrentados pelas instituições participantes do Sistema Financeiro Aberto, principalmente no que diz respeito ao devido cumprimento da LGPD.



## 1. CONSENTIMENTO NA PRÁTICA 

> O consentimento é a declaração livre e evidente pela qual o titular dos dados pessoais aceita o tratamento dos seus dados para uma finalidade específica.

- Como atender à clareza e evidência exigidas da manifestação de vontade do titular, que deve se dar livre de vícios de consentimento, se este último será concedido virtual e digitalmente no contexto do Open Banking?

O desafio aqui se encontra justamente na tradução dos requisitos legais para o funcionamento prático da interface pela qual o titular dos dados consentirá o compartilhamento e tratamento de seus dados(e revogará essa concessão, sem assim quiser). Há a necessidade de desenvolver **efetivos** meios técnicos para demonstrar a **efetiva** manifestação de vontade do titular, **livre de vícios de consentimento**: não pode se tratar de mera adesão, não podem existir opções previamente marcadas ou preenchidas, além de haver a necessidade de assegurar a real identidade do titular - por meio da biometria, por exemplo. 

Nesse sentido e conforme as disposições da Resolução Conjunta, é necessário que seja oferecida ao público uma interface dedicada, digital, de acesso gratuito, bem como que a declaração de consentimento do titular seja traga a lista de todos os dados que serão coletados/tratados, bem como de todas as instituições que a eles terão acesso, além, é claro, da **possibilidade de personalização dos parâmetros de consentimento** - podendo o titular escolher **quais** dados serão compartilhados e para quais **finalidades**. 

Para tanto, o foco prático interno das Fintechs deve ser em uma equipe multidisciplinar, que consiga conversar com a área jurídica e de tecnologia, a fim de que toda a construção do sistema esteja em devida conformidade com as questões regulatórias, e que entenda, valorize e aplique de forma contínua, especialmente, os conceitos de **Design de Experiência do Usuário**. As boas práticas em UI e UX são mais que essenciais para a construção de uma interface limpa, prática, intuitiva e de fácil compreensão ao usuário e devem ser um ponto chave na construção e administração da plataforma.

Em resumo, no que diz respeito ao Consentimento:

- [x] Manifestação de vontade livre de vícios de consentimento
- [x] Personalização dos parâmteros de consentimento
- [x] Equipe multidisciplinar - integração jurídico-tecnológica
- [x] Experiência do Usuário

## 2. REVOGAÇÃO DO CONSENTIMENTO

É imperativo, ainda, assegurar aos titulares a possibilidade da revogação do consentimento _a qualquer tempo_, pelo menos pelo mesmo canal em que foi concedido. E uma vez revogado, todos os controladores de dados envolvidos no compartilhamento precisam ser imediatamente informados para que seja interrompido o tratamento de tais dados.

O principal desafio, aqui, é operacional: Como, tendo diversos players acessando a plataforma ao mesmo tempo, assegurar o cumprimento imediato da revogação de consentimento, com suas devidas consequências e cumprindo os prazo extremamente exíguos exigidos pelas normativas:

PRAZO         | TIPO DE COMPARTILHAMENTO
------------- | ------------------
1 dia         | Serviços de Iniciação de Pagamentos
Imediatamente | Todo o resto

A solução, aqui, será de ordem estritamente tecnológica: É necessário investir em um sistema bem estruturado, planejado, forte e, especialmente, rápido.

Além disso, há ainda desafios de ordem jurídica. Como cumprir, ao mesmo tempo, as exigências do regulador no que diz respeito à manutenção de registro de atividades e movimentações financeiras por prazo legal estabelecido e a necessidade de interrupção **imediata**, ou em até **1 dia**, do compartilhamento e todo o tratamento de dados conforme solicitado por seu titular?

É preciso contato com a prática, nesse caso, bem como acompanhar, junto aos órgãos regulatórios, as orientações, exigências e a própria experiência do mercado financeiro como um todo. A chave é a participação ativa das Fintechs na autorregulação do Sistema Financeiro Aberto.

## 3. COMPROVAR ESTAR EM COMPLIANCE COM A LGPD 

> A proteção de dados, no âmbito tecnológico, não é demonstrada prática e visivelmente de forma tão fácil para o público em geral.

Partimos desse pressuposto, afinal, tratam-se aqui de sistemas de segurança que o usuário, de modo geral, não necessariamente tem condições de compreender ou visualizar de forma clara, devido à sua complexidade. Pode-se dizer o mesmo, ainda que em menor grau, sobre a letra da lei e demais normativas/resoluções que guiam o Open Banking.

A fim de captar o consentimento para o compartilhamento e tratamento de dados do potencial usuário do Open Banking, é preciso que antes se consiga sua confiança. Num contexto de revolução do Sistema Financeiro, é necessário convencer o usuário de que

1. Seus dados estão armazenados de forma segura
2. O compartilhamento desses dados é seguro
3. As operações financeiras dentro do Open Banking são seguras
4. Ele tem, de fato, pleno controle sobre essas questões

Em resumo, é preciso que o usuário esteja convencido de que as instituições financeiras estão cumprindo a lei no que diz respeito à proteção de dados. 

Isso pode ser feito por meio dos chamados [_Legal Design_ e _Visual Law_](https://besouza86.jusbrasil.com.br/artigos/804292299/visual-law-o-que-voce-precisa-saber), que são abordagens de comunicação interdisciplinares entre Direito e Tecnologia, que buscam utilizar elementos gráficos para melhor compreensão de teses jurídicas, alcançando o público além do "juridiquês", reduzindo a disparidade informacional e tentando simplificar ao máximo a linguagem jurídica.

Essas abordagens podem ser aplicadas tanto à complexidade tecnológica da proteção de dados, quanto aos conceitos jurídicos envolvidos. Simplificando e tratando de forma gráfica as informações mais caras ao usuário, torna-se mais fácil conseguir, de fato, sua confiança.

Aqui, novamente, se demonstra a importância do Design de Experiência do Usuário e da aplicação dos conceitos de UI e UX não somente quanto à interface da plataforma, mas também em relação às informações que são disponibilizadas aos usuários.


## 4. GARANTIR DE FATO NÃO SOMENTE A SEGURANÇA DOS DADOS ARMAZENADOS, MAS PRINCIPALMENTE NO COMPARTILHAMENTO DESSES DADOS E INTERNAMENTE NAS INSTITUIÇÕES
necessidade de garantir sistema seguro, ágil e com interface sempre operante 24/7 com, ainda, uma segunda opção em caso de indisponibilidade da plataforma, conforme requerido pela Resolução Conjunta. Equipe de apoio a postos 24h.
Especialista em infraestrutura de rede que vai cuidar de todas as ferramentas de firewall, configurações de servidor e métodos para tornar a segurança digital mais robusta 
internamente, talvez a necessidade de autenticação de mais de uma pessoa para cada contato com dados sensíveis









