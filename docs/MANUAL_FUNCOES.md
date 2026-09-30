# Manual de funções — Visita IA CRM (rascunho)

> **Rascunho vivo.** Cada função nova do CRM é explicada aqui assim que fica pronta, em linguagem
> de imobiliária (sem termo técnico), pra depois virar o manual oficial entregue aos clientes.
> Público: **Dono**, **Gerente** e **Corretor**. Cada seção diz pra quem ela serve.
>
> Última atualização: 29/09/2026.

---

## 1. Roleta de atendimento

**Pra quem:** Dono e Gerente configuram; corretor recebe.

A roleta decide para qual corretor vai cada lead novo. Ela é justa: o lead sempre vai para quem
está há **mais tempo sem receber**. Ninguém fura a fila e ninguém recebe dois seguidos fora da vez.

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
  - **Descartar**: o lead **não vai pra roleta**, vai pro **Bolsão (Rebatidas)** com o motivo. A IA
    se despede com educação, sem dizer o motivo. Se a IA errou, qualquer corretor pode puxar o lead.
  - **Só etiquetar e seguir**: coloca a etiqueta escolhida e o lead segue normal pra roleta.
- **Mensagem ao passar pro corretor**, **máximo de respostas da IA** e **tempos de espera**.
- **Jeito humano**:
  - **Espera antes de responder** (padrão 15 segundos): pra quem manda a mensagem em pedaços
    ("oi" · "tudo bem?" · "vi o anúncio"), cada mensagem nova reinicia a contagem, e a IA responde
    tudo de uma vez quando o cliente para de digitar.
  - **Lida + "digitando…"**: depois da espera, a mensagem do cliente fica com o visto azul, aparece
    "digitando…" por um tempo proporcional ao tamanho da resposta, e às vezes a resposta vem em dois
    balões, como uma pessoa faria.

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

## Pendências (ainda não existem — não prometer ao cliente)

- **Números bloqueados no número central**: impedir que parentes/amigos do dono virem lead ao
  mandar mensagem no WhatsApp da imobiliária.
- **Agente de IA, próximas etapas**: resumo da qualificação dentro do aviso de WhatsApp ao
  corretor; a IA consultar o catálogo de imóveis e agendar visita.
