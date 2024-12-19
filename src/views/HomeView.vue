<template>
  <!-- Header Section -->
  <header class="header-container">
    <div class="content-wrapper">
      <div class="text-content">
        <h1>
          Desperte o Prazer Feminino: <br />O Guia Definitivo para o Orgasmo
        </h1>
        <p>
          Eleve sua relação a um novo nível de intimidade e prazer. Descubra as
          técnicas e segredos para proporcionar à sua parceira orgasmos intensos
          e memoráveis. Desperte o potencial de prazer que existe em sua relação
          e vivencie uma experiência transformadora!
        </p>
        <button class="cta-button">
          Adquira Agora e Obtenha 15% de Desconto!
        </button>
      </div>
      <div class="image-content">
        <img
          src="../../public/Images/header.png"
          alt="Couple enjoying intimacy"
        />
      </div>
    </div>
  </header>

  <!-- Step Section -->
  <section class="section-container">
    <div class="circle-custom circle-custom-right"></div>
    <div class="circle-custom circle-custom-left"></div>
    <div class="section-wrapper">
      <div class="text-section">
        <h2>O Segredo Para Proporcionar Prazer!</h2>
        <ul class="steps-list">
          <li v-for="(step, index) in steps" :key="index">
            <div class="step-icon">
              <img src="../../public/Images/Vector.png" alt="Step Icon" />
              <span class="step-number">{{ index + 1 }}</span>
            </div>
            <div>
              <h3>{{ step.title }}</h3>
              <p>{{ step.description }}</p>
            </div>
          </li>
        </ul>
        <button class="cta-button">Clique Aqui para Garantir!</button>
      </div>
      <div class="container-img-section">
        <div class="image-section">
          <img src="../../public/Images/section1.jpg" alt="Intimate couple" />
        </div>
      </div>
    </div>
  </section>

  <section class="seduction-section">
    <div class="container-seduction">
      <div class="seduction">
        <h2>Domine a Arte da Sedução!</h2>
        <div class="features">
          <div
            class="feature"
            v-for="(feature, index) in features"
            :key="index"
          >
            <h3>{{ feature.title }}</h3>
            <p>{{ feature.description }}</p>
          </div>
        </div>
        <button class="cta-button">Adquira Já e Atraia o Prazer!</button>
      </div>
    </div>
  </section>

  <!-- Promo Section -->
  <section class="promo-section">
    <div class="container-promo">
      <div class="timer">
        <div class="time-unit" v-for="(time, unit) in countdown" :key="unit">
          <span>{{ time }}</span>
          <p>{{ unit.toUpperCase() }}</p>
        </div>
      </div>
      <div class="promo-text-container">
        <p class="promo-text">
          O seu acesso nesta página garante as
          <span class="highlight">ofertas de promoção</span> deste mês durante o
          tempo deste contador
        </p>
      </div>
      <button class="cta-button">
        Adquira Agora e Obtenha 15% de Desconto!
      </button>
    </div>
    <div class="footer-banner">
      <span v-for="n in 12" :key="n">15% OFF</span>
    </div>
  </section>

  <section class="mockup-section">
    <div class="circle circle-right"></div>
    <div class="circle circle-left"></div>
    <div class="mockup-container">
      <img src="../../public/Images/cel1.png" alt="Mockup Celular Esquerdo" />
      <img src="../../public/Images/cel2.png" alt="Mockup Celular Direito" />
    </div>
    <div class="text-container">
      <h2>
        A Fórmula Perfeita Para Recuperar o <span>Prazer</span> e
        <span>Intimidade</span>. Ideal para:
      </h2>
      <div class="text-row">
        <div class="text-item">
          <img src="../../public/Images/gota.png" alt="Gota" />
          <p>
            Para as casadas que desejam reavivar a paixão e desfrutar de
            momentos íntimos mais prazerosos.
          </p>
        </div>
        <div class="text-item">
          <img src="../../public/Images/gota.png" alt="Gota" />
          <p>
            Para as jovens e adultas que buscam uma vida sexual vibrante e cheia
            de fogo.
          </p>
        </div>
        <div class="text-item">
          <img src="../../public/Images/gota.png" alt="Gota" />
          <p>
            Para mulheres solteiras em busca de mais energia e realização na
            vida amorosa.
          </p>
        </div>
      </div>
      <div class="text-row">
        <div class="text-item">
          <img src="../../public/Images/gota.png" alt="Gota" />
          <p>
            Para as mulheres cujos hormônios precisam de equilíbrio e que
            anseiam recuperar sua libido.
          </p>
        </div>
        <div class="text-item">
          <img src="../../public/Images/gota.png" alt="Gota" />
          <p>
            Para as amantes do prazer genuíno, buscando a elevação das sensações
            e experiências.
          </p>
        </div>
        <div class="text-item">
          <img src="../../public/Images/gota.png" alt="Gota" />
          <p>
            Para as mães que passaram pela gestação e agora buscam reconectar-se
            com a intimidade.
          </p>
        </div>
      </div>
    </div>
  </section>

  <section class="pleasure-section">
    <div class="overlay"></div>
    <div class="content-container">
      <h2>Seja o Protagonista do Prazer!</h2>
      <div class="pleasure-cards">
        <div class="card">
          <div class="card-number">1</div>
          <div class="card-content">
            <h3>Intimidade e Confiança</h3>
            <p>
              Construa uma base sólida de intimidade e confiança com sua
              parceira. A comunicação aberta, a empatia e a compreensão mútua
              são essenciais para uma relação sexual plena e satisfatória.
            </p>
          </div>
        </div>
        <div class="card">
          <div class="card-number">2</div>
          <div class="card-content">
            <h3>Exploração e Descoberta</h3>
            <p>
              Desvendem juntos os desejos e preferências um do outro, abram-se
              para novas experiências e aprendam a se comunicar de forma clara e
              honesta sobre seus desejos e necessidades.
            </p>
          </div>
        </div>
        <div class="card">
          <div class="card-number">3</div>
          <div class="card-content">
            <h3>Compartilhar Emoções</h3>
            <p>
              A intimidade sexual é uma oportunidade de compartilhar emoções,
              fortalecer os laços e aprofundar a conexão. Expresse seus
              sentimentos, deixe-se levar pela paixão e desfrute da
              cumplicidade.
            </p>
          </div>
        </div>
        <div class="card">
          <div class="card-number">4</div>
          <div class="card-content">
            <h3>Prazer Mútuo</h3>
            <p>
              O foco deve estar no prazer mútuo, na busca pelo bem-estar e na
              satisfação de ambos. Aprenda a dar e receber prazer, reconhecendo
              as necessidades e desejos do outro.
            </p>
          </div>
        </div>
      </div>
      <button class="cta-button-pleasure">
        Transforme sua relação: obtenha agora!
      </button>
    </div>
  </section>

  <section class="positions-section">
    <div class="content-container">
      <h2>As Melhores Posições Para Explorar</h2>
      <div class="table-container">
        <table>
          <thead>
            <tr>
              <th>Posição</th>
              <th>Benefícios</th>
            </tr>
          </thead>
          <tbody>
            <tr v-for="(position, index) in positions" :key="index">
              <td>{{ position.name }}</td>
              <td>{{ position.benefits }}</td>
            </tr>
          </tbody>
        </table>
      </div>
      <button class="cta-button-position">
        Garanta e Seja o Protagonista do Prazer!
      </button>
    </div>
  </section>
</template>

<script setup lang="ts">
import { ref, onMounted } from "vue";

const steps = [
  {
    title: "Entenda a Anatomia Feminina",
    description:
      "Comece por compreender as zonas erógenas femininas e como a estimulação de cada área contribui para o prazer.",
  },
  {
    title: "Comunicação Aberta e Sincera",
    description:
      "Construa uma atmosfera de confiança e comunicação aberta com sua parceira. Pergunte o que ela gosta e quais são seus desejos, para que possa oferecer o prazer que ela realmente busca.",
  },
  {
    title: "Domine a Arte das Preliminares",
    description:
      "Dedique tempo às preliminares e explore diferentes toques, beijos e carícias que despertem a sensualidade da sua parceira.",
  },
  {
    title: "Explore Posições Inovadoras",
    description:
      "Varie as posições sexuais e descubra quais delas despertam o maior prazer em sua parceira.",
  },
  {
    title: "Aprenda Técnicas de Estimulação",
    description:
      "Desvende as melhores técnicas para estimular o clitóris, o Ponto G e outras áreas sensíveis proporcionando orgasmos intensos e satisfatórios para sua parceira.",
  },
  {
    title: "Conecte-se Emocionalmente",
    description:
      "O prazer sexual vai além do físico. Crie uma conexão emocional forte com sua parceira demonstre afeto, carinho e atenção, intensificando a experiência íntima.",
  },
];

const features = [
  {
    title: "Linguagem Corporal e Sedução",
    description:
      "O olhar, o toque, a postura e a maneira como você se move podem comunicar muito sobre seus desejos e intensificar o clima de sedução. Aprenda a usar a linguagem corporal a seu favor.",
  },
  {
    title: "Crie um Ambiente Romântico",
    description:
      "Um ambiente relaxante, com música suave, iluminação suave, aromas agradáveis e um toque de sensualidade contribui para a atmosfera ideal para a sedução e o prazer.",
  },
  {
    title: "Desperte os Sentidos",
    description:
      "Explore diferentes texturas, aromas, sabores e sons para estimular os sentidos da sua parceira. Use a criatividade para criar uma experiência multissensorial que intensifique o prazer.",
  },
];

const positions = [
  {
    name: "Missionária",
    benefits:
      "Clássica e versátil, permite fácil acesso ao clitóris e ao Ponto G.",
  },
  {
    name: "De Cima",
    benefits:
      "Permite maior controle para a mulher, intensificando a estimulação do clitóris e do Ponto G.",
  },
  {
    name: "A Cavalgada",
    benefits:
      "Oferece maior liberdade de movimento para a mulher, intensificando o prazer e o controle.",
  },
  {
    name: "Lateral",
    benefits:
      "Ideal para intimidade e conexão, permite toques mais sensuais e facilita a estimulação do clitóris.",
  },
  {
    name: "De Quatro",
    benefits:
      "Facilita o acesso ao Ponto G e intensifica a estimulação do clitóris, proporcionando orgasmos intensos.",
  },
];

// Timer dinâmico
const countdown = ref({
  dias: "00",
  horas: "00",
  minutos: "00",
  segundos: "00",
});
const countdownTarget = new Date().getTime() + 2 * 60 * 60 * 1000;

const startCountdown = () => {
  setInterval(() => {
    const now = new Date().getTime();
    const distance = countdownTarget - now;

    if (distance <= 0) return;
    countdown.value = {
      dias: String(Math.floor(distance / (1000 * 60 * 60 * 24))).padStart(
        2,
        "0"
      ),
      horas: String(
        Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60))
      ).padStart(2, "0"),
      minutos: String(
        Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60))
      ).padStart(2, "0"),
      segundos: String(Math.floor((distance % (1000 * 60)) / 1000)).padStart(
        2,
        "0"
      ),
    };
  }, 1000);
};

onMounted(() => {
  startCountdown();
});
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap");

/* Circulos */

section {
  position: relative;
  background-color: #000;
  padding: 100px 0;
  overflow: hidden;
}

/* Círculos vermelhos */
.circle {
  position: absolute;
  background-color: #ff3b3b;
  border-radius: 50%;
  width: 500px;
  height: 500px;
  opacity: 90%;
  filter: blur(50px);
  box-shadow: 0 0 100px 50px rgba(255, 59, 59, 0.6);
  z-index: 0;
}

/* Posicionamento dos círculos */
.circle-left {
  left: -150px;
}

.circle-right {
  right: 80px;
}

.circle-custom {
  position: absolute;
  background-color: #ff3b3b;
  border-radius: 50%;
  width: 500px;
  height: 500px;
  opacity: 90%;
  filter: blur(50px);
  box-shadow: 0 0 100px 50px rgba(255, 59, 59, 0.6);
  z-index: 0;
}

.circle-custom-left {
  left: -250px;
}

.circle-custom-right {
  right: 10px;
}

/* Primeiro círculo no topo */
.circle-custom:nth-child(1) {
  top: 375px;
}

/* Segundo círculo mais abaixo */
.circle-custom:nth-child(2) {
  top: -280px;
}

/* Primeiro círculo no topo */
.circle:nth-child(1) {
  top: 600px;
}
/* Segundo círculo mais abaixo */
.circle:nth-child(2) {
  top: 150px;
}

h2 {
  margin-bottom: 20px;
  font-size: 2rem;
}

p {
  font-size: 1.2rem;
  max-width: 600px;
  margin: 0 auto;
  line-height: 1.5;
}

body {
  overflow-x: hidden;
}

html::-webkit-scrollbar {
  width: 0.8rem;
}

html::-webkit-scrollbar-thumb {
  background: #e60000;
}

button {
  color: #fff;
  text-align: center;
  font-family: "DM Sans";
  font-size: 16.073px;
  font-style: normal;
  font-weight: 700;
  line-height: 25.92px;
}

/* section {
  min-height: 100vh;
} */

/* Header */

.header-container {
  background: url("../../public/Images/header_background.jpg") no-repeat center
    center / cover;
  color: #fff;
  height: 850px;
  flex-shrink: 0;
}

.content-wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
  justify-content: space-between;
  max-width: 1200px;
  padding-top: 150px;
  margin: 0 auto;
}

.text-content {
  max-width: 600px;
}

.text-content h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: #faebeb;
  font-family: "Playfair Display";
  font-weight: 700;
}

.text-content p {
  font-size: 1.125rem;
  line-height: 1.6;
  margin-bottom: 1.5rem;
  color: #ffe5e5;
  font-family: "DM Sans";
  font-weight: 400;
}

/* Button */

.cta-button {
  display: inline-block;
  margin: 30px auto 0;
  padding: 15px 20px;
  background-color: #e60000;
  color: #fff;
  font-weight: 700;
  font-size: 1rem;
  font-family: "DM Sans";
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.cta-button:hover {
  background-color: #f04e4e;
}

/* IMG header | Section 1 */

.image-content img {
  max-width: 400px;
  border-radius: 25px;
}

.section-container {
  background-color: #000000;
  color: #fff;
  padding: 3rem 2rem;
}

.container-img-section img {
  width: 290px;
  height: 900px;
  object-fit: cover;
}

.section-wrapper {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  max-width: 900px;
  margin: 0 auto;
}

.text-section {
  max-width: 600px;
}

.text-section h2 {
  font-size: 2rem;
  margin-bottom: 1.5rem;
  color: #faebeb;
  font-family: "Playfair Display";
  font-weight: 600;
}

.step-icon {
  position: relative;
  width: 40px;
  height: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.step-icon img {
  width: 45px;
  height: auto;
}

.step-number {
  position: absolute;
  font-size: 1rem;
  font-weight: bold;
  color: #fff;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.steps-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.steps-list li {
  display: flex;
  align-items: flex-start;
  margin-bottom: 1.5rem;
}

.steps-list .step-icon {
  width: 40px;
  height: auto;
  margin-right: 1rem;
}

.steps-list h3 {
  font-size: 1.25rem;
  margin-bottom: 0.5rem;
  color: #ffe5e5;
  font-family: "Playfair Display";
  font-weight: 600;
}

.steps-list p {
  font-size: 1rem;
  line-height: 1.5;
  color: #ffe5e5;
  font-family: "DM Sans";
  font-weight: 400;
}

/* Seduction section */

.seduction-section {
  background-color: #000;
  color: #fff;
  display: flex;
  justify-content: center;
  padding: 40px 20px;
}

.seduction h2 {
  text-align: left;
  font-size: 45px;
  font-weight: 600;
  margin-bottom: 30px;
  margin-left: 10px;
  color: #faebeb;
  font-family: "Playfair Display";
}

.container-seduction {
  max-width: 900px;
  padding: 5px;
}

.features {
  display: flex;
  justify-content: space-between;
  gap: 40px;
  text-align: left;
}

.feature {
  flex: 1;
  padding: 10px;
}

.feature h3 {
  font-size: 22.5px;
  margin-bottom: 10px;
  color: #faebeb;
  font-family: "Playfair Display";
  font-weight: 600;
}

.feature p {
  font-size: 16.2px;
  line-height: 1.5;
  color: #ffe5e5;
  font-family: "DM Sans";
  font-weight: 400;
}

/* Promo Section */
.promo-section {
  background-color: #000;
  color: #fff;
  text-align: center;
}

.container-promo {
  padding: 0;
  margin: 0 auto;
  margin-bottom: 100px;
  max-width: 800px;
}

.promo-text-container {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  max-width: 450px;
}

.timer {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 15px;
  margin-bottom: 20px;
}

.time-unit {
  background-color: #e60000;
  border-radius: 50%;
  width: 80px;
  height: 80px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.time-unit span {
  font-size: 2rem;
  font-weight: bold;
}

.time-unit p {
  font-size: 0.7rem;
}

.timer span {
  color: #ffffff;
  font-size: 2rem;
  font-weight: bold;
}

.promo-text {
  margin-bottom: 20px;
  font-size: 1.7rem;
  color: #ccc;
}

.promo-text .highlight {
  color: #e60000;
  font-weight: bold;
}

/* Footer Banner */
.footer-banner {
  margin-top: 50px;
  background-color: #e60000;
  color: #fff;
  padding: 10px;
  font-size: 26px;
  display: flex;
  justify-content: space-around;
  font-weight: bold;
}

/* Mockup section */

.mockup-section {
  background-color: #000;
  color: #fff;
  padding: 50px 20px;
  text-align: center;
}

.mockup-container {
  display: flex;
  justify-content: center;
  gap: 100px;
  margin-top: 50px;
  margin-bottom: 150px;
}

.mockup-container img {
  width: 300px;
  max-width: 100%;
  border-radius: 20px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
}

.text-container {
  max-width: 800px;
  margin: 0 auto;
  text-align: center;
}

.text-container h2 {
  font-size: 2rem;
  margin-bottom: 30px;
  font-weight: 400;
  font-family: "Playfair Display";
}

.text-container h2 span {
  color: #ff3b3b;
  font-weight: 700;
}

.text-row {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 30px;
  margin-bottom: 20px;
}

.text-item {
  display: flex;
  align-items: start;
  max-width: 30%;
  text-align: left;
  line-height: 1.5;
}

.text-item img {
  width: 20px;
  margin-right: 10px;
}

.text-item p {
  font-size: 1rem;
  color: #fff;
  font-family: "DM Sans";
  font-weight: 400;
}

/* pleasure section */

.pleasure-section {
  position: relative;
  background: url("../../public/Images/section4.jpg") no-repeat center center;
  background-size: cover;
  padding: 4rem 2rem;
  color: #ffe5e5;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.767);
  z-index: 0;
}

.content-container {
  position: relative;
  max-width: 950px;
  margin: 0 auto;
  z-index: 1;
  text-align: left;
}

.content-container h2 {
  margin-left: 8px;
  font-size: 45px;
  margin-bottom: 2rem;
  color: #faebeb;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: 600;
}

.pleasure-cards {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  margin-bottom: 2rem;
}

.card {
  display: flex;
  align-items: flex-start;
  padding: 1.5rem;
  border-radius: 8px;
}

.card-number {
  background-color: #e50914;
  color: #ffe5e5;
  font-size: 1.25rem;
  font-family: "Playfair Display";
  width: 45px;
  height: 35px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 4px;
  padding-bottom: 6px;
  margin-right: 1rem;
  font-weight: bold;
}

.card-content h3 {
  padding-left: 5px;
  color: #ffe5e5;
  font-family: "Playfair Display";
  font-size: 22.5px;
  font-style: normal;
  font-weight: 600;
  line-height: 28.13px;
}

.card-content p {
  padding: 8px;
  color: #ffe5e5;
  font-family: "DM Sans";
  font-size: 16.2px;
  font-style: normal;
  font-weight: 400;
  padding-right: 25px;
  line-height: 25.92px;
}

.cta-button-pleasure {
  background-color: #e60000;
  color: #fff;
  padding: 15px 30px;
  border: none;
  border-radius: 8px;
  font-family: "DM Sans", sans-serif;
  font-size: 16px;
  font-weight: 600;
  cursor: pointer;
  transition: background-color 0.3s ease;
  margin-top: 20px;
  margin-right: 680px;
}

.cta-button-pleasure:hover {
  background-color: #f04e4e;
}

/* Positions section */

.positions-section {
  background-color: #000;
  color: #fff;
  padding: 80px 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.content-container {
  max-width: 1200px;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

h2 {
  font-family: "Playfair Display", serif;
  font-size: 48px;
  font-weight: 500;
  color: #fff;
  margin-bottom: 40px;
  text-align: center;
}

.table-container {
  width: 100%;
  max-width: 800px;
  margin-bottom: 40px;
  background: linear-gradient(
    180deg,
    rgba(255, 255, 255, 0.1) 0%,
    rgba(255, 255, 255, 0.05) 100%
  );
  border-radius: 12px;
  overflow: hidden;
}

table {
  width: 100%;
  border-collapse: collapse;
  background-color: transparent;
}

thead {
  background-color: rgba(255, 255, 255, 0.1);
}

th {
  padding: 20px;
  text-align: left;
  font-family: "DM Sans", sans-serif;
  font-size: 18px;
  font-weight: 500;
  color: #fff;
}

td {
  padding: 20px;
  max-width: 10px;
  font-family: "DM Sans", sans-serif;
  font-size: 16px;
  color: rgba(255, 255, 255, 0.8);
  line-height: 1.5;
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}

tr:last-child td {
  border-bottom: none;
}

tr:nth-child(even) {
  background-color: rgba(255, 255, 255, 0.03);
}

.cta-button-position {
  background-color: #e60000;
  color: #fff;
  padding: 15px 30px;
  border: none;
  border-radius: 8px;
  font-family: "DM Sans", sans-serif;
  font-size: 16px;
  font-weight: 600;
  cursor: pointer;
  transition: background-color 0.3s ease;
  margin-top: 20px;
  margin-right: 425px;
}

.cta-button-position:hover {
  background-color: #f04e4e;
}

/* Responsividade */

@media (max-width: 768px) {
  .content-wrapper,
  .section-wrapper {
    flex-direction: column;
    text-align: center;
  }

  .image-content img,
  .image-section img {
    max-width: 300px;
    margin-top: 1.5rem;
  }
  .container-img-section img {
    display: none;
  }
  .features {
    flex-direction: column;
    align-items: center;
  }
}

@media (max-width: 768px) {
  h2 {
    font-size: 36px;
    padding: 0 20px;
  }

  .table-container {
    margin: 0 10px;
  }

  th,
  td {
    padding: 15px;
    font-size: 14px;
  }

  .cta-button {
    padding: 12px 24px;
    font-size: 14px;
  }
}
</style>
