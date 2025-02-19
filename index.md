---
layout: page
permalink: /
---

# Cześć!
Szukamy programistów do zespołu technologicznego. Opis stanowisk i&nbsp;przykładowe zadania znajdziesz w zakładce <a href="/pozycje.html">pozycje</a>. Szczegółowe informacje o naszej działalności i&nbsp;głównym projekcie - platformie zwolnienizteorii.pl - znajdziesz w zakładce <a href="/o-nas.html">o nas</a>. Zależy nam na tworzeniu długofalowych relacji i wspólnym znajdowaniu możliwości, więc jeśli coś Cię zainteresuje, po prostu napisz <a href="mailto:jan.horubala@gmail.com">e-maila</a> i umówmy się na spotkanie.

<div class="sws">
  <div data-index="0" class="sw" style="background-image: url('{{ site.baseurl }}/images/sw/min_s0.jpg')"></div>
  <div data-index="1" class="sw" style="background-image: url('{{ site.baseurl }}/images/sw/min_s1.jpg')"></div>
  <div data-index="2" class="sw" style="background-image: url('{{ site.baseurl }}/images/sw/min_s2.jpg')"></div>
  <div data-index="3" class="sw" style="background-image: url('{{ site.baseurl }}/images/sw/min_s3.jpg')"></div>
</div>

# Co oferujemy?
- elastyczne godziny pracy
- możliwość pracy zdalnej
- świeże owoce i&nbsp;pyszną kawę
- startupową, przyjazną i&nbsp;inspirującą atmosferę
- pracę z zaangażowanymi i&nbsp;przedsiębiorczymi ludźmi
- dostęp do konferencji i&nbsp;warsztatów, książki branżowe
- wspólne imprezy i&nbsp;wyjazdy integracyjne 2 razy w roku
- wydarzenia Zwolnionych - Wielki Finał, trasa, imprezy i&nbsp;szkolenia mentorskie
- świetną lokalizację biura na Żoliborzu, 15 metrów od wyjścia z metra Plac Wilsona
- dobrze wyposażone biuro (kuchnia, lodówka, ekspres, prysznic i&nbsp;pralka ;)
- możliwość rozwijania własnych projektów, wsparcie merytoryczne
- możliwość nauki i&nbsp;rozwoju w oparciu o najlepsze praktyki programistyczne
- dostęp do inicjatywy i energii tysięcy młodych ludzi z całej Polski, realizujących projekty społeczne na platformie
- motywację do rozwoju, uczestnictwo w konferencjach programistycznych, doskonalenia warsztatu technicznego przez kursy i hackathony
- nieformalne rozmowy oraz czerpanie wiedzy biznesowej od naszych Przyjaciół i&nbsp;partnerów biznesowych, m.in. kadry zarządzającej Coca-Cola czy Google
- wynagrodzenie (złotych / miesięcznie): junior do 3k, senior do 10k

<!-- # Z kim działamy?
<div class="marks">
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/partners/p2.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/partners/p3.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/partners/p4.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/partners/p1.jpg')"></div>
</div>
 -->
# Wyróżnienia
<div class="marks">
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/marks/m1.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/marks/m2.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/marks/m8.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/marks/m6.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/marks/m4.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/marks/m3.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/marks/m7.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/marks/m9.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/marks/m5.jpg')"></div>
  <div class="mark" style="background-image: url('{{ site.baseurl }}/images/marks/m10.jpg')"></div>
</div>

{% include gallery.html %}

<script>
var pswpElement = document.querySelectorAll('.pswp')[0];
var items = [];

for (var i = 0; i < 10; i++) {
  items.push({
    src: '{{ site.baseurl }}/images/sw/s' + i + '.jpg',
    w: 1200,
    h: 800,
  })
}

// Initializes and opens PhotoSwipe
document.addEventListener('click', function (event) {
  if (!event.target.matches('.sw')) return;
  event.preventDefault();
  var index = parseInt(event.target.dataset.index || 0, 10);
  var gallery = new PhotoSwipe(pswpElement, PhotoSwipeUI_Default, items, { index: index });
  gallery.init();
}, false);
</script>





