---
layout: lecture
title: "Ինչու՞ ենք մենք դասավանդում այս դասը"
---

Համակարգչային գիտության ավանդական կրթության ընթացքում, հավանականությունը մեծ է, որ դուք կվերցնեք
շատ դասեր, որոնք ձեզ սովորեցնում են համակարգչային գիտության առաջադեմ թեմաներ՝ 
Օպերացիոն համակարգեր, ծրագրավորման լեզուներ և մեքենայական ուսուցում: Բայց շատ 
հաստատություններում կա մեկ էական թեմա, որը հազվադեպ է լուսաբանվում և փոխարենը 
թողնվում է ուսանողներին ինքնուրույն սովորելու համար: Դա հաշվողական էկոհամակարգի 
գրագիտությունն է:

Տարիների ընթացքում մենք օգնել ենք մի քանի դասերի դասավանդմանը MIT-ում, և նորից 
ու նորից տեսել ենք, որ շատ ուսանողներ սահմանափակ գիտելիքներ ունեն իրենց հասանելի 
գործիքների վերաբերյալ: Համակարգիչները ստեղծվել են ձեռքով առաջադրանքները 
ավտոմատացնելու համար, սակայն ուսանողները հաճախ կրկնվող առաջադրանքները կատարում 
են ձեռքով կամ չեն կարողանում լիարժեք օգտվել հզոր գործիքներից, ինչպիսիք են 
տարբերակների կառավարումը և տեքստային խմբագրիչները: Լավագույն դեպքում դա 
հանգեցնում է անարդյունավետության և ժամանակի վատնման. վատագույն դեպքում դա 
հանգեցնում է այնպիսի խնդիրների, ինչպիսիք են տվյալների կորուստը կամ որոշակի 
առաջադրանքներ կատարելու անկարողությունը:

Այս թեմաները չեն դասավանդվում որպես համալսարանական ուսումնական պլանի մաս: 
Ուսանողներին երբեք չեն սովորեցնում, թե ինչպես արդյունավետ օգտագործել այս 
գործիքները և այդպիսով չվատնել ժամանակ և ջանք այն առաջադրանքների վրա, որոնք պետք 
է լինեն պարզ: Համակարգչային գիտությունների ստանդարտ ուսումնական ծրագրում 
բացակայում են հաշվողական էկոհամակարգի վերաբերյալ կարևոր թեմաներ, որոնք կարող 
են զգալիորեն հեշտացնել ուսանողների կյանքը:

# Ձեր Համակարգչային գիտության կրթությունից բացակայող կիսամյակը

Դա շտկելու համար մենք վարում ենք դաս, որն ընդգրկում է բոլոր այն թեմաները, 
որոնք մենք կարևոր ենք համարում արդյունավետ համակարգչային գիտնական և ծրագրավորող 
լինելու համար: Դասը պրագմատիկ և գործնական է, և այն գործնականում ներկայացնում է 
գործիքներ և տեխնիկա, որոնք դուք կարող եք անմիջապես կիրառել ամենատարբեր 
իրավիճակներում։ Դասընթացն անցկացվում է MIT-ի «Անկախ գործունեության ժամանակաշրջանի» 
ընթացքում՝ 2020 թվականի հունվարին՝ մեկամսյա կիսամյակ, որը ներառում է ավելի կարճ 
դասեր, որոնք դասավանդվում են ուսանողների կողմից: Թեև դասախոսություններն իրենք 
հասանելի են միայն MIT-ի ուսանողների համար, մենք հանրությանը կտրամադրենք 
դասախոսության բոլոր նյութերը դասախոսությունների տեսագրությունների հետ միասին:

Եթե թվում է, թե դա կարող է ձեզ համար լինել, ահա մի քանի կոնկրետ
օրինակներ, թե ինչ կսովորեցնեն ձեզ.

## Հրամանի պատյան (Command shell)

Ինչպես ավտոմատացնել սովորական և կրկնվող առաջադրանքները կեղծանուններով (aliases), 
սցենարներով (scripts), և կառուցման համակարգերով (build systems): Այլևս տեքստից 
պատճենահանման հրամաններ չկան փաստաթուղթ։

Օրինակ, ձեր հրամանների պատմության մեջ արագ որոնումը կարող է հսկայական ժամանակ խնայել:
Ստորև բերված օրինակում մենք ցույց ենք տալիս մի քանի հնարքներ հրամանի պատյանում 
ձեր կողմից արված `convert` հրամանների որոնման համար:

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/history.mp4" type="video/mp4">
</video>

## Տարբերակի վերահսկում (Version control)

Ինչպես ճիշտ օգտագործել տարբերակի վերահսկումը ուրիշների հետ համագործակցելու, 
խնդրահարույց փոփոխությունները արագ գտնելու և մեկուսացնելու համար. 
Մենք նույնիսկ կսովորեցնենք ձեզ, թե ինչպես նպաստել այլ մարդկանց 
նախագծերին ձգողական պահանջներով (pull requests):

Ստորև բերված օրինակում մենք օգտագործում ենք `git bisect` հրամանը խնդրահարույց 
փոփոխությունները գտնելու համար: Այնուհետև մենք այն ուղղում ենք `git revert`-ով:
<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/git.mp4" type="video/mp4">
</video>

## Text editing

How to efficiently edit files from the command-line, both locally and
remotely, and take advantage of advanced editor features. No more
copying files back and forth. No more repetitive file editing.

Vim macros are one of its best features, in the example below we quickly convert an html table to csv format using a nested vim macro.
<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/vim.mp4" type="video/mp4">
</video>

## Remote machines

How to stay sane when working with remote machines using SSH keys and
terminal multiplexing. No more keeping many terminals open just to
run two commands at once. No more typing your password every time you
connect. No more losing everything just because your Internet
disconnected or you had to reboot your laptop.

In the example below we use `tmux` to keep sessions alive in remote servers and `mosh` to support network roaming and disconnection.

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/ssh.mp4" type="video/mp4">
</video>

## Finding files

How to quickly find files that you are looking for. No
more clicking through files in your project until you find the one
that has the code you want.

In the example below we quickly look for files with `fd` and for code snippets with `rg`. We also quickly `cd` and `vim` recent/frequent files/folder using `fasd`.

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/find.mp4" type="video/mp4">
</video>

## Data wrangling

How to quickly and easily modify, view, parse, plot, and compute over
data and files directly from the command-line. No more copy pasting
from log files. No more manually computing statistics over data. No
more spreadsheet plotting.

## Virtual machines

How to use virtual machines to try out new operating systems, isolate
unrelated projects, and keep your main machine clean and tidy. No
more accidentally corrupting your computer while doing a security
lab. No more millions of randomly installed packages with differing
versions.

## Security

How to be on the Internet without immediately revealing all of your
secrets to the world. No more coming up with passwords that match the
insane criteria yourself. No more unsecured, open WiFi networks. No
more unencrypted messaging.

# Conclusion

This, and more, will be covered across the 12 class lectures, each including an
exercise for you to get more familiar with the tools on your own. If you can't
wait for January, you can also take a look at the lectures from [Hacker
Tools](https://hacker-tools.github.io/lectures/), which we ran during IAP last
year. It is the precursor to this class, and covers many of the same topics.

We hope to see you in January, whether virtually or in person!

Happy hacking,<br>
Anish, Jose, and Jon
