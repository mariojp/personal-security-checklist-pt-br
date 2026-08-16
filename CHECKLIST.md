
[![Awesome](https://awesome.re/badge-flat2.svg)](https://github.com/zbetcheckin/Security_list)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/badge/LICENSE-CC_BY_4.0-00a2ff?&style=flat-square)](https://creativecommons.org/licenses/by/4.0/)
[![Contributors](https://img.shields.io/github/contributors/lissy93/personal-security-checklist?color=%23ffa900&style=flat-square)](https://github.com/Lissy93/personal-security-checklist/graphs/contributors)

<p align="center"><img src="https://i.ibb.co/rGQK71g/personal-security-checklist-6.png" /></p>

*<p align="center">Uma lista curada de dicas para proteger sua segurança e privacidade digital</p>*

### Conteúdo

[<img src="https://i.ibb.co/XbyGTrP/1-authentication-2-36x36.png" width="28" height="28" /> Autenticação](#authentication)<br>
[<img src="https://i.ibb.co/8KMrdbX/2-internet-36x36.png" width="28" height="28" /> Navegação na Web](#web-browsing)<br>
[<img src="https://i.ibb.co/7NrXW3L/5-email-36x36.png" width="28" height="28" /> Email](#emails)<br>
[<img src="https://i.ibb.co/DrWJBT9/13-messaging-36x36.png" width="28" height="28" /> Mensagens Seguras](#secure-messaging)<br>
[<img src="https://i.ibb.co/GFYyXMd/6-social-media-36x36.png" width="28" height="28" /> Redes Sociais](#social-media)<br>
[<img src="https://i.ibb.co/0VTZQpH/3-networking-36x36.png" width="28" height="28" /> Redes](#networking)<br>
[<img src="https://i.ibb.co/F3WwqsV/7-phones-36x36.png" width="28" height="28" /> Telefones Celulares](#mobile-devices)<br>
[<img src="https://i.ibb.co/ZftcgJq/8-computers-36x36.png" width="28" height="28" /> Computadores Pessoais](#personal-computers)<br>
[<img src="https://i.ibb.co/b2S9372/9-smart-home-36x36.png" width="28" height="28" /> Casa Inteligente](#smart-home)<br>
[<img src="https://i.ibb.co/4JTqL5y/12-finance-36x36.png" width="28" height="28" /> Finanças Pessoais](#personal-finance)<br>
[<img src="https://i.ibb.co/KVPV1Lk/10-human-36x36.png" width="28" height="28" /> Aspecto Humano](#sensible-computing)<br>
[<img src="https://i.ibb.co/9NbhBww/11-physical-36x36.png" width="28" height="28" /> Segurança Física](#physical-security)<br>

Muito longo? 🦒 Veja a [versão TLDR](https://github.com/Lissy93/personal-security-checklist/blob/HEAD/articles/2_TLDR_Short_List.md).

Para uma lista de softwares que respeitam a privacidade, confira [Awesome-Privacy](https://github.com/lissy93/awesome-privacy).

Um espelho deste repositório está disponível em [codeberg.org/alicia/personal-security-checklist](https://codeberg.org/alicia/personal-security-checklist).

---

<!-- checklist-start -->
## Autenticação

A maioria das violações de dados reportadas é causada pelo uso de senhas fracas, padrão ou roubadas (de acordo com [este relatório da Verizon](http://www.verizonenterprise.com/resources/reports/rp_dbir-2016-executive-summary_xg_en.pdf)). Use senhas longas, fortes e únicas, gerencie-as em um gerenciador de senhas seguro, habilite autenticação de 2 fatores, acompanhe vazamentos e tenha cuidado ao entrar em suas contas.

**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Use uma senha forte** | Essencial | Se a sua senha for muito curta, ou contiver palavras de dicionário, lugares ou nomes, ela poderá ser facilmente quebrada por força bruta ou adivinhada por alguém. A forma mais fácil de criar uma senha forte é torná-la longa (12+ caracteres) — considere usar uma 'frase-senha' composta por várias palavras. Como alternativa, use um gerador de senhas para criar uma senha aleatória longa e forte. Teste o [How Secure Is My Password? do Security.org](https://security.org/how-secure-is-my-password/) para ter uma ideia de quão rapidamente senhas comuns podem ser quebradas. Leia mais sobre como criar senhas fortes: [securityinabox.org](https://securityinabox.org/en/passwords/passwords/).
**Não reutilize senhas** | Essencial | Se alguém reutilizar uma senha e um site em que tinha conta sofrer um vazamento, um criminoso poderá obter acesso não autorizado às outras contas dessa pessoa com facilidade. Isso geralmente é feito por meio de solicitações automatizadas de login em larga escala e é chamado de Credential Stuffing. Infelizmente, isso é muito comum, mas é simples se proteger — use uma senha diferente para cada uma das suas contas online.
**Use um gerenciador de senhas seguro** | Essencial | Para a maioria das pessoas, é quase impossível lembrar centenas de senhas fortes e únicas. Um gerenciador de senhas é um aplicativo que gera, armazena e preenche automaticamente suas credenciais de login. Todas as suas senhas serão criptografadas com base em 1 senha mestra (que você deve lembrar e que deve ser muito forte). A maioria dos gerenciadores de senhas tem extensões de navegador e aplicativos móveis, então, qualquer que seja o dispositivo em que você esteja, suas senhas podem ser preenchidas automaticamente. Uma boa opção geral é o [Bitwarden](https://awesome-privacy.xyz/essentials/password-managers/bitwarden), ou veja [Gerenciadores de Senhas Recomendados](https://awesome-privacy.xyz/essentials/password-managers).
**Evite compartilhar senhas** | Essencial | Embora possa haver momentos em que você precise compartilhar o acesso a uma conta com outra pessoa, em geral você deve evitar isso, porque torna mais fácil a conta ser comprometida. Se você realmente precisar compartilhar uma senha — por exemplo, ao trabalhar em equipe com uma conta compartilhada — isso deve ser feito por meio de recursos internos de um gerenciador de senhas.
**Habilite a autenticação de 2 fatores** | Essencial | 2FA é quando você precisa fornecer algo que sabe (uma senha) e algo que possui (como um código no seu telefone) para entrar. Isso significa que, se alguém tiver sua senha (por exemplo, por phishing, malware ou vazamento de dados), não conseguirá acessar sua conta. É fácil começar: baixe [um aplicativo autenticador](https://github.com/Lissy93/awesome-privacy#2-factor-authentication) no seu telefone, depois vá até as configurações de segurança da sua conta e siga as etapas para habilitar 2FA. Na próxima vez que você entrar em um novo dispositivo, será solicitado o código exibido no aplicativo do seu telefone (ele funciona sem internet e o código geralmente muda a cada 30 segundos).
**Mantenha os códigos de backup em segurança** | Essencial | Quando você habilita a autenticação multifator, normalmente recebe vários códigos que pode usar caso seu método de 2FA seja perdido, quebrado ou fique indisponível. Guarde esses códigos em algum lugar seguro para evitar perda ou acesso não autorizado. Você deve armazená-los em papel ou em um local seguro em disco (por exemplo, armazenamento offline ou um arquivo/unidade criptografado). Não armazene isso no seu gerenciador de senhas, pois as fontes de 2FA e as senhas devem ser mantidas separadas.
**Cadastre-se para receber alertas de vazamento** | Opcional | Depois que um site sofre uma violação significativa de dados, os dados vazados frequentemente acabam na internet. Vários sites coletam esses registros vazados e permitem que você pesquise seu endereço de email para verificar se está em alguma de suas listas. [Firefox Monitor](https://monitor.firefox.com), [Have I Been Pwned](https://haveibeenpwned.com) e [DeHashed](https://dehashed.com) permitem que você se cadastre para monitoramento, no qual será notificado se seu endereço de email aparecer em novos conjuntos de dados. É útil saber disso o quanto antes para que você possa trocar as senhas das contas afetadas. [Have i been pwned](https://awesome-privacy.xyz/security-tools/online-tools/have-i-been-pwned) também tem notificação para o domínio inteiro, em que você pode receber alertas se algum endereço de email sob todo o seu domínio aparecer (útil se você usa aliases para [encaminhamento anônimo](https://github.com/Lissy93/awesome-privacy#anonymous-mail-forwarding)).
**Proteja sua senha/PIN** | Opcional | Ao digitar sua senha em locais públicos, certifique-se de não estar diretamente na linha de visão de uma câmera de CCTV e de que ninguém possa olhar por cima do seu ombro. Cubra sua senha ou código PIN enquanto digita e não revele senhas em texto puro na sua tela.
**Atualize periodicamente senhas críticas** | Opcional | Vazamentos e violações de bancos de dados são comuns e, provavelmente, várias de suas senhas já estão em algum lugar online. Atualizar ocasionalmente as senhas de contas críticas para a segurança pode ajudar a mitigar isso. Mas, desde que todas as suas senhas sejam longas, fortes e únicas, não há necessidade de fazer isso com muita frequência — uma vez por ano deve ser suficiente. Exigir trocas obrigatórias de senha em organizações [não é mais recomendado](https://duo.com/decipher/microsoft-will-no-longer-recommend-forcing-periodic-password-changes), pois incentiva colegas a escolherem senhas mais fracas.
**Não salve sua senha nos navegadores** | Opcional | A maioria dos navegadores modernos oferece salvar suas credenciais quando você entra em um site. Não permita isso, pois elas nem sempre são criptografadas e podem permitir que alguém acesse suas contas. Em vez disso, use um gerenciador de senhas dedicado para armazenar (e preencher automaticamente) suas senhas.
**Evite entrar em dispositivos de outras pessoas** | Opcional | Evite fazer login em computadores de outras pessoas, pois você não pode ter certeza de que o sistema delas está limpo. Tenha atenção especial com máquinas públicas, já que malware e rastreamento são mais comuns nelas. Usar o dispositivo de outra pessoa é especialmente perigoso com contas críticas, como banco online. Ao usar a máquina de outra pessoa, certifique-se de estar em uma sessão privada/anônima (Use Ctrl+Shift+N/ Cmd+Shift+N). Isso solicitará ao navegador que não salve suas credenciais, cookies e histórico de navegação.
**Evite dicas de senha** | Opcional | Alguns sites permitem que você defina dicas de senha. Muitas vezes, é muito fácil adivinhar as respostas. Nos casos em que dicas de senha forem obrigatórias, use respostas aleatórias e registre-as no seu gerenciador de senhas (`Nome da primeira escola: 6D-02-8B-!a-E8-8F-81`).
**Nunca responda com sinceridade a perguntas de segurança online** | Opcional | Se um site fizer perguntas de segurança (como local de nascimento, nome de solteira da mãe ou primeiro carro etc.), não forneça respostas reais. É uma tarefa trivial para hackers descobrir essas informações online ou por engenharia social. Em vez disso, crie uma resposta fictícia e armazene-a dentro do seu gerenciador de senhas. Usar palavras reais é melhor do que caracteres aleatórios, como [explicado aqui](https://news.ycombinator.com/item?id=29244870).
**Não use um PIN de 4 dígitos** | Opcional | Não use um PIN curto para acessar seu smartphone ou computador. Em vez disso, use uma senha de texto ou um PIN muito mais longo. Frases-senha numéricas são fáceis de quebrar (um PIN de 4 dígitos tem 10.000 combinações, em comparação com 7,4 milhões para um código alfanumérico de 4 caracteres).
**Evite usar SMS para 2FA** | Opcional | Ao habilitar a autenticação multifator, prefira códigos baseados em aplicativo ou um token de hardware, se houver suporte. SMS é suscetível a várias ameaças comuns, como [SIM-swapping](https://www.maketecheasier.com/sim-card-hijacking) e [interceptação](https://secure-voice.com/ss7_attacks). Também não há garantia de quão seguramente seu número de telefone será armazenado ou para que mais ele será usado. Do ponto de vista prático, SMS só funciona quando você tem sinal e pode ser lento. Se um site ou serviço exigir o uso de um número de SMS para recuperação, considere comprar um segundo número de telefone pré-pago usado apenas para recuperação de conta nesses casos.
**Evite usar seu gerenciador de senhas para gerar OTPs** | Avançado | Muitos gerenciadores de senhas também conseguem gerar códigos de 2FA. É melhor não usar seu gerenciador de senhas principal como autenticador de 2FA também, já que ele se tornaria um ponto único de falha se fosse comprometido. Em vez disso, use [um aplicativo autenticador](https://github.com/Lissy93/awesome-privacy#2-factor-authentication) dedicado no seu telefone ou laptop.
**Evite desbloqueio facial** | Avançado | A maioria dos telefones e laptops oferece um recurso de autenticação por reconhecimento facial, usando a câmera para comparar uma imagem do seu rosto com um hash armazenado. Pode ser muito conveniente, mas existem várias formas de [enganá-lo](https://www.forbes.com/sites/jvchamary/2017/09/18/security-apple-face-id-iphone-x/) e obter acesso ao dispositivo por meio de fotos digitais e reconstruções a partir de imagens de CCTV. Diferentemente da sua senha, provavelmente há fotos do seu rosto na internet e vídeos gravados por câmeras de vigilância.
**Fique atento a keyloggers** | Avançado | Um [keylogger](https://en.wikipedia.org/wiki/Hardware_keylogger) de hardware é um dispositivo físico colocado entre o seu teclado e a porta USB, que intercepta todas as teclas digitadas e às vezes retransmite os dados para um servidor remoto. Isso dá a um hacker acesso a tudo o que foi digitado, incluindo senhas. A melhor forma de se manter protegido é verificar sua conexão USB depois que o seu PC ficou sem supervisão. Também é possível que keyloggers sejam instalados dentro da carcaça do teclado, então procure por quaisquer sinais de violação e considere levar seu próprio teclado ao trabalho. Dados digitados em um teclado virtual, colados da área de transferência ou preenchidos automaticamente por um gerenciador de senhas não podem ser interceptados por um keylogger de hardware.
**Considere um token de hardware** | Avançado | Uma chave de segurança U2F/FIDO2 é um dispositivo USB (ou NFC) que você insere ao entrar em um serviço online para verificar sua identidade em vez de digitar um OTP do seu autenticador. [SoloKey](https://solokeys.com) e [NitroKey](https://www.nitrokey.com) são exemplos dessas chaves. Elas trazem vários benefícios de segurança. Como o navegador se comunica diretamente com o dispositivo, ele não pode ser enganado quanto a qual host está solicitando
**Use passkeys quando disponíveis** | Recomendado | Passkeys (também conhecidas como FIDO2 WebAuthn) são um método de autenticação sem senha mais seguro e conveniente do que senhas tradicionais. Elas usam a autenticação biométrica do seu dispositivo (impressão digital, face ID) ou um PIN para fazer login e são resistentes a ataques de phishing. Muitos serviços importantes agora suportam passkeys, incluindo Google, Apple, Microsoft e GitHub. Considere habilitar passkeys para contas que as oferecem como alternativa a senhas ou como método adicional de 2FA. autenticação porque o certificado TLS é verificado. [Este post](https://security.stackexchange.com/a/71704) é uma boa explicação sobre a segurança do uso de tokens FIDO U2F. Claro, é importante guardar a chave física em algum lugar seguro ou mantê-la com você. Algumas contas online permitem habilitar vários métodos de 2FA.
**Considere um gerenciador de senhas offline** | Avançado | Para maior segurança, um gerenciador de senhas offline e criptografado dará a você controle total sobre seus dados. [KeePass](https://awesome-privacy.xyz/essentials/password-managers/keepass) é uma escolha popular, com muitos [plugins](https://[KeePass](https://awesome-privacy.xyz/essentials/password-managers/keepass).info/plugins.html) e forks da comunidade com compatibilidade e funcionalidades adicionais. Clientes populares incluem: [KeePassXC](https://keepassxc.org) (desktop), [KeePassDX](https://www.keepassdx.com) (Android) e [StrongBox](https://apps.apple.com/us/app/strongbox-password-safe/id897283731) (iOS). A desvantagem é que pode ser um pouco menos conveniente para algumas pessoas, e caberá a você fazer backup e armazená-lo com segurança.
**Considere nomes de usuário únicos** | Avançado | Ter senhas diferentes para cada conta é um bom primeiro passo, mas, se você também usar um nome de usuário, email ou número de telefone único para fazer login, será significativamente mais difícil para qualquer pessoa tentar obter acesso não autorizado. O método mais fácil para vários emails é usar aliases gerados automaticamente para encaminhamento anônimo de emails. É aí que [anything]@yourdomain.com chegará à sua caixa de entrada, permitindo que você use um email diferente para cada conta (veja [Provedores de Alias de Email](https://github.com/Lissy93/awesome-privacy#mail-forwarding)). Nomes de usuário são mais fáceis, já que você pode usar seu gerenciador de senhas para gerá-los, armazená-los e preenchê-los automaticamente. Números de telefone virtuais podem ser gerados pelo seu provedor VOIP.

### Software recomendado
- [Gerenciadores de Senhas](https://awesome-privacy.xyz/essentials/password-managers)
- [Autenticação de 2 Fatores](https://awesome-privacy.xyz/essentials/2-factor-authentication)


## Navegação na Web

A maioria dos sites na internet usa alguma forma de rastreamento, muitas vezes para obter informações sobre o comportamento e as preferências de seus usuários. Esses dados podem ser incrivelmente detalhados e, por isso, são extremamente valiosos para corporações, governos e ladrões de propriedade intelectual. Violações e vazamentos de dados são comuns, e desanonimizar a atividade web dos usuários costuma ser uma tarefa trivial.

Existem dois métodos principais de rastreamento: com estado (baseado em cookies) e sem estado (baseado em fingerprint). Cookies são pequenos pedaços de informação armazenados no seu navegador com um ID único usado para identificá-lo. A impressão digital do navegador (browser fingerprinting) é uma forma altamente precisa de identificar e rastrear usuários onde quer que vão online. As informações coletadas são bastante abrangentes e frequentemente incluem detalhes do navegador, SO, resolução de tela, fontes suportadas, extensões, fuso horário, idioma e preferências de fonte, e até configurações de hardware.

Esta seção descreve as etapas que você pode seguir para estar melhor protegido contra ameaças, minimizar o rastreamento online e melhorar a privacidade.

**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Bloqueie anúncios** | Essencial | Usar um bloqueador de anúncios pode ajudar a melhorar sua privacidade ao bloquear os rastreadores implementados pelos anúncios. [uBlock Origin](https://awesome-privacy.xyz/networking/ad-blockers/ublock-origin) é um complemento de navegador muito eficiente e de código aberto, desenvolvido por Raymond Hill. Quando anúncios de terceiros são exibidos em uma página da web, eles podem rastreá-lo, coletando informações pessoais sobre você e seus hábitos, que podem então ser vendidas ou usadas para mostrar anúncios mais direcionados, e alguns anúncios são simplesmente maliciosos ou falsos. Bloquear anúncios também faz as páginas carregarem mais rápido, usa menos dados e oferece uma experiência menos poluída.
**Garanta que o site é legítimo** | Básico | Pode parecer óbvio, mas, ao fazer login em qualquer conta online, confira em dobro se a URL está correta. Salvar sites visitados com frequência nos favoritos é uma boa forma de garantir que a URL seja fácil de encontrar. Ao visitar novos sites, procure sinais comuns de que eles podem ser inseguros: avisos do navegador, redirecionamentos, spam no site e pop-ups. Você também pode verificar um site com uma ferramenta como: [Virus Total](https://awesome-privacy.xyz/security-tools/online-tools/virus-total), [IsLegitSite](https://www.islegitsite.com), [Google Safe Browsing Status](https://transparencyreport.google.com/safe-browsing/search), se estiver em dúvida.
**Fique atento a malware no navegador** | Básico | Seu sistema ou navegador pode ser comprometido por spyware, mineradores, sequestradores de navegador, redirecionamentos maliciosos, adware etc. Geralmente você consegue se proteger apenas ignorando pop-ups, tendo cuidado com o que clica e não prosseguindo para um site se o navegador avisar que ele pode ser malicioso. Sinais comuns de malware no navegador incluem: mecanismo de busca padrão ou página inicial modificados, barras de ferramentas, extensões ou ícones desconhecidos, quantidade significativamente maior de anúncios, erros e páginas carregando muito mais devagar do que o normal. Estes artigos da Heimdal explicam [sinais de malware no navegador](https://heimdalsecurity.com/blog/warning-signs-operating-system-infected-malware), [como navegadores são infectados](https://heimdalsecurity.com/blog/practical-online-protection-where-malware-hides) e [como remover malware do navegador](https://heimdalsecurity.com/blog/malware-removal).
**Use um navegador que respeite a privacidade** | Essencial | [Firefox](https://awesome-privacy.xyz/essentials/browsers/firefox) (com alguns ajustes) e [Brave](https://awesome-privacy.xyz/essentials/browsers/brave-browser) são navegadores seguros e que respeitam a privacidade. Ambos são rápidos, de código aberto, fáceis de usar e disponíveis nos principais sistemas operacionais. Seu navegador tem acesso a tudo o que você faz online, então, se possível, evite Google Chrome, Edge e Safari, pois (sem a configuração correta) os três coletam dados de uso, “ligam para casa” e permitem rastreamento invasivo. O Firefox exige algumas mudanças para alcançar segurança ideal, por exemplo, as configurações user.js do [arkenfox](https://github.com/arkenfox/user.js/wiki) ou do [12byte](https://12bytes.org/firefox-configuration-guide-for-privacy-freaks-and-performance-buffs/). Veja mais em: [Navegadores Privados](https://github.com/Lissy93/awesome-privacy#browsers).
**Use um mecanismo de busca privado** | Essencial | Usar um mecanismo de busca que preserve a privacidade e não rastreie reduzirá o risco de que seus termos de pesquisa sejam registrados ou usados contra você. Considere [DuckDuckGo](https://awesome-privacy.xyz/essentials/search-engines/duckduckgo) ou [Qwant](https://awesome-privacy.xyz/essentials/search-engines/qwant). O Google implementa algumas políticas de rastreamento [incrivelmente invasivas](https://hackernoon.com/data-privacy-concerns-with-google-b946f2b7afea) e tem histórico de exibir [resultados de busca tendenciosos](https://www.businessinsider.com/evidence-that-google-search-results-are-biased-2014-10). Portanto, Google, junto com Bing, Baidu, Yahoo e Yandex, é incompatível com quem busca proteger a própria privacidade. Recomenda-se atualizar a [busca padrão do seu navegador](https://duckduckgo.com/install) para um mecanismo que respeite a privacidade.
**Remova extensões desnecessárias do navegador** | Essencial | Extensões conseguem ver, registrar ou modificar tudo o que você faz no navegador, e alguns aplicativos de navegador aparentemente inocentes têm intenções maliciosas. Sites conseguem ver quais extensões você instalou e podem usar isso para fortalecer sua impressão digital, identificando/rastreando você com mais precisão. Tanto a loja do [Firefox](https://awesome-privacy.xyz/essentials/browsers/firefox) quanto a Chrome Web Store permitem verificar quais permissões/direitos de acesso uma extensão exige antes de instalá-la. Veja as avaliações. Instale apenas extensões de que você realmente precisa e remova as que não usa há algum tempo.
**Mantenha o navegador atualizado** | Essencial | Vulnerabilidades de navegador estão constantemente sendo [descobertas](https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=browser) e corrigidas, então é importante mantê-lo atualizado para evitar um exploit de zero-day. Você pode [ver qual versão do navegador está usando aqui](https://www.whatismybrowser.com/), ou seguir [este guia](https://www.whatismybrowser.com/guides/how-to-update-your-browser/) com instruções de atualização. Alguns navegadores serão atualizados automaticamente para a versão estável mais recente.
**Verifique se há HTTPS** | Essencial | Se você inserir informações em um site sem HTTPS, esses dados serão transportados sem criptografia e, portanto, poderão ser lidos por qualquer pessoa que os intercepte. Não insira nenhum dado em um site sem HTTPS, mas também não deixe que o cadeado verde lhe dê uma falsa sensação de segurança: só porque um site tem certificado SSL, não significa que ele seja legítimo ou confiável. [HTTPS-Everywhere](https://www.eff.org/https-everywhere) (desenvolvido pela [EFF](https://www.eff.org/)) costumava ser uma extensão/complemento de navegador que habilitava HTTPS automaticamente nos sites, mas desde 2022 está descontinuada. Em seu [artigo de anúncio](https://www.eff.org/), a EFF explica que a maioria dos navegadores agora integra essas proteções. Além disso, o texto fornece instruções para os navegadores [Firefox](https://awesome-privacy.xyz/essentials/browsers/firefox), Chrome, Edge e Safari sobre como habilitar suas proteções seguras de HTTPS.
**Use DNS-over-HTTPS** | Essencial | O DNS tradicional faz requisições em texto puro para todos verem. Isso permite espionagem e manipulação dos dados de DNS por meio de ataques man-in-the-middle. Já o DNS-over-HTTPS faz a resolução de DNS via protocolo HTTPS, o que significa que os dados entre você e seu resolvedor DNS são criptografados. Uma opção popular é o [1.1.1.1](https://awesome-privacy.xyz/security-tools/mobile-apps/1.1.1.1) da [CloudFlare](https://awesome-privacy.xyz/networking/dns-providers/cloudflare), ou compare provedores — é simples habilitar no navegador. Observe que DoH tem seus próprios problemas, principalmente impedir filtragem web.
**Contêineres Multi-[Session](https://awesome-privacy.xyz/communication/encrypted-messaging/session)** | Essencial | Compartimentalização é realmente importante para manter separados os diferentes aspectos da sua navegação. Por exemplo, usar perfis diferentes para trabalho, navegação geral, redes sociais, compras online etc. reduzirá o número de associações que corretores de dados podem vincular a você. Uma opção é usar [Firefox Containers](https://awesome-privacy.xyz/security-tools/browser-extensions/firefox-multi-account-containers), que foi projetado exatamente para esse propósito. Como alternativa, você pode usar navegadores diferentes para tarefas diferentes ([Brave](https://awesome-privacy.xyz/essentials/browsers/brave-browser), [Firefox](https://awesome-privacy.xyz/essentials/browsers/firefox), [Tor](https://awesome-privacy.xyz/networking/mix-networks/tor) etc).
**Use modo anônimo** | Essencial | Ao usar a máquina de outra pessoa, certifique-se de estar em uma sessão privada/anônima. Isso impedirá que histórico do navegador, cookies e alguns dados sejam salvos, mas não é infalível — você ainda pode ser rastreado.
**Entenda a impressão digital do seu navegador** | Essencial | A impressão digital do navegador (Browser Fingerprinting) é um método incrivelmente preciso de rastreamento, em que um site identifica você com base nas informações do seu dispositivo. Você pode ver sua impressão digital em amiunique.org — o objetivo é ser o menos único possível.
**Gerencie cookies** | Essencial | Limpar cookies regularmente é uma medida que você pode tomar para ajudar a reduzir o rastreamento por sites. Cookies também podem armazenar seu token de sessão, que, se capturado, permitiria a alguém acessar suas contas sem credenciais. Para mitigar isso, limpe os cookies com frequência.
**Bloqueie cookies de terceiros** | Essencial | Cookies de terceiros são colocados no seu dispositivo por um site diferente daquele que você está visitando. Isso representa um risco à privacidade, já que uma terceira entidade pode coletar dados da sua sessão atual. Este guia explica como você pode desabilitar cookies de terceiros, e você pode verificar aqui para garantir que isso funcionou.
**Bloqueie rastreadores de terceiros** | Essencial | Bloquear rastreadores ajudará a impedir que sites, anunciantes, ferramentas de análise e outros rastreiem você em segundo plano. [Privacy Badger](https://awesome-privacy.xyz/security-tools/browser-extensions/privacy-badger), [DuckDuckGo Privacy Essentials](https://awesome-privacy.xyz/security-tools/browser-extensions/privacy-essentials), [uBlock Origin](https://awesome-privacy.xyz/networking/ad-blockers/ublock-origin) e uMatrix (avançado) são bloqueadores de rastreadores muito eficazes e de código aberto, disponíveis para os principais navegadores.
**Cuidado com redirecionamentos** | Opcional | Embora alguns redirecionamentos sejam inofensivos, outros, como redirecionamentos não validados, são usados em ataques de phishing, podendo fazer um link malicioso parecer legítimo. Se você não tiver certeza sobre uma URL de redirecionamento, pode verificar para onde ela encaminha com uma ferramenta como RedirectDetective.
**Não faça login no seu navegador** | Opcional | Muitos navegadores permitem que você faça login para sincronizar histórico, favoritos e outros dados de navegação entre dispositivos. No entanto, isso não apenas permite mais coleta de dados, como também aumenta a superfície de ataque ao oferecer mais um caminho para que um agente malicioso obtenha suas informações pessoais.
**Desative serviços de predição** | Opcional | Alguns navegadores permitem serviços de predição, nos quais você recebe resultados de busca em tempo real ou preenchimento automático de URL. Se isso estiver habilitado, os dados serão enviados ao Google (ou ao seu mecanismo de busca padrão) a cada tecla pressionada, em vez de apenas quando você apertar Enter.
**Evite G Translate para páginas da web** | Opcional | Ao visitar uma página escrita em outro idioma, você pode ser solicitado a instalar a extensão Google Translate. Esteja ciente de que o Google coleta todos os dados (incluindo campos de entrada), junto com detalhes do usuário atual. Em vez disso, use um serviço de tradução que não esteja vinculado ao seu navegador.
**Desative notificações web** | Opcional | Notificações push do navegador são um método comum para criminosos incentivarem você a clicar em seus links, já que é fácil falsificar a origem. Esteja ciente disso e, para instruções sobre como desabilitar notificações do navegador, veja este artigo.
**Desative downloads automáticos** | Opcional | Downloads drive-by são uma forma comum de colocar arquivos nocivos no dispositivo de um usuário. Isso pode ser mitigado desativando downloads automáticos de arquivos e tendo cautela com sites que peçam para você baixar arquivos inesperadamente.
**Negue acesso a sensores** | Opcional | Sites móveis podem acessar os sensores do seu dispositivo sem pedir. Se você conceder essas permissões ao navegador uma vez, então todos os sites poderão usar esses recursos, sem permissão ou notificação.
**Negue acesso à localização** | Opcional | Serviços de localização permitem que sites solicitem sua localização física para melhorar sua experiência. Isso deve ser desativado nas configurações. Observe que ainda existem outros métodos de determinar sua localização aproximada.
**Negue acesso à câmera/microfone** | Opcional | Verifique as configurações do navegador para garantir que nenhum site tenha acesso à webcam ou ao microfone. Também pode ser benéfico usar proteção física, como tampa para webcam e bloqueador de microfone.
**Desative o salvamento de senhas no navegador** | Opcional | Não permita que seu navegador armazene nomes de usuário e senhas. Eles podem ser facilmente visualizados ou acessados. Em vez disso, use um gerenciador de senhas.
**Desative o preenchimento automático do navegador** | Opcional | Desative o autofill para quaisquer detalhes confidenciais ou pessoais. Esse recurso pode ser prejudicial se seu navegador for comprometido de alguma forma. Em vez disso, considere usar o recurso de Notas do seu gerenciador de senhas.
**Proteja-se contra ataque de exfiltração** | Opcional | O ataque CSS Exfiltrate é um método em que credenciais e outros detalhes sensíveis podem ser capturados usando apenas CSS puro. Você pode se manter protegido com o plugin [CSS Exfil Protection](https://awesome-privacy.xyz/security-tools/browser-extensions/css-exfil-protection).
**Desative ActiveX** | Opcional | ActiveX é uma API de extensão de navegador integrada ao Microsoft IE e habilitada por padrão. Não é mais muito usada, mas, como concede permissões de acesso profundas aos plugins e pode ser perigosa, você deve desativá-la.
**Desative WebRTC** | Opcional | WebRTC permite comunicação de áudio/vídeo de alta qualidade e compartilhamento de arquivos P2P diretamente do navegador. No entanto, pode representar um vazamento de privacidade. Para saber mais, confira este guia.
**Mascare a assinatura do HTML5 Canvas** | Opcional | Canvas Fingerprinting permite que sites identifiquem e rastreiem usuários com muita precisão. Você pode usar a extensão Canvas-Fingerprint-Blocker para mascarar sua impressão digital ou usar [Tor](https://awesome-privacy.xyz/networking/mix-networks/tor).
**Mascare o agente do usuário (User Agent)** | Opcional | O user agent informa ao site qual dispositivo, navegador e versão você está usando. Alterá-lo periodicamente é um pequeno passo que você pode dar para se tornar menos único.
**Desconsidere DNT** | Opcional | Habilitar Do Not Track tem impacto muito limitado, já que muitos sites não respeitam isso. Como é raramente usado, também pode se somar à sua assinatura, tornando você mais único.
**Evite rastreamento por HSTS** | Opcional | HSTS foi projetado para ajudar a proteger sites, mas preocupações de privacidade foram levantadas porque permitia que operadores plantassem supercookies. Ele pode ser desativado visitando chrome://net-internals/#hsts em navegadores baseados em Chromium.
**Evite conexões automáticas do navegador** | Opcional | Mesmo quando você não está usando o navegador, ele pode “ligar para casa” para relatar atividade de uso, análises e diagnósticos. Você pode querer desabilitar parte disso, o que pode ser feito nas configurações.
**Habilite isolamento de primeira parte** | Opcional | [First Party Isolation](https://awesome-privacy.xyz/security-tools/browser-extensions/first-party-isolation) significa que todas as fontes de identificação e o estado do navegador são delimitados usando o domínio da barra de URL, o que pode reduzir bastante o rastreamento.
**Remova parâmetros de rastreamento das URLs** | Avançado | Os sites frequentemente acrescentam parâmetros GET adicionais às URLs em que você clica para identificar informações como origem/referenciador. Você pode higienizar isso manualmente, ou usar uma extensão como [ClearURLs](https://awesome-privacy.xyz/security-tools/browser-extensions/clearurls) para remover dados de rastreamento das URLs automaticamente.
**Segurança no primeiro lançamento** | Avançado | Depois de instalar um navegador web, na primeira vez que você o abre (antes de configurar as opções de privacidade), a maioria dos navegadores “liga para casa”. Portanto, após instalar um navegador, você deve primeiro desabilitar sua conexão com a internet, configurar as opções de privacidade e só então reativar a conectividade.
**Use o navegador Tor** | Avançado | O projeto [Tor](https://awesome-privacy.xyz/networking/mix-networks/tor) fornece um navegador que criptografa e roteia seu tráfego por vários nós, mantendo usuários protegidos contra interceptação e rastreamento. As principais desvantagens são velocidade e experiência de uso.
**Desative JavaScript** | Avançado | Muitos aplicativos web modernos são baseados em JavaScript, então desativá-lo reduzirá bastante sua experiência de navegação. Mas, se você realmente quiser ir ao extremo, isso reduzirá bastante sua superfície de ataque.

### Software recomendado
- [Navegadores Privados](https://github.com/Lissy93/awesome-privacy#browsers)
- [Extensões de Navegador](https://github.com/Lissy93/awesome-privacy#browser-extensions)
- [Sincronização de Navegador e Favoritos](https://github.com/Lissy93/awesome-privacy#browser-sync)


## Email

Quase 50 anos desde que o primeiro email foi enviado, ele ainda é uma grande parte do nosso dia a dia e continuará sendo no futuro próximo. Portanto, considerando o quanto confiamos nele, é surpreendente quão fundamentalmente insegura é essa infraestrutura. Fraudes relacionadas a email [estão aumentando](https://www.csoonline.com/article/3247670/email/email-security-in-2018.html), e, sem tomar medidas básicas, você pode estar em risco.

Se um hacker obtiver acesso aos seus emails, isso oferece uma porta de entrada para que suas outras contas sejam comprometidas (por meio de redefinições de senha), portanto a segurança do email é primordial para a sua segurança digital.

As grandes empresas que oferecem serviço de email “gratuito” não têm boa reputação no respeito à privacidade dos usuários: o Gmail foi pego dando [acesso total a terceiros](https://www.wsj.com/articles/techs-dirty-secret-the-app-developers-sifting-through-your-gmail-1530544442) aos emails dos usuários e também [rastreamento de todas as suas compras](https://www.cnbc.com/2019/05/17/google-gmail-tracks-purchase-history-how-to-delete-it.html). O Yahoo também foi pego escaneando emails em tempo real [para agências de vigilância dos EUA](http://news.trust.org/item/20161004170601-99f8c). Anunciantes [receberam acesso](https://thenextweb.com/insider/2018/08/29/both-yahoo-and-aol-are-scanning-customer-emails-to-attract-advertisers) às mensagens de usuários do Yahoo e AOL para “identificar e segmentar clientes em potencial ao captar sinais contextuais de compra e compras passadas”.

**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Tenha mais de um endereço de email** | Essencial | Considere usar um endereço de email diferente para comunicações críticas de segurança e para mensagens triviais, como newsletters. Essa compartimentalização pode reduzir a quantidade de dano causada por uma violação de dados e também facilitar a recuperação de uma conta comprometida.
**Mantenha seu endereço de email privado** | Essencial | Não compartilhe seu email principal publicamente, pois endereços de email frequentemente são o ponto de partida para a maioria dos ataques de phishing.
**Mantenha sua conta segura** | Essencial | Use uma senha longa e única, habilite 2FA e tenha cuidado ao fazer login. Sua conta de email fornece um ponto de entrada fácil para todas as suas outras contas online para um invasor.
**Desative o carregamento automático de conteúdo remoto** | Essencial | Mensagens de email podem conter conteúdo remoto, como imagens ou folhas de estilo, frequentemente carregadas automaticamente do servidor. Você deve desabilitar isso, pois expõe seu endereço IP e informações do dispositivo e muitas vezes é usado para rastreamento. Para mais informações, veja [este artigo](https://www.theverge.com/2019/7/3/20680903/email-pixel-trackers-how-to-stop-images-automatic-download).
**Use texto puro** | Opcional | Existem dois tipos principais de email na internet: texto puro e HTML. O primeiro é fortemente preferível para privacidade e segurança, pois mensagens HTML frequentemente incluem identificadores em links e imagens embutidas, que podem coletar dados de uso e pessoais. Também há numerosos riscos de execução remota de código direcionados ao parser HTML do seu cliente de email, que não podem ser explorados se você estiver usando texto puro. Para mais informações, bem como instruções de configuração para seu provedor de email, veja [UsePlaintext.email](https://useplaintext.email/).
**Não conecte aplicativos de terceiros à sua conta de email** | Opcional | Se você der a um aplicativo ou plugin de terceiros acesso total à sua caixa de entrada, ele efetivamente terá acesso irrestrito a todos os seus emails e seus conteúdos, o que representa riscos significativos de segurança e privacidade.
**Não compartilhe dados sensíveis por email** | Opcional | Emails são muito facilmente interceptados. Além disso, você não pode ter certeza de quão seguro é o ambiente do destinatário. Portanto, emails não podem ser considerados seguros para troca de informações confidenciais, a menos que estejam criptografados.
**Considere migrar para um provedor de email seguro** | Opcional | Provedores de email seguros e respeitáveis, como [Forward Email](https://awesome-privacy.xyz/communication/encrypted-email/forward-email), [ProtonMail](https://awesome-privacy.xyz/communication/mail-forwarding/protonmail) e [Tutanota](https://awesome-privacy.xyz/communication/encrypted-email/tuta), permitem criptografia de ponta a ponta, privacidade total e recursos mais focados em segurança. Diferentemente de provedores de email típicos, sua caixa de correio não pode ser lida por ninguém além de você, já que todas as mensagens são criptografadas.
**Use uma Smart Key** | Avançado | OpenPGP não oferece suporte a sigilo futuro (forward secrecy), o que significa que, se a sua chave privada ou a do destinatário for roubada algum dia, todas as mensagens anteriores criptografadas com ela serão expostas. Portanto, você deve tomar muito cuidado para manter suas chaves privadas seguras. Um método para isso é usar uma USB Smart Key para assinar ou descriptografar mensagens, permitindo fazer isso sem que sua chave privada saia do dispositivo USB.
**Use aliases / encaminhamento anônimo** | Avançado | Aliasing de email permite que mensagens sejam enviadas para [anything]@my-domain.com e ainda cheguem à sua caixa de entrada principal. Na prática, isso permite que você use um endereço de email diferente e único para cada serviço em que se cadastra. Isso significa que, se você começar a receber spam, poderá bloquear aquele alias e descobrir qual empresa vazou seu endereço de email.
**Subendereçamento** | Opcional | Uma alternativa ao uso de aliases é o subendereçamento, em que tudo após o símbolo `+` é omitido durante a entrega do email. Isso permite acompanhar quem compartilhou/vazou seu endereço de email, mas, ao contrário do uso de aliases, não protege contra a revelação do seu endereço real.
**Use um domínio personalizado** | Avançado | Usar um domínio personalizado significa que você não depende do endereço atribuído pelo seu provedor de email. Assim, você pode trocar de provedor facilmente no futuro e não precisa se preocupar com a descontinuação de um serviço.
**Sincronize com um cliente para backup** | Avançado | Para evitar perder acesso temporário ou permanente aos seus emails durante um evento não planejado (como uma indisponibilidade ou bloqueio de conta), o Thunderbird pode sincronizar/fazer backup de mensagens de várias contas via IMAP e armazená-las localmente no seu dispositivo principal.
**Tenha cuidado com assinaturas de email** | Avançado | Você não sabe o quão seguro pode ser o ambiente de email do destinatário da sua mensagem. Existem várias extensões que rastreiam automaticamente mensagens e criam um banco de dados detalhado de informações de contato com base em assinaturas de email.
**Tenha cuidado com respostas automáticas** | Avançado | Respostas automáticas de ausência são muito úteis para informar que haverá atraso na resposta, mas, com frequência, as pessoas revelam informações demais — que podem ser usadas em engenharia social e ataques direcionados.
**Escolha o protocolo de email correto** | Avançado | Não use protocolos desatualizados (anteriores ao IMAPv4 ou POPv3); ambos têm vulnerabilidades conhecidas e segurança obsoleta.
**Auto-hospedagem** | Avançado | Hospedar seu próprio servidor de email não é recomendado para usuários não avançados, já que protegê-lo corretamente é crítico e exige forte conhecimento de redes.
**Sempre use portas TLS** | Avançado | Existem opções SSL para POP3, IMAP e SMTP como portas TCP/IP padrão. Elas são fáceis de usar e amplamente suportadas, então devem sempre ser usadas em vez de portas de email em texto puro.
**Disponibilidade de DNS** | Avançado | Para servidores de email auto-hospedados, a fim de evitar que problemas de DNS afetem a disponibilidade, use pelo menos 2 registros MX, com registros MX secundário e terciário para redundância quando o registro MX principal falhar.
**Previna ataques DDoS e de força bruta** | Avançado | Para servidores de email auto-hospedados (especificamente SMTP), limite o número total de conexões simultâneas e a taxa máxima de conexão para reduzir o impacto de tentativas de ataques de bots.
**Mantenha uma blacklist de IP** | Avançado | Para servidores de email auto-hospedados, você pode melhorar filtros de spam e endurecer a segurança mantendo uma blacklist local de IP atualizada e listas de bloqueio em tempo real de URIs de spam para filtrar hyperlinks maliciosos.

### Software recomendado
- [Provedores de Email Seguro](https://github.com/Lissy93/awesome-privacy#encrypted-email)
- [Encaminhamento de Email](https://github.com/Lissy93/awesome-privacy#anonymous-mail-forwarding)
- [Servidores de Email Pré-configurados](https://github.com/Lissy93/awesome-privacy#pre-configured-mail-servers)
- [Clientes de Email](https://github.com/Lissy93/awesome-privacy#email-clients)


## Mensagens



**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Use apenas mensageiros com criptografia ponta a ponta completa** | Essencial | Criptografia de ponta a ponta é um sistema de comunicação no qual as mensagens são criptografadas no seu dispositivo e só são descriptografadas quando chegam ao destinatário pretendido. Isso garante que qualquer agente que intercepte o tráfego não possa ler o conteúdo das mensagens, e que ninguém com acesso aos servidores centrais onde os dados são armazenados também possa fazê-lo.
**Use apenas plataformas de mensagens de código aberto** | Essencial | Se o código é de código aberto, ele pode ser examinado e auditado independentemente por qualquer pessoa qualificada para garantir que não existam portas dos fundos, vulnerabilidades ou outros problemas de segurança.
**Use uma plataforma de mensagens “confiável”** | Essencial | Ao selecionar um aplicativo de mensagens criptografadas, garanta que ele seja totalmente de código aberto, estável, mantido ativamente e, idealmente, apoiado por desenvolvedores respeitáveis.
**Verifique as configurações de segurança** | Essencial | Habilite configurações de segurança, incluindo verificação de contatos, notificações de segurança e criptografia. Desative recursos opcionais não relacionados à segurança, como confirmação de leitura, visto por último e notificação de digitação.
**Garanta que o ambiente dos seus destinatários seja seguro** | Essencial | Sua conversa só pode ser tão segura quanto o elo mais fraco. Muitas vezes, a forma mais fácil de infiltrar um canal de comunicação é atingir o indivíduo ou nó com menor proteção.
**Desative serviços em nuvem** | Essencial | Alguns aplicativos móveis de mensagens oferecem um complemento web ou para desktop. Isso não apenas aumenta a superfície de ataque, como também já foi associado a vários problemas críticos de segurança, e, portanto, deve ser evitado, se possível.
**Proteja conversas em grupo** | Essencial | O risco de comprometimento aumenta exponencialmente quanto mais participantes existem em um grupo, já que a superfície de ataque cresce. Verifique periodicamente se todos os participantes são legítimos.
**Crie um ambiente seguro para comunicação** | Essencial | Há várias etapas em que suas comunicações digitais podem ser monitoradas ou interceptadas. Isso inclui: seu dispositivo ou o dos participantes, seu ISP, gateway nacional ou registros do governo, o provedor de mensagens e os servidores.
**Combine um plano de comunicação** | Opcional | Em certas situações, pode valer a pena criar um plano de comunicação. Isso deve incluir métodos principais e de backup para entrar em contato uns com os outros com segurança.
**Remova metadados de mídias** | Opcional | Metadados são “dados sobre dados” ou informações adicionais anexadas a um arquivo ou transação. Quando você envia uma foto, gravação de áudio, vídeo ou documento, pode estar revelando mais do que pretendia.
**Neutralize URLs** | Opcional | Enviar links por vários serviços pode expor suas informações pessoais sem querer. Isso ocorre porque, quando uma miniatura ou prévia é gerada, isso acontece no lado do cliente.
**Verifique seu destinatário** | Opcional | Sempre garanta que está falando com o destinatário pretendido e que ele não foi comprometido. Um método para fazer isso é usar um app com suporte à verificação de contato.
**Habilite mensagens efêmeras** | Opcional | Mensagens autodestrutivas são um recurso que faz com que suas mensagens sejam apagadas automaticamente após um determinado tempo. Isso significa que, se seu dispositivo for perdido, roubado ou apreendido, um adversário terá acesso apenas às comunicações mais recentes.
**Evite SMS** | Opcional | SMS pode ser conveniente, mas não é seguro. É suscetível a ameaças como interceptação, sim swapping, manipulação e malware.
**Fique atento a rastreadores** | Opcional | Tenha cuidado com aplicativos de mensagens com rastreadores, pois as estatísticas detalhadas de uso que eles coletam costumam ser muito invasivas e às vezes podem revelar sua identidade, bem como informações pessoais que você não pretendia compartilhar.
**Considere a jurisdição** | Avançado | As jurisdições onde a organização está sediada e onde os dados são hospedados também devem ser levadas em conta.
**Use uma plataforma anônima** | Avançado | Se você acredita que pode ser alvo, deve optar por uma plataforma de mensagens anônima que não exija número de telefone nem qualquer outra informação pessoal identificável para cadastro ou uso.
**Garanta suporte a sigilo futuro (forward secrecy)** | Avançado | Prefira uma plataforma que implemente sigilo futuro (forward secrecy). É quando seu aplicativo gera uma nova chave de criptografia para cada mensagem.
**Considere uma plataforma descentralizada** | Avançado | Se todos os dados fluem por um provedor central, você precisa confiar a ele seus dados e metadados. Você não consegue verificar que o sistema em execução é autêntico e sem portas dos fundos.

### Software recomendado
- [Aplicativos de Mensagens Seguras](https://github.com/Lissy93/awesome-privacy#encrypted-messaging)
- [Plataformas de Mensagens P2P](https://github.com/Lissy93/awesome-privacy#p2p-messaging)


## Redes Sociais

Comunidades online existem desde a invenção da internet e dão às pessoas do mundo todo a oportunidade de se conectar, comunicar e compartilhar. Embora essas redes sejam uma ótima forma de promover interação social e aproximar pessoas, elas têm um lado obscuro — existem sérias [preocupações de privacidade com serviços de redes sociais](https://en.wikipedia.org/wiki/Privacy_concerns_with_social_networking_services), e esses sites de redes sociais pertencem a corporações privadas, que ganham dinheiro coletando dados sobre indivíduos e revendendo esses dados, muitas vezes para anunciantes terceirizados.
Proteja sua conta, restrinja suas configurações de privacidade, mas saiba que, mesmo depois de fazer isso, todos os dados carregados intencionalmente e não intencionalmente são efetivamente públicos. Se possível, evite usar redes sociais convencionais.


**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Proteja sua conta** | Essencial | Perfis de redes sociais são roubados ou tomados com frequência. Para proteger sua conta: use uma senha forte e única e habilite autenticação de 2 fatores.
**Verifique as configurações de privacidade** | Essencial | A maioria das redes sociais permite que você controle suas configurações de privacidade. Garanta que você se sente confortável com quais dados está expondo atualmente e para quem.
**Considere todas as interações como públicas** | Essencial | Ainda existem inúmeros métodos de visualizar conteúdo 'privado' de usuários em muitas redes sociais. Portanto, antes de fazer upload, postar ou comentar qualquer coisa, pense: “Eu me importaria se isso fosse totalmente público?”
**Considere todas as interações como permanentes** | Essencial | Praticamente toda publicação, comentário, foto etc. está sendo continuamente copiada por uma infinidade de serviços de terceiros, que arquivam esses dados e os tornam indexáveis e publicamente disponíveis quase para sempre.
**Não revele demais** | Essencial | Informações de perfil criam uma mina de ouro para hackers, o tipo de dado que os ajuda a personalizar golpes de phishing. Evite compartilhar detalhes demais (data de nascimento, cidade natal, escola etc.).
**Tenha cuidado com o que você publica** | Essencial | Atualizações de status, comentários, check-ins e mídias podem revelar sem querer muito mais do que você pretendia. Isso é especialmente relevante para fotos e vídeos, que podem mostrar coisas ao fundo.
**Não compartilhe email ou número de telefone** | Essencial | Publicar seu endereço de email real ou número de celular dá a hackers, trolls e spammers mais munição para usar contra você e também pode permitir que aliases, perfis ou pontos de dados separados sejam conectados.
**Não conceda permissões desnecessárias** | Essencial | Por padrão, muitos aplicativos populares de redes sociais pedem permissão para acessar seus contatos, registro de chamadas, localização, histórico de mensagens etc. Se eles não precisam desse acesso, não conceda.
**Tenha cuidado com integrações de terceiros** | Essencial | Evite criar contas usando login de rede social e revogue o acesso de aplicativos sociais que você não usa mais.
**Evite publicar dados geográficos enquanto ainda estiver no local** | Essencial | Se você pretende compartilhar qualquer conteúdo que revele uma localização, espere até ter saído daquele lugar. Isso é particularmente importante quando você estiver fazendo uma viagem, em restaurante, campus, hotel/resort, prédio público ou aeroporto.
**Remova metadados antes de enviar mídia** | Opcional | A maioria dos smartphones e algumas câmeras anexam automaticamente um conjunto abrangente de dados adicionais (chamados dados EXIF) a cada fotografia. Remova esses dados antes de fazer upload.
**Implemente camuflagem em imagens** | Avançado | Ferramentas como Fawkes podem ser usadas para alterar de forma muito sutil a estrutura dos rostos em fotos de um jeito imperceptível para humanos, mas que impede que sistemas de reconhecimento facial consigam reconhecer determinado rosto.
**Considere mascarar GPS nas proximidades de casa** | Avançado | Mesmo que você nunca use redes sociais, sempre haverá outras pessoas que não são tão cuidadosas e podem revelar sua localização.
**Considere informações falsas** | Avançado | Se você só quer ler e não pretende postar muito, considere usar um nome de alias e dados de contato falsos.
**Não tenha contas em redes sociais** | Avançado | Redes sociais são fundamentalmente anti-privacidade, então, para máxima segurança e privacidade online, evite usar redes sociais convencionais.

### Software recomendado
- [Redes Sociais Alternativas](https://github.com/Lissy93/awesome-privacy#social-networks)
- [Plataformas de Vídeo Alternativas](https://github.com/Lissy93/awesome-privacy#video-platforms)
- [Plataformas de Blogging Alternativas](https://github.com/Lissy93/awesome-privacy#blogging-platforms)
- [Leitores e Agregadores de Notícias](https://github.com/Lissy93/awesome-privacy#news-readers-and-aggregation)


## Redes

Esta seção cobre como você conecta seus dispositivos à internet com segurança, incluindo a configuração do seu roteador e de uma VPN.


**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Use uma VPN** | Essencial | Use uma VPN paga e respeitável. Isso pode ajudar a proteger sua privacidade, impedindo que sites registrem seu IP real, reduzindo a quantidade de dados que seu ISP pode coletar e aumentando a proteção em WiFi público.
**Troque a senha do seu roteador** | Essencial | Depois de obter um novo roteador, troque a senha. Senhas padrão de roteadores são publicamente conhecidas, o que significa que qualquer pessoa nas proximidades poderia se conectar.
**Use WPA2 e uma senha forte** | Essencial | Existem diferentes protocolos de autenticação para se conectar ao WiFi. Atualmente, as opções mais seguras são WPA2 e WPA3 (em roteadores mais novos).
**Mantenha o firmware do roteador atualizado** | Essencial | Fabricantes lançam atualizações de firmware que corrigem vulnerabilidades de segurança, implementam novos padrões e às vezes adicionam recursos ou melhoram o desempenho do seu roteador.
**Implemente uma VPN em toda a rede** | Opcional | Se você configurar sua VPN no roteador, firewall ou servidor doméstico, então o tráfego de todos os dispositivos será criptografado e roteado por ela, sem necessidade de aplicativos VPN individuais.
**Proteja-se contra vazamentos de DNS** | Opcional | Ao usar uma VPN, é extremamente importante usar exclusivamente o servidor DNS do seu provedor VPN ou de um serviço seguro.
**Use um protocolo VPN seguro** | Opcional | OpenVPN e WireGuard são protocolos de tunelamento de código aberto, leves e seguros. Evite usar PPTP ou SSTP.
**DNS seguro** | Opcional | Use DNS-over-HTTPS, que faz a resolução de DNS via protocolo HTTPS, criptografando os dados entre você e seu resolvedor DNS.
**Evite o roteador “gratuito” do seu ISP** | Opcional | Normalmente, eles são fabricados em massa de forma barata, com firmware proprietário inseguro que não recebe atualizações regulares de segurança.
**Use whitelist de endereços MAC** | Opcional | Você pode colocar endereços MAC em whitelist nas configurações do roteador, impedindo que dispositivos desconhecidos se conectem imediatamente à sua rede, mesmo que conheçam suas credenciais.
**Altere o endereço IP local do roteador** | Opcional | É possível que um script malicioso no seu navegador explore uma vulnerabilidade de cross-site scripting, acessando roteadores vulneráveis conhecidos em seu endereço IP local e adulterando-os.
**Não revele informações pessoais no SSID** | Opcional | Você deve atualizar o nome da sua rede, escolhendo um SSID que não o identifique, não inclua número do apartamento/endereço e não especifique a marca/modelo do dispositivo.
**Saia de listagens de roteadores** | Opcional | SSIDs de WiFi são escaneados, registrados e depois publicados em vários sites, o que é uma séria preocupação de privacidade para algumas pessoas.
**Oculte seu SSID** | Opcional | O Service Set Identifier do seu roteador é simplesmente o nome da rede. Se ele não estiver visível, pode sofrer menos abusos.
**Desative WPS** | Opcional | Wi-Fi Protected Setup oferece um método mais fácil de conexão, sem inserir uma senha longa de WiFi, mas WPS introduz uma série de grandes problemas de segurança.
**Desative UPnP** | Opcional | Universal Plug and Play permite que aplicativos encaminhem automaticamente uma porta no seu roteador, mas tem um longo histórico de problemas sérios de segurança.
**Use uma rede de convidados para visitantes** | Opcional | Não conceda acesso à sua rede WiFi principal a visitantes, pois isso permite que interajam com outros dispositivos na rede.
**Mude o IP padrão do seu roteador** | Opcional | Modificar o endereço IP padrão do painel administrativo do seu roteador tornará mais difícil que scripts maliciosos direcionados a endereços IP locais atuem com sucesso.
**Elimine processos e serviços não usados no roteador** | Opcional | Serviços como Telnet e SSH que fornecem acesso por linha de comando a dispositivos nunca devem ficar expostos à internet e também devem ser desabilitados na rede local, a menos que sejam realmente necessários.
**Não tenha portas abertas** | Opcional | Feche quaisquer portas abertas no seu roteador que não sejam necessárias. Portas abertas fornecem uma entrada fácil para hackers.
**Desative protocolos de acesso remoto não utilizados** | Opcional | Quando protocolos como PING, Telnet, SSH, UPnP e HNAP etc. estão habilitados, eles permitem que seu roteador seja sondado de qualquer lugar do mundo.
**Desative gerenciamento baseado em nuvem** | Opcional | Você deve tratar o painel administrativo do seu roteador com o máximo cuidado, pois danos consideráveis podem ser causados se um invasor conseguir acesso.
**Gerencie corretamente o alcance** | Opcional | É comum querer aumentar o alcance do roteador ao máximo, mas, se você mora em um apartamento menor, sua superfície de ataque aumenta quando sua rede WiFi pode ser detectada do outro lado da rua.
**Roteie todo o tráfego por [Tor](https://awesome-privacy.xyz/networking/mix-networks/tor)** | Avançado | VPNs têm suas fraquezas. Para aumentar a segurança, roteie todo o seu tráfego de internet pela rede [Tor](https://awesome-privacy.xyz/networking/mix-networks/tor).
**Desative WiFi em todos os dispositivos** | Avançado | Conectar-se até mesmo a uma rede WiFi segura aumenta sua superfície de ataque. Desative o WiFi de casa e conecte cada dispositivo via Ethernet.

### Software recomendado
- [Redes Privadas Virtuais](https://github.com/Lissy93/awesome-privacy#virtual-private-networks)
- [Redes Mistas](https://github.com/Lissy93/awesome-privacy#mix-networks)
- [Firmware para Roteadores](https://github.com/Lissy93/awesome-privacy#router-firmware)
- [Proxies Open Source](https://github.com/Lissy93/awesome-privacy#proxies)
- [Provedores de DNS](https://github.com/Lissy93/awesome-privacy#dns)
- [Firewalls](https://github.com/Lissy93/awesome-privacy#firewalls)
- [Ferramentas de Análise de Rede](https://github.com/Lissy93/awesome-privacy#network-analysis)
- [Ferramentas de Segurança de Rede Self-Hosted](https://github.com/Lissy93/awesome-privacy#self-hosted-network-security)


## Dispositivos Móveis

Smartphones revolucionaram muitos aspectos da vida e colocaram o mundo na ponta dos nossos dedos. Para muitos de nós, smartphones são nosso principal meio de comunicação, entretenimento e acesso ao conhecimento. Mas, embora tenham trazido conveniência a outro nível, há coisas bem desagradáveis acontecendo por trás da tela.
Rastreamento geográfico é usado para traçar cada movimento nosso, e temos pouco controle sobre quem possui esses dados — seu telefone é até capaz de [rastrear sua localização sem GPS](https://gizmodo.com/how-to-track-a-cellphone-without-gps-or-consent-1821125371). Ao longo dos anos, surgiram inúmeros relatórios mostrando maneiras pelas quais o [microfone](https://www.independent.co.uk/life-style/gadgets-and-tech/news/smartphone-apps-listening-privacy-alphonso-shazam-advertising-pool-3d-honey-quest-a8139451.html) do seu telefone pode espioná-lo e a [câmera pode observá-lo](https://www.businessinsider.com/hackers-governments-smartphone-iphone-camera-wikileaks-cybersecurity-hack-privacy-webcam-2017-6) — tudo sem seu conhecimento ou consentimento. E depois há aplicativos maliciosos, falta de correções de segurança e possíveis/prováveis portas dos fundos.
Usar um smartphone gera muitos dados sobre você — desde informações que você compartilha intencionalmente até dados gerados silenciosamente por suas ações. Pode ser assustador ver o que Google, Microsoft, Apple e Facebook sabem sobre nós — às vezes sabem mais do que nossa família mais próxima. É difícil compreender o que seus dados revelarão, especialmente em conjunto com outros dados.
Esses dados são usados para [muito mais do que apenas publicidade](https://internethealthreport.org/2018/the-good-the-bad-and-the-ugly-sides-of-data-tracking/) — com mais frequência, são usados para avaliar pessoas em finanças, seguros e emprego. Anúncios direcionados podem até ser usados para vigilância refinada (veja [ADINT](https://adint.cs.washington.edu)).
Mais pessoas estão preocupadas com a forma como [governos coletam e usam dados de smartphones](https://www.statista.com/statistics/373916/global-opinion-online-monitoring-government/), e com razão: agências federais frequentemente [solicitam nossos dados ao Google](https://www.statista.com/statistics/273501/global-data-requests-from-google-by-federal-agencies-and-governments/), [Facebook](https://www.statista.com/statistics/287845/global-data-requests-from-facebook-by-federal-agencies-and-governments/), Apple, Microsoft, Amazon e outras empresas de tecnologia. Às vezes, solicitações são feitas em massa, retornando informações detalhadas de todos dentro de um determinado cercamento geográfico, [muitas vezes de pessoas inocentes](https://www.nytimes.com/interactive/2019/04/13/us/google-location-tracking-police.html). E isso sem incluir todo o tráfego de internet ao qual agências de inteligência no mundo todo têm acesso irrestrito.


**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Criptografe seu dispositivo** | Essencial | Para manter seus dados protegidos contra acesso físico, use criptografia de arquivos. Isso significa que, se seu dispositivo for perdido ou roubado, ninguém terá acesso aos seus dados.
**Desative recursos de conectividade que não estejam sendo usados** | Essencial | Quando você não estiver usando WiFi, Bluetooth, NFC etc., desligue esses recursos. Há várias ameaças comuns que exploram essas funcionalidades.
**Mantenha o número de apps no mínimo** | Essencial | Desinstale aplicativos de que você não precisa ou usa regularmente. Como apps frequentemente rodam em segundo plano, eles não apenas deixam o dispositivo mais lento como também coletam dados.
**Permissões de aplicativos** | Essencial | Não conceda aos apps permissões de que eles não precisam. No Android, [Bouncer](https://awesome-privacy.xyz/security-tools/mobile-apps/bouncer) é um aplicativo que permite conceder permissões temporárias/de uso único.
**Instale apps apenas de fontes oficiais** | Essencial | Aplicativos na Apple App Store e Google Play Store são escaneados e assinados criptograficamente, tornando-os menos propensos a serem maliciosos.
**Tenha cuidado com ameaças ao carregar o telefone** | Opcional | Juice Jacking é quando hackers usam estações públicas de recarga para instalar malware no seu smartphone ou tablet por meio de uma porta USB comprometida.
**Configure um PIN da operadora móvel** | Essencial | SIM hijacking é quando um hacker consegue transferir seu número de celular para o SIM dele. A forma mais fácil de se proteger é configurar um PIN por meio da sua operadora.
**Saia de listagens de identificador de chamadas** | Opcional | Para manter seus dados privados, você pode remover seu número de apps de identificador de chamadas como TrueCaller, CallApp, SyncMe e Hiya.
**Use mapas offline** | Opcional | Considere usar um aplicativo de mapas offline, como OsmAnd ou Organic Maps, para reduzir vazamentos de dados de apps de mapas.
**Desative anúncios personalizados** | Opcional | Você pode reduzir ligeiramente a quantidade de dados coletados optando por não ver anúncios personalizados.
**Apague após muitas tentativas de login** | Opcional | Para se proteger contra um invasor tentando força bruta no seu PIN, configure seu dispositivo para apagar dados após muitas tentativas de login falhas.
**Monitore rastreadores** | Opcional | [εxodus](https://awesome-privacy.xyz/security-tools/online-tools/εxodus) é um ótimo serviço que permite pesquisar qualquer aplicativo e ver quais rastreadores estão embutidos nele.
**Use um firewall móvel** | Opcional | Para evitar que aplicativos vazem dados sensíveis à privacidade, você pode instalar um aplicativo de firewall.
**Reduza atividade em segundo plano** | Opcional | No Android, SuperFreeze torna possível congelar completamente todas as atividades em segundo plano por aplicativo.
**Use sandbox para aplicativos móveis** | Opcional | Impedir que apps famintos por permissões acessem seus dados privados com [Island](https://awesome-privacy.xyz/security-tools/mobile-apps/island), um ambiente sandbox.
**Tráfego Tor** | Avançado | [Orbot](https://awesome-privacy.xyz/security-tools/mobile-apps/orbot) oferece uma conexão Tor em todo o sistema, o que ajudará a protegê-lo contra vigilância e ameaças em WiFi público.
**Evite teclados virtuais personalizados** | Opcional | Recomenda-se usar o teclado padrão do seu dispositivo. Se você optar por usar um app de teclado de terceiros, certifique-se de que ele seja confiável.
**Reinicie o dispositivo regularmente** | Opcional | Reiniciar o telefone pelo menos uma vez por semana limpará o estado dos aplicativos em cache na memória e poderá fazê-lo funcionar com mais fluidez depois da reinicialização.
**Evite SMS** | Opcional | SMS não deve ser usado para receber códigos 2FA nem para comunicação; em vez disso, use um aplicativo de mensagens criptografadas, como [Signal](https://awesome-privacy.xyz/communication/encrypted-messaging/signal).
**Mantenha seu número privado** | Opcional | [MySudo](https://awesome-privacy.xyz/finance/virtual-credit-cards/mysudo) permite criar e usar números de telefone virtuais para pessoas ou grupos diferentes. Isso é ótimo para compartimentalização.
**Fique atento a stalkerware** | Opcional | Stalkerware é malware instalado diretamente no seu dispositivo por alguém que você conhece. A melhor maneira de se livrar disso é fazendo uma restauração de fábrica.
**Prefira o navegador a aplicativos dedicados** | Opcional | Sempre que possível, considere usar um navegador seguro para acessar sites, em vez de instalar aplicativos dedicados.
**Considere executar uma ROM personalizada (Android)** | Avançado | Se você está preocupado com o fabricante do seu dispositivo coletando informações pessoais demais, considere uma ROM personalizada focada em privacidade.

### Software recomendado
- [Aplicativos Móveis para Segurança + Privacidade](https://github.com/Lissy93/awesome-privacy#mobile-apps)
- [Mensagens Criptografadas](https://github.com/Lissy93/awesome-privacy#encrypted-messaging)
- [Sistemas Operacionais Móveis](https://github.com/Lissy93/awesome-privacy#mobile-operating-systems)


## Computadores Pessoais

Embora Windows e OS X sejam fáceis de usar e convenientes, ambos estão longe de ser seguros. Seu SO fornece a interface entre o hardware e seus aplicativos, então, se for comprometido, pode ter efeitos prejudiciais.


**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Mantenha seu sistema atualizado** | Essencial | Atualizações do sistema contêm correções/patches para problemas de segurança, melhoram o desempenho e às vezes adicionam novos recursos. Instale novas atualizações quando solicitado.
**Criptografe seu dispositivo** | Essencial | Use BitLocker no Windows, FileVault no MacOS ou LUKS no Linux para habilitar criptografia completa de disco. Isso evita acesso não autorizado se seu computador for perdido ou roubado.
**Faça backup de dados importantes** | Essencial | Manter backups criptografados evita perdas causadas por ransomware, roubo ou danos. Considere usar [Cryptomator](https://awesome-privacy.xyz/security-tools/mobile-apps/cryptomator) para arquivos em nuvem ou [VeraCrypt](https://awesome-privacy.xyz/essentials/file-encryption/veracrypt) para unidades USB.
**Tenha cuidado ao conectar dispositivos USB ao seu computador** | Essencial | Dispositivos USB podem representar ameaças sérias. Considere montar um sanitizador USB com CIRCLean para verificar dispositivos USB com segurança.
**Ative o bloqueio de tela quando ocioso** | Essencial | Bloqueie seu computador quando se ausentar e configure-o para exigir senha ao retomar do protetor de tela ou do modo de suspensão para evitar acesso não autorizado.
**Desative Cortana ou Siri** | Essencial | Assistentes controlados por voz podem trazer implicações de privacidade devido aos dados enviados de volta para processamento. Desative-os ou limite seus recursos de escuta.
**Revise seus aplicativos instalados** | Essencial | Mantenha o mínimo de aplicativos instalados para reduzir a exposição a vulnerabilidades e limpe regularmente os caches de aplicativos.
**Gerencie permissões** | Essencial | Controle quais apps têm acesso à sua localização, câmera, microfone, contatos e outras informações sensíveis.
**Não permita que dados de uso sejam enviados para a nuvem** | Essencial | Limite a quantidade de informações de uso ou feedback enviada para a nuvem para proteger sua privacidade.
**Evite desbloqueio rápido** | Essencial | Use uma senha forte em vez de biometria ou PINs curtos para desbloquear seu computador e aumentar a segurança.
**Desligue o computador em vez de deixá-lo em espera** | Essencial | Desligue o dispositivo quando não estiver em uso, especialmente se o disco estiver criptografado, para manter os dados seguros.
**Não vincule seu PC à sua conta Microsoft ou Apple** | Opcional | Use apenas uma conta local para evitar sincronização e exposição de dados. Evite usar serviços de sincronização que comprometam a privacidade.
**Verifique quais serviços de compartilhamento estão habilitados** | Opcional | Desative recursos de compartilhamento de rede que você não utiliza para fechar portas de entrada para ameaças comuns.
**Não use conta Root/Admin para tarefas sem administração** | Opcional | Use uma conta de usuário sem privilégios para tarefas diárias e eleve permissões apenas para mudanças administrativas, a fim de mitigar vulnerabilidades.
**Bloqueie webcam + microfone** | Opcional | Cubra sua webcam quando não estiver em uso e considere bloquear gravação de áudio não autorizada para proteger a privacidade.
**Use um filtro de privacidade** | Opcional | Use um filtro de privacidade de tela em espaços públicos para evitar shoulder surfing e proteger informações sensíveis.
**Proteja fisicamente o dispositivo** | Opcional | Use um Kensington Lock para proteger seu laptop em espaços públicos e considere travas de porta para impedir acesso físico não autorizado.
**Não carregue dispositivos a partir do seu PC** | Opcional | Use uma bateria externa (power bank) ou carregador de parede AC em vez do PC para evitar riscos de segurança associados a conexões USB.
**Randomize seu endereço de hardware no Wi-Fi** | Opcional | Modifique ou randomize seu endereço MAC para se proteger contra rastreamento em diferentes redes WiFi.
**Use um firewall** | Opcional | Instale um aplicativo de firewall para monitorar e bloquear acessos indesejados à internet por certos aplicativos, protegendo contra ataques de acesso remoto e violações de privacidade.
**Proteja-se contra keyloggers de software** | Opcional | Use ferramentas de criptografia de teclas digitadas para se proteger contra keyloggers de software registrando suas teclas.
**Verifique a conexão do teclado** | Opcional | Fique atento a keyloggers de hardware ao usar computadores públicos ou desconhecidos, verificando as conexões do teclado.
**Previna ataques de injeção de teclas** | Opcional | Bloqueie seu PC quando estiver longe e considere usar USBGuard ou ferramentas semelhantes para se proteger contra ataques de injeção de teclas.
**Não use antivírus comercial “gratuito”** | Opcional | Confie nas ferramentas de segurança integradas e evite aplicativos antivírus gratuitos devido ao potencial de invasão de privacidade e coleta de dados.
**Verifique periodicamente a presença de rootkits** | Avançado | Verifique regularmente a presença de rootkits para detectar e mitigar ameaças de controle total do sistema usando ferramentas como [chkrootkit](https://awesome-privacy.xyz/operating-systems/linux-defenses/chkrootkit).
**Senha de boot da BIOS** | Avançado | Habilite uma senha de BIOS ou UEFI para adicionar uma camada extra de segurança durante a inicialização, embora você deva estar ciente de suas limitações.
**Use um sistema operacional focado em segurança** | Avançado | Considere migrar para Linux ou para uma distribuição focada em segurança, como QubeOS ou [Tails](https://awesome-privacy.xyz/operating-systems/desktop-operating-systems/tails), para mais privacidade e segurança.
**Faça uso de VMs** | Avançado | Use máquinas virtuais para atividades arriscadas ou para testar softwares suspeitos, a fim de isolar ameaças potenciais do seu sistema principal.
**Compartimentalize** | Avançado | Isole programas e fontes de dados diferentes uns dos outros tanto quanto possível para limitar a extensão de possíveis violações.
**Desative recursos indesejados (Windows)** | Avançado | Desative “recursos” e serviços desnecessários do Windows que executam em segundo plano para reduzir coleta de dados e uso de recursos.
**Inicialização Segura (Secure Boot)** | Avançado | Garanta que o Secure Boot esteja habilitado para impedir que malware substitua seu carregador de inicialização e outros softwares críticos.
**Proteja o acesso SSH** | Avançado | Tome medidas para proteger o acesso SSH contra ataques alterando a porta padrão, usando chaves SSH e configurando firewalls.
**Feche portas abertas não utilizadas** | Avançado | Desative serviços escutando em portas externas que não sejam necessários para se proteger contra exploits remotos e melhorar a segurança.
**Implemente controle de acesso obrigatório** | Avançado | Restrinja o acesso privilegiado para limitar os danos que podem ser causados se um sistema for comprometido.
**Use Canary Tokens** | Avançado | Implante canary tokens para detectar mais rapidamente acesso não autorizado a seus arquivos ou emails e coletar informações sobre o intruso.

### Software recomendado
- [Sistemas Operacionais Seguros](https://github.com/Lissy93/awesome-privacy#desktop-operating-systems)
- [Defesas para Linux](https://github.com/Lissy93/awesome-privacy#linux-defences)
- [Defesas para Windows](https://github.com/Lissy93/awesome-privacy#windows-defences)
- [Defesas para Mac OS](https://github.com/Lissy93/awesome-privacy#mac-os-defences)
- [Anti-Malware](https://github.com/Lissy93/awesome-privacy#anti-malware)
- [Firewalls](https://github.com/Lissy93/awesome-privacy#firewalls-1)
- [Criptografia de Arquivos](https://github.com/Lissy93/awesome-privacy#file-encryption)


## Casa Inteligente

Assistentes domésticos (como Google Home, Alexa e Siri) e outros dispositivos conectados à internet coletam grandes quantidades de dados pessoais (incluindo amostras de voz, dados de localização, detalhes da casa e registros de todas as interações). Como você tem controle limitado sobre o que está sendo coletado, como é armazenado e para que será usado, fica difícil recomendar qualquer produto de casa inteligente para consumidores que se importam com privacidade e segurança.
Segurança vs Privacidade: Existem muitos dispositivos inteligentes no mercado que afirmam aumentar a segurança da sua casa ao mesmo tempo em que são fáceis e convenientes de usar (como alarmes inteligentes contra invasão, câmeras de segurança conectadas à internet, fechaduras inteligentes e campainhas com acesso remoto, para citar alguns). Esses dispositivos podem parecer tornar a segurança mais fácil, mas há uma troca em termos de privacidade: como coletam grandes quantidades de dados pessoais, você fica sem controle sobre como isso é armazenado ou usado. A segurança desses dispositivos também é questionável, já que muitos deles podem ser (e estão sendo) hackeados, permitindo que um invasor contorne a detecção com esforço mínimo.
A opção que mais respeita a privacidade seria não usar dispositivos “inteligentes” conectados à internet em sua casa e não depender de um dispositivo de segurança que exija conexão com a internet. Mas, se você usar, é importante compreender totalmente os riscos de qualquer produto antes de comprá-lo. Depois, ajuste as configurações para aumentar privacidade e segurança. A checklist a seguir ajudará a mitigar os riscos associados a dispositivos domésticos conectados à internet.

**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Renomeie dispositivos para não especificar marca/modelo** | Essencial | Altere nomes padrão dos dispositivos para algo genérico, a fim de evitar ataques direcionados ao ocultar informações de marca ou modelo.
**Desative microfone e câmera quando não estiverem em uso** | Essencial | Use chaves físicas para desligar microfones e câmeras em dispositivos inteligentes para proteger contra gravações acidentais ou acesso direcionado.
**Entenda quais dados são coletados, armazenados e transmitidos** | Essencial | Pesquise e garanta que você está confortável com as práticas de tratamento de dados de dispositivos de casa inteligente antes da compra, evitando dispositivos que compartilham dados com terceiros.
**Ajuste as configurações de privacidade e desative o compartilhamento de dados com terceiros** | Essencial | Ajuste as configurações dos aplicativos para os controles de privacidade mais rígidos e desative o compartilhamento de dados com terceiros sempre que possível.
**Não vincule seus dispositivos de casa inteligente à sua identidade real** | Essencial | Use nomes de usuário e senhas anônimos, evitando cadastro/login via redes sociais ou outros serviços de terceiros para manter a privacidade.
**Mantenha o firmware atualizado** | Essencial | Atualize regularmente o firmware dos dispositivos inteligentes para aplicar correções e melhorias de segurança.
**Proteja sua rede** | Essencial | Proteja seu WiFi doméstico e sua rede para impedir acesso não autorizado a dispositivos inteligentes.
**Tenha cautela com wearables** | Opcional | Considere a ampla capacidade de coleta de dados de dispositivos vestíveis e suas implicações para a privacidade.
**Não conecte a infraestrutura crítica da sua casa à internet** | Opcional | Avalie os riscos de termostatos, alarmes e detectores conectados à internet devido ao potencial de acesso remoto por hackers.
**Mitigue riscos do Alexa/ Google Home** | Opcional | Considere alternativas focadas em privacidade, como [Mycroft](https://awesome-privacy.xyz/smart-home-and-iot/voice-assistants/mycroft), ou use Project Alias para impedir escuta ociosa por assistentes ativados por voz.
**Monitore sua rede doméstica de perto** | Opcional | Use ferramentas como FingBox ou recursos do roteador para monitorar atividade de rede incomum.
**Negue acesso à internet quando possível** | Avançado | Use firewalls para bloquear acesso à internet para dispositivos que não precisam dela, limitando a operação ao uso na rede local.
**Avalie os riscos** | Avançado | Considere as implicações de privacidade para todos os membros da casa e ajuste as configurações dos dispositivos para segurança e privacidade, como desativá-los em determinados horários.

### Software recomendado
- [Automação Residencial](https://github.com/Lissy93/awesome-privacy#home-automation)
- [Assistentes de Voz com IA](https://github.com/Lissy93/awesome-privacy#ai-voice-assistants)


## Finanças Pessoais

Fraude com cartão de crédito é a forma mais comum de roubo de identidade (com [133.015 registros apenas nos EUA em 2017](https://www.experian.com/blogs/ask-experian/identity-theft-statistics/)) e uma perda total de US$ 905 milhões, o que representou um aumento de 26% em relação ao ano anterior. A perda mediana por pessoa foi de US$ 429 em 2017. É mais importante do que nunca tomar medidas básicas para se proteger de cair em golpes.
Observação sobre cartões de crédito: cartões de crédito possuem métodos tecnológicos para detectar e impedir algumas transações fraudulentas. Grandes processadores de pagamento implementam isso minerando enormes quantidades de dados de seus portadores para conhecer muito sobre os hábitos de consumo de cada pessoa. Esses dados são usados para identificar fraude, mas também são vendidos a outros corretores de dados. Portanto, cartões de crédito são bons para segurança, mas péssimos para privacidade de dados.

**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Cadastre-se para alertas de fraude e monitoramento de crédito** | Essencial | Habilite alertas de fraude e monitoramento de crédito por meio de Experian, TransUnion ou Equifax para ser avisado sobre atividade suspeita.
**Aplique um congelamento de crédito** | Essencial | Impeça consultas de crédito não autorizadas congelando seu crédito em Experian, TransUnion e Equifax.
**Use cartões virtuais** | Opcional | Utilize números de cartão virtual para transações online para proteger seus dados bancários reais. Serviços como [Privacy.com](https://awesome-privacy.xyz/finance/virtual-credit-cards/privacy.com) e [MySudo](https://awesome-privacy.xyz/finance/virtual-credit-cards/mysudo) oferecem esses recursos.
**Use dinheiro em transações locais** | Opcional | Pague com [Cash](https://awesome-privacy.xyz/finance/other-payment-methods/cash) em compras locais e cotidianas para evitar perfilamento financeiro por instituições.
**Use criptomoeda em transações online** | Opcional | Prefira criptomoedas focadas em privacidade, como [Monero](https://awesome-privacy.xyz/finance/cryptocurrencies/monero), em transações online para manter o anonimato. Use criptomoedas com sabedoria para garantir privacidade.
**Armazene cripto com segurança** | Avançado | Armazene criptomoedas com segurança usando geração de carteiras offline, hardware wallets como [Trezor](https://awesome-privacy.xyz/finance/crypto-wallets/trezor) ou [ColdCard](https://awesome-privacy.xyz/finance/crypto-wallets/coldcard), ou considere soluções de armazenamento de longo prazo como [CryptoSteel](https://awesome-privacy.xyz/finance/crypto-wallets/cryptosteel).
**Compre cripto anonimamente** | Avançado | Compre criptomoedas sem vinculá-las à sua identidade por meio de serviços como [LocalBitcoins](https://awesome-privacy.xyz/finance/crypto-exchanges/localbitcoins), [Bisq](https://awesome-privacy.xyz/finance/crypto-exchanges/bisq) ou caixas eletrônicos de Bitcoin.
**Misture moedas** | Avançado | Use um mixer de bitcoin ou CoinJoin antes de converter Bitcoin em moeda para obscurecer rastros de transação.
**Use detalhes de alias em compras online** | Avançado | Para compras online, considere usar detalhes de alias, endereços de email de encaminhamento, números VOIP e métodos de entrega seguros para proteger sua identidade.
**Use endereço alternativo para entrega** | Avançado | Prefira entregas para endereços não pessoais, como caixas postais, endereços de encaminhamento ou pontos de retirada locais, para evitar vincular compras diretamente a você.

### Software recomendado
- [Cartões de Crédito Virtuais](https://github.com/Lissy93/awesome-privacy#virtual-credit-cards)
- [Criptomoedas](https://github.com/Lissy93/awesome-privacy#cryptocurrencies)
- [Carteiras de Cripto](https://github.com/Lissy93/awesome-privacy#crypto-wallets)
- [Exchanges de Cripto](https://github.com/Lissy93/awesome-privacy#crypto-exchanges)
- [Outros Métodos de Pagamento](https://github.com/Lissy93/awesome-privacy#other-payment-methods)
- [Ferramentas de Orçamento](https://github.com/Lissy93/awesome-privacy#budgeting-tools)


## Aspecto Humano

Muitas violações de dados, invasões e ataques são causados por erro humano. A lista a seguir contém medidas que você deve tomar para reduzir o risco de que isso aconteça com você. Muitas delas são senso comum, mas ainda assim vale a pena prestar atenção.

**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Verifique destinatários** | Essencial | Emails podem ser facilmente falsificados. Verifique a autenticidade do remetente, especialmente para ações sensíveis, e prefira digitar URLs manualmente em vez de clicar em links em emails.
**Não confie nas suas notificações pop-up** | Essencial | Pop-ups falsos podem ser implantados por agentes maliciosos. Sempre verifique a URL antes de inserir qualquer informação em um pop-up.
**Nunca deixe o dispositivo sem supervisão** | Essencial | Dispositivos sem supervisão podem ser comprometidos mesmo com senhas fortes. Use criptografia e recursos de apagamento remoto, como Find My Phone, para dispositivos perdidos.
**Previna camfecting** | Essencial | Proteja-se contra camfecting usando tampas para webcam e bloqueadores de microfone. Coloque assistentes domésticos no mudo quando não estiverem em uso ou ao discutir assuntos sensíveis.
**Proteja-se de shoulder surfers** | Essencial | Use telas de privacidade em laptops e celulares para impedir que outras pessoas leiam sua tela em espaços públicos.
**Eduque-se sobre ataques de phishing** | Essencial | Tenha cuidado com tentativas de phishing. Verifique URLs, o contexto das mensagens recebidas e empregue boas práticas de segurança, como usar 2FA e não reutilizar senhas.
**Fique atento a stalkerware** | Essencial | Esteja ciente de stalkerware instalado por conhecidos para espionagem. Procure sinais como uso incomum de bateria e realize restaurações de fábrica se suspeitar disso.
**Instale software confiável de fontes confiáveis** | Essencial | Baixe software apenas de fontes legítimas e verifique arquivos com ferramentas como [Virus Total](https://awesome-privacy.xyz/security-tools/online-tools/virus-total) antes da instalação.
**Armazene dados pessoais com segurança** | Essencial | Garanta que todos os dados pessoais em dispositivos ou na nuvem estejam criptografados para proteger contra acesso não autorizado.
**Oculte detalhes pessoais em documentos** | Essencial | Ao compartilhar documentos, oculte detalhes pessoais com retângulos opacos para evitar vazamento de informações.
**Não presuma que um site é seguro só porque usa `HTTPS`** | Essencial | HTTPS não garante a legitimidade de um site. Verifique URLs e tenha cautela com dados pessoais.
**Use cartões virtuais ao pagar online** | Opcional | Use cartões virtuais para pagamentos online para proteger seus dados bancários e limitar riscos de transação.
**Revise permissões de aplicativos** | Opcional | Revise e gerencie regularmente as permissões de aplicativos para garantir que não haja acesso desnecessário a recursos sensíveis do dispositivo.
**Saia de listas públicas** | Opcional | Remova-se de bancos de dados públicos e listas de marketing para reduzir contatos indesejados e riscos potenciais.
**Nunca forneça PII adicional ao solicitar remoção** | Opcional | Não forneça informações pessoais adicionais ao solicitar exclusão de serviços de dados para evitar mais coleta de dados.
**Desative compartilhamento de dados** | Opcional | Muitos apps e serviços vêm com configurações de compartilhamento de dados ativadas por padrão. Desative isso para proteger seus dados de compartilhamento com terceiros.
**Revise e atualize a privacidade das redes sociais** | Opcional | Verifique e atualize regularmente as configurações das suas redes sociais devido a atualizações frequentes de termos que podem afetar sua privacidade.
**Compartimentalize** | Avançado | Mantenha separadas diferentes áreas da atividade digital para limitar a exposição de dados em caso de violação.
**WhoIs Privacy Guard** | Avançado | Use WhoIs Privacy Guard para registros de domínio a fim de proteger suas informações pessoais contra buscas públicas.
**Use um endereço de encaminhamento** | Avançado | Use uma caixa postal ou endereço de encaminhamento para correspondências para impedir que empresas saibam seu endereço real, adicionando uma camada de proteção de privacidade.
**Use métodos de pagamento anônimos** | Avançado | Prefira métodos de pagamento anônimos, como criptomoedas, para evitar inserir informações identificáveis online.


## Segurança Física

Registros públicos frequentemente incluem dados pessoais sensíveis (nome completo, data de nascimento, número de telefone, email, endereço, etnia etc.) e são reunidos a partir de várias fontes (registros censitários, certidões de nascimento/óbito/casamento, registros de eleitores, informações de marketing, bases de clientes, registros de veículos, licenças profissionais/comerciais e todos os processos judiciais em detalhes completos). Essas informações pessoais sensíveis são [fáceis e legais de acessar](https://www.consumerreports.org/consumerist/its-creepy-but-not-illegal-for-this-website-to-provide-all-your-public-info-to-anyone/), o que levanta [sérias preocupações de privacidade](https://privacyrights.org/resources/public-records-internet-privacy-dilemma) (roubo de identidade, riscos à segurança pessoal/stalkers, destruição de reputações, sociedade de dossiês).

CCTV é uma das principais formas pelas quais corporações, indivíduos e o governo rastreiam seus movimentos. Em Londres, Reino Unido, a pessoa média é filmada cerca de 500 vezes por dia. Essa rede continua crescendo e, em muitas cidades do mundo, reconhecimento facial está sendo implantado, o que significa que o Estado pode saber a identidade dos residentes nas imagens em tempo real.
Autenticação forte, dispositivos criptografados, software corrigido e navegação web anônima podem servir de pouco se alguém conseguir comprometer fisicamente você, seus dispositivos e seus dados. Esta seção descreve alguns métodos básicos de segurança física.

**Segurança** | **Prioridade** | **Detalhes e dicas**
--- | --- | ---
**Destrua documentos sensíveis** | Essencial | Triture ou anonimize documentos sensíveis antes do descarte para proteger contra roubo de identidade e manter a confidencialidade.

**Saia de registros públicos** | Essencial | Entre em contato com sites de busca de pessoas para remover listagens que mostrem informações pessoais, usando guias como o Personal Data Removal Workbook de Michael Bazzell.

**Marque documentos com marca d'água** | Essencial | Adicione uma marca d'água com o nome do destinatário e a data a cópias digitais de documentos pessoais para rastrear a origem de um vazamento.

**Não revele informações em chamadas recebidas** | Essencial | Compartilhe dados pessoais apenas em chamadas iniciadas por você e verifique o número de telefone do destinatário.

**Mantenha-se alerta** | Essencial | Esteja ciente do seu entorno e avalie riscos potenciais em novos ambientes.
**Proteja o perímetro** | Essencial | Garanta a segurança física de locais que armazenam dispositivos com informações pessoais, minimizando acesso externo e usando sistemas de detecção de intrusão.
**Proteja fisicamente os dispositivos** | Essencial | Use medidas de segurança física, como Kensington locks, tampas para webcam e telas de privacidade nos dispositivos.
**Mantenha dispositivos fora da linha direta de visão** | Essencial | Evite que dispositivos fiquem visíveis do lado de fora para mitigar riscos de lasers e roubo.
**Proteja seu PIN** | Essencial | Cubra a digitação do seu PIN contra curiosos e câmeras e limpe telas sensíveis ao toque após o uso.
**Verifique skimmers** | Essencial | Inspecione caixas eletrônicos e dispositivos públicos em busca de skimmers e sinais de adulteração antes do uso.
**Proteja seu endereço residencial** | Opcional | Use locais alternativos, endereços de encaminhamento e métodos de pagamento anônimos para proteger seu endereço residencial.
**Use PIN, não biometria** | Avançado | Prefira PINs à biometria para segurança de dispositivos em situações em que possa haver coerção legal para desbloqueá-los.
**Reduza exposição a CCTV** | Avançado | Use disfarces e escolha rotas com menos câmeras para evitar vigilância.
**Roupas anti-reconhecimento facial** | Avançado | Use roupas com padrões que enganem tecnologia de reconhecimento facial.
**Reduza a exposição à visão noturna** | Avançado | Use fontes de luz IR ou óculos refletivos para obstruir câmeras de visão noturna.
**Proteja seu DNA** | Avançado | Evite compartilhar DNA com sites de ancestralidade e tenha cautela ao deixar rastros de DNA.


<!-- checklist-end -->

----

#### Existe uma versão interativa!
- [Digital Defense](https://digital-defense.io) - Veja detalhes, marque itens e acompanhe seu progresso

#### Outras listas incríveis de segurança
- @sbilly/[awesome-security](https://github.com/sbilly/awesome-security)
- @0x4D31/[awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection)
- @hslatman/[awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence)
- @PaulSec/[awesome-sec-talks](https://github.com/PaulSec/awesome-sec-talks)
- @Lissy93/[awesome-privacy](https://github.com/lissy93/awesime-privacy)
- @Zbetcheckin/[security_list](https://github.com/zbetcheckin/Security_list)
- Michael Horowitz / [defensivecomputingchecklist.com](https://defensivecomputingchecklist.com/)

[Ver mais](/4_Privacy_And_Security_Links.md#other-github-security-lists)

----

## Notas

*Obrigado pela visita, espero que você tenha encontrado algo útil aqui :) Contribuições são bem-vindas e muito apreciadas — para propor uma edição, [abra uma issue](https://github.com/Lissy93/personal-security-checklist/issues/new/choose) ou [abra um PR](https://github.com/Lissy93/personal-security-checklist/pull/new/master). Veja: [`CONTRIBUTING.md`](/.github/CONTRIBUTING.md).*

*Aviso: esta não é uma lista exaustiva e pretende apenas servir como guia.*

*Licenciado sob [Creative Commons, CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), © [Alicia Sykes](https://aliciasykes.com) 2020*

[![Attribution 4.0 International](https://licensebuttons.net/l/by/3.0/88x31.png)](/LICENSE.md)

---

Ajude a apoiar o desenvolvimento contínuo deste projeto 💖

[![Sponsor Lissy93 on GitHub](https://img.shields.io/badge/Sponsor_on_GitHub-Lissy93-%23ff4dda?style=for-the-badge&logo=githubsponsors&logoColor=ff4dda)](https://github.com/sponsors/Lissy93)

----

Achou isso útil? Considere compartilhar com outras pessoas para ajudá-las também a melhorar sua segurança digital 😇

[![Share on Twitter](https://img.shields.io/badge/Share-Twitter-17a2f3?style=for-the-badge&logo=Twitter)](http://twitter.com/share?text=Check%20out%20the%20Personal%20Cyber%20Security%20Checklist-%20an%20ultimate%20list%20of%20tips%20for%20protecting%20your%20digital%20security%20and%20privacy%20in%202020%2C%20with%20%40Lissy_Sykes%20%F0%9F%94%90%20%20%F0%9F%9A%80&url=https://github.com/Lissy93/personal-security-checklist)
[![Share on LinkedIn](https://img.shields.io/badge/Share-LinkedIn-0077b5?style=for-the-badge&logo=LinkedIn)](
http://www.linkedin.com/shareArticle?mini=true&url=https://github.com/Lissy93/personal-security-checklist&title=The%20Ultimate%20Personal%20Cyber%20Security%20Checklist&summary=%F0%9F%94%92%20A%20curated%20list%20of%20100%2B%20tips%20for%20protecting%20digital%20security%20and%20privacy%20in%202020&source=https://github.com/Lissy93)
[![Share on Facebook](https://img.shields.io/badge/Share-Facebook-4267b2?style=for-the-badge&logo=Facebook)](https://www.linkedin.com/shareArticle?mini=true&url=https%3A//github.com/Lissy93/personal-security-checklist&title=The%20Ultimate%20Personal%20Cyber%20Security%20Checklist&summary=%F0%9F%94%92%20A%20curated%20list%20of%20100%2B%20tips%20for%20protecting%20digital%20security%20and%20privacy%20in%202020&source=)
[![Share on Mastodon](https://img.shields.io/badge/Share-Mastodon-56a7e1?style=for-the-badge&logo=Mastodon)](https://mastodon.social/web/statuses/new?text=Check%20out%20the%20Ultimate%20Personal%20Cyber%20Security%20Checklist%20by%20%40Lissy93%20on%20%23GitHub%20%20%F0%9F%94%90%20%E2%9C%A8)

---

Entre em contato 📬

[![Alicia Sykes on Twitter](https://img.shields.io/twitter/follow/Lissy_Sykes?style=social&logo=twitter)](https://twitter.com/Lissy_Sykes)
[![Alicia Sykes on GitHub](https://img.shields.io/github/followers/lissy93?label=Lissy93&style=social)](https://github.com/Lissy93)
[![Alicia Sykes on Mastodon](https://img.shields.io/mastodon/follow/1032965?domain=https%3A%2F%2Fmastodon.social)](https://mastodon.social/web/accounts/1032965)
[![Alicia Sykes on Keybase](https://img.shields.io/badge/aliciasykes--lightgrey?style=social&logo=Keybase)](https://keybase.io/aliciasykes)
[![PGP da Alicia Sykes](https://img.shields.io/badge/PGP--lightgrey?style=social&logo=Let%E2%80%99s%20Encrypt)](https://keybase.io/aliciasykes/pgp_keys.asc)
[![Site da Alicia Sykes](https://img.shields.io/badge/aliciasykes.com--lightgrey?style=social&logo=Tencent%20QQ)](https://aliciasykes.com)

---
