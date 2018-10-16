---
layout: page
permalink: /o-nas
---

## Zwolnieni z Teorii
Platforma edukacyjna <a target="_blank" href="https://zwolnienizteorii.pl/">Zwolnieni z Teorii</a> powstała w 2013 roku, by dać każdemu młodemu człowiekowi możliwość darmowego nabywania kompetencji przyszłości, takich jak: współpraca, komunikacja, czy przywództwo.

Jest ona oparta o nowoczesną metodykę nauczania - Social Project Method™ - gdzie robiąc prawdziwy projekt społeczny, rozwija się praktyczne kompetencje, niemożliwe do zdobycia tradycyjnymi metodami nauczania.

Mamy ponad 40 tys. użytkowników, których działania wpłynęły na 10 mln beneficjentów! Dajemy młodym ludziom dostęp do profesjonalnych narzędzi biznesowych, dzięki którym realizują prawdziwe projekty społeczne.

<div class="sws">
  <div data-index="0" class="sw" style="background-image: url('{{ site.baseurl }}/images/wth/min_w0.jpg')"></div>
  <div data-index="1" class="sw" style="background-image: url('{{ site.baseurl }}/images/wth/min_w1.jpg')"></div>
  <div data-index="2" class="sw" style="background-image: url('{{ site.baseurl }}/images/wth/min_w2.jpg')"></div>
  <div data-index="3" class="sw" style="background-image: url('{{ site.baseurl }}/images/wth/min_w3.jpg')"></div>
</div>

## Wataha
Budujemy zgrany zespół ludzi, których łączy fascynacja technologią. Skupiamy inżynierów, czyli osoby które na codzień myślą technicznie, porządkują rzeczywistość i&nbsp;dążą do automatyzacji tam, gdzie to możliwe.

Pracując w startupie społecznym kładziemy nacisk na budowanie relacji i&nbsp;dbanie o wspólnie spędzony czas. Nie ma tu przypadkowych osób. Nasza praca to nie sprint, tylko maraton, dlatego inspirujemy i&nbsp;motywujemy się na pozostałych płaszczyznach życia.

## O mnie
Nazywam się Janek Horubała, jestem programistą web i&nbsp;mobile z ponad 5-letnim doświadczeniem. W ramach licencjatu z informatyki na MIM UW napisałem aplikację do rozpoznawania piw. Przewinąłem się przez takie miejsca jak Kalicińscy, Laboratorium EE czy Daftcode. Działałem w firmach zatrudniających ponad 100 pracowników, jak i&nbsp;małych startupach złożonych z 2-3 osób. Aktywnie uczestniczę w środowiskach programistyczno-startupowych (Reaktor, Indiehackers) i&nbsp;prowadzę szkolenia z&nbsp;programowania w&nbsp;ramach warsztatów WarsawJS. Od roku działam w Zwolnionych z&nbsp;Teorii w roli tech leada.


## Zapraszamy do naszego zespołu!
<div class="mes">
  <div class="me">
    <div style="background-image: url('/images/me/frontend.jpg')" class="img"></div>
    Frontend
  </div>
  <div class="me">
    <div style="background-image: url('/images/me/backend.jpg')" class="img"></div>
    Backend
  </div>
  <div class="me">
    <div style="background-image: url('/images/me/devops.jpg')" class="img"></div>
    DevOps
  </div>
</div>

{% include gallery.html %}

<script>
var pswpElement = document.querySelectorAll('.pswp')[0];
var items = [
  {
    src: '{{ site.baseurl }}/images/wth/w0.jpg',
    w: 1200,
    h: 800,
  },
  {
    src: '{{ site.baseurl }}/images/wth/w1.jpg',
    w: 1200,
    h: 800,
  },
  {
    src: '{{ site.baseurl }}/images/wth/w2.jpg',
    w: 1200,
    h: 800,
  },
  {
    src: '{{ site.baseurl }}/images/wth/w3.jpg',
    w: 1200,
    h: 800,
  },
  {
    src: '{{ site.baseurl }}/images/wth/w4.jpg',
    w: 900,
    h: 1200,
  },
  {
    src: '{{ site.baseurl }}/images/wth/w5.jpg',
    w: 1200,
    h: 800,
  },
  {
    src: '{{ site.baseurl }}/images/wth/w6.jpg',
    w: 1200,
    h: 800,
  },
  {
    src: '{{ site.baseurl }}/images/wth/w7.jpg',
    w: 1200,
    h: 800,
  },
  {
    src: '{{ site.baseurl }}/images/wth/w8.jpg',
    w: 1200,
    h: 800,
  },
  {
    src: '{{ site.baseurl }}/images/wth/w9.jpg',
    w: 800,
    h: 1200,
  },
];

// Initializes and opens PhotoSwipe
document.addEventListener('click', function (event) {
  if (!event.target.matches('.sw')) return;
  event.preventDefault();
  var index = parseInt(event.target.dataset.index || 0, 10);
  var gallery = new PhotoSwipe(pswpElement, PhotoSwipeUI_Default, items, { index: index });
  gallery.init();

}, false);

</script>
