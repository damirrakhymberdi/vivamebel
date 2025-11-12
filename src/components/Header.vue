<template>
  <header class="header">
    <!-- Top Bar -->
    <div class="top-bar">
      <div class="top-bar-content">
        <div class="language-selector">
          <span>Язык - РУС</span>
          <span class="arrow">▼</span>
        </div>
        <nav class="top-nav">
          <a href="#about">О нас</a>
          <a href="#dealers">Информация для дилеров</a>
          <a href="#catalog">Каталог</a>
          <a href="#projects">Завершенные проекты</a>
        </nav>
        <button class="login-btn">Войти</button>
      </div>
    </div>
    
    <!-- Second Bar -->
    <div class="second-bar">
      <div class="second-bar-content">
        <div class="logo">
          <img src="../assets/logo.png" alt="logo" class="logo-image">
        </div>  
        <p class="tagline">Комплексные решения для вашего бизнеса – от проекта до реализации</p>
      </div>
    </div>

    <!-- Hero Section -->
    <section class="hero">
      <div class="hero-container">
        <img src="../assets/Group 1 (2).png" alt="logo" class="viva-big">
        <div class="categories-grid">
          <div class="category-card">
            <h3>Офисные кресла и стулья</h3>
            <button class="catalog-btn">В каталог</button>
          </div>
          <div class="category-card">
            <h3>Офисная мебель</h3>
            <button class="catalog-btn">В каталог</button>
          </div>
          <div class="category-card">
            <h3>Мягкая мебель</h3>
            <button class="catalog-btn">В каталог</button>
          </div>
          <div class="category-card category-card4">
            <div style="position: relative; z-index: 10; padding: 2px; "> 
                <h3 class="h33">Мебель для общественного питания</h3>
                <button class="catalog-btn3">В каталог</button>
            </div>
            <img src="../assets/7952e0f3a10539625aa8250bb28486054e52ee25.png" alt="logo" class="logo-image">
       
          </div>
        </div>
      </div>
    </section>

    <!-- Partners Section -->
    <section class="partners-section">
      <h2 class="partners-title">Нам доверяют</h2>
      <div class="partners-grid">
        <div class="partner-logo">
          <span> <img src="../assets/image 1.png" alt=""></span>
        </div>
        <div class="partner-logo">
          <span><img src="../assets/image 2.png" alt=""></span>
        </div>
        <div class="partner-logo">
          <span><img src="../assets/image 3.png" alt=""></span>
        </div>
        <div class="partner-logo">
          <span><img src="../assets/image 4.png" alt=""></span>
        </div>
        <div class="partner-logo">
          <span><img src="../assets/image 5.png" alt=""></span>
        </div>
        <div class="partner-logo">
          <span><img src="../assets/image 6.png" alt=""></span>
        </div>
      </div>
    </section>
    <!-- About Section -->
    <section class="about-section">
      <div class="about-container">
        <div class="about-contacts">
          <div class="contact-item">
            <h3 class="contact-city">Алматы</h3>
            <p class="contact-address">ул Масаначи 98А, 3 этаж, кабинет 33 (+7 705 121 83 98)</p>
          </div>
          <div class="contact-item">
            <h3 class="contact-city">Астана</h3>
            <p class="contact-address">пр Кабанбай Батыр 11/5, Блок Б, 7 этаж, кабинет 701 и 708 (+7 777 755 10 00)</p>
          </div>
          <div class="contact-item">
            <h3 class="contact-city">Шымкент</h3>
            <p class="contact-address">ул Акпан батыра 111 (+7 777 744 20 00)</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Company Info Section -->
    <section class="company-section">
      <div class="company-container">
        <div class="company-left">
          <h2 class="company-title">О компании</h2>
          <p class="company-subtitle">Viva Mebel — Ваш Стратегический Партнер</p>
        </div>
        <div class="company-right">
          <h3 class="company-heading">Viva Mebel — это не просто офисная мебель.</h3>
          <p class="company-text">
            Мы не просто продаем мебель и офисные кресла — мы создаем пространства, которые вдохновляют на продуктивную работу, способствуют обучению и отражают статус вашей компании. С филиалами в ключевых городах — Астане, Алматы и Шымкенте — мы гарантируем высокий уровень сервиса и оперативную реализацию проектов по всему Казахстану
          </p>
        </div>
      </div>
    </section>

    <!-- Mission Section -->
    <section class="mission-section">
      <div class="mission-overlay"></div>
      <div class="mission-content">
        <div class="mission-top-right">
          <h2 class="mission-title-right">Наша Миссия</h2>
          <p class="mission-text-right">
            Быть лидером и стратегическим партнёром №1 в Казахстане по комплексной поставке офисных и учебных пространств.
            Мы достигаем этого, предлагая инновационные, функциональные и стильные мебельные решения, которые повышают
            эффективность и комфорт наших клиентов.
          </p>
        </div>
        <div class="mission-bottom-left">
          <h3 class="mission-title-left">Наша Цель</h3>
          <p class="mission-text-left">
            Трансформировать каждое рабочее и учебное место в идеальную среду для достижений. Мы стремимся превосходить
            потребности рынка, импортируя лучшие мировые тренды и предлагая безупречный сервис на каждом этапе: от
            консультации до реализации проекта «под ключ».
          </p>
        </div>
      </div>
    </section>

    <!-- Reasons Section -->
    <section class="reasons-section">
      <div class="reasons-container">
        <h2 class="reasons-title">Почему выбирают Viva Mebel?</h2>
        <p class="reasons-subtitle">
          Мы создали репутацию самого надежного партнера в секторе B2B, и вот почему с нами стоит работать:
        </p>
      </div>
    </section>

    <!-- Features Grid Section -->
    <section class="features-grid-section">
      <div class="features-container">
        <div class="features-grid">
          <div class="feature-card feature-card-white">
            <div class="feature-icon">
              <img src="../assets/Layer 2.png" alt="">
            </div>
            <h3 class="feature-title">Экспертиза в Проектных Продажах (В2В):</h3>
            <p class="feature-text">
              Наша основная компетенция — полное оснащение корпоративных клиентов. Мы понимаем язык бизнеса и берем на себя реализацию самых амбициозных проектов — от опен-спейсов и кабинетов руководителей до конференц-залов, что подтверждено нашим портфолио.
            </p>
          </div>

          <div class="feature-card feature-card-gray">
            <div class="feature-icon">
                <img src="../assets/fi_10701637.png" alt="">
            </div>
            <h3 class="feature-title">Надежный Поставщик для Дилеров:</h3>
            <p class="feature-text">
              Мы предлагаем эксклюзивные условия для наших дилеров и партнеров. Работая с нами, вы получаете доступ к широкому ассортименту востребованной продукции и конкурентные цены.
            </p>
          </div>

          <div class="feature-card feature-card-gray">
            <div class="feature-icon">
              <img src="../assets/fi_15106449.png" alt="">
            </div>
            <h3 class="feature-title">Опыт работы с тендерами:</h3>
            <p class="feature-text">
              Viva Mebel — аккредитованный и опытный участник коммерческих тендеров. Мы гарантируем точное соответствие техническим спецификациям, соблюдение сроков и полную прозрачность документации.
            </p>
          </div>

          <div class="feature-card feature-card-white">
            <div class="feature-icon">
                <img src="../assets/fi_2630085.png" alt="">
            </div>
            <h3 class="feature-title">Комплексный Ассортимент:</h3>
            <p class="feature-text">
              Мы специализируемся на ключевых направлениях: офисная мебель, школьная мебель и офисные кресла.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Product Catalog Section -->
    <section class="product-catalog-section">
      <div class="product-catalog-container">
        <div class="product-grid">
          <div class="product-card">
            <button class="product-view-btn">
                <img src="../assets/Group 2.png" />
            </button>

            <p class="product-category">Кресла для руководителя</p>
            <h3 class="product-name">CHAIRMAN HOME 505</h3>
            <div class="product-image-wrapper">
              <img src="../assets/Rectangle 1.png" alt="CHAIRMAN HOME 505" class="product-image" />
            </div>
          </div>

          <div class="product-card">
            <button class="product-view-btn">
                <img src="../assets/Group 2.png" />
            </button>
            <p class="product-category">Кресла для руководителя</p>
            <h3 class="product-name">CHAIRMAN HOME 505</h3>
            <div class="product-image-wrapper">
                 <img src="../assets/Rectangle 1.png" alt="CHAIRMAN HOME 505" class="product-image" />
            </div>
          </div>

          <div class="product-card">
            <button class="product-view-btn">
                <img src="../assets/Group 2.png" />
            </button>
            <p class="product-category">Кресла для руководителя</p>
            <h3 class="product-name">CHAIRMAN HOME 505</h3>
            <div class="product-image-wrapper">
                 <img src="../assets/Rectangle 1.png" alt="CHAIRMAN HOME 505" class="product-image" />
            </div>
          </div>

          <div class="product-card">
            <button class="product-view-btn">
                <img src="../assets/Group 2.png" />
            </button>
            <p class="product-category">Кресла для руководителя</p>
            <h3 class="product-name">CHAIRMAN HOME 505</h3>
            <div class="product-image-wrapper">
                 <img src="../assets/Rectangle 1.png" alt="CHAIRMAN HOME 505" class="product-image" />
            </div>
          </div>

          <div class="product-card">
            <button class="product-view-btn">
                <img src="../assets/Group 2.png" />
            </button>
            <p class="product-category">Кресла для руководителя</p>
            <h3 class="product-name">CHAIRMAN HOME 505</h3>
            <div class="product-image-wrapper">
                 <img src="../assets/Rectangle 1.png" alt="CHAIRMAN HOME 505" class="product-image" />
            </div>
          </div>

          <div class="product-card">
            <button class="product-view-btn">
                <img src="../assets/Group 2.png" />
            </button>
            <p class="product-category">Кресла для руководителя</p>
            <h3 class="product-name">CHAIRMAN HOME 505</h3>
            <div class="product-image-wrapper">
                 <img src="../assets/Rectangle 1.png" alt="CHAIRMAN HOME 505" class="product-image" />
            </div>
          </div>

          <div class="product-card">
            <button class="product-view-btn">
                <img src="../assets/Group 2.png" />
            </button>
            <p class="product-category">Кресла для руководителя</p>
            <h3 class="product-name">CHAIRMAN HOME 505</h3>
            <div class="product-image-wrapper">
                 <img src="../assets/Rectangle 1.png" alt="CHAIRMAN HOME 505" class="product-image" />
            </div>
          </div>

          <div class="product-card">
            <button class="product-view-btn">
                <img src="../assets/Group 2.png" />
            </button>
            <p class="product-category">Кресла для руководителя</p>
            <h3 class="product-name">CHAIRMAN HOME 505</h3>
            <div class="product-image-wrapper">
                 <img src="../assets/Rectangle 1.png" alt="CHAIRMAN HOME 505" class="product-image" />
            </div>
          </div>
        </div>
        
        <div class="catalog-footer">
          <button class="catalog-footer-btn">В каталог</button>
        </div>
      </div>
    </section>

    <!-- Footer Section -->
    <footer class="main-footer">
      <div class="footer-container">
        <div class="footer-content">
          <div class="footer-logo-section">
            <div class="footer-logo-text">
              <img src="/src/assets/Logo (2).png" style="width: 100%; border: 1px solid rgba(255, 255, 255, 0.1); padding: 40px; grid-column: 1 / 2; padding: 50px 64px;" alt="">
            </div>
          </div>
          
          
          <div class="footer-text-section">
            <p class="footer-description">
                2022–2026 Viva Mebel – ваш надежный партнер в Казахстане по созданию профессиональных интерьерных решений для офисов и учебных заведений. Мы специализируемся на поставках офисной и школьной мебели, которая отвечает самым современным требованиям к эргономике и дизайну рабочего пространства.
            </p>
          </div>
        </div>
        
        <div class="footer-nav-bar">
          <div class="footer-nav-social">
            <a href="#" class="footer-social-icon" aria-label="Instagram">
              <img src="/src/assets/vecteezy_instagram-logo-png-instagram-icon-transparent_18930460.png" alt="Instagram" />
            </a>
            <a href="#" class="footer-social-icon" aria-label="WhatsApp">
              <img  src="../assets/vecteezy_whatsapp-logo-png-whatsapp-icon-png-whatsapp-transparent_18930462.png" alt="WhatsApp" />
            </a>
            <a href="#" class="footer-social-icon" aria-label="Telegram">
              <img src="/src/assets/Vector (6).png" style="width: 20px;" alt="Telegram" />
            </a>
          </div>
          
          <nav class="footer-nav-menu">
            <a href="#about" class="footer-nav-item">О нас</a>
            <a href="#dealers" class="footer-nav-item">Для дилеров</a>
            <a href="#employees" class="footer-nav-item">Для сотрудников</a>
            <a href="#catalog" class="footer-nav-item">Каталог</a>
            <a href="#partners" class="footer-nav-item">Партнеры</a>
          </nav>
        </div>
      </div>
    </footer>

    <!-- Approval Section -->
    <section class="approval-section">
      <div class="approval-container">
        <div class="approval-content">
          <h2 class="approval-title">Макет утверждено (Мустафин Данияр Русланович)</h2>
          <p class="approval-request">Просьба внимательно ознакомиться с представленным дизайн-макетом.</p>
          <p class="approval-notice">
            После его утверждения любые дополнительные изменения — включая корректировки структуры, визуальных элементов, текстов, добавление новых блоков, разделов или страниц — будут выполняться в рамках дополнительных услуг и подлежат отдельному согласованию и оплате.
          </p>
        </div>
      </div>
    </section>
  </header>
</template>

<script setup>
// Header компонент
import logo from '../assets/logo.png'
</script>

<style scoped>
@import '../assets/font.css';



.header {
  width: 100%;
}

.top-bar {
  background: #ffffff;
  
}

.top-bar-content {
  max-width: 100%;
  margin: 0;
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  justify-content: space-between;
  align-items: center;
}

.logo-image{
    width: 100%;
    height: 100%;
}

.language-selector {
  display: flex;
  text-align: center;
  align-items: center;
  justify-content: center;
  gap: 0px;
  color: #fff;
  font-size: 14px;
  cursor: pointer;
  transition: opacity 0.3s;
  grid-column: 1 / 2;
  background: rgb(35, 35, 35);
  padding: 10.5px 20px;
}

.language-selector:hover {
  opacity: 0.8;
}

.arrow {
  font-size: 10px;
}

.top-nav {
  display: grid;
  grid-column: 2 / 6;
  grid-template-columns: repeat(4, 1fr);
  text-align: center;
  flex: 1;
 
}

.top-nav a {
  color: #000000;
  text-decoration: none;
  font-size: 14px;
  transition: opacity 0.3s;
  border-right: 1px solid #e0e0e0;
  border-bottom: 1px solid #e0e0e0;
  padding: 10px;
}

.top-nav a:hover {
  opacity: 0.8;
}

.login-btn {
  background: rgb(35, 35, 35);
  border: none;
  color: #fff;
  padding: 11px;
  cursor: pointer;
  font-size: 14px;
  transition: background 0.3s;
  grid-column: 6 / 7;
}

.login-btn:hover {
  background: #3a3a3a;
} 

.second-bar {
  background: #fff;
  border-bottom: 1px solid #e0e0e0;
}

.second-bar-content {
  max-width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-right: 1px solid #e0e0e0;
}

.logo {
  display: flex;
  flex-direction: column;
  border-right: 1px solid #e0e0e0;
  padding: 25px 65px;
}



.tagline {
  color: #555;
  font-size: 27px;
  font-family: 'Nasalization Rg', sans-serif;
  max-width: auto;
  margin: auto;
}



.hero-container {
  max-width: 100%;
  margin: 0;
  padding: 0;
  display: block;
}

.categories-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 0px;
  margin: 0px  40px;
 
}

.category-card {
  background: #ffffff;
  padding: 30px;
  border-radius: 0px;
  height: 90vh;
  display: flex;
  flex-direction: column;
  justify-content: end;
  align-items: start;
  gap: 13px;
}

.viva-big{
    position: absolute;
    z-index: 1;
    top: 320px;
    left: 11%;
}

.category-card h3 {
  font-size: 25px;
  font-weight: 500;
  color: #333;
  margin-bottom: 12px;
  width: 68%;
}

.category-card4{
    position: relative;
}


.h33{
    background: white;
}


.category-card4 .logo-image{
    position: absolute;
    bottom: 0;
    left: 0;
}
.catalog-btn {
  background: rgb(35, 35, 35);
  color: #fff;
  border: none;
  padding: 12px 27px;
  font-size: 15px;
  cursor: pointer;
  border-radius: 1px;
  transition: background 0.2s ease;
}

.catalog-btn3 {
  background: rgb(35, 35, 35);
  color: #fff;
  border: none;
  padding: 12px 27px;
  font-size: 15px;
  cursor: pointer;
  border-radius: 1px;
  transition: background 0.2s ease;
}

.catalog-btn:hover {
  background: #3a3a3a;
}

.hero-right {
  position: relative;
}

.hero-image {
  position: relative;
  width: 100%;
  height: 560px;
  border-radius: 8px;
  overflow: hidden;
}

.hero-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.category-card-overlay {
  position: absolute;
  bottom: 24px;
  right: 24px;
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  max-width: 300px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
  border: 1px solid #e0e0e0;
}

.category-card-overlay h3 {
  font-size: 16px;
  font-weight: 500;
  color: #333;
  margin-bottom: 12px;
}

/* Partners Section */
.partners-section {
  padding: 80px 40px;
  background: #fff;
  text-align: center;
}

.partners-title {
  font-size: 48px;
  font-weight: 500;
  color: #333;
  margin-bottom: 60px;
}

.partners-grid {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  gap: 30px;
  max-width: 1400px;
  margin: 0 auto;
  align-items: center;
}

.partner-logo {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 20px;
  color: #666;
  font-size: 14px;
  font-weight: 600;
  text-align: center;
  min-height: 100px;
  filter: grayscale(100%);
  transition: filter 0.3s ease;
}

.partner-logo:hover {
  filter: grayscale(0%);
}

.partner-logo span {
  line-height: 1.4;
}



/* About Section */
.about-section {
  padding: 0px 50px;
  background: #fff;
}

.about-container {
  max-width: 100%;
}

.about-contacts {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 0px;
  align-items: center;
  border: 1px solid #e0e0e0;

}

.contact-item {
  display: flex;
  flex-direction: column;
  gap: 0px;
  padding: 20px;
  border-right: px solid #e0e0e0;
  
}

.contact-city {
  font-size: 20px;
  font-weight: 600;
  color: #333;
  margin: 0;
}

.contact-address {
  font-size: 16px;
  color: #555;
  margin: 0;
}

.contact-phone {
  font-size: 16px;
  color: #555;
  margin: 0;
}

/* Company Info Section */
.company-section {
  padding: 80px 50px;
  background: #fff;
  position: relative;
}

.company-section::before,
.company-section::after {
  content: '';
  position: absolute;
  top: 0;
  bottom: 0;
  width: 50px;
  background: #ffffff;
}

.company-section::before {
  left: 0;
}

.company-section::after {
  right: 0;
}

.company-container {
  max-width: 1400px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: 1fr 1.5fr;
  gap: 60px;
  position: relative;
  z-index: 1;
}

.company-left {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.company-title {
  font-size: 50px;
  font-weight: 700;
  color: #333;
  margin: 0;
}

.company-subtitle {
  font-size: 15px;
  font-weight: 500;
  color: #555;
  margin: 0;
}

.company-right {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.company-heading {
  font-size: 24px;
  font-weight: 600;
  color: #333;
  margin: 0;
}

.company-text {
  font-size: 16px;
  color: #555;
  line-height: 1.4;
  margin: 0;
}

/* Mission Section */
.mission-section {
  position: relative;
  margin: auto;
  width: 95%;
  min-height: 90vh;
  background: url('../assets/7718287a8739e379562b0cf766b132f89aae8795.png') center/cover no-repeat;
  display: flex;
  align-items: stretch;
  
}

.mission-overlay {
  position: absolute;
  inset: 0;
  border-radius: 0;

  background:
    linear-gradient(
      to top right,
      rgba(0, 0, 0, 0.9),
      rgba(0, 0, 0, 0)
    ),

    linear-gradient(
      to bottom left,
      rgba(0, 0, 0, 0.9),
      rgba(0, 0, 0, 0)
    );

  backdrop-filter: blur(1px);
  z-index: 0;
}




.mission-content {
  position: relative;
  z-index: 1;
  display: grid;
  grid-template-rows: 1fr 1fr;
  width: 100%;
  padding: 32px 40px;
  
  
}

.mission-top-right {
  align-self: start;
  justify-self: end;
  max-width: 620px;
  text-align: right;
  color: #fff;
  
}

.mission-title-right {
  font-size: 42px;
  font-weight: 700;
  margin: 12px 0 16px 0;
  
}

.mission-text-right {
  font-size: 15px;
  line-height: 1.6;
  opacity: 0.95;
}

.mission-bottom-left {
  align-self: end;
  justify-self: start;
  max-width: 520px;
  color: #fff;
}

.mission-title-left {
  font-size: 32px;
  font-weight: 700;
  margin: 0 0 13px 0;
}

.mission-text-left {
  font-size: 15px;
  line-height: 1.6;
  opacity: 0.95;
}



/* Reasons Section */
.reasons-section {
  padding: 37px;
  padding-top: 100px;
  background: #fff;
}

.reasons-container {
  max-width: 100%;
  margin: 0px 0px;
}

.reasons-title {
  font-size: 50px;
  font-weight: 500;
  color: #333;
  margin: 0 0 12px 0;
}

.reasons-subtitle {
  font-size: 20px;
  color: #555;
  margin: 0;
}

/* Features Grid Section */
.features-grid-section {
  padding: 60px 37px;
  background: #fff;
}

.features-container {
  max-width: 1500px;
  margin: 0 auto;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 11px;
}

.feature-card {
  padding: 40px;
  border-radius: 0px;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.06);
  transition: box-shadow 0.3s ease;
  border: 1px solid #e0e0e0;
}

.feature-card:hover {
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.1);
}

.feature-card-white {
  background: #ffffff;
}

.feature-card-gray {
  background: #F5F5F5;
}

.feature-icon {
  margin-bottom: 20px;
  display: flex;
  align-items: center;
}

.feature-icon svg {
  width: 32px;
  height: 32px;
}

.feature-title {
  font-size: 24px;
  font-weight: 600;
  color: #222;
  margin: 0 0 12px 0;
  line-height: 1.4;
}

.feature-text {
  font-size: 18px;
  color: #555;
  line-height: 1.4;
  margin: 0;
}

/* Product Catalog Section */
.product-catalog-section {
  padding: 60px 40px;
  background: #fff;
}

.product-catalog-container {
  max-width: 1500px;
  margin: 0 auto;
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 10px;
  margin-bottom: 0;
}

.product-card {
  background: #ffffff;
  border: 1px solid #E6E6E6;
  padding: 24px;
  position: relative;
  display: flex;
  flex-direction: column;
}

.product-card:hover {
  transition: box-shadow 0.3s ease;
  box-shadow: 0 6px 18px rgba(0,0,0,0.10);
}




.product-view-btn {
  position: absolute;
  top: 16px;
  right: 16px;
  
  width: 40px;
  height: 40px;
  border-radius: 50%;
  
  background: #2c2c2c;
  border: none;
  display: flex;
  align-items: center;
  justify-content: center;

  cursor: pointer;
  opacity: 0;                     /* ЖАСЫРУ */
  visibility: hidden;            /* Click алып тастау */
  transform: translateY(-8px);   /* Жоғарыға көтеріп қою */
  transition: 
      opacity 0.25s ease,
      transform 0.25s ease,
      visibility 0.25s;
}


.product-card:hover .product-view-btn {
  opacity: 1;
  visibility: visible;
  transform: translateY(0);
}


.product-view-btn:hover {
  background: #1a1a1a;
}

.product-category {
  font-size: 13px;
  color: #888;
  font-weight: 400;
  margin: 0 0 8px 0;
  text-align: left;
}

.product-name {
  font-size: 16px;
  font-weight: 700;
  color: #000;
  margin: 0 0 20px 0;
  text-transform: uppercase;
  font-family: 'Nasalization Rg', sans-serif;
  letter-spacing: 0.5px;
  text-align: left;
}

.product-image-wrapper {
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 280px;
  margin-top: auto;
}

.product-image {
  max-width: 100%;
  max-height: 100vh;
  object-fit: contain;
}

.catalog-footer {
  margin-top: 40px;
  width: 100%;
  display: flex;
  justify-content: center;
}

.catalog-footer-btn {
  background: #2c2c2c;
  color: #fff;
  border: none;
  padding: 16px 48px;
  font-size: 16px;
  font-weight: 500;
  cursor: pointer;
  transition: background 0.3s ease;
  width: 1500px;

}

.catalog-footer-btn:hover {
  background: #1a1a1a;
}

/* Footer Section */
.main-footer {
  background: #2c2c2c;
  color: #fff;
  margin: 40px 0px;

}

.footer-container {
  max-width: 100%;
  margin: 0 auto;
}

.footer-content {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
  align-items: center;
  gap: 0px;
}

.footer-logo-section {
  display: flex;
  align-items: center;
}

.footer-logo-text {
  display: flex;
  flex-direction: column;
  color: white;
}

.footer-logo-viva {
  font-size: 50px;
  font-weight: 700;
  color: #fff;
  line-height: 1;

}

.footer-logo-mebel {
  font-size: 24px;
  font-weight: 400;
  color: #fff;
  line-height: 1;
  letter-spacing: 2px;
  margin-top: -5px;
}

.footer-vertical-divider {
  width: 1px;
  height: 100%;
  background: rgba(255, 255, 255, 0.2);
  align-self: stretch;
}

.footer-text-section {
  display: flex;
  flex-direction: column;
  padding: 0px 40px;
  grid-column: 2 / 7;
}

.footer-title {
  font-size: 6px;
  font-weight: 700;
  color: #fff;
  line-height: 1.6;
  margin: 0;
}

.footer-description {
  font-size: 17px;
  line-height: 1.2;
  color: #fff;
  margin: 0;
  font-weight: 400;
}

.footer-nav-bar {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
  gap: 0;
  align-items: center;
  background: #2c2c2c;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  padding: 0;
}

.footer-nav-social {
  display: flex;
  gap: 30px;
  grid-column: 1 / 2;
  align-items: centr;
  padding: 20px 24px;
  padding-left: 58px;
  border-right: 1px solid rgba(255, 255, 255, 0.1);
}

.footer-social-icon {
  width: 24px;
  height: 24px;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: opacity 0.3s ease;
  cursor: pointer;
}

.footer-social-icon:hover {
  opacity: 0.7;
}

.footer-social-icon img {
  width: 170%;
  object-fit: contain;
  filter: brightness(0) invert(1);
}

.footer-nav-menu {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  align-items: center;
  height: 100%;
  grid-column: 2 / 7;
}

.footer-nav-item {
  font-size: 15px;
  color: #fff;
  text-decoration: none;
  text-align: center;
  padding: 20px 16px;
  transition: background 0.3s ease, color 0.3s ease;
  border-right: 1px solid rgba(255, 255, 255, 0.1);
  display: flex;
  align-items: center;
  justify-content: center;
}

.footer-nav-item:last-child {
  border-right: none;
}

.footer-nav-item:hover {
  background: rgba(255, 255, 255, 0.05);
  color: #CCCCCC;
}

.footer-nav-separator {
  display: none;
}

/* Approval Section */
.approval-section {
  background: #ffffff;
  padding: 0;
  margin: 260px 70px 30px 70px;
}

.approval-container {
  max-width: 100%;
  margin: 0 auto;
  position: relative;
}

.approval-container::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 2px;
  background: #000000;
}

.approval-content {
  padding: 40px 60px;
  text-align: center;
  max-width: 100%;
  margin: 0 auto;
}

.approval-title {
  font-size: 35px;
  font-weight: 700;
  color: #000000;
  margin: 0 0 70px 0;
  text-align: center;
}

.approval-request {
  font-size: 19px;
  color: #000000;
  margin: 0 0 20px 0;
  text-align: center;
  font-weight: 600;
}

.approval-notice {
  font-size: 17px;
  color: #000000;
  line-height: 1.6;
  margin: 0;
  text-align: center;
  max-width: 100%;
  margin-left: auto;
  margin-right: auto;
}

/* Responsive Design */
@media (max-width: 768px) {
  .top-bar-content {
    flex-direction: column;
    gap: 15px;
    padding: 15px 20px;
  }
  
  .top-nav {
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
  }
  
  .second-bar-content {
    flex-direction: column;
    align-items: flex-start;
    gap: 20px;
  }
  
  .tagline {
    max-width: 100%;
  }

  .hero-container {
    padding: 0 20px;
  }

  .categories-grid {
    grid-template-columns: 1fr;
  }

  .partners-section {
    padding: 60px 20px;
  }

  .partners-title {
    font-size: 36px;
    margin-bottom: 40px;
  }

  .partners-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
  }

  .partner-logo {
    min-height: 80px;
    font-size: 12px;
  }

  .about-section {
    padding: 60px 20px;
  }

  .about-contacts {
    grid-template-columns: 1fr;
    gap: 40px;
  }

  .company-section {
    padding: 60px 20px;
  }

  .company-section::before,
  .company-section::after {
    display: none;
  }

  .company-container {
    grid-template-columns: 1fr;
    gap: 40px;
  }

  .company-title {
    font-size: 36px;
  }

  .company-heading {
    font-size: 20px;
  }

  .company-text {
    font-size: 14px;
  }

  .mission-section {
    min-height: 60vh;
    background-position: center;
  }
  .mission-content {
    grid-template-rows: auto auto;
    padding: 20px;
    gap: 24px;
  }
  .mission-title-right {
    font-size: 28px;
  }
  .mission-title-left {
    font-size: 22px;
  }
  .mission-text-right,
  .mission-text-left {
    font-size: 12px;
  }

  .features-grid-section {
    padding: 40px 20px;
  }

  .features-grid {
    grid-template-columns: 1fr;
    gap: 20px;
  }

  .feature-card {
    padding: 24px;
  }

  .feature-title {
    font-size: 16px;
  }

  .feature-text {
    font-size: 14px;
  }

  .product-catalog-section {
    padding: 40px 20px;
  }

  .product-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 16px;
  }

  .product-card-highlighted {
    transform: scale(1);
  }

  .product-image-wrapper {
    min-height: 200px;
  }

  .product-image {
    max-height: 200px;
  }

  .product-name {
    font-size: 14px;
  }

  .main-footer {
    padding: 40px 20px;
  }

  .footer-content {
    grid-template-columns: 1fr;
    gap: 30px;
  }

  .footer-vertical-divider {
    display: none;
  }

  .footer-logo-viva {
    font-size: 36px;
  }

  .footer-logo-mebel {
    font-size: 18px;
  }

  .footer-title {
    font-size: 14px;
  }

  .footer-description {
    font-size: 13px;
  }

  .footer-nav-bar {
    grid-template-columns: 1fr;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
  }

  .footer-nav-social {
    border-right: none;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    justify-content: center;
    padding: 16px;
  }

  .footer-nav-menu {
    grid-template-columns: 1fr;
  }

  .footer-nav-item {
    border-right: none;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    padding: 12px 16px;
  }

  .footer-nav-item:last-child {
    border-bottom: none;
  }

  .approval-content {
    padding: 30px 20px;
  }

  .approval-title {
    font-size: 22px;
  }

  .approval-request {
    font-size: 16px;
  }

  .approval-notice {
    font-size: 13px;
  }
}
</style>