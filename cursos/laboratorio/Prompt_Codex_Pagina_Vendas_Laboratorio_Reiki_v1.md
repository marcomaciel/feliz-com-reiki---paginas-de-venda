# Prompt e instruções para gerar a página de vendas do
# Laboratório de Percepção Energética para Reikianos

**Uso:** Visual Studio Code + Codex  
**Objetivo:** gerar o `index.html` da página de vendas do Laboratório usando como base técnica e visual a página de vendas de Reiki já existente, mas com uma estrutura comercial própria para esta oferta.

---

## 1. Fonte de referência

Use o arquivo atual `index.html` da página de Reiki como **referência de infraestrutura e padrão visual**, não como referência de copy.

Reaproveitar, quando fizer sentido:

- HTML semântico;
- Tailwind CSS;
- fontes;
- responsividade;
- espaçamentos;
- cards;
- sombras e bordas;
- AOS/animações;
- FAQ expansível;
- botão flutuante do WhatsApp;
- footer;
- padrão visual de CTA;
- seção da Kátia;
- componentes de agenda;
- padrão de acessibilidade já existente;
- organização do JavaScript.

### Importante

A página do Laboratório é uma oferta diferente.

**Não copiar:**

- narrativa do Reiki 3A;
- linguagem de “Mestre Interior”;
- “próximo nível”;
- “expansão da consciência” como eixo comercial;
- transformação 360º físico/mental/espiritual;
- lista extensa de módulos como principal elemento da página;
- promessas e textos da página de curso tradicional;
- geolocalização Brasil/Europa do checkout, porque nesta oferta o preço é segmentado por público e não por país.

Se o `index.html` de referência estiver no mesmo diretório em que será criada a nova página, primeiro faça uma cópia de segurança dele, por exemplo:

`reference-reiki-page.html`

Depois gere o novo `index.html`.

---

# 2. Produto

## Nome oficial

**Laboratório de Percepção Energética para Reikianos**

## Conceito

Um dia inteiro de prática, experimentação, troca e orientação.

O produto **não deve parecer mais uma aula teórica de Reiki**.

A experiência central é:

**praticar → perceber → comparar → perguntar → receber orientação → ganhar confiança**

O participante deve sentir que terá espaço para:

- praticar Reiki;
- experimentar exercícios;
- observar o que acontece durante a aplicação;
- comparar experiências;
- compartilhar dúvidas com outros reikianos;
- ouvir pessoas que vivem questões semelhantes;
- tirar dúvidas diretamente com a Mestra Kátia;
- receber orientação durante a prática.

---

# 3. Público

O Laboratório é destinado a **reikianos**.

Não assumir na copy que todo reikiano sente sensações nas mãos.

As duas frases que a Kátia mais escuta dos alunos são:

1. **“Não sinto nada.”**
2. **“Não sei se estou fazendo certo.”**

Ela também ouve, com frequência bem menor:

- “Não sei se o Reiki está funcionando.”
- “Não confio no que percebo.”

Esses dados devem orientar a estrutura, mas a pesquisa com a audiência ainda será usada para definir a hierarquia final da comunicação.

---

# 4. Headline já aprovada como direção principal

Usar no HERO:

## **Pare de se perguntar se você está fazendo Reiki certo.**

Essa headline pode ser usada agora.

## Subheadline

**Ainda não fechar uma subheadline definitiva.**

Criar no HTML uma subheadline provisória, discreta e facilmente substituível, marcada com comentário:

```html
<!-- TODO APÓS PESQUISA: revisar subheadline com base nas respostas reais -->
```

A subheadline provisória não deve:

- afirmar que todo mundo já sente;
- prometer que todo participante obrigatoriamente vai sentir energia;
- transformar “interpretar sinais” na dor principal;
- usar Byosen como termo comercial de entrada.

---

# 5. Princípio estratégico da oferta

Usar como base:

## **“Venda o que eles querem e entregue o que eles precisam.”**

### O que o aluno quer

A página deve conversar com pensamentos/desejos como:

- “Quero saber se estou fazendo Reiki certo.”
- “Eu não sinto nada.”
- “Será que sou capaz?”
- “Quero praticar sem ficar duvidando de mim.”
- “Quero ter mais segurança na aplicação.”
- “Quero poder perguntar para alguém experiente.”
- “Quero saber se o que acontece comigo é normal.”
- “Quero praticar junto com outros reikianos.”

### O que o Laboratório entrega

A Kátia desenhou uma entrega que inclui:

- prática;
- percepção;
- exercícios entre as mãos;
- observação;
- comparação de experiências;
- diferentes sensações;
- Byosen;
- Reiji-ho;
- orientação de como responder ao que é percebido;
- limites éticos;
- autocuidado;
- limpeza, proteção e preparação;
- prática em grupo;
- estrutura de atendimento;
- orientação direta da Kátia.

**Não transformar essa lista em headline.**

A página deve primeiro vender o desejo e a experiência.

---

# 6. Território emocional: SENTIR

“SENTIR” é um território importante da oferta, porque uma das frases mais recorrentes é:

**“Não sinto nada.”**

Porém, é obrigatório respeitar estes limites:

- não prometer “você vai finalmente sentir Reiki”;
- não afirmar que todas as mãos já percebem;
- não usar “Suas mãos já percebem. Você sabe reconhecer os sinais?”;
- não excluir quem sente pouco ou nada;
- não apresentar como fato que a maior dor seja “sentir e não saber interpretar”.

A pessoa que pensa “eu não sinto nada” precisa se reconhecer na página.

---

# 7. Tom da página

A copy e o design devem ser:

- simples;
- emocional;
- acolhedores;
- humanos;
- práticos;
- curiosos;
- confiáveis;
- diretos;
- sem exagero;
- sem promessas irreais;
- sem jargão técnico desnecessário.

Evitar:

- copy acadêmica;
- texto muito espiritualizado;
- excesso de abstração;
- excesso de módulos;
- listas técnicas muito cedo;
- linguagem corporativa;
- linguagem fria;
- “expansão energética” e semelhantes como promessa principal.

---

# 8. Direção visual

A página de referência tem boa infraestrutura e pode continuar reconhecível como parte do universo Feliz com Reiki/UniReiki.

Porém, o Laboratório deve ter uma sensação visual mais ligada a:

- prática;
- mãos;
- experimentação;
- interação;
- curiosidade;
- troca;
- presença da Kátia;
- pessoas praticando Reiki.

Menos foco visual em:

- pessoa meditando sozinha;
- espiritualidade abstrata;
- símbolos místicos como elemento principal;
- atmosfera excessivamente contemplativa.

## Cores

Pode manter a base Reiki atual como ponto de partida, mas não é obrigatório manter exatamente a mesma proporção do roxo da página 3A.

O design deve continuar leve, acolhedor e coerente com Reiki.

## Imagens

Não inventar imagens finais.

Onde não houver imagem adequada já disponível, criar um placeholder visual elegante e incluir comentário no HTML:

```html
<!-- TODO: substituir por imagem oficial do Laboratório -->
```

A foto existente da Kátia pode ser reaproveitada na seção sobre ela.

---

# 9. Estrutura da página

A página deve seguir esta sequência.

---

## BLOCO 1 — HERO

### Objetivo

Fazer o reikiano se reconhecer rapidamente e entender que existe uma experiência criada para ajudá-lo com essa insegurança.

### Incluir

- pequeno kicker com o nome do produto;
- headline:
  **Pare de se perguntar se você está fazendo Reiki certo.**
- subheadline provisória;
- CTA principal;
- 2 ou 3 microbenefícios curtos;
- elemento visual relacionado a prática/Reiki;
- indicação clara de que é uma experiência **ao vivo, prática e para reikianos**.

### CTA provisório

Pode usar:

**Quero participar do Laboratório**

Não criar urgência falsa.

---

## BLOCO 2 — IDENTIFICAÇÃO

### Objetivo

Mostrar ao visitante que suas dúvidas são comuns e que a página entende a realidade de quem pratica Reiki.

Trabalhar, de forma simples, questões como:

- “Não sinto nada.”
- “Será que estou fazendo certo?”
- sentir pouco;
- duvidar da própria capacidade;
- insegurança durante a prática.

Não afirmar que todas essas dores têm o mesmo peso.

Adicionar comentário:

```html
<!-- TODO APÓS PESQUISA: reorganizar as dores pela frequência real das respostas -->
```

Essa seção deve ser mais emocional que a seção “O momento do aluno” da página de Reiki tradicional.

---

## BLOCO 3 — O QUE É O LABORATÓRIO

### Objetivo

Explicar o conceito do produto.

Destacar:

**Não é mais uma aula para você assistir. É um dia para praticar Reiki.**

A seção deve mostrar a dinâmica:

**praticar → perceber → comparar → perguntar → receber orientação → ganhar confiança**

Comunicar que o participante terá:

- prática;
- experimentação;
- troca;
- dúvidas respondidas;
- contato com outros reikianos;
- orientação direta da Mestra Kátia.

---

## BLOCO 4 — COMO VAI FUNCIONAR O DIA

Não chamar de “módulos”.

Usar linguagem como:

**O que vamos viver juntos nesse dia**

ou equivalente simples.

### MANHÃ — Descobrindo sua percepção

Conteúdo proposto pela Kátia:

- exercício de percepção entre as mãos;
- aproximação e afastamento;
- diferenças entre calor, frio, pulsação, formigamento, pressão etc.;
- Byosen;
- Reiji-ho;
- como observar sem tentar adivinhar o que a pessoa tem;
- conversa sobre dúvidas comuns;
- autocuidado;
- orientações para trazer o Reiki mais presente para a vida;
- práticas de limpeza, proteção e preparação/expansão da energia Reiki.

### TARDE — Laboratório

- prática de aplicação;
- vivência em que uma pessoa recebe Reiki sem informar previamente onde sente desconforto;
- observação de onde o praticante percebe necessidade de atenção;
- aplicação prática;
- comparação de percepções;
- espaço para perguntas;
- orientação da Kátia.

### Limite ético

Inserir de forma clara, mas sem transformar a seção em aviso jurídico:

**O treinamento não ensina diagnóstico energético.**

O objetivo é desenvolver:

- atenção;
- percepção;
- prática;
- confiança.

Reiki é uma prática complementar e não substitui cuidado médico ou outros profissionais de saúde.

---

## BLOCO 5 — POR QUE UM LABORATÓRIO

### Objetivo

Mostrar o diferencial do formato.

Criar uma seção visual forte com ideias como:

- você pratica em vez de apenas ouvir;
- pode comparar sua experiência com outros reikianos;
- pode compartilhar dúvidas;
- recebe orientação durante o processo;
- pode perguntar diretamente à Kátia;
- aprende também com a troca do grupo.

Não exagerar na quantidade de texto.

---

## BLOCO 6 — PARA QUEM É

Criar a estrutura, mas deixar o conteúdo final fácil de editar depois da pesquisa.

Pode trabalhar provisoriamente com perfis como:

- reikianos que sentem pouco ou nada;
- quem se pergunta se está fazendo certo;
- quem quer praticar mais;
- quem quer mais confiança;
- quem aplica apenas em si;
- quem aplica em familiares/amigos;
- quem atende ou quer atender outras pessoas.

Adicionar:

```html
<!-- TODO APÓS PESQUISA: revisar perfis e ordem com base nos cruzamentos do formulário -->
```

---

## BLOCO 7 — BÔNUS 1

### Estrutura de um Atendimento Eficaz

Apresentar como bônus, não como eixo principal da promessa.

Incluir:

- preparação pessoal;
- preparação do ambiente;
- início da sessão;
- conversa/entrevista;
- situações inesperadas;
- encerramento;
- feedback;
- relatório final.

Fluxo:

**recepção → conversa inicial → aplicação → encerramento → feedback**

Casos propostos:

1. pessoa extremamente ansiosa;
2. pessoa fala durante toda a sessão;
3. pessoa começa a chorar;
4. pessoa diz: “Não senti absolutamente nada.”;
5. pessoa pergunta: “Você viu alguma coisa na minha energia?”.

---

## BLOCO 8 — BÔNUS 2

### Tratamento em grupo com a Mestra Kátia

A Kátia realizará um tratamento/sessão em grupo para:

- limpar;
- energizar os participantes;
- proporcionar uma experiência coletiva.

Apresentar de forma acolhedora, sem promessas médicas.

---

## BLOCO 9 — KÁTIA

Reaproveitar a estrutura visual da seção atual da Kátia, mas mudar a narrativa.

O foco não deve ser “Mestre Interior”.

Destacar a Kátia como:

- Mestra Reiki experiente;
- pessoa que estará presente no Laboratório;
- profissional que vai orientar as práticas;
- pessoa para quem o aluno poderá perguntar diretamente;
- facilitadora da troca e da experiência.

Usar somente credenciais já existentes e confirmadas na página de referência ou fornecidas pelo usuário.

Não inventar números de alunos, anos, certificações ou resultados.

---

## BLOCO 10 — AGENDA

Reaproveitar o componente visual de agenda da página existente.

### Informações já definidas

- realização planejada para **26/09/2026**;
- formato de um dia inteiro/quase inteiro;
- horário exato ainda deve ser confirmado.

Criar placeholders visíveis no código para o horário:

```html
<!-- TODO: confirmar horário oficial -->
```

Não criar um segundo dia como se estivesse confirmado.

---

## BLOCO 11 — OFERTA / PREÇO

### Valores definidos

**Alunos e ex-alunos: R$ 197**

**Público geral: R$ 297**

Importante:

A página de referência usa detecção geográfica BR/EU.

**Remover essa lógica para o Laboratório.**

O preço agora depende da relação com a Kátia/UniReiki, não da localização.

Criar duas opções/cards:

### Sou aluno ou ex-aluno
**R$ 197**

CTA com link placeholder:

`#LINK_ALUNO`

### Público geral
**R$ 297**

CTA com link placeholder:

`#LINK_PUBLICO`

Adicionar comentários claros no HTML para substituição dos links.

Não inventar parcelamento.

Não inventar garantia.

Não inventar desconto percentual.

Não usar preço riscado sem valor validado.

---

## BLOCO 12 — FAQ

Reaproveitar o componente de FAQ expansível.

Criar as perguntas abaixo.

Quando a resposta ainda depender de uma definição operacional, não inventar. Usar placeholder/TODO.

### Perguntas

1. Preciso ser reikiano para participar?
2. Qual nível de Reiki preciso ter?
3. E se eu não sentir nada durante as aplicações?
4. O Laboratório é só para terapeutas?
5. Posso participar mesmo aplicando Reiki apenas em mim?
6. Preciso de outra pessoa comigo para praticar?
7. O encontro é ao vivo e online?
8. Haverá gravação?
9. Receberei certificado?
10. O Laboratório ensina diagnóstico energético?
11. Como funciona o tratamento em grupo?
12. Como sei se tenho direito ao valor de aluno/ex-aluno?

### Respostas que já podem ser afirmadas

- O produto é para reikianos.
- Não é exclusivo para terapeutas.
- Quem aplica em si também faz parte do público.
- O treinamento não ensina diagnóstico energético.
- Reiki é prática complementar e não substitui cuidado médico.

### Respostas ainda pendentes

Marcar com TODO:

- nível mínimo exato;
- necessidade de parceiro de prática;
- gravação;
- certificado;
- critério operacional de aluno/ex-aluno;
- plataforma;
- horário oficial.

---

## BLOCO 13 — CTA FINAL

Fechar com convite simples.

Não usar “aceite o chamado”, “próximo nível” ou copy de formação espiritual.

O CTA pode reforçar:

- prática;
- oportunidade de tirar dúvidas;
- orientação da Kátia;
- experiência junto a outros reikianos.

Botão:

**Quero participar do Laboratório**

---

# 10. WhatsApp

Reaproveitar o botão flutuante.

Alterar a mensagem para algo relacionado ao Laboratório.

Usar placeholder para o número se necessário.

Mensagem sugerida para o link:

**Olá, gostaria de saber mais sobre o Laboratório de Percepção Energética para Reikianos da Kátia.**

Não adicionar argumentos comerciais dentro da mensagem automática.

---

# 11. Footer

Reaproveitar o footer atual:

- política de privacidade;
- termos;
- aviso legal;
- cookies;
- contato;
- copyright.

---

# 12. Requisitos técnicos

O novo `index.html` deve:

- continuar sendo um único arquivo HTML, salvo se houver necessidade técnica real de separar;
- manter Tailwind via CDN como na referência;
- manter fontes atuais, salvo motivo claro para alteração;
- ser totalmente responsivo;
- funcionar bem em mobile;
- preservar acessibilidade básica;
- usar `alt` adequado nas imagens;
- usar `loading="lazy"` fora do hero;
- manter FAQ funcional;
- manter AOS apenas se não prejudicar carregamento;
- evitar dependências adicionais desnecessárias;
- evitar JavaScript complexo;
- remover o JavaScript de detecção de país/checkout;
- não inserir trackers, pixels ou scripts que não existam na página de referência;
- não inventar URLs de checkout;
- não inventar imagens oficiais;
- não criar dados que ainda não foram definidos.

---

# 13. Marcação de conteúdo provisório

Sempre que algo ainda depender da pesquisa ou de decisão operacional, usar comentários claros no código.

Exemplos:

```html
<!-- TODO APÓS PESQUISA: revisar esta copy -->
```

```html
<!-- TODO: confirmar horário oficial -->
```

```html
<!-- TODO: inserir link de checkout para alunos/ex-alunos -->
```

```html
<!-- TODO: inserir link de checkout para público geral -->
```

```html
<!-- TODO: substituir por imagem oficial do Laboratório -->
```

Isso é obrigatório para evitar que conteúdo provisório seja confundido posteriormente com decisão fechada.

---

# 14. O que NÃO deve ser decidido pelo Codex

O Codex não deve inventar ou “otimizar” por conta própria:

- nova promessa principal;
- nova headline;
- subheadline definitiva;
- perfil principal do público;
- número de vagas;
- urgência;
- escassez;
- garantia;
- parcelamento;
- desconto;
- bônus adicionais;
- certificado;
- gravação;
- nível mínimo;
- horário;
- plataforma;
- links de checkout;
- depoimentos;
- números de alunos;
- resultados;
- estatísticas;
- claims de saúde;
- novos módulos.

Quando faltar uma informação, usar `TODO`.

---

# 15. Prompt pronto para colar no Codex

Copie o texto abaixo para o Codex no Visual Studio Code.

---

## PROMPT

Tenho neste projeto um `index.html` que é a página de vendas de um curso de Reiki e quero usá-lo como **referência técnica, visual e de infraestrutura** para criar a página de um novo produto:

**Laboratório de Percepção Energética para Reikianos**

Antes de editar qualquer coisa, leia o `index.html` atual por completo e entenda:

- estrutura;
- Tailwind;
- estilos customizados;
- fontes;
- AOS;
- FAQ;
- componentes;
- responsividade;
- WhatsApp;
- footer;
- JavaScript;
- checkout.

Se o arquivo atual for o mesmo que será substituído, primeiro faça uma cópia de segurança chamada:

`reference-reiki-page.html`

Depois gere um novo `index.html`.

### IMPORTANTE

Não adapte simplesmente a copy da página antiga.

O novo produto é diferente de um curso tradicional de Reiki.

A experiência do Laboratório é:

**praticar → perceber → comparar → perguntar → receber orientação → ganhar confiança**

O público é reikiano.

As duas frases que a Kátia mais escuta são:

- **“Não sinto nada.”**
- **“Não sei se estou fazendo certo.”**

A headline aprovada como direção principal é:

# **Pare de se perguntar se você está fazendo Reiki certo.**

Não invente outra headline.

A subheadline final ainda será refinada depois de uma pesquisa com a audiência. Crie uma versão provisória simples e marque-a no HTML com:

`<!-- TODO APÓS PESQUISA: revisar subheadline com base nas respostas reais -->`

Não assuma que todos os reikianos sentem sensações nas mãos.

Não use:

“Suas mãos já percebem. Você sabe reconhecer os sinais?”

Não prometa que todos vão “sentir energia” depois do Laboratório.

Não transforme Byosen em termo principal de venda.

Não transforme “interpretar sinais” na principal dor sem dados.

### ESTRUTURA DA PÁGINA

Crie a página nesta ordem:

1. HERO
   - nome do produto;
   - headline aprovada;
   - subheadline provisória;
   - CTA “Quero participar do Laboratório”;
   - 2 ou 3 microbenefícios;
   - informação de que é ao vivo, prático e para reikianos.

2. IDENTIFICAÇÃO
   - trabalhar “não sinto nada”;
   - “será que estou fazendo certo?”;
   - insegurança;
   - sentir pouco;
   - dúvida sobre a própria capacidade.
   - Marcar a ordem das dores com:
     `<!-- TODO APÓS PESQUISA: reorganizar as dores pela frequência real das respostas -->`

3. O QUE É O LABORATÓRIO
   - destacar que não é mais uma aula para assistir;
   - mostrar:
     **praticar → perceber → comparar → perguntar → receber orientação → ganhar confiança**
   - deixar claro que haverá troca com outros reikianos e orientação direta da Mestra Kátia.

4. COMO VAI FUNCIONAR O DIA
   - não chamar de módulos;
   - dividir em manhã e tarde.

   MANHÃ — Descobrindo sua percepção:
   - percepção entre as mãos;
   - aproximação e afastamento;
   - calor, frio, pulsação, formigamento, pressão etc.;
   - Byosen;
   - Reiji-ho;
   - observar sem tentar diagnosticar;
   - dúvidas comuns;
   - autocuidado;
   - limpeza, proteção e preparação.

   TARDE — Laboratório:
   - aplicação prática;
   - exercício em que uma pessoa recebe Reiki sem informar previamente onde sente desconforto;
   - observação;
   - comparação de percepções;
   - perguntas;
   - orientação da Kátia.

   Inserir de forma clara:
   **O treinamento não ensina diagnóstico energético.**
   Reiki é prática complementar e não substitui cuidados de saúde.

5. POR QUE UM LABORATÓRIO
   - praticar em vez de só ouvir;
   - compartilhar;
   - comparar;
   - perguntar;
   - receber orientação;
   - aprender com outros reikianos.

6. PARA QUEM É
   - criar estrutura editável;
   - reikianos que sentem pouco ou nada;
   - quem se pergunta se está fazendo certo;
   - quem quer praticar;
   - quem busca confiança;
   - quem aplica em si;
   - familiares/amigos;
   - terapeutas.
   - Marcar:
     `<!-- TODO APÓS PESQUISA: revisar perfis e ordem -->`

7. BÔNUS 1 — Estrutura de um Atendimento Eficaz
   - preparação;
   - ambiente;
   - conversa inicial;
   - aplicação;
   - situações inesperadas;
   - encerramento;
   - feedback;
   - relatório.
   - Mostrar o fluxo:
     **recepção → conversa inicial → aplicação → encerramento → feedback**

   Casos:
   - pessoa ansiosa;
   - pessoa fala durante toda a sessão;
   - pessoa começa a chorar;
   - “Não senti absolutamente nada.”;
   - “Você viu alguma coisa na minha energia?”.

8. BÔNUS 2 — Tratamento em grupo com a Mestra Kátia
   - experiência coletiva;
   - limpeza e energização;
   - sem claims médicos.

9. KÁTIA
   - reaproveitar a estrutura visual da seção da Kátia da página antiga;
   - usar credenciais já presentes no arquivo de referência;
   - mudar a narrativa para prática, orientação, proximidade e dúvidas respondidas;
   - não inventar credenciais ou números.

10. AGENDA
   - data: 26/09/2026;
   - um dia inteiro/quase inteiro;
   - horário ainda não confirmado;
   - usar:
     `<!-- TODO: confirmar horário oficial -->`

11. OFERTA
   - remover completamente a lógica de país BR/EU.
   - criar dois cards:

   **Alunos e ex-alunos — R$ 197**
   botão com link placeholder `#LINK_ALUNO`

   **Público geral — R$ 297**
   botão com link placeholder `#LINK_PUBLICO`

   Não inventar parcelamento, garantia ou preço riscado.

12. FAQ
   Criar FAQ expansível com:
   - Preciso ser reikiano?
   - Qual nível preciso ter?
   - E se eu não sentir nada?
   - É só para terapeutas?
   - Posso participar se aplico apenas em mim?
   - Preciso de outra pessoa para praticar?
   - É ao vivo e online?
   - Haverá gravação?
   - Receberei certificado?
   - Ensina diagnóstico energético?
   - Como funciona o tratamento em grupo?
   - Como sei se tenho direito ao preço de aluno/ex-aluno?

   Quando não houver resposta confirmada, usar TODO em vez de inventar.

13. CTA FINAL
   - convite simples;
   - foco em prática, dúvidas, troca e orientação;
   - botão:
     **Quero participar do Laboratório**

14. WHATSAPP
   - manter botão flutuante;
   - alterar mensagem para:
     “Olá, gostaria de saber mais sobre o Laboratório de Percepção Energética para Reikianos da Kátia.”

15. FOOTER
   - reaproveitar o atual.

### VISUAL

Reaproveite o padrão técnico da página de referência, mas faça o Laboratório parecer:

- mais prático;
- mais vivo;
- mais humano;
- mais ligado a mãos, aplicação, troca e experimentação;
- menos contemplativo;
- menos “curso espiritual avançado”.

Não invente imagens oficiais.

Quando necessário, use placeholder visual elegante e marque:

`<!-- TODO: substituir por imagem oficial do Laboratório -->`

A foto atual da Kátia pode ser reutilizada na seção dela.

### REQUISITOS TÉCNICOS

- HTML responsivo;
- mobile-first;
- Tailwind via CDN como na referência;
- manter FAQ funcional;
- manter AOS se fizer sentido;
- preservar boa acessibilidade;
- manter código limpo;
- remover JavaScript de geolocalização;
- não adicionar bibliotecas sem necessidade;
- não adicionar pixels ou trackers novos;
- não inventar links;
- não inventar dados.

### REGRA FINAL

Se qualquer informação necessária não estiver definida neste prompt ou no arquivo de referência, **não invente**.

Use comentários `TODO`.

Ao terminar:

1. revise o HTML completo;
2. confirme que não restaram textos do Reiki 3A;
3. confirme que não restou lógica de checkout por país;
4. confirme que todos os dados provisórios estão marcados com TODO;
5. confira mobile;
6. informe resumidamente quais pontos ficaram pendentes de conteúdo ou decisão.

---

# 16. Depois de gerar o HTML

Antes de considerar a página pronta para publicação, revisar manualmente:

- hero;
- textos provisórios;
- hierarquia das dores após resultado do formulário;
- subheadline;
- fotos;
- links;
- horário;
- nível mínimo;
- certificado;
- gravação;
- necessidade de parceiro;
- checkout;
- WhatsApp;
- comportamento mobile;
- FAQ;
- claims relacionados a saúde.

A página gerada agora deve ser considerada **estrutura avançada de trabalho**, não versão comercial final, até a incorporação dos resultados da pesquisa.
