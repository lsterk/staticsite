---

layout: default

title: "Christmas Letter 2025"

---

<!-- Existing content remains unchanged -->

## April in Europe - Tulips and More!

In April, we traveled across Europe with Rae's parents for a spring break. We met in Amsterdam, and enjoyed time walking along canals, visiting museums, and acclimating to vacation time.

![Rae and Landon in Amsterdam](assets/img/amsterdam_bicycle.jpg)

One of the highlights for all of us was visiting the tulip fields in Keukenhof near Amsterdam:

![Rae with the tulips](assets/img/tulips/rae1.jpg)
![Our group](assets/img/tulips/group1.jpg)
![Rae and her mom](assets/img/tulips/pair1.jpg)

We give thanks for wonderful memories with our family this year.

<!-- Swiper.js carousel structure moved to the bottom -->
<div class="swiper">
  <div class="swiper-wrapper">
    <div class="swiper-slide"><img src="assets/img/tulips/rae1.jpg" alt="Rae with the tulips"></div>
    <div class="swiper-slide"><img src="assets/img/tulips/group1.jpg" alt="Our group"></div>
    <div class="swiper-slide"><img src="assets/img/tulips/pair1.jpg" alt="Rae and her mom"></div>
  </div>
  <!-- Add navigation buttons -->
  <div class="swiper-button-next"></div>
  <div class="swiper-button-prev"></div>
  <div class="swiper-pagination"></div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    const swiper = new Swiper('.swiper', {
      loop: true,
      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
      },
      pagination: {
        el: '.swiper-pagination',
        clickable: true,
      },
    });
  });
</script>

Here's another carousel with the items in reverse order:

<div class="swiper tulip2">
  <div class="swiper-wrapper">
    <div class="swiper-slide"><img src="assets/img/tulips/pair1.jpg" alt="Rae and her mom" tile="Wow they look great"></div>
    <div class="swiper-slide"><img src="assets/img/tulips/group1.jpg" alt="Our group"></div>
    <div class="swiper-slide"><img src="assets/img/tulips/rae1.jpg" alt="Rae with the tulips"></div>
  </div>
  <!-- Add navigation buttons -->
  <div class="swiper-button-next"></div>
  <div class="swiper-button-prev"></div>
  <div class="swiper-pagination"></div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    const reverseSwiper = new Swiper('.tulip2', {
      loop: true,
      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
      },
      pagination: {
        el: '.swiper-pagination',
        clickable: true,
      },
    });
  });
</script>
