---
layout: page
title: Ծրագրավորման կրթությունից բացակայող կիսամյակը
---

Դասընթացները ձեզ սովորեցնում են ամեն ինչ Ծրագրավորման առաջադեմ թեմաների 
մասին՝ օպերացիոն համակարգերից մինչև մեքենայական ուսուցում, բայց կա մեկ կարևոր թեմա, 
որը հազվադեպ է լուսաբանվում, և փոխարենը թողնված է ուսանողներին ինքնուրույն 
պարզելու: Դա հմուտ տիրապետումն է ծրագրավորման առօրյայում հաճախ օգտագործվող գործիքներին: 
Մենք կսովորեցնենք ձեզ, թե ինչպես տիրապետել տերմինալին, օգտագործել հզոր տեքստային 
խմբագրիչ, օգտագործել տարբերակների վերահսկման համակարգերի առաջադեմ 
հատկություններ և շատ ավելին:

Ուսանողները ծախսում են հարյուրավոր ժամեր օգտագործելով այս գործիքներն իրենց 
ուսման ընթացքում (և հազարավոր՝ իրենց կարիերայի ընթացքում), ուստի իմաստ ունի 
փորձը դարձնել հնարավորինս սահուն: Այս գործիքների տիրապետումը թույլ է տալիս 
լուծել խնդիրներ, որոնք նախկինում անհավանական բարդ էին թվում:

[Դասընթացի մոտիվացիայի և նպատակների մասին](/about/):

<ul>
{% assign lectures = site['2020'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%-m/%d/%y' }}</strong>:
        {% if lecture.ready %}
            <a href="{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>

Տեսանյութերի տեսացանկը հասանելի է [YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)-ում:

# Դասընթացի մասին

**Դասախոսներ**: [Anish](https://www.anishathalye.com/), [Jon](https://thesquareplanet.com/), և [Jose](http://josejg.com/):<br>

# Լրացուցիչ ռեսուրսներ

- [Hacker News](https://news.ycombinator.com/item?id=22226380)
- [Lobsters](https://lobste.rs/s/ti1k98/missing_semester_your_cs_education_mit)
- [/r/learnprogramming](https://www.reddit.com/r/learnprogramming/comments/eyagda/the_missing_semester_of_your_cs_education_mit/)
- [/r/programming](https://www.reddit.com/r/programming/comments/eyagcd/the_missing_semester_of_your_cs_education_mit/)
- [Twitter](https://twitter.com/jonhoo/status/1224383452591509507)
- [YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)

# Թարգմանություններ

- [Chinese (Simplified)](https://missing-semester-cn.github.io/)
- [Chinese (Traditional)](https://missing-semester-zh-hant.github.io/)
- [Japanese](https://missing-semester-jp.github.io/)
- [Korean](https://missing-semester-kr.github.io/)
- [Portuguese](https://missing-semester-pt.github.io/)
- [Russian](https://missing-semester-rus.github.io/)
- [Serbian](https://netboxify.com/missing-semester/)
- [Spanish](https://missing-semester-esp.github.io/)
- [Turkish](https://missing-semester-tr.github.io/)
- [Vietnamese](https://missing-semester-vn.github.io/)

Նշում: Այս թարգմանությունները կատարվել են օգտվողների կողմից և սրբագրված չեն:

## Երախտագիտություն

Շնորհակալություն ենք հայտնում Elaine Mello-ին, Jim Cain-ին, և [MIT Open
Learning](https://openlearning.mit.edu/) կայքին տեսագրությունների համար; Anthony Zolnik-ին և [MIT
AeroAstro](https://aeroastro.mit.edu/) կայքին աուդիո և վիդեո սարքավորումների համար; Brandi Adams-ին և
[MIT EECS](https://www.eecs.mit.edu/) կայքին դասընթացին աջակցելու համար:

---

<div class="small center">
<p><a href="https://github.com/missing-semester/missing-semester">Source code</a>.</p>
<p>Լիցենզիա CC BY-NC-SA:</p>
<p><a href="/license/">Լիցենզիայի և մասնակցության մանրամասներ:</a></p>
</div>