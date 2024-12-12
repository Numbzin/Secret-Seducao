<template>
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

  <section class="section-container">
    <div class="section-wrapper">
      <div class="text-section">
        <h2>O Segredo Para Proporcionar Prazer!</h2>
        <ul class="steps-list">
          <li>
            <div class="step-icon">
              <img
                src="../../public/Images/Vector.png"
                alt="Step 1"
                class="step-icon"
              />
              <span class="step-number">1</span>
            </div>
            <div>
              <h3>Entenda a Anatomia Feminina</h3>
              <p>
                Comece por compreender as zonas erógenas femininas e como a
                estimulação de cada área contribui para o prazer.
              </p>
            </div>
          </li>
          <li>
            <div class="step-icon">
              <img
                src="../../public/Images/Vector.png"
                alt="Step 2"
                class="step-icon"
              />
              <span class="step-number">2</span>
            </div>
            <div>
              <h3>Comunicação Aberta e Sincera</h3>
              <p>
                Construa uma atmosfera de confiança e comunicação aberta com sua
                parceira. Pergunte o que ela gosta e deseja.
              </p>
            </div>
          </li>
          <li>
            <div class="step-icon">
              <img
                src="../../public/Images/Vector.png"
                alt="Step 3"
                class="step-icon"
              />
              <span class="step-number">3</span>
            </div>
            <div>
              <h3>Domine a Arte das Preliminares</h3>
              <p>
                Dedique tempo às preliminares e explore diferentes toques,
                beijos e carícias que despertem a sensualidade.
              </p>
            </div>
          </li>
          <li>
            <div class="step-icon">
              <img
                src="../../public/Images/Vector.png"
                alt="Step 4"
                class="step-icon"
              />
              <span class="step-number">4</span>
            </div>
            <div>
              <h3>Explore Posições Inovadoras</h3>
              <p>
                Varie as posições sexuais e descubra quais delas despertam o
                maior prazer em sua parceira.
              </p>
            </div>
          </li>
          <li>
            <div class="step-icon">
              <img
                src="../../public/Images/Vector.png"
                alt="Step 5"
                class="step-icon"
              />
              <span class="step-number">5</span>
            </div>
            <div>
              <h3>Aprenda Técnicas de Estimulação</h3>
              <p>
                Desvende as melhores técnicas para estimular o clitóris e outras
                áreas sensíveis.
              </p>
            </div>
          </li>
          <li>
            <div class="step-icon">
              <img
                src="../../public/Images/Vector.png"
                alt="Step 6"
                class="step-icon"
              />
              <span class="step-number">6</span>
            </div>
            <div>
              <h3>Conecte-se Emocionalmente</h3>
              <p>
                Crie uma conexão emocional forte para intensificar a experiência
                íntima.
              </p>
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
    <div class="seduction">
      <h2>Domine a Arte da Sedução!</h2>
      <div class="features">
        <div class="feature">
          <h3>Linguagem Corporal e Sedução</h3>
          <p>
            O olhar, o toque e a postura podem comunicar muito sobre seus
            desejos e criar o clima de sedução ideal.
          </p>
        </div>
        <div class="feature">
          <h3>Crie um Ambiente Romântico</h3>
          <p>
            Invista em música suave, iluminação adequada e aromas agradáveis
            para um ambiente propício à sedução.
          </p>
        </div>
        <div class="feature">
          <h3>Desperte os Sentidos</h3>
          <p>
            Explore texturas, sabores e sons para estimular os sentidos e criar
            uma experiência única.
          </p>
        </div>
      </div>
      <button class="cta-button">Adquira Já o Seu Acesso!</button>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
section {
  width: 100vw;
}

.header-container {
  background: url("../../public/Images/header_background.jpg") no-repeat center
    center / cover;
  color: #fff;
  width: 100vw;
  height: 927px;
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
}

.text-content p {
  font-size: 1.125rem;
  line-height: 1.6;
  margin-bottom: 1.5rem;
}

.cta-button {
  background-color: #e63946;
  color: #fff;
  border: none;
  padding: 0.75rem 1.5rem;
  font-size: 1rem;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s;
}

.cta-button:hover {
  background-color: #d62828;
}

.image-content img {
  max-width: 400px;
  border-radius: 10px;
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
  width: 100%;
  height: auto;
}

.step-number {
  position: absolute;
  font-size: 1rem;
  font-weight: bold;
  color: #fff;
  top: 50%;
  left: 30%;
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
}

.steps-list p {
  font-size: 1rem;
  line-height: 1.5;
}

.seduction-section {
  background-color: #000000;
  color: #fff;
  padding: 3rem 2rem;
  text-align: center;
}

.seduction-section h2 {
  font-size: 2rem;
  margin-bottom: 2rem;
}

.features {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  gap: 2rem;
}

.feature {
  max-width: 300px;
}

.feature h3 {
  font-size: 1.25rem;
  margin-bottom: 0.5rem;
}

.feature p {
  font-size: 1rem;
  line-height: 1.5;
}

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
</style>
