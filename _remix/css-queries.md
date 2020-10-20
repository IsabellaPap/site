---
layout: single
title: CSS queries
header: no
categories:
  - method
tags:
  - css
  - queries
  - IV
---

Παράδειγμα κώδικα με σκοπό να γίνει κατανοητή η χρήση των CSS media queries. Αλλάζοντας το μέγεθος του παραθύρου του περιηγητή (browser) σας αλλάζει το χρώμα της επιφάνειας του παραδείγματος.

<p data-height="350" data-theme-id="17517" data-slug-hash="vOoyJG" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='https://codepen.io/sckarolos/pen/vOoyJG/'>media queries example</a> by sckarolos (<a href='https://codepen.io/sckarolos'>@sckarolos</a>) on <a href='https://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Πειραματιστείτε με το παράδειγμα προσθέτοντας περισσότερα CSS media queries και αλλάζοντας το χρώμα του παραθούρου. Στη συνέχεια δοκιμάστε να εφαρμόσετε CSS media queries στο μέγεθος της γραμματοσειράς ώστε να απεικονίζεται σωστά σε όλα τα μεγέθη παραθύρων.

<!DOCTYPE html>
<html>
<head>
<style>
body {
    background-color: #66cd00;
    font-family: helvetica, arial, serif;
    color: #fff;
    font-size: 50px;
}

@media screen and (max-width: 1220px) {
    body {
        background-color: #8a2be2;
        font-size: 40px;
    }
}

@media screen and (max-width: 768px) {
    body {
        background-color: #ff2500;
        font-size: 27px;
    }
}

@media screen and (max-width: 420px) {
    body {
        background-color: #fcc419;
        color: #000;
      font-size: 23px;
    }
}
</style>
</head>
<body>
<p>RESIZE BROWSER'S WINDOW</p>
</body>
</html>
