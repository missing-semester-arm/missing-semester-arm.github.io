---
layout: lecture
title: "Ինչու՞ այս դասը:"
---

Համակարգչային գիտության ավանդական կրթության ընթացքում, հավանականությունը մեծ է, 
որ ձեզ կսովորեցնեն համակարգչային գիտության առաջադեմ թեմաներ՝ 
Օպերացիոն համակարգեր, ծրագրավորման լեզուներ և մեքենայական ուսուցում: Բայց շատ 
հաստատություններում կա մեկ էական թեմա, որը հազվադեպ է լուսաբանվում, և փոխարենը 
թողնվում է ուսանողներին՝ ինքնուրույն սովորելու համար: Դա հմուտ տիրապետումն է 
ծրագրավորման առօրյայում հաճախ օգտագործվող գործիքներին:

Տարիների ընթացքում մենք օգնել ենք մի քանի դասերի դասավանդմանը Մասաչուսեթսի 
տեխնոլոգիական ինստիտուտում (MIT), և նորից ու նորից տեսել ենք, որ շատ ուսանողներ 
սահմանափակ գիտելիքներ ունեն իրենց հասանելի գործիքների վերաբերյալ: Համակարգիչները 
ստեղծվել են ձեռքով առաջադրանքները ավտոմատացնելու համար, սակայն ուսանողները հաճախ 
կրկնվող առաջադրանքները կատարում են ձեռքով, կամ չեն կարողանում լիարժեք օգտվել 
հզոր գործիքներից, ինչպիսիք են տարբերակների վերահսկման համակարգերը (version control) 
և տեքստային խմբագրիչները (text editor): Լավագույն դեպքում դա հանգեցնում է 
անարդյունավետության և ժամանակի վատնման: Վատագույն դեպքում դա հանգեցնում է այնպիսի 
խնդիրների, ինչպիսիք են տվյալների կորուստը, կամ որոշակի առաջադրանքներ 
կատարելու անկարողությունը:

Այս թեմաները չեն դասավանդվում որպես համալսարանական ուսումնական պլանի մաս: 
Ուսանողներին երբեք չեն սովորեցնում, թե ինչպես արդյունավետ օգտագործել այս 
գործիքակազմը, և այդպիսով, չվատնել ժամանակ և ջանք այն առաջադրանքների վրա, որոնք պետք 
է լինեն պարզ:

# Ծրագրավորման կրթությունից բացակայող կիսամյակը

Դա շտկելու համար մենք վարում ենք դաս, որն ընդգրկում է բոլոր այն թեմաները, 
որոնք մենք կարևոր ենք համարում արդյունավետ ծրագրավորող լինելու համար: 
Դասը պրագմատիկ և գործնական է, և այն գործնականում ներկայացնում է 
գործիքներ և տեխնիկա, որոնք դուք կարող եք անմիջապես կիրառել ամենատարբեր 
իրավիճակներում։ Դասընթացն անցկացվում է Մասաչուսեթսի 
տեխնոլոգիական ինստիտուտոի «Անկախ գործունեության ժամանակաշրջան»-ի 
ընթացքում, 2020 թվականի հունվարին՝ մեկամսյա կիսամյակ, որը ներառում է ավելի կարճ 
դասեր, որոնք դասավանդվում են ուսանողների կողմից: Թեև դասախոսություններն  
հասանելի են միայն ինստիտուտոի ուսանողների համար, մենք հանրությանը կտրամադրենք 
դասախոսության բոլոր նյութերը, տեսագրությունների հետ միասին:

Ահա մի քանի թեմաներ դասընթացից:

## Տերմինալ (Command shell)

Ինչպե՞ս ավտոմատացնել սովորական և կրկնվող առաջադրանքները կեղծանուններով (aliases), 
սցենարներով (scripts), և կառուցման համակարգերով (build systems):

Օրինակ, նպատակային որոնումը նախկինում արված հրամանների պատմության մեջ կարող է 
հսկայական ժամանակ խնայել: Ստորև բերված օրինակում մենք ցույց ենք տալիս մի քանի 
հնարքներ տերմինալում արված `convert` հրամանների որոնման համար:

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/history.mp4" type="video/mp4">
</video>

## Տարբերակի վերահսկում (Version control)

Ինչպե՞ս ճիշտ օգտագործել տարբերակների վերահսկման համակարգերը ուրիշների հետ համագործակցելու, 
խնդրահարույց փոփոխությունները արագ գտնելու և մեկուսացնելու համար:
Մենք նույնիսկ կսովորեցնենք ձեզ, թե ինչպես համագործակցել այլ մարդկանց նախագծերի 
շուրջ տարբերակների վերահսկման համակարգերի միջոցով:

Ստորև բերված օրինակում մենք օգտագործում ենք `git bisect` հրամանը խնդրահարույց 
փոփոխությունները գտնելու համար: Այնուհետև մենք ուղղում ենք դրանք `git revert` հրամանի օգնությամբ:
<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/git.mp4" type="video/mp4">
</video>

## Տեքստի խմբագրում (Text editing)

Ինչպե՞ս արդյունավետ կերպով խմբագրել ֆայլերը տերմինալից, ինչպես տեղական, այնպես էլ
հեռակա կարգով, և օգտվել խմբագրի առաջադեմ հնարավորություններից:

Մակրոները Vim-ի լավագույն հատկանիշներից են: Ստորև բերված օրինակում մենք հեշտությամբ 
փոխակերպում ենք html աղյուսակը csv ձևաչափի, օգտագործելով ներկառուցված մակրո:
<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/vim.mp4" type="video/mp4">
</video>

## Հեռակա կառավարում (Remote machines)

Ինչպե՞ս աշխատել հեռակա մեքենաների հետ՝ օգտագործելով [SSH](https://en.wikipedia.org/wiki/Secure_Shell) և տերմինալային մուլտիպլեքսավորում:

Ստորև բերված օրինակում մենք օգտագործում ենք `tmux` հեռակա սերվերներում նիստերը 
կենդանի պահելու համար, և `mosh`՝ ցանցի ռոումինգին ու անջատմանը աջակցելու համար:

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/ssh.mp4" type="video/mp4">
</video>

## Ֆայլերի որոնում (Finding files)

Ինչպե՞ս արագ գտնել այն ֆայլերը, որոնք փնտրում եք:

Ստորև բերված օրինակում մենք `fd`-ով փնտրում ենք ֆայլեր և `rg`-ով փնտրում ենք կոդի հատվածներ: 
Օգտագործելով `fasd`, մենք արագ գտնում և վերախմբագրում ենք վերջին փոփոխված ֆայլը:

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/find.mp4" type="video/mp4">
</video>

## Տվյալների փոխակերպում (Data wrangling)

Ինչպե՞ս արագ և հեշտությամբ փոփոխել, դիտել, վերլուծել, գծագրել և հաշվարկել
տվյալները և ֆայլերը անմիջապես տերմինալից:

## Վիրտուալ մեքենաներ (Virtual machines)

Ինչպե՞ս օգտագործել վիրտուալ մեքենաներ նոր օպերացիոն համակարգեր փորձարկելու, 
և ձեր հիմնական մեքենան մաքուր և կոկիկ պահելու համար:

## Անվտանգություն (Security)

Ինչպե՞ս օգտվել համացանցից՝ առանց բացահայտելու ձեր գաղտնիքները:

## Եզրափակում (Conclusion)

Սա և ավելին կներկայացվեն 12 դասախոսությունների ընթացքում, որոնցից յուրաքանչյուրը 
ներառում է վարժություններ, որպեսզի դուք ձեռք բերեք այս գործիքների հետ աշխատելու գործնական փորձ:

<br>
Anish, Jose, and Jon
