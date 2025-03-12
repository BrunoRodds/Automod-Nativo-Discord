<a id="automod"></a>
# Automod Nativo do Discord 
Um compilado de palavras e regex para aprimorar o Automod nativo do Discord.

Este conteúdo foi reunido para otimizar o uso do Automod em seu servidor, incluindo uma lista de palavras comumente banidas e regras em regex para evitar spam e a divulgação de links. 

Para sugestões, modificações ou adições, entre em contato com o servidor [Warlocks Dungeons](https://discord.gg/wrJ6aVfDs9).

# 	
<br>

| Automod                     | Função                                                       |
|-----------------------------|-------------------------------------------------------------|
| <p align="center">[Palavras Proibidas](palavras_banidas)</p> | Automod de palavras comumente sinalizadas como impróprias. |
| <p align="center">[Markdowns (Regex)](regex_markdowns)</p> | Filtro em Regex para expressões regulares Anti-Markdowns.  |
| <p align="center">[Links e Convites (Regex)](regex_spam_links)</p> | Filtro em Regex para bloquear os envios de links e convites.  |

<br><br><br><br>
<a id="yagpdb"></a>
# Configurando o Bot YagPDB
O YagPDB oferece diversas ferramentas essenciais para gerenciar sua comunidade com segurança, incluindo proteção contra spam, flood e um sistema de automod personalizado. Para convidá-lo ao servidor, acesse sua [Página Oficial](https://yagpdb.xyz).

A seguir, listamos algumas dicas e recursos que podem ser utilizados em conjunto com o seu [Automod Nativo](#automod).  

# 	
<br>

**1. Criando um Automod contra Flood:**
> Após convidar o YagPDB, acesse o Painel de Configurações e vá até a aba **"Moderation → Advanced Automoderator"**. Nomeie a nova Ruleset como **"Flood"**.

<br>![image](https://github.com/user-attachments/assets/90f68a77-c50a-408f-a0ce-4add7d9d8988)
<br><br><br>

**2. Defina Canais e Cargos isentos da Regra:**
> Na aba **"Ruleset Scoped Conditions"**, defina os canais e cargos que devem ser excluídos da ação do Automod, como aqueles utilizados para moderação.

<br>![image](https://github.com/user-attachments/assets/51bf497d-4152-4ff4-bc33-5c11135e7691)
<br><br><br>

**3. Adicionando a Regra "Antiraid":**
> Descendo para o scopo **"Create a new rule"**, adicione **"Antiraid"** e clique em **"Create"**.

<br>![image](https://github.com/user-attachments/assets/d959abc4-462f-4626-8bf4-f5ee054b9bfe)
<br><br><br>


**4.1 Configurando a Regra "Antiraid":**
> Descendo até a nova Regra, em **"Triggers"**, adicione **"x user messages in y seconds"** e **"x consecutive identical messages"**, ajustando os limites conforme seu servidor.

<br>![image](https://github.com/user-attachments/assets/92c27cd8-ef3b-473f-b7e0-1008ec88ce65)
<br><br><br>

**4.2 Condições da Regra "Antiraid":**
> Em **"Conditions"**, adicione **"ignore roles"**, **"ignore bots"** e **"ignore channels"**, ajustando as exceções conforme seu servidor.

<br>![image](https://github.com/user-attachments/assets/e89d1536-8c2e-425f-b41d-20d2e4707de6)
<br><br><br>
