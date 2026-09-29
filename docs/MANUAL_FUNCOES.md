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
- **Trazer pro CRM**: é um cliente. Vira lead dele, na coluna "Lead Novo", e dali pra frente a
  conversa é espelhada.
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

## Pendências (ainda não existem — não prometer ao cliente)

- **Números bloqueados no número central**: impedir que parentes/amigos do dono virem lead ao
  mandar mensagem no WhatsApp da imobiliária.
- **Agente de IA** que atende, qualifica e só depois manda o lead para a roleta certa (desenho
  combinado: a IA conversa e anota as respostas; quem decide a roleta é o CRM).
