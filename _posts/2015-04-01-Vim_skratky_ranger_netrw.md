---
layout: post
title: Vim skratky, netrw a ranger
categories: linux
---

# Vim skratky  

**Skratky s lomkou**

`[\ + r]` - otvorenie rangeru vo vime

`[\ + w]` - uloženie súbore v insert mode

`[\ + q]` - uloží a vypne súbor keď je v inser mode

`[\ + jj]` - vyhodi mi okno Explore

`[\ + kk]` - vrati ma z Explore do vimu (bufferu)

`[\ + n]` - vo vim-markdown sa posúvam dole cez jednolivé header-y

`[\ + u]` - vo vim-markdown sa posúvam hore ku jednotlivým headerom

`[\ + tg]` - vyhodi mi obsah funkcii a tagov z prostredia python, R
súborov/kódov

**Hľadanie**

`[F + znak]` - nájde mi znak smerom dozadu (do ľava)

`[*]` - v normal mode vyhľadá slovo na ktorom je kurzom po stlačeni *

`[g*]` - v normal mode vyhľadá slovo aj suffixam a prefixami

`[;]` - opakovanie zanku po f alebo F (funkcia hľadať)


**Insert mode**

`[<C-r> +]` - v insert mode vloží skopírovaný link

`[<C-r> *]` - v insert mode vloží text zo schránky browsera označení myšou

`[<C-d>]` - vymaže znak v insert mode smerom dopredu

`[<C-b]` - pohyb kurzorom smerom dozadu v insert mode

`[0-9 + i + znak]` - v normal mode napíšem číslo a potom v insert mode
napíšem znak, ktorý sa repetitívne vloží

**Ǔprava textu**

`[gq]` - upravý označený text pod visual modom, úpravy širku textu

`[gqG]` - upravý šírku textu od kurzora smerom dole

`[visual + [: s/old/new]]` - vo visual mode stlačim ':' potom s/old/new 
zamením všetky znaky old vo visual mode na new

`[visual + [: s/old/new/g]]` - vo visual mode zmení všetky znaky

`[:%s/.$//g]` - v normal mode mi vymaže posledný znak v každom riadku

`[:%s/.\{6}$//]` - v normal mode mi vymažé posledných 6 znakov v každom
riadku

`[vi + tvar zátvorky]` - vo visual móde mi označí obsah textu v dane
zátvorke a môžem s ním pracovať.

`[di + tvar zátvorky]` - v normal mode mi vymaže obsah danej zátvorky

`[ci + tvar zátvorky]` - robí to isté, čo di

`[<C-n>]` - v normal mode mi visuálne označí slovo na ktorom je 
kurzor, môžem ho vymazať alebo kopírovať. `označi mi aj slovo v zátvorke`

**Visual mode**

`[<C-V>]` - môžem vizuálne označovať, kopírovať, mazať text po stlpcoch

`[<C-V> I + znak]` - vizuálne označím kde všade chcem vložiť znak/zanky, cez
insert mode 'I' napíšem ľubovoľný znak, ktorý sa vloží do viacerýčh
riadkov



**Práca s oknami**

`[<C-w> v]` - rozdeli mi okno vo vime na verticalnu polovicu

`[<C-w> s]` - horizontalne rozdelenie okna

`[<C-w> H alebo K]` - vymena okien medzi ľavým a pravým | z horizon n
vertik.

`[<C-w> n]` - vytvori novy buffer (subor ak ho ulozim) na aktualne 'cd
miesto

`[:bd]` - zavrie buffer, na konci vykričník zavrie neuložený buffer


**Pohyb**

`[zt]` - posunie obsah textu dole pričom miesto kurzora sa nemeni

`[zb]` - posunie obsah textu hore, pozicia kurzora ostava

`[M] ` - presun kurzora na stred strany

`[L] ` - presun kurzora na spodnú časť strany

`[H] ` - presun kurzora na vrch strany

`[(] alebo [)]` - je pohyb medzi vetami riadkami oddelenými bodkou

`[{] alebo [}]` - je pohyb po odstavcoh

`[cd.]` - zmení mi miesto 'cd' na to, ktoré mám otvorené v bufferi



# Netrw skratky

`[%]`- tvorba nového súboru

`[D]`- vymaže súbory aj adresáre

`[d]`- tvorba nového adresára

`[R]`- premenovanie súboru alebo adresára

`[gb]` - presun do adresára označeného cez bookmark

`[mb]` - označenie adresára ako bookmarkd

`[u]` - pohyb naspäť do predchádzajúcich adresárov

`[-]` - pohyb vyššie ku kmeňovým adresárom

`[a]` - videnie .swp a dot file v Explore

`[md]` - označené dva súbory porovná cez vim diff

`[mu]` - zruši označenie všetkýčh súborov

`[V]` -  visualne označí súbory v Explore

# Ranger skratky

`[gn]` - vytvorí mi novú kartu (tab) s aktuálnym adresárom

`[tab]` - môžem prepínať medzi kartami adresárov

`[gt]` - tiež prepínanie medzi kartami adresárov

`[<C-w>]` - zatvorí mi kartu (tab)

`[f]` - nájde a okamžite otvorí adresár (výborne namiesto '/' na
vyhľadanie)

`[r]` - vyhodí mi ponuku otvorenia označeného súboru rôznymi programami
(napr. .exe, .mp4 súbory, .jpg a iné)

`[H]` - naspáť v histórii prezeranie

`[L]` - opak 'H' a ide dopredu v histórii prezerenia adresárov

`[V]` - visual mode na označenie súborov

`[S]` - dostane ma do zshellu s adresárom v ktorom som bol v rangeri

