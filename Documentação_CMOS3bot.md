# <img src="https://cdn.discordapp.com/attachments/1375167062414069935/1378816268919898188/emoji_status.png?ex=683dfa37&is=683ca8b7&hm=8ad3d41e9ed8ddffc0db79975fdc87bdc602b08a454c9bc16fa1607f49022159&" alt="status emoji" width="64" height="64" style="vertical-align:middle; margin-right:12px;"/> CMOS3bot — Guia Completo de Uso

> ⚠️ **Aviso:** Este bot ainda está em desenvolvimento. Algumas funções podem mudar, apresentar instabilidades ou serem aprimoradas nas próximas versões. Use e reporte bugs ou sugestões!

> ❌ **aviso de versão:** Um erro de incompatibilidade do DSharpPlus fez que o cadastro e o login atraves de comandos slash (comandos ultilizado "/") não funcionar corretamente, mas não se precupe, o cadastro e login ainda é possivel ultilizando o prefixo "c;". Desculpe-me pelo transtorno, tentarei concertar o mais rapido o possivel! Ass: Mercury (Dev)

---

## Índice
- [Introdução](#introdução)
- [Como adicionar o bot ao seu servidor](#como-adicionar-o-bot-ao-seu-servidor)
- [Configuração inicial](#configuração-inicial)
- [Comandos disponíveis](#comandos-disponíveis)
  - [Comandos de moderação](#comandos-de-moderação)
  - [Comandos de utilidade](#comandos-de-utilidade)
  - [Comandos de perfil e sociais](#comandos-de-perfil-e-sociais)
  - [Comandos de administração](#comandos-de-administração)
  - [Comandos por DM](#comandos-por-dm)
- [Sistema de login e contas](#sistema-de-login-e-contas)
- [Permissões e segurança](#permissões-e-segurança)
- [Personalização de anúncios](#personalização-de-anúncios)
- [Status do bot](#status-do-bot)
- [Exemplos de uso](#exemplos-de-uso)
- [Dúvidas frequentes (FAQ)](#dúvidas-frequentes-faq)
- [Contato e suporte](#contato-e-suporte)
- [Política de Privacidade](#política-de-privacidade)
- [Termos de Serviço](#termos-de-serviço)

---

## Introdução
O **CMOS3bot** é um bot multi-servidor para Discord, focado em **moderação**, **utilidades**, **login seguro** e recursos sociais. Ele foi projetado para ser fácil de usar, seguro e compatível com múltiplos servidores.

---

## Como adicionar o bot ao seu servidor
1. Obtenha o link de convite do bot (fornecido pelo desenvolvedor).
2. Clique no link e selecione o servidor desejado.
3. Autorize as permissões solicitadas.
4. O bot aparecerá online e pronto para uso!

---

## Configuração inicial
- O bot funciona imediatamente após ser adicionado.
- Para comandos de moderação, apenas administradores ou o dono do servidor têm acesso.
- Recomenda-se criar um canal específico para anúncios e logs.
- Configure permissões do bot para garantir acesso aos canais necessários.
- É necessario uma conta no bot para ultilizar seus serviços.
- Os comandos não slash podem ser acionados com o prefixo "c;".
  
---

## Comandos disponíveis
Todos os comandos podem ser usados via **slash commands** (barra `/`) ou prefixo `c;` (ex: `c;ajuda`).

### Comandos de moderação
- `/banir <@usuário> <motivo>` — Bane um usuário do servidor.
- `/banirtemp <@usuário> <tempo> <motivo>` — Ban temporário (ex: 10m, 2h).
- `/desbanir <ID ou @usuário> <motivo>` — Remove o banimento de um usuário.
- `/expulsar <@usuário> <motivo>` — Expulsa (kick) o usuário.
- `/mutar <@usuário>` — Muta o usuário em canais de voz.
- `/desmutar <@usuário>` — Desmuta o usuário em canais de voz.
- `/timeout <@usuário> <tempo> <motivo>` — Timeout (mute temporário).
- `/untimeout <@usuário>` — Remove o timeout.
- `/limpar <quantidade>` — Limpa mensagens em lote.
- `/avisar <@usuário> <mensagem>` — Envia aviso privado ao usuário.
- `/anunciar <#canal> <mensagem> [cor_hex]` — Anúncio público customizável.
- `/logmoder <#canal>` — Define canal de logs de moderação.
- `/ficha <@usuário>` — Exibe histórico de punições, avisos e timeouts do usuário.
- `/triagem <@usuário> <motivo>` — Coloca usuário em triagem (restrição).

### Comandos de utilidade
- `/ajuda` — Mostra todos os comandos disponíveis.
- `/idinfo2 <ID>` — Mostra informações detalhadas de um usuário.
- `/convite` — Envia o painel de convite do bot.
- `/ping` — Mostra o ping do bot.

### Comandos de perfil e sociais
- `/cadastrar <nome> <senha>` — Cria uma conta no sistema do bot.
- `/login <nome> <senha>` — Faz login na sua conta do bot.
- `/perfil` — Exibe seu perfil ou de outro usuário.
- `/perfilinfo <@usuário>` — Exibe informações detalhadas do perfil de outro usuário.
- `/perfiledit <dados>` — Edita seu perfil do bot.

### Comandos por DM
- `c;meuid` — Mostra seu ID do Discord (apenas DM).
- `c;eco2 <mensagem>` — O bot repete sua mensagem (apenas DM).

---

## Sistema de login e contas
- O bot possui um sistema de contas **próprio** (separado do Discord).
- Para acessar recursos avançados, registre-se com `/cadastrar` e faça login com `/login`.
- As senhas são criptografadas com bcrypt.
- O login é necessário para acessar histórico de infrações e perfil completo.

---

## Permissões e segurança
- Apenas administradores e donos de servidor podem usar comandos de moderação.
- O bot verifica permissões universais do Discord (não depende de nomes de cargos).
- O dono do servidor sempre tem acesso total aos comandos de moderação.
- O bot não lê mensagens privadas, apenas comandos e informações necessárias para funcionamento.

---

## Personalização de anúncios
- O comando `/anunciar` permite definir uma cor personalizada para o embed usando um código hexadecimal (ex: `#FF5733`).
- O anúncio pode ser enviado em qualquer canal onde o bot tenha permissão.

---

## Exemplos de uso
- **Banir um usuário:**
  - `/banir @usuario Quebrou as regras`
- **Enviar um anúncio com cor personalizada:**
  - `/anunciar #avisos "Reunião hoje às 20h!" #00FF00`
- **Registrar uma conta no bot:**
  - `/cadastrar meuNick senhaSegura123`
- **Ver seu perfil:**
  - `/perfil`
- **Ver histórico de punições:**
  - `/ficha @usuario`

---

## Dúvidas frequentes (FAQ)
**1. Preciso criar conta no bot para usar comandos?**  
Sim, todos os comandos do bot exigem um login.

**2. O bot lê minhas mensagens?**  
Não, apenas comandos e informações necessárias para funcionamento.

**3. Como excluo minha conta do bot?**  
Envie um e-mail para cmos3dev@gmail.com solicitando a exclusão.

**4. O bot é gratuito?**  
Sim, todas as funções são gratuitas.

**5. O bot funciona em múltiplos servidores?**  
Sim, o bot é multi-servidor e mantém dados separados por servidor.

**6. Como vejo o histórico de punições de um usuário?**  
Use o comando `/ficha @usuario`.

**7. Como configuro logs de moderação?**  
Use `/logmoder #canal` para definir o canal de logs.

---

## Contato e suporte
- Dúvidas, sugestões ou problemas:  
  📩 **cmos3dev@gmail.com**

---

## Política de Privacidade
Leia a Política de Privacidade completa em:  
🔗 [Política de Privacidade do CMOS3bot](https://github.com/mercury063/termos-de-servico-CMOS3bot/blob/main/Termos_de_privacidade.md)

---

## Termos de Serviço
Leia os Termos de Serviço completos em:  
🔗 [Termos de Serviço do CMOS3bot](https://github.com/mercury063/termos-de-servico-CMOS3bot/blob/main/Termos_de_servi%C3%A7oes.md)

---
