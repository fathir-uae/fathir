<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Message by Fathir</title>
     <style>
      * {
  box-sizing: border-box;
}
body {
  margin: 0;
  display: flex;
  min-height: 100dvh;
  perspective: 1000px;
  font: 1em/1.4 "Calibri", sans-serif;
  overflow: hidden;
  color: hsl(180 68% 5%);
  background-image: radial-gradient(
      circle farthest-corner at 50% 50%,
      hsl(187 20% 88%) 30%,
      hsl(149 20% 94%) 100%
  );
}
.image-container {
  display: flex;
  justify-content: center;
  margin-top: 20px;
}
.image-container img {
  width: 80%;
  max-width: 180px;
  border-radius: 15px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
}
.book {
  position: relative;
  display: flex;
  margin: auto;
  width: 42cqmin; /* Increased width */
  pointer-events: none;
  transform-style: preserve-3d;
  transition: translate 1s;
  translate: calc(min(var(--c), 1) * 50%) 0%;
  rotate: 1 0 0 30deg;
}
.page {
  --thickness: 4;
  flex: none;
  display: flex;
  width: 100%;
  font-size: 2.2cqmin; /* Slightly increased font size */
  pointer-events: all;
  user-select: none;
  transform-style: preserve-3d;
  transform-origin: left center;
  transition: transform 1s,
      rotate 1s ease-in calc((min(var(--i), var(--c)) - max(var(--i), var(--c))) * 50ms);
  translate: calc(var(--i) * -100%) 0px 0px;
  transform: translateZ(calc((var(--c) - var(--i) - 0.5) * calc(var(--thickness) * 0.23cqmin)));
  rotate: 0 1 0 calc(clamp(0, var(--c) - var(--i), 1) * -180deg);
}
.front,
.back {
  position: relative;
  flex: none;
  width: 100%;
  backface-visibility: hidden;
  overflow: hidden;
  background-color: #fff;
  translate: 0px;
}
.back {
  translate: -100% 0;
  rotate: 0 1 0 180deg;
}
.book {
  counter-reset: page -1;
}
.book a {
  color: inherit;
}
.page {
  box-shadow: 0em 0.5em 1em -0.2em #00000020;
}
.front,
.back {
  display: flex;
  flex-flow: column wrap;
  justify-content: space-between;
  padding: 2em;
  border: 1px solid #0002;
}
.front:has(img),
.back:has(img) {
  padding: 0;
}
.front img,
.back img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.front::after,
.back::after {
  position: absolute;
  bottom: 1em;
  counter-increment: page;
  content: counter(page) ".";
  font-size: 0.8em;
}
.cover::after {
  content: "";
}
.front::after {
  right: 1em;
}
.front {
  background: linear-gradient(to left, #f7f7f7 80%, #eee 100%);
  border-radius: 0.1em 0.5em 0.5em 0.1em;
}
.back::after {
  left: 1em;
}
.back {
  background-image: linear-gradient(to right, #f7f7f7 80%, #eee 100%);
  border-radius: 0.5em 0.1em 0.1em 0.5em;
}
.front.cover {
  background: radial-gradient(
          circle farthest-corner at 80% 20%,
          hsl(150 80% 20% / 0.3) 0%,
          hsl(170 60% 10% / 0.1) 100%
      ),
      hsl(231, 32%, 29%) url("https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjLqknq5WAiKkv0rdMvyQhmh7XdEUKUUc7hUfSfbeyWXFJ3trpech1bybCP8gyv6i_lFgV6yp7-BVdalJ7w8uOxNF-O-ZIbsngDS7_F3pTEznoxhKZq2DKydn5Ki_sMCEW_ZVLEY8TwYWovcseHdE_gSY0Z4At8IdQ3TAAkL3hsyXFzJ0JjLfOwOVXmZ-8/s16000/A%20CARD%20by%20FATHIR.png") 50% / cover;
  color: white;
}

.back.cover {
  background: radial-gradient(
          circle farthest-corner at 80% 20%,
          hsl(150 80% 20% / 0.3) 0%,
          hsl(170 60% 10% / 0.1) 100%
      ),
      hsl(20, 80%, 40%) url("https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgmqfvaNwcfeZg-43XEhm2YNncWS2PMMhDmZ5aoVQu3t0v9yW7Z0gb4fp3aLqUNgeAThehBGaV-u_pnZPv91-7lbyGFuEuvZ2neCbF4S-iHYNpXwZCXTxem_L8tq4ZckBPGDV6nLzQiLoUr1YUicsgApo8Z6k9zXGo84i_n892AaIxyKv3qVSZdGIrKm58/s16000/A%20CARD%20by%20FATHIR%20(1).png") 50% / cover;
  color: white;
}
h1,
h2,
h3 {
  margin-bottom: 1px;
  color: hsl(0, 100%, 30%); /* Dark red heading color */
}
p {
  margin-top: 1px;
  margin-bottom: 8px;
  line-height: 1.4;
  color: hsl(0, 100%, 30%); /* Dark red text color for paragraphs */
}
.front,
.back {
  padding: 1.5em;
  color: hsl(0, 100%, 30%); /* Dark red text color for front and back pages */
}
.book {
  width: 40cqmin; /* Slightly increased width */
}
.page {
  font-size: 2cqmin; /* Slightly increased font size */
}
p:last-child {
  margin-bottom: 0;
}
.front,
.back {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  padding: 1.5em;
}
h2 {
  margin-bottom: 5px;
}
p {
  margin-top: 5px;
  line-height: 1.4;
}
body {
  margin: 0;
  display: flex;
  min-height: 100dvh;
  perspective: 1000px;
  font: 1em/1.4 "Calibri", sans-serif;
  overflow: hidden;
  color: hsl(180 68% 5%);
  background: linear-gradient(to right, #ff7eb9, #ff65a3, #ff165d);
  background-size: 400% 400%;
  animation: gradientAnimation 10s ease infinite;
}
@keyframes gradientAnimation {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}
/* Emoji Animation */
.emoji {
  position: absolute;
  font-size: 3rem;
  opacity: 0;
  animation: floatEmojis 6s ease-in-out infinite;
}
@keyframes floatEmojis {
  0% {
    transform: translateY(100px);
    opacity: 1;
  }
  50% {
    transform: translateY(-100px) rotate(20deg);
    opacity: 0.7;
  }
  100% {
    transform: translateY(100px);
    opacity: 1;
  }
}
/* Add random timing for each emoji */
.emoji:nth-child(1) {
  animation-delay: 0s;
  left: 10%;
}
.emoji:nth-child(2) {
  animation-delay: 1s;
  left: 20%;
}
.emoji:nth-child(3) {
  animation-delay: 2s;
  left: 30%;
}
.emoji:nth-child(4) {
  animation-delay: 3s;
  left: 40%;
}
.emoji:nth-child(5) {
  animation-delay: 4s;
  left: 50%;
}
.emoji:nth-child(6) {
  animation-delay: 5s;
  left: 60%;
}
.emoji:nth-child(7) {
  animation-delay: 6s;
  left: 70%;
}
.emoji:nth-child(8) {
  animation-delay: 7s;
  left: 80%;
}
.emoji:nth-child(9) {
  animation-delay: 8s;
  left: 90%;
}
     </style>
  </head>
  <body>
    <div class="book">
      <div class="page">
        <div class="front cover">
          <h1
            style="
              color: rgb(255, 255, 255);
              text-shadow: 5px 2px 5px rgb(0, 0, 0);
            "
          >
          </h1>
          <p
            style="
              color: rgb(255, 255, 255);
              text-shadow: 5px 2px 5px rgb(0, 0, 0);
            "
          >
          </p>
        </div>
        <div class="back">
          <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhuH7tVRMl2sAa8uxGg9t69koRHssYF9Dlqw3p3B_t4NkbjpBJrRkIJ8zC3gLWMh2U3Y_U9hFge50xeWDirsI27-qX3keqaRXNpTUYXm7A9Z4_jEVjbtnOggBZquFC8bpYd3jdSOXjUBW6CL8d-U18B2aGAphBnQAqwKbzavCqF9vCyO6NcSFCkmQAN0g0/s320/atb1.png" alt="Img 1" />
          </p>
        </div>
      </div>
      <!--2nd page-->
      <div class="page">
        <div class="front">
          <h2>New Steps, New Dreams! ✨</h2>
          <p>
            Hai Tiara! 🎉
<p>
Selamat ulang tahun! 🎉🥳 Semoga di usia sekarang ini, kamu selalu diberi kesehatan, kebahagiaan, dan kesuksesan dalam segala hal yang kamu cita-citakan. Semoga apa yang kamu impikan bisa segera terwujud!
<p>
Selain itu, sebentar lagi kita akan berpisah setelah melewati masa-masa SMA bersama. Meskipun kita mungkin baru kenal sebentar, aku tetap bersyukur pernah berada di lingkungan yang sama dan berbagi banyak ilmu selama tiga tahun ini.
<p>
Semoga kita bisa bertemu lagi di lain waktu, dalam keadaan yang lebih sukses dan bahagia. Selamat menempuh perjalanan baru, semoga bisa lulus UTBK! ✨😊
          </p>
        </div>
      <div class="back">
<h2>Selamat Hari Raya Idul Fitri 1446!</h2>
<p>
  Taqabbalallahu minna wa minkum, shiyamana wa shiyamakum.
  <p>
  كُلُّ عَامٍ وَأَنْتُمْ بِخَيْرٍ. اَللّهُمَّ اجْعَلْنَا وَإِيَّاكُمْ مِنَ العَاءِدِيْنَ وَالفَاءِزِيْنَ وَالمَقْبُوْلِيْنَ.
  <p>
  Mohon maaf lahir dan batin atas segala khilaf dan kesalahan. Semoga Allah SWT senantiasa melimpahkan keberkahan, kesehatan, umur panjang, serta impian yang diinginkan bagi kita semua, dan kita bisa kembali dipertemukan dengan bulan Ramadan ini di tahun mendatang. Aamiin yaa Rabbal ‘Alamiin. 🌙✨

<p>
</div>
</div>
<div class="page">
  <div class="front">
    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjRnu_Qw7iKWMNm41dEbdLT7HxOdyHIThgCneqHjcoTqOF9KEi5r52X-zcLKgd8jxHrO7OGrrDgm6ityyDx3qEEt5CGi_cyY_Gd2C8f2qN4p_Pxir_4H53V93mP6X1n6eoblsdINVptL9y4Aigld-CPcQYN7yrpIw5ZP0-IpIWo07V2RRJTyrz3DqKCRj4/s16000/mubarak.png" alt="Img 1" />
            </p>
          </div>
        <div class="back cover">
            <br />
          </p>
        </div>
      </div>
    </div>
    <div class="emoji">🎂</div>
<div class="emoji">🫶🏻</div>
<div class="emoji">❤️</div>
<div class="emoji">🎉</div>
<div class="emoji">🎉</div>
<div class="emoji">💓</div>
<div class="emoji">❣️</div>
<div class="emoji">🥳</div>
<div class="emoji">💖</div>
<div class="emoji">💙</div>
<div class="emoji">💚</div>
<div class="emoji">🥰</div>
<div class="emoji">💗</div>
<script>
  const flipBook = (elBook) => {
    elBook.style.setProperty("--c", 0); // Set current page
    elBook.querySelectorAll(".page").forEach((page, idx) => {
      page.style.setProperty("--i", idx);
      page.addEventListener("click", (evt) => {
        if (evt.target.closest("a")) return;
        const curr = evt.target.closest(".back") ? idx : idx + 1;
        elBook.style.setProperty("--c", curr);
      });
    });
  };
  
  document.querySelectorAll(".book").forEach(flipBook);
  
</script>
 
            
  </body>
</html>
