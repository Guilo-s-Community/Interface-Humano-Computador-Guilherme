**Projeto de IHC**

**Detecção e Identificação de som ambiente para auxílio doméstico de pessoas surdas**

**Membros de Equipe:**

- Guilherme Marcato Mendes Justiça - 22.225.030-0
- Paulo Vinicius Araujo Feitosa - 24.122.042-5

# **Entrega 1 (29/08) - [concluído]**

**1\) Conhecendo o Problema** 

1.1) Membros de Equipe:
- Guilherme Marcato Mendes Justiça 22.225.030-0
- Paulo Vinicius Araujo Feitosa 24.122.042-5

1.2) Título Original do TCC:

- Detecção e identificação de som ambiente para auxílioo doméstico de pessoas com deficiência auditiva

1.3) Nome do orientador:

- Plinio Thomaz Aquino Junior

1.4) Previsto desenvolver Interface? ( x ) Sim  (  ) Não

1.5) Objetivo do trabalho?

- Desenvolver um hardware capaz de detectar e identificar um som e enviar para um aplicativo, auxiliando de forma direta a independência de pessoas surdas, por meio de uma notificação.

1.6) Qual o produto final? 

- Hardware para detectar e identificar som.
- Software para experiência do usuário.

1.7) Quem é o usuário final deste produto?

- Pessoas surdas com intenção de utilizar a tecnologia ao seu favor.

1.8) O que o usuário recebe de benefício ao usar esse produto? 

- Independência/autonomia e percepcão do ambiente.

1.9) Quais as funcionalidades da ferramenta (visão do usuário)?
	
- Cadastro
- Login 
- Cadastro do dispositivo
- Edição do perfil
- Configuração do dispositivo

1.10) Quais tecnologias e ferramentas computacionais que pretendem usar neste projeto (TCC)?
- Hardware: Raspberry Pi 4 Model B (8 GB).
- Microfone Adafruit I2S MEMS SPH0645LM4H.
- Armazenamento de Dados : Serviços da Firebase.
- Mobile: Flutter (Dart) para o aplicativo multiplataforma.

1.11) Qual é o contexto de uso dessa aplicação?

- Usuário : Pessoas de qualquer idade com qualquer grau de surdez.
- Objetivo : Saber onde e quando ocorreu um barulho.
- Interação : Receber uma notificação e agir conforme vontade.
- Equipamento : Celular.

- O contexto de uso é: Uma casa, um ambiente confortável com barulhos tradicionais do cotidiano, a pessoa segue com sua rotina normalmente, porém um barulho foi detecado em outro cômodo da casa. A pessoa recebe em seu celular a notificação - "Barulho em QUARTO detectado - Som de objeto quebrando". Assim, ela corre para ver o que aconteceu e se depara com um vaso quebrado do lado de sua cama e seu gato em cima da escrivaninha. Após perceber que tudo está bem e arrumar a ocorrência, ela segue sua rotina novamente.


# **Entrega 2 29/08 [concluído]**

**\[1 solução completa por pessoa da equipe\]**

**Dica: fator mais importante desta entrega é a equipe conseguir identificar e documentar prints de telas de interfaces concorrentes (ou interfaces representativas para o público alvo). Esses prints serão usados na fase de caracterização de padrões, affordances, heurísticas, etc.**

1) **Público Alvo**
- Pessoa surdas e/ou pessoas interessadas em tecnologia.
2) **Análise de Concorrência**  
1. **Principais concorrentes mais utilizados pelo seu público-alvo (link, descrição e imagens de ilustração):**
- Positivo Casa Inteligente
- Amazon Alexa
- Smart Life
- LG Thinq
- Philips Hue
- Tuya 
2. **Características e funcionalidades dos concorrentes:**
- Todos estão envolvidos no contexto de IoT, conectividade com hardware, software e ambiente, maioria possuem as mesmas características padrões do mercado e funcionalidades parecidas para cada tipo de dispositivo.
3. **Experiência do usuário (UX) e pesquisa de satisfação do cliente e opiniões:**
- Avaliações dos usuários do aplicativo Positivo Casa Inteligente:
  "Prático","Experiência excelente","Lâmpada pisca muito para emparelhar","Aplicativo é lento","Não funciona em paisagem no tablet"
4. **Preços e modelos de negócio:**
- "Gratuito, depende da compra de dispositivos"
5. **Padrões e tendências no mercado:**
- Navegação no estilo BottomNavigation
- Tela principal com os dispositivos aparecendo de forma de cards
- Simples

6. **Telas dos aplicativos**
   
   ![Positivo](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/opcaopositivo.jpg?raw=true)
   
   ![Positivo](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/cadastropositivo.jpg?raw=true)

   ![Positivo](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/loginpositivo.jpg?raw=true)
   
   ![SmartLife](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/opcaosmartlife.jpg?raw=true)

   ![SmartLife](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/cadastrosmartlife.jpg?raw=true)
   
   ![SmartLife](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/loginsmartlife.jpg?raw=true)

   ![Alexa](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/tpalexa.jpg?raw=true)

   ![GoogleHome](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/tpgooglehome.jpg?raw=true)
   
   ![PhilipsHue](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/tphue.jpg?raw=true)

   ![LGThinq](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/tplgthinq.jpg?raw=true)
   
   ![Positivo](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/tppositivo.jpg?raw=true)
   
   ![Smartlife](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/tpsmartlife.jpg?raw=true)
   
   ![Tuya](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/tptuya.jpg?raw=true) 
   
# **Entrega 3 08/09 [concluído]**

**1\) Personas** 

*Persona Primária*

Bianca Bianca, 45 anos, professora de LIBRAS

![Bianca](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/biancabianca.jpg?raw=true) 

Bianca Bianca é surda de nascença e trabalha como professora de LIBRAS em sua própria escola. Ela passa bastante tempo em casa preparando aulas, fazendo as refeições para o filho de 10 anos e cuidando de Thor, o cachorro da família. Bianca não desenvolveu muitas habilidades com tecnologia e depende muito do marido, Tobias, em atividades dessa área.
Em seu cotidiano, sente-se sobrecarregada: muitas situações a deixam preocupada, pois precisa prestar atenção em todos os lugares da casa. Fica constantemente de olho no celular para abrir a porta assim que o filho chega, verificar se o cachorro está aprontando em outro cômodo, cuidar do preparo das refeições, garantir que não há nenhuma torneira aberta e outros pontos que geram ansiedade.

Bianca deseja ter mais tranquilidade e busca alternativas para resolver esses problemas, acreditando que a tecnologia pode ajudá-la.

*Persona Secundária*

Tobias Tobias, 47 anos, técnico em manutenção elétrica

![Tobias](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/tobiastobias.jpg?raw=true) 

Tobias é casado com Bianca e juntos cuidam do filho de 10 anos. Diferente da esposa, Tobias tem maior familiaridade com tecnologia, embora use mais no trabalho do que no dia a dia em casa. Ele entende o quanto a surdez de Bianca traz preocupações extras e procura sempre estar disponível para apoiá-la.
No entanto, Tobias também tem sua rotina corrida: trabalha em uma empresa de manutenção elétrica, o que faz com que passe boa parte do dia fora. Isso o preocupa, já que sabe que Bianca pode se sentir sobrecarregada sozinha com as tarefas da casa e os cuidados com o filho e o cachorro.
Seu maior desejo é garantir que a esposa tenha mais autonomia e tranquilidade dentro de casa, sem depender sempre dele para resolver problemas relacionados à tecnologia ou segurança. Para Tobias, soluções tecnológicas acessíveis e confiáveis são fundamentais para dar mais independência à Bianca e, ao mesmo tempo, trazer mais segurança e paz para toda a família.

**2\) Mapa de Empatia**

![MapaEmpatia](https://github.com/Guilo-s-Community/Interface-Humano-Computador-Guilherme/blob/main/images/imagem_2025-09-08_143917738.png?raw=true)


**3\) Contexto de Uso**
Uma casa, um ambiente confortável com barulhos tradicionais do cotidiano, a pessoa segue com sua rotina normalmente, porém um barulho foi detecado em outro cômodo da casa. A pessoa recebe em seu celular a notificação - "Barulho em QUARTO detectado - Som de objeto quebrando". Assim, ela corre para ver o que aconteceu e se depara com um vaso quebrado do lado de sua cama e seu cachorro em cima da escrivaninha. Após perceber que tudo está bem e arrumar a ocorrência, ela segue sua rotina novamente.

**4\) Jornada do Usuário**

#### 1. Situação inicial (cotidiano sem solução)
- **Ações:** Prepara aulas, cuida da casa, acompanha o filho e o cachorro.  
- **Pensamentos:** “Preciso estar em todos os lugares ao mesmo tempo.”  
- **Sentimentos:** Ansiedade, sobrecarga.  

---

#### 2. Descobrindo a solução (primeiro contato)
- **Ações:** Conhece o sistema que identifica sons e envia alertas visuais no celular.  
- **Pensamentos:** “Será que isso pode mesmo me ajudar?”  
- **Sentimentos:** Esperança, curiosidade.  

---

#### 3. Configuração do sistema
- **Ações:** Tobias ajuda a instalar o aplicativo e vincular a Raspberry Pi ao Wi-Fi.  
- **Pensamentos:** “Ainda preciso do Tobias para configurar, mas quero aprender.”  
- **Sentimentos:** Alívio (por contar com ajuda), leve insegurança.  

---

#### 4. Uso no dia a dia
- **Ações:** Recebe notificações visuais e vibratórias no celular quando o filho chega, quando o cachorro late ou quando a campainha toca.  
- **Pensamentos:** “Agora não preciso ficar conferindo tudo o tempo todo.”  
- **Sentimentos:** Tranquilidade, confiança, mais autonomia.  

---

#### 5. Resultado esperado
- **Ações:** Usa a tecnologia como apoio constante em casa.  
- **Pensamentos:** “Finalmente tenho mais paz no meu dia a dia.”  
- **Sentimentos:** Autonomia, segurança, qualidade de vida.

# **Entrega 4  (data) \[em andamento/concluído\]**

**\[1 solução completa por pessoa da equipe\]**

1) **Cenário de Análise/Problema**

Em um dia normal, Bianca, depois de um dia cansativo, quer descansar um pouco em seu sofá de casa e , então, se prepara para ler seu livro favorito. Seu vizinho de apartamento recém-chegado, o Breno, notou que Thor, cachorro de Bianca, estava há muito tempo latindo e, então, decidiu ver o que estava acontecendo, porque Breno precisava terminar seu trabalho. Ao chegar, Breno tocou a campainha, mas ninguém atendeu, tocou novamente, e nada...
Breno, não sabendo se Bianca estava em casa, foi ao porteiro explicar a situação. O porteiro explicou que Bianca era surda e que ia chamar um amigo próximo que Bianca deixou como contato de emergência para ver se estava tudo bem. Marco, amigo de Bianca, ao receber a ligação do porteiro, foi direto ao prédio e, ao abrir o apartamento deparou com Bianca deitada no sofá lendo um livro. Com cuidado Marco apareceu para Bianca e , com surpresa, ela perguntou o que aconteceu. Com a situação explicada, Marco foi ver porque Thor estava latindo muito e se deparou com várias situações. Ao andar pelo apartamento, Marco reparou que o banheiro estava bem molhado, pois a torneira estava um pouco aberta e vazando água, o Thor estava no quarto de Bianca com a porta fechada, pois Bianca fechou a porta sem saber que Thor ficou por lá, além de um alguns pequenos vasos quebrados pelo chão do quarto que caiu por conta de um forte vento que entrou com a janela aberto, o microondas e a máquina de lavar roupa estavam apitando, pois Bianca havia deixado seu chá para esquentar e as roupas para lavar antes de deitar no sofá pra ler seu livro.

3) ## **Questões de Refinamento**

4) **Refinamento do Cenário Análise/Problema**

# 

# **Entrega 5  (data) \[em andamento/concluído\]**

**\[1 solução por pessoa\]**

**DICA: nesta entrega a equipe deve descrever as funcionalidades mais importantes da interface/produto. Dividir pelo número de integrantes. Cada um se responsabiliza pela modelagem de 1 bloco. Cada aluno deve modelar pelo menos 1 HTA, 1 GOMS e 1 CTT (de funcionalidade diferentes ou da mesma \- escolha de cada um). Cada diagrama deve ter um texto explicando a funcionalidade.**

**Análise de Tarefas**

**1\) HTA**

**2\) GOMS**

**3\) CTT**

# 

# **Entrega 6  (data) \[em andamento/concluído\]**

**\[PARTE A \- 1 solução por equipe\]**

**DICA: protótipo em papel**

# **Entrega 7  (data) \[em andamento/concluído\]**

**\[PARTE A: 1 solução completa por pessoa da equipe\]**

**1\)	Identificação de Necessidades dos Usuários e Requisitos de IHC: exercício de perguntas**

* **Que dados coletar?**

* **De quem coletar?**

	

**2\)	Aspectos Éticos**

* **Seu projeto deverá considerar aspectos éticos? Justifique usando os conceitos da aula.**

	

**\[PARTE B: 1 solução completa por pessoa da equipe \- e com técnicas diferente; questionário deve ser uma das técnicas escolhidas\]**

**3\)	Ferramentas de Coleta de Dados**  
**3.1) nome do instrumento e objetivo de aplicação**  
**3.2) explicar como aplicar (serve para normalizar o processo de aplicação quando pessoas distintas aplicam o instrumento)**  
**3.3) instrumento (por exemplo, link do questionário no Google Forms, roteiro de entrevista, roteiro do Grupo Focal, etc)**

# 

# **Entrega 8  (data) \[em andamento/concluído\]**

**\[1 solução por equipe\]**

**CICLO DE VIDA DE ENGENHARIA DE USABILIDADE**

**![][image1]**

1. **Características da Plataforma**  
   

| Característica | Descrição |
| :---- | :---- |
| Descrição do Software |  |
| Descrição do Hardware |  |
| LISTA DE Capacidades da Plataforma (com explicação) |  |
| LISTA DE Restrições da Plataforma (com explicação) |  |

   

2. **Princípios Gerais do Projeto (INCREMENTAR TABELA)**  
   

| Nome | Descrição | Link |
| :---- | :---- | :---- |
| Descrição do Contexto | .  |  |
| Lei Geral de Proteção de Dados (LGPD) \- Lei n.º 13.709/2018 | A LGPD é a legislação brasileira que regulamenta o tratamento de dados pessoais no Brasil. É importante para o projeto porque estabelece regras sobre como os dados dos usuários devem ser coletados, armazenados, processados e protegidos, garantindo sua privacidade e segurança. | [https://www.planalto.gov.br/ccivil\_03/\_ato2015-2018/2018/lei/l13709.htm](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm) |
| Lei n.º 10.098/2000 \- Lei da Acessibilidade |  Esta lei brasileira estabelece normas gerais e critérios básicos para a promoção da acessibilidade das pessoas com deficiência ou com mobilidade reduzida. É importante para o projeto porque define diretrizes para tornar produtos e serviços, incluindo interfaces de usuário, acessíveis a todos os usuários, independentemente de suas habilidades físicas ou cognitivas. | [https://www.planalto.gov.br/ccivil\_03/leis/l10098.htm](https://www.planalto.gov.br/ccivil_03/leis/l10098.htm) |
| ABNT NBR ISO 9241 Ergonomia da interação humano-sistema |  Esta série de normas brasileiras, baseadas nas normas ISO 9241, fornece diretrizes e orientações para o design centrado no usuário de sistemas interativos, incluindo a concepção de interfaces de usuário. A parte 210 aborda o processo de design centrado no humano, enquanto a parte 11 fornece orientações específicas sobre usabilidade. Essas normas são importantes para o projeto porque estabelecem princípios e métodos para garantir que a interface do usuário atenda às necessidades e expectativas dos usuários. | [https://www.inf.ufsc.br/\~edla.ramos/ine5624/\_Walter/Normas/Parte%2011/iso9241-11F2.pdf](https://www.inf.ufsc.br/~edla.ramos/ine5624/_Walter/Normas/Parte%2011/iso9241-11F2.pdf) |
|  | . |  |

   

3. **Metas de Usabilidade**

   1. **Qualitativo**

    


   2. **Quantitativo**  
      

| Metas | Porcentagem | Justificativa |
| ----- | :---- | :---- |
| Facilidade de … |  |  |
|  |  |  |
|  |  |  |
|  | 1% |  |
|  | 20% |  |
| **Total** | **100%** |  |

      

# **Entrega 9 (data) \[em andamento/concluído\]**

**\[1 solução completa por pessoa da equipe\]**

1) **Cenários de Interação (destacar em cor diferente o texto alterado entre Cenário Problema e Cenário de Interação)**

2) **Design Centrado na Comunicação**

**Nome do Cenário: XXXXXX**

| tópico \> subtópico (diálogo) | falas e signos |
| :---- | :---- |
|  | U: Preciso … |
| \>  | U: Quero … D: Aqui está o mapa |
|  | U:  |
|  | U:  |
|  | D: Aqui está a informação filtrada |

3) **Mapa de Objetivos (cada um coloca seu mapa de objetivos e deverá ter um diagrama de consolidação)**

4) **Esquema Conceitual de Signos**

Exemplo: (fazer a junção das 3 tabelas abaixo em uma única)

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |
| :---- | :---- | :---- |
| **signo** | **origem** | **observações** |
| usuário | domínio |  |
| senha | domínio |  |

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |  |
| :---- | :---- | :---- | :---- |
| **signo** | **Tipo de conteúdo** | **restrição sobre conteúdo** | **valor default** |
| usuário | texto | não pode ser nulo | — |
| senha | texto | não pode ser nulo | — |

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |
| :---- | :---- | :---- |
| **signo** | **prevenção** | **recuperação** |
| usuário | PP: campo obrigatório | RA |
| senha | PP campo obrigatório  | RA |

# **Entrega 10 (data) \[em andamento/concluído\]**

**\[1 solução completa por pessoa da equipe\]**

**MOLIC**

**Nome do Cenário:**  
**Diagrama:**

# **Entrega 11 (data) \[em andamento/concluído\]**

**\[1 solução completa por pessoa da equipe\]**

# 

**Protótipo Correspondente ao MOLIC**  
**Link para o FIGMA:**

# **Entrega 12 (data) \[em andamento/concluído\]**

**\[1 solução por equipe\]**

# 

1) **Planejamento de Usabilidade (método DECIDE)**

| D |  |
| :---: | :---- |
| **E** |   |
| **C** |  |
| **I** |  |
| **D** |  |
| **E** | A análise e produção dos resultados precisam considerar vários aspectos… |

2) Lista de Instrumentos (exemplos \- dica… tudo pronto por atividades anteriores ou compartilhado pelo professor)  
   1) Termo de consentimento  
   2) Questionários  
   3) Tabela de Observação  
   4) Formulário de avaliação Heuristica.

# **Entrega 13 (data) \[em andamento/concluído\]**

DICA: MATERIAL ABAIXO DISPONÍVEL EM ARQUIVO NO MOODLE.

1) **Avaliação de IHC através de inspeção HEURÍSTICA \[1 solução completa por pessoa da equipe \- todas as telas do projeto\]**

**DICA: SOMENTE VIOLAÇÕES**

Dez Heurísticas de Nielsen

**Descrição da avaliação**

Avaliação heurística, definida por Nielsen e Molich (1994), é um método de avaliação de usabilidade onde um avaliador procura problemas de usabilidade numa interface com o usuário através da análise e interpretação de um conjunto de princípios ou heurísticas. Este método de avaliação é baseado no julgamento do avaliador.

1\. Primeiramente, leia e analise as dez heurísticas (ver Tabela 1).

**Tabela 1 \- Conjunto de heurísticas de Nielsen (1994)**

| 1\. | Visibilidade do status do sistema: |
| :---- | :---- |
| O sistema deve sempre manter os usuários informados sobre o que está acontecendo através de feedback apropriado, em um tempo razoável. |  |
| **2\.** | **Compatibilidade entre sistema e mundo real:** |
| O sistema deve utilizar a linguagem do usuário, com palavras, frases e conceitos familiares para ele, ao invés de termos específicos de sistemas. Seguir convenções do mundo real, fazendo com que a informação apareça em uma ordem lógica e natural. |  |
| **3\.** | **Controle e liberdade para o usuário:** |
| Estão relacionados à situação em que os usuários frequentemente escolhem as funções do sistema por engano e então necessitam de "uma saída de emergência” claramente definida para sair do estado não desejado sem ter que percorrer um longo diálogo, ou seja, é necessário suporte a *undo* e *redo*. |  |
| **4\.** | **Consistência e padrões:** |
| Referem-se ao fato de que os usuários não deveriam ter acesso a diferentes situações, palavras ou ações representando a mesma coisa. A interface deve ter convenções não-ambíguas. |  |
| **5\.** | **Prevenção de erros:** |
| Os erros são as principais fontes de frustração, ineficiência e ineficácia durante a utilização do sistema. |  |
| **6\.** |  **Reconhecimento em lugar de lembrança:** |
| Tornar objetos, ações, opções visíveis e coerentes. O usuário não deve ter que lembrar informações de uma parte do diálogo para outra. Instruções para o uso do sistema devem estar visíveis ou facilmente acessíveis. |  |
| **7\.** | **Flexibilidade e eficiência de uso:** |
| A ineficiência nas tarefas pode reduzir a eficácia do usuário e causar-lhes frustração. O sistema deve ser adequado tanto para usuários inexperientes quanto para usuários experientes. |  |
| **8\.** | **Projeto minimalista e estético:** |
| Os diálogos não devem conter informações irrelevantes ou raramente necessárias. Cada unidade extra de informação em um diálogo compete com unidades relevantes e diminui sua visibilidade relativa. |  |
| **9\.** | **Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros:** |
| Mensagens de erro devem ser expressas em linguagem natural (sem códigos), indicando precisamente o erro e sugerindo uma solução. |  |
| **10\.** | **Ajuda e documentação:** |
| Mesmo que seja melhor que o sistema possa ser usado sem documentação, pode ser necessário fornecer ajuda e documentação. Tais informações devem ser fáceis de encontrar, ser centradas na tarefa do usuário, listar passos concretos a serem seguidos e não ser muito grandes. A ajuda deve estar facilmente acessível e on-line. |  |

	2\. A seguir, avalie o sistema procurando possíveis problemas de usabilidade.   
3\. Quando um problema qualquer for detectado, classifique-o em uma das dez heurísticas de Nielsen, anotando o problema na tabela correspondente e atribuindo o **grau de severidade** (0 até 4\) para este problema (dado pela tabela 2\) e recomece novamente até não encontrar mais problemas de usabilidade.

**Tabela 2 \- Grau de severidade dos problemas de usabilidade**

| Grau de severidade | Tipo | Descrição |
| ----- | :---- | :---- |
| 0 | Sem importância | Não afeta a operação da interface |
| 1 | Cosmético | Não há necessidade imediata de solução |
| 2 | Simples | Problema de baixa prioridade (pode ser reparado) |
| 3 | Grave | Problema de alta prioridade (deve ser reparado) |
| 4 | Catastrófico | Muito grave, deve ser reparado de qualquer forma. |

**\[colocar o print\]**

**\[escolher a tabela de declaração de violação padrão da equipe\]**

2) **INDICAÇÃO DE BOAS PRÁTICAS DE HEURÍSTICA \- HEURÍSTICAS NÃO VIOLADAS \[1 solução completa por pessoa da equipe\]**

**DICA: 1 EXEMPLO DO SEU SISTEMA ONDE A HEURÍSTICA FOI ATENDIDA (ISSO NÃO É USADO NO MERCADO, SERVE APENAS PARA APRENDIZADO)**

# **Entrega 14 (data) \[em andamento/concluído\]**

**\[1 solução completa por pessoa da equipe\]**

**Método de Avaliação de Usabilidade por Observação do Usuário**   
**(o número de usuários observados é igual o número de membros da equipe)**

1) **Fluxograma de Avaliação de Usabilidade por Observação do Usuário \[1 solução por equipe\]**

2) **DESCRIÇÃO DO PROCEDIMENTO DE PREPARAÇÃO DO TESTE \[1 solução por equipe\]**

**Passo1:**  
**Passo 2: Lista de tarefas que o usuário deve cumprir.**  
**Passo 3: Formulário de perfil do usuário**  
**etc…**

3) **RESULTADOS DO TESTE \[1 solução por equipe\]**

**Avaliação de cada Tarefa (para cada usuário)**

| Tarefa | Grau de Sucesso | Total de Erros cometidos | Tipos de Erros | Tempo Necessário | Grau de Satisfação |
| ----- | ----- | ----- | ----- | ----- | ----- |
| **1** | **Sucesso Parcial** | **2** | **Não completou a tarefa(1), (1) Compreensão** | **5 segundos** | **Confusão Moderada** |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |

**Links dos vídeos:**

**Respostas do Formulário do Usuário:**

**Conclusão da avaliação por observação do usuário:**
