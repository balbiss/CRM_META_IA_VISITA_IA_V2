# Manual de funções — Visita IA CRM (rascunho)

> **Rascunho vivo.** Cada função nova do CRM é explicada aqui assim que fica pronta, em linguagem
> de imobiliária (sem termo técnico), pra depois virar o manual oficial entregue aos clientes.
> Público: **Dono**, **Gerente** e **Corretor**. Cada seção diz pra quem ela serve.
>
> Última atualização: 29/09/2026.

---

## 1. Roleta de atendimento

**Pra quem:** Dono e Gerente configuram; corretor recebe.

A roleta decide para qual corretor vai cada lead novo. Ninguém fura a fila e ninguém recebe dois
seguidos fora da vez. Ela funciona de dois jeitos, conforme o Aviso por WhatsApp (seção 2):

- **Com o Aviso por WhatsApp ligado: fila fixa.** Um lead para cada, **na ordem da lista** (1, 2,
  3… até o último) e depois volta para o 1º. A tela marca quem é o **PRÓXIMO** e quem **recebeu o
  último**, então o corretor confere sozinho de quem é a vez. Só quem está **bloqueado** é pulado.
  - Mudar a ordem pelas setas não faz ninguém perder a vez: o próximo é sempre quem vem depois
    de quem recebeu por último.
  - Tirar da roleta quem recebeu por último também não pula ninguém.
  - Dois leads que chegam no mesmo segundo vão para duas pessoas diferentes, uma depois da outra.
- **Sem o Aviso por WhatsApp:** o lead vai para o corretor **em plantão** que está há mais tempo
  sem receber.

Todo lead novo passa pela roleta, venha de onde vier: formulário do Facebook/Instagram, formulário
do site ou uma mensagem nova no WhatsApp da imobiliária.

### Como tirar alguém da roleta

1. Menu **Roleta**.
2. Na roleta onde a pessoa aparece, clique no **X** ao lado do nome dela.

Pronto: ela não recebe mais leads por essa roleta. Para colocar de volta, use **"+ Adicionar
corretor..."** no fim da lista.

- **Dono e Gerente não entram na roleta** por padrão. Só quem é corretor recebe lead.
- Se a pessoa vai ficar fora só por um tempo, outra opção é **bloquear o perfil** dela em
  **Equipe**. Perfil bloqueado nunca recebe lead, em nenhuma roleta.
- **Atenção:** se a imobiliária usa o **Aviso ao corretor por WhatsApp** (seção 2), desligar o
  "plantão" do corretor **não** tira ele da roleta. Nesse modo, o jeito é o **X** ou o bloqueio.

---

## 2. Aviso ao corretor por WhatsApp

**Pra quem:** o Dono ou Gerente liga; o corretor recebe no celular.

Quando a roleta entrega um lead para um corretor, ele recebe na hora uma mensagem **no WhatsApp
pessoal dele**, enviada pelo número da imobiliária, com os dados do lead:

> Olá, Bruno! **Novo lead atribuído a você**
> Nome · WhatsApp · E-mail (se tiver) · Canal · Campanha (se tiver)

Serve para a equipe que **não fica com o CRM aberto o dia todo**: o corretor fica sabendo na hora e
já liga para o cliente.

### Como ligar

**Integrações** → escolha o modo **número central** → marque **"Avisar o corretor por WhatsApp
(celular pessoal), sem passar pelo CRM"**.

Precisa de duas coisas:
- o número da imobiliária **conectado** em Integrações;
- o **telefone de cada corretor cadastrado** no perfil dele (em Equipe). Sem telefone, não tem
  como avisar.

### O que muda quando está ligado

- **Não precisa estar "online" ou de plantão.** Qualquer corretor da roleta recebe a qualquer
  hora, mesmo com o CRM fechado.
- **Não existe "Aceitar ou Recusar".** Quando a mensagem chega, o lead **já é dele**.
- **O lead continua no CRM normalmente.** Aparece no painel do corretor, na coluna "Lead Novo",
  com sininho de notificação. O WhatsApp é um aviso **a mais**, não substitui nada.
- A ordem da roleta **não muda**: continua a mesma regra justa da seção 1.

### Texto pronto para mandar à equipe

> Pessoal, boa noite! Vi que rolou dúvida sobre como fica a distribuição de lead agora que a gente
> ligou o aviso automático por WhatsApp, então deixa eu explicar certinho:
>
> A roleta continua exatamente igual. Não mudou a ordem, não mudou a justiça — continua caindo pra
> quem está há mais tempo sem receber lead, na sequência certa. Ninguém fura fila, ninguém recebe
> dobrado.
>
> A única diferença é que agora, além de cair no CRM, também chega uma mensagem no seu WhatsApp
> pessoal com o nome, telefone, e-mail (quando tiver), campanha e canal do lead — assim vocês ficam
> sabendo na hora, sem precisar ficar de olho no sistema o tempo todo.
>
> Vocês NÃO precisam estar "online" no CRM pra receber. Pode estar offline, sem plantão marcado,
> que o lead cai pra vocês do mesmo jeito — o aviso no WhatsApp já é a confirmação de que caiu.
>
> E não tem "aceitar ou recusar" nem prazo de 45 segundos — quando a mensagem chega, o lead já é
> oficialmente de vocês, já está registrado no painel de vocês lá dentro do CRM também. Podem entrar
> no sistema quando quiserem pra ver os detalhes, mover de etapa, anotar visita, etc. — tudo continua
> lá normalmente, o WhatsApp é só um aviso a mais pra ninguém perder tempo.
>
> Qualquer dúvida me chama!

---

## 3. Avisos por WhatsApp (histórico)

**Pra quem:** Dono e Gerente.

Menu **Ferramentas → Avisos por WhatsApp**. Mostra cada aviso que o CRM tentou mandar a um
corretor:

| Coluna | O que mostra |
|---|---|
| Quando | dia e hora |
| Lead | qual lead foi |
| Corretor | pra quem foi o aviso |
| Status | **✓ Enviado** ou **✗ Falhou** (com o motivo) |

Os botões **Todos / Enviados / Falharam** filtram a lista. Se aparecer falha, o lead **foi
atribuído do mesmo jeito**; só o aviso no celular não chegou. Vale conferir se o telefone do
corretor está certo e se o número da imobiliária continua conectado.

Para imobiliária que não usa o aviso por WhatsApp, a tela fica vazia ("Nenhum aviso ainda").

---

## 4. Mensagem nova no WhatsApp da imobiliária

**Pra quem:** todos.

Quando alguém manda mensagem pela primeira vez no **número da imobiliária** conectado ao CRM:

1. o CRM cria o lead sozinho na coluna **"Lead Novo"** (canal WhatsApp);
2. o lead passa pela **roleta**, igual aos leads de campanha;
3. se o Aviso por WhatsApp (seção 2) estiver ligado, o corretor sorteado é avisado.

Se o número **já é um lead** da imobiliária, a mensagem só entra na conversa dele. Não passa pela
roleta de novo e não gera aviso.

Se o **Agente de IA** (seção 6) estiver ligado, o passo 2 muda: a IA atende e qualifica primeiro, e
só então manda pra roleta.

> **Cuidado:** hoje, parente ou amigo que manda mensagem no número da imobiliária também vira lead.
> Uma lista de "números bloqueados" para o número central está **planejada** (ver Pendências).

---

## 5. WhatsApp de cada corretor: privacidade

**Pra quem:** corretores (e o Dono, que escolhe o modo).

No modo **"WhatsApp de cada corretor"** (Integrações), cada corretor conecta o próprio WhatsApp e
o CRM espelha as conversas com os clientes. Para proteger a vida pessoal do corretor:

### Só entra no CRM quem é lead

- Conversa com um **lead do corretor** aparece normalmente no CRM. Isso vale para qualquer lead
  que a roleta entregou para ele (Facebook, site, número central...). Não precisa fazer nada.
- Conversa com **quem não é lead** (família, amigos, outros contatos) **não entra no CRM** e o
  gestor não vê. Nenhuma mensagem dessas pessoas é guardada.

### Contatos novos no seu WhatsApp

Quando um número que não é lead manda mensagem, ele aparece para o corretor em **Conversas →
"Contatos novos no seu WhatsApp"**. **Só o próprio corretor vê essa lista**, nem o Dono nem o
Gerente. Aparece só o nome e o número, nunca o conteúdo.

Para cada contato, o corretor escolhe:
- **Trazer pro CRM**: é um cliente. Vira lead dele, na coluna "Lead Novo", e a conversa aparece em
  **Conversas** já com as últimas mensagens trocadas (até 30), puxadas do WhatsApp na hora. Dali pra
  frente, tudo é espelhado. Fotos, áudios e arquivos antigos aparecem como "Anexo (abra no WhatsApp
  pra ver)"; os novos chegam normalmente.
- **É pessoal**: família, amigo etc. O número **nunca mais aparece** no CRM.

Se não escolher nada, o contato só fica parado na lista dele.

### Números pessoais (desfazer)

Na mesma área, o link **"Números pessoais"** lista quem foi marcado como pessoal. **Desfazer** faz
a próxima mensagem daquele número voltar a aparecer em "Contatos novos".

### Tirar do CRM uma conversa que já tinha entrado

Abrindo a conversa, o botão **"Conversa pessoal"** (no topo, ao lado de "Ver lead") apaga aquele
lead e a conversa do CRM e passa a ignorar o número.

- Só funciona para conversa que **entrou pelo WhatsApp do próprio corretor**.
- Lead da imobiliária (que veio da roleta, de campanha, do site ou do número central) **não pode
  ser apagado assim**, mesmo que seja parente. Isso é proposital, para ninguém sumir com lead da
  empresa.
- O que é apagado **não volta**.

---

## 6. Agente de IA (atendimento e qualificação)

**Pra quem:** Dono e Gerente configuram. **Função adicional do plano**: precisa ser liberada pela
Visita IA. Sem liberação, a tela mostra "Função não liberada no seu plano".

A IA atende o cliente no WhatsApp da imobiliária, faz as perguntas de qualificação e **só depois**
manda o lead pra roleta, que funciona igualzinho (mesma ordem justa, aviso ao corretor e follow-up).
O corretor recebe o lead já qualificado.

### Onde a IA atua (você escolhe)

Menu **Ferramentas → Agente de IA → Configuração**:
- **Quem manda mensagem pela primeira vez no WhatsApp da imobiliária**: a IA responde.
- **Leads de formulário (Facebook, Instagram, Site)**: marque os canais em que a IA deve fazer o
  **primeiro contato**. Ela manda a primeira mensagem já usando o que o cliente preencheu
  (ex.: "Oi Maria, vi que você se interessou pelo apartamento no Jardim Europa...") e não repete o
  que já foi respondido. Canal desmarcado = vai direto pra roleta, como sempre.

A IA **só atua no número central** da imobiliária (nunca no WhatsApp pessoal de corretor) e **só em
lead sem corretor**. Cliente antigo que volta a falar vai direto pro corretor dele.

### O que configurar

- **Nome da atendente** e **tom de voz** (cordial, formal, descontraído).
- **Sobre a imobiliária**: o que a IA pode contar.
- **Instruções extras** (ex.: "não trabalhamos com imóveis rurais").
- **Perguntas de qualificação**: o que a IA precisa descobrir. Cada uma pode ser **obrigatória** e
  ter **opções** (ex.: Comprar, Alugar). A de **finalidade** decide a roleta (compra ou aluguel).
  Já vem uma lista pronta: finalidade, tipo de imóvel, região, faixa de valor, renda, pagamento e prazo.
- **Etiquetas que a IA pode colocar**: escolha a etiqueta e escreva quando usar
  (ex.: "Investidor: quando disser que é pra investir"). A IA só usa as desta lista.
- **Desqualificação**: casos em que o lead não tem perfil (ex.: "Renda familiar abaixo de R$ 2.500").
  Pra cada caso, escolha:
  - **Descartar**: o lead **não vai pra roleta**, vai pro **Bolsão (Rebatidas)** com o motivo (e a
    etiqueta, se você escolher uma). Se a IA errou, qualquer corretor pode puxar o lead.
  - **Só etiquetar e seguir**: coloca a etiqueta escolhida e o lead segue normal pra roleta.
  - **Antes de descartar, tentar** (opcional): uma tentativa de não perder o cliente. Ex.: no
    critério de renda, "perguntar se consegue compor renda com outra pessoa (cônjuge, familiar) ou
    usar FGTS". A IA faz essa pergunta **uma vez**; se o cliente topar, a conversa segue normal (e
    ela soma as rendas); só se ele confirmar que não tem jeito é que ela descarta.
  - **O que responder pra quem for descartado**: a IA explica com educação que, no momento, não tem
    uma opção que se encaixe (padrão), **ou** um texto fixo seu, sem citar motivo nenhum. O cliente
    nunca fica sem resposta.
- **Mensagem ao passar pro corretor**, **máximo de respostas da IA** e **tempos de espera**.
- **Apresentação**: na primeira resposta a IA se apresenta pelo nome e pela imobiliária, com
  bom dia/boa tarde/boa noite conforme a hora ("Oi, boa noite! Aqui é a Ana, da InoovaWeb Imóveis 😊").
  Ela não diz que é IA; só se o cliente perguntar diretamente, responde com honestidade que é uma
  assistente virtual e que um corretor vai continuar.
- **Jeito humano**:
  - **Espera antes de responder** (padrão 8 segundos): pra quem manda a mensagem em pedaços
    ("oi" · "tudo bem?" · "vi o anúncio"), cada mensagem nova reinicia a contagem, e a IA responde
    tudo de uma vez quando o cliente para de digitar. Se ele mandar mais alguma coisa enquanto a IA
    está "digitando", ela refaz a resposta considerando tudo, e nunca manda a mesma resposta duas vezes.
  - **Lida + "digitando…"**: depois da espera, a mensagem do cliente fica com o visto azul, aparece
    "digitando…" por um tempo proporcional ao tamanho da resposta, e às vezes a resposta vem em dois
    balões, como uma pessoa faria.

### Catálogo de imóveis e fotos

Com **"Sugerir imóveis do cadastro"** ligado (quadro "Catálogo de imóveis"):
- A cada resposta, o sistema procura no menu **Imóveis** os que combinam com o que o cliente
  procura: compra ou aluguel, tipo, bairro, faixa de valor (com 15% de folga) e quartos. A IA
  recebe **até 3** e só fala desses, **nunca inventa imóvel**.
- Assim que entende o que o cliente quer, a IA sugere 1 (no máximo 2) imóvel com os destaques e
  **sempre pergunta se ele quer ver as fotos**. As fotos **só são enviadas depois que o cliente
  pede ou aceita**.
- O envio sai sempre nesta ordem: uma frase curta ("Te mando as fotos aqui 👇") → **as fotos**
  numeradas (📷 1/3, 2/3...) → uma **ficha do imóvel** (endereço, valor, quartos, vagas, área,
  destaques, situação).
- O imóvel de que o cliente gostou fica **anotado no lead** (Imóvel de interesse), pro corretor.
- **"A IA pode informar o preço"**: desmarcado, ela diz que os valores o corretor passa.
- **"Fotos por imóvel"**: quantas fotos mandar (padrão 3). Só vão imóveis com foto no cadastro.
- Se o cliente veio de anúncio de um imóvel específico, esse imóvel entra sempre primeiro.

### Ligar anúncios da Meta a um imóvel ("Nome na campanha")

No cadastro do imóvel (menu **Imóveis → Editar**), preencha **"Nome na campanha de anúncio"** com o
**nome do meio** da campanha, o que fica entre o código e o [FORM]:

| Nome da campanha na Meta | O que cadastrar no imóvel |
|---|---|
| [NC 02]**[CENARIUM]**[FORM] | CENARIUM |
| [NC 03]**[CAMPO DOS PALMAS]**[FORM] | CAMPO DOS PALMAS |

- Copie do jeito que está na campanha. Maiúscula, minúscula e acento não fazem diferença.
- O código da campanha (NC 02, NC 03, NC 07...) e o [FORM] são ignorados: todas as campanhas daquele
  empreendimento caem no mesmo imóvel.
- Cadastre o **nome inteiro**, nunca só um pedaço ("Palmas" ou "Campo" sozinhos podem pegar outra
  campanha, tipo um futuro "CAMPO BELO").

Quando chegar um lead de formulário (Meta ou site) de uma campanha que contém esse nome:
- o lead já chega com o **imóvel de interesse** preenchido e com **compra/aluguel** do imóvel, o
  que manda ele pra roleta certa;
- o Agente de IA abre a conversa falando **daquele imóvel** ("Vi que você se interessou pelo
  lançamento de 2 quartos no Pedreira...") e pode mandar as fotos dele;
- o nome/código da campanha **nunca** é mostrado ao cliente.

Mais de um nome pro mesmo imóvel: separe por vírgula. Se dois imóveis casarem com a mesma campanha,
vale o nome mais completo.

### Áudio e região

- **Áudio:** se o cliente manda áudio enquanto a IA atende, ela **entende o áudio** e responde ao
  que foi dito. A **transcrição aparece embaixo do áudio** no CRM ("Transcrição: ..."), o que ajuda
  o corretor depois. Se o áudio não der pra entender, a IA pede com gentileza pra escrever.
- **Região pelo DDD:** a IA recebe a região do DDD do telefone (ex.: "91 = Belém e região") como
  **pista**, pra conversar com naturalidade ("procura aqui em Belém mesmo?"). Ela nunca afirma onde
  a pessoa mora nem preenche a região só pelo DDD. Localização por IP não existe no WhatsApp.

### Depois que a IA passa o lead

A IA avisa que vai encaminhar, e o sistema conta ao cliente a situação real:
- **Um corretor pegou:** "Quem vai continuar seu atendimento é o Bruno, já já fala com você por aqui".
- **Dentro do horário, mas ninguém livre:** "Nossos corretores estão em atendimento agora, mas assim
  que um ficar livre ele fala com você".
- **Fora do horário:** informa o horário de atendimento da imobiliária (o mesmo de Ajustes →
  Atendimento) e que um corretor fala com ele quando abrir.

O lead **sempre** é transferido, mesmo fora do horário: ele fica na fila e cai pro próximo
corretor que entrar de plantão. Se o cliente escrever de novo enquanto ninguém pegou, o sistema
responde "Recebi sua mensagem..." (no máximo uma vez por hora; "ok" e "obrigado" não recebem resposta).

### Quando a IA passa o lead pra roleta

- Terminou as perguntas obrigatórias e se despediu;
- O cliente **pediu pra falar com uma pessoa**;
- O cliente disse que **não tem interesse**;
- Chegou no **máximo de respostas** configurado;
- O cliente **não respondeu ao primeiro contato** no tempo configurado (padrão: 20 min);
- O cliente **parou de responder no meio** (padrão: 2 horas);
- O número **não tem WhatsApp**, ou a IA teve algum erro.

**Nenhum lead fica preso na IA**: em qualquer um desses casos ele vai pra roleta com o que ela já
descobriu.

### O que a equipe vê

- No **Kanban**, o card mostra "IA atendendo" enquanto a IA conversa.
- Em **Conversas**, o selo **IA** na lista e as mensagens da IA em verde-escuro com o selo
  "Agente de IA". Dá pra acompanhar tudo ao vivo.
- Na **ficha do lead**, o quadro **"Qualificação feita pelo Agente de IA"** com as respostas
  (ex.: Finalidade: Comprar · Região: Umarizal · Renda familiar: 12000). É o que o corretor lê antes
  de ligar.
- **Atendimentos da IA** (aba na tela do Agente): cada resposta da IA, o que o cliente disse, o que
  ela entendeu e por que passou pra roleta ou descartou.

### Assumir a conversa

- **Assumir** (em Conversas, Dono/Gerente): a IA para naquele lead e a equipe continua.
- **Passar pra roleta**: encerra a IA na hora e distribui com o que ela já coletou.
- Se alguém da equipe **responder o cliente** (pelo CRM ou pelo celular do número), a IA para
  sozinha naquele lead.
- Atribuir ou descartar o lead na mão também tira ele da IA.
- **Desligar o agente**: os leads que ela estava atendendo vão pra roleta.

### Chave da IA (custo)

A Visita IA define no plano de cada imobiliária:
- **Incluída no plano**: nada a configurar.
- **Chave própria**: a imobiliária cola a chave da OpenAI dela na tela do Agente (fica guardada
  criptografada). O custo das conversas fica na conta OpenAI dela.

---

## 7. Vários números (caixas de entrada)

A imobiliária pode conectar mais de um WhatsApp central. Exemplo: um número de **Vendas** e outro
de **Locação**.

**Onde:** Integrações → Números da imobiliária → "+ Conectar outro número". Dê um nome (rótulo)
para cada número, como "Vendas" ou "Locação". Esse nome aparece no resto do CRM.

### Regra de ouro: a conversa continua no número em que começou

Se o cliente chamou no número de Locação, tudo sai por esse número:
- as respostas da equipe;
- as respostas do Agente de IA;
- o follow-up automático.

O cliente nunca recebe mensagem de um número diferente do que ele conhece.

### Ligar número a uma equipe (Roletas → Editar regras)

- **"Só leads deste número de WhatsApp"**: quem chamar nesse número cai nessa roleta. Exemplo: o
  número de Locação vai para a equipe de Locação.
- **"Número do 1º contato (formulário/site)"**: aparece quando há mais de um número. Vale para os
  leads de formulário (Facebook, Instagram, site), que ainda não falaram com nenhum número. Ele
  define:
  - por qual número o Agente de IA faz o primeiro contato;
  - por qual número o corretor recebe o aviso do lead.
  
  Sem escolha, o CRM usa o primeiro número conectado.

### Aviso ao corretor

O aviso "Novo lead atribuído a você" sai pelo número por onde o lead chegou. Para lead de
formulário, sai pelo número de 1º contato da roleta. Se esse número estiver desconectado, o CRM
usa outro número conectado da imobiliária, para o aviso não se perder.

### Em quais números a IA atende (Agente de IA → Onde a IA atua)

Com mais de um número, aparece uma caixinha por número. Desmarque um número se ele não deve ter
IA; por exemplo, o número do pós-venda. Quem chamar nesse número vai direto para a roleta, sem IA.
A escolha salva na hora.

Um número sem IA também não é usado pela IA no primeiro contato de formulário. Se nenhum número
tiver IA, o lead de formulário vai direto para a roleta.

### Conversas

Com mais de um número:
- cada conversa mostra uma etiqueta com o nome do número;
- no topo há um filtro **"Todos os números"** para ver só as conversas de um deles;
- dentro da conversa, o cabeçalho mostra "pelo número X".

---

## Pendências (ainda não existem — não prometer ao cliente)

- **Agente de IA com personalidade diferente por número**: hoje a configuração da IA (prompt,
  perguntas, etiquetas) é a mesma para todos os números da imobiliária.

- **Números bloqueados no número central**: impedir que parentes/amigos do dono virem lead ao
  mandar mensagem no WhatsApp da imobiliária.
- **Agente de IA, próximas etapas**: resumo da qualificação dentro do aviso de WhatsApp ao
  corretor; agendar visita.
