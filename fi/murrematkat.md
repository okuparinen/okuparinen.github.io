---
layout: default
lang: fi
i18n-link: murrematkat
title: Murrematkat
---
# Murrematkat
Kirjoitan tälle sivulle raportteja pyörämatkoistani Suomen kielen näytteitä -murresarjan puhujien kotipaikoille. Murreaineistoon on haastateltu vanhoja puhujia 50:stä suomenkielisestä pitäjästä 1960- ja 70-luvuilla. Sarjan puhujien asuinpaikat on merkitty oheiseen karttaan yhdessä suomen murrealueiden kanssa.
Aineistosta lisää [Kotimaisten kielten keskuksen sivuilla](https://www.kotus.fi/aineistot/puhutun_kielen_aineistot/murreaanitteita/suomen_kielen_naytteita_-sarja).

<img src="../assets/images/murrematkat.png" alt="Suomen kielen näytteitä -sarjan haastattelupaikat sekä suomen murrealueet" hspace="20" width="70%" align="center"/>

## Viimeisimmät

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
