---
layout: about
title: Skontaktuj się!
hide_description: true
---

## Dane Kontaktowe

Można się ze mną skontaktować poprzez poniższe metody:

---

<div class="contact-info">
  <img class="contact-img" src="/assets/img/jacek-wilczak.webp">
  <div>
    <div class="author-name"><b>Dr Jacek Wilczak</b><br></div>
    <div id="container">
        <a id="emailLink" href="#" rel="noopener noreferrer" style="display: none;"></a> <br>
        <a id="phoneLink" href="#" rel="noopener noreferrer" style="display: none;"></a>
    </div> 
  </div>
</div>

---

## Social Media

Jestem także aktywny w **Social Mediach** na poniższych kontach:

[Facebook - DietaPeta](https://www.facebook.com/DietaPeta) <br>
[Instagram - dieta_peta](https://www.instagram.com/dieta_peta/)

<script>
    (function () {
      var emailLink = document.getElementById('emailLink');
      var phoneLink = document.getElementById('phoneLink');

      // Replace with your address pieces
      var user = 'jacekwilczak';
      var domain = 'dietapeta.pl';
      var p1 = '+48';
      var top = '600';
      var mid = '231';
      var last = '463';

      // After 4 seconds, show the email and phone links
      setTimeout(function () {
        // Update email link
        var mailto = user + '@' + domain;
        emailLink.href = 'mailto:' +mailto;
        emailLink.textContent = mailto;
        emailLink.className = 'neon-button'; // apply your neon style
        emailLink.style.display = 'inline-block';

        // Update phone link
        var telLink = p1 + ' ' + top + ' ' + mid + ' ' + last;
        phoneLink.href = 'tel:' + telLink;
        phoneLink.textContent = telLink;
        phoneLink.className = 'neon-button'; // apply your neon style
        phoneLink.style.display = 'inline-block';
      }, 2000);
    })();
</script>