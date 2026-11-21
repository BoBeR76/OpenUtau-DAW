# 📖 Guia do OpenUtau DAW

[← Início](../README.md)

🌍 [Русский](GUIDE.md) · [English](GUIDE-en.md) · [Українська](GUIDE-uk.md) · [日本語](GUIDE-ja.md) · [Español](GUIDE-es.md) · [Deutsch](GUIDE-de.md) · [Français](GUIDE-fr.md) · [Italiano](GUIDE-it.md) · **Português** · [Polski](GUIDE-pl.md) · [Čeština](GUIDE-cs.md) · [Türkçe](GUIDE-tr.md) · [简体中文](GUIDE-zh.md) · [한국어](GUIDE-ko.md)

> [!NOTE]
> Este guia foi traduzido com um tradutor automático: o autor não fala português. Correções são bem-vindas em [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues).

O OpenUtau DAW integra o editor de canto OpenUtau diretamente na janela do plugin do Cubase. Aqui está o que o plugin acrescenta; o OpenUtau em si funciona como sempre. *(As animações mostram a interface em russo.)*

## Instalação

1. Baixe `OpenUtauDAW-Setup-2.7.0.exe` em [Releases](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest).
2. **Feche o Cubase.** Se ele estiver aberto, o instalador pede para fechá-lo e clicar em “Repetir”.
3. Na primeira página, escolha o idioma — ele também será o idioma do OpenUtau e da barra do plugin.
4. Marque a caixa do contrato de licença — sem ela, “Avançar” fica desativado.

São instalados o plugin **OpenUtau DAW** (VST3 e CLAP), a ponte de andamento **OpenUtau DAW Bridge** (ARA2) e o OpenUtau para DAW em `C:\OpenUtau-DAW`.

| | |
|---|---|
| ![Escolha do idioma](installer-welcome.png) | ![Licença](installer-license.png) |

> **Atualização.** A nova versão é instalada por cima da antiga. Configurações do OpenUtau, voicebanks e projetos são mantidos.

## Primeiro uso

1. No Cubase, adicione uma **faixa de instrumento** com o plugin **OpenUtau DAW**.
2. **O OpenUtau abre dentro da janela do plugin**, com uma faixa vazia já criada para este plugin.
3. Escolha um cantor e comece a escrever.

![Adicionando uma faixa OpenUtau DAW](media/01.gif)

> Se o plugin não estiver na lista: *Studio → VST Plug-in Manager → escanear de novo*.

## A barra do plugin

A faixa acima do OpenUtau na janela do plugin:

![Barra do plugin](media/panel.png)

| O que aparece | Significado |
|---|---|
| 🟢 **conectado** | Tudo pronto, o som corresponde às notas |
| 🟡 **renderizando 45%** | O OpenUtau está preparando o som |
| 🔴 **⚠ …** | Algo está errado — e diz o quê, p. ex. “a faixa 1 não tem cantor — escolha um no OpenUtau” |
| **110.00 BPM** | O andamento do Cubase que o OpenUtau vê |
| **Sinc. MIDI** | Traz as notas do Cubase durante a reprodução (veja abaixo) |
| **⚙** | Configurações do plugin |

![Sem cantor: mensagem vermelha; cantor escolhido: ponto verde](media/02.gif)

## Notas entre o Cubase e o OpenUtau

### Arrastar e soltar

- **Cubase → OpenUtau:** arraste uma parte MIDI da janela de projeto do Cubase para a janela do OpenUtau, na faixa e no compasso desejados.
- **OpenUtau → Cubase:** segure uma parte no OpenUtau, arraste-a **para fora da borda da janela do plugin** e solte-a num **espaço vazio** de uma faixa do Cubase.

![MIDI do Cubase para o OpenUtau e de volta](media/04.gif)

> Se o Cubase colocar a parte numa faixa nova: *Edit → Preferences → MIDI → MIDI File* → ative **“Import Dropped File as Single Part”**.

### Sincronizar ao reproduzir

1. Escreva as notas numa parte MIDI da faixa “OpenUtau DAW”.
2. Ative **“Sinc. MIDI”** na barra do plugin e reproduza o trecho.
3. As notas aparecem no OpenUtau. **As sílabas já digitadas são mantidas** — dá para mudar a melodia no Cubase sem perder a letra.
4. Ao terminar, desative “Sinc. MIDI”.

### As teclas acendem

As notas pressionadas aparecem no piano roll do OpenUtau, como no editor do Cubase:

- você toca num **teclado MIDI** ou clica nas teclas do editor do Cubase — essas teclas **acendem no OpenUtau**;
- você clica nas teclas do piano roll do OpenUtau — a nota soa **pelo Cubase**, na saída do plugin.

![Teclas pressionadas no OpenUtau](media/keys.gif)

## Transporte e andamento

![Transporte do OpenUtau](media/transport.png)

- **Reproduzir, Parar e “ir para o início”** no OpenUtau (e `Espaço`, `Home`) controlam o Cubase — toca a música inteira, não só a voz.
- O OpenUtau pega **o andamento e a fórmula de compasso** do Cubase: mudou o BPM, o OpenUtau acompanha.

## Ponte de andamento OpenUtau DAW Bridge

Se **o andamento muda durante a música**, adicione a ponte — assim o OpenUtau conhece todo o mapa de andamento e compassos. Uma vez por projeto:

1. Crie uma faixa de áudio e coloque nela qualquer evento de áudio cobrindo a música inteira. Silencie-o (Mute).
2. Selecione o evento → *Audio → Extensions →* **“OpenUtau DAW Bridge”**.

Funciona da mesma forma que no VOCALOID.

![OpenUtau DAW Bridge](media/10.gif)

## Várias vozes

**Cada faixa “OpenUtau DAW” do Cubase é uma voz própria**, todas na mesma janela do OpenUtau.

- Nova faixa “OpenUtau DAW” no Cubase → nova faixa vazia no OpenUtau.
- **“+”** no OpenUtau → nova faixa **também no Cubase**.

![“+” no OpenUtau cria uma faixa no Cubase](media/11.gif)

- **O nome e a cor** da faixa do Cubase passam para o OpenUtau.

![A cor da faixa do Cubase passa para o OpenUtau](media/13.gif)

### ⚙ Se o “+” não deve criar faixa no Cubase

> [!TIP]
> **Precisa de várias vozes numa só faixa do Cubase?** Clique em **⚙** à direita da barra do plugin e desmarque **“O botão “+” do OpenUtau também adiciona uma faixa no Cubase”**.
>
> Aí o “+” adiciona a voz só no OpenUtau, e ela toca na saída **“Track N”** do mesmo plugin (ative-a em **F11**).

![Menu ⚙ do plugin](media/gear-menu.png)

## Salvamento e backups

- **A voz é salva automaticamente com o projeto do Cubase.**
- São guardadas **as 10 últimas versões**. Para restaurar uma: *Arquivo →* **“Restaurar de um backup”**.

## Pequenas conveniências

- 🔁 **Reinício automático.** Se o OpenUtau travar, o plugin o reinicia. A voz não se perde.
- 🪟 **Janelas sobre o plugin.** Preferências, cantores e mensagens do OpenUtau abrem sobre a janela do plugin — o Cubase não a esconde.
- 🎚 **Saídas separadas.** 8 saídas estéreo “Track 1…8”, uma por faixa do OpenUtau (ative em F11).
- ⏳ **A exportação espera o render.** Se o OpenUtau ainda prepara o som, o Audio Mixdown espera.
- ⚡ **Sem janelas a mais.** No Cubase, o OpenUtau pula a página inicial e abre direto a voz do projeto.
- 🌍 **14 idiomas**, e a barra do plugin usa o mesmo idioma do OpenUtau.

## Ainda não é possível

- **Escrever notas no editor do próprio Cubase** (como no VOCALOID) e sincronização bidirecional ao vivo. Isso depende do ARA 3 — será feito assim que a Celemony lançá-lo.
- Os marcadores do Cubase não ficam acessíveis aos plugins, então o OpenUtau não os mostra.

## Perguntas frequentes

**O instalador diz que o Cubase está aberto.** Feche o Cubase por completo (o processo continua alguns segundos depois da janela) e clique em “Repetir”.

**Sem som.** Olhe o ponto na barra do plugin: 🔴 — a causa está escrita ao lado; 🟡 — espere o render terminar.

**O plugin não está na lista.** *Studio → VST Plug-in Manager → escanear de novo*.

**“O OpenUtau está aberto em outra janela do plugin”.** Clique na mensagem — o OpenUtau passa para esta janela.
