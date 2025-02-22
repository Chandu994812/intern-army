# intern-army
HTML AND CSS CODE FOR THE 01 URL SHORTENING LANDING PAGE ::

HTML CODE::

<main class="main">
  <!-- Header -->
  <header class="header">
    <div class="container flex-between">
      <div class="logo">
        <a href="#">
          <img src="https://raw.githubusercontent.com/MohamedAridah/frontendmentor_url-shortening-api/main/images/logo.svg" alt="" />
        </a>
      </div>
      <nav class="main-navgation flex-between flex-ver-top">
        <div class="nav-links">
          <a href="#features">Features</a>
          <a href="#pricing">Pricing</a>
          <a href="#resources">Resources</a>
        </div>
        <div class="nav-buttons">
          <a href="#" class="log-in">Login</a>
          <a href="#" class="sign-up btn btn-sm">Sign Up</a>
        </div>
      </nav>
      <div class="burger-menu">
        <i class="fa-regular fa-bars icon"></i>
      </div>
    </div>
  </header>
  <!-- Landing -->
  <section class="landing">
    <div class="landing-text">
      <h1>More than just shorter links</h1>
      <p>
        Build your brand’s recognition and get detailed insights on how your
        links are performing.
      </p>
      <a href="#url-shorten-form" class="btn btn-lg">Get Started</a>
    </div>
    <div class="landing-image">
      <img src="https://raw.githubusercontent.com/MohamedAridah/frontendmentor_url-shortening-api/main/images/illustration-working.svg" alt="Working Illustration" />
    </div>
  </section>
  <!-- Features -->
  <section class="features" id="features">
    <div class="container">
      <!-- Short URL Feature -->
      <div class="url-shorten-feature">
        <form class="url-shorten-form" id="url-shorten-form">
          <div>
            <input type="text" class="url-input" placeholder="Shorten a link here..." autocomplete="off" />
            <span class="alert"></span>
          </div>
          <button type="submit" class="btn btn-lg btn-plus-icon">Shorten It!</button>
        </form>
        <div class="url-shorten-results"></div>
      </div>
      <!-- Advanced Features -->
      <div class="more-features">
        <div class="section-header">
          <h2>Advanced Statistics</h2>
          <p>
            Track how your links are performing across the web with our
            advanced statistics dashboard.
          </p>
        </div>
        <div class="more-features-content">
          <div class="feature">
            <div class="feature-illustration">
              <img src="https://raw.githubusercontent.com/MohamedAridah/frontendmentor_url-shortening-api/main/images/icon-brand-recognition.svg" alt="Feature Illustration Icon" />
            </div>
            <div class="feature-details">
              <h3>Brand Recognition</h3>
              <p>
                Boost your brand recognition with each click. Generic links
                don’t mean a thing. Branded links help instil confidence in
                your content.
              </p>
            </div>
          </div>
          <div class="feature">
            <div class="feature-illustration">
              <img src="https://raw.githubusercontent.com/MohamedAridah/frontendmentor_url-shortening-api/main/images/icon-detailed-records.svg" alt="Feature Illustration Icon" />
            </div>
            <div class="feature-details">
              <h3>Detailed Records</h3>
              <p>
                Gain insights into who is clicking your links. Knowing when
                and where people engage with your content helps inform
                better decisions.
              </p>
            </div>
          </div>
          <div class="feature">
            <div class="feature-illustration">
              <img src="https://raw.githubusercontent.com/MohamedAridah/frontendmentor_url-shortening-api/main/images/icon-fully-customizable.svg" alt="Feature Illustration Icon" />
            </div>
            <div class="feature-details">
              <h3>Fully Customizable</h3>
              <p>
                Improve brand awareness and content discoverability through
                customizable links, supercharging audience engagement.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Pricing -->
  <section class="pricing" id="pricing">
    <div class="container">
      <div class="section-header">
        <h2>Boost your links today</h2>
        <a href="#" class="btn btn-lg">Get Started</a>
      </div>
    </div>
  </section>
  <!-- Footer -->
  <footer class="footer" id="resources">
    <div class="container">
      <!-- Website Logo -->
      <div class="logo">
        <a href="#">
          <img src="https://raw.githubusercontent.com/MohamedAridah/frontendmentor_url-shortening-api/main/images/logo.svg" alt="" />
        </a>
      </div>
      <!-- Quick Links -->
      <div class="quick-links">
        <div class="links-group">
          <span>Features</span>
          <div>
            <a href="#">Link Shortening</a>
            <a href="#">Branded Links</a>
            <a href="#">Analytics</a>
          </div>
        </div>
        <div class="links-group">
          <span>Resources</span>
          <div>
            <a href="#">Blog</a>
            <a href="#">Developers</a>
            <a href="#">Support</a>
          </div>
        </div>
        <div class="links-group">
          <span>Company</span>
          <div>
            <a href="#">About</a>
            <a href="#">Our Team</a>
            <a href="#">Careers</a>
            <a href="#">Contact</a>
          </div>
        </div>
      </div>
      <!-- Social Media -->
      <div class="social-media">
        <a href="#">
          <img src="https://raw.githubusercontent.com/MohamedAridah/frontendmentor_url-shortening-api/main/images/icon-facebook.svg" alt="Facebook Logo">
        </a>
        <a href="#">
          <img src="https://raw.githubusercontent.com/MohamedAridah/frontendmentor_url-shortening-api/main/images/icon-twitter.svg" alt="Twitter Logo">
        </a>
        <a href="#">
          <img src="https://raw.githubusercontent.com/MohamedAridah/frontendmentor_url-shortening-api/main/images/icon-pinterest.svg" alt="Pinterest Logo">
        </a>
        <a href="#">
          <img src="https://raw.githubusercontent.com/MohamedAridah/frontendmentor_url-shortening-api/main/images/icon-instagram.svg" alt="Instagram Logo">
        </a>
      </div>
    </div>
    <!-- Made By -->
    <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" class="outer-link" target="_blank">Frontend Mentor</a>.
      Coded by <span class="outer-link">Mohamed Aridah</span>.
      <ul class="social-media">
        <li>
          <a href="https://www.codepen.io/FedLover" title="go To My Codepen Account">
            <i class="fa-brands fa-codepen icon"></i>
          </a>
        </li>
        <li>
          <a href="https://www.frontendmentor.io/profile/MohamedAridah" title="go To My Frontend Mentor Account">
            <img src="https://mohamedaridah.github.io/hosted-assets/FEM.png" class="image" alt="">
          </a>
        </li>
      </ul>
    </div>
  </footer>
</main>


CSS CODE::

@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap");
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
  font-size: 16px;
}

body {
  font-family: "Poppins", sans-serif, "Segoe UI", Tahoma, Geneva, Verdana;
  font-weight: 500;
  outline: none;
}

h1,
h2,
h3,
h4 {
  color: #35323e;
  font-weight: 700;
}

p {
  color: #9e9aa7;
  font-weight: 500;
  line-height: 1.7;
}

a {
  text-decoration: none;
}

img {
  max-width: 100%;
}

.btn {
  display: inline-block;
  color: white;
  background-color: #2acfcf;
  text-transform: capitalize;
  font-weight: 700;
  border: none;
  outline: none;
  cursor: pointer;
  border-radius: 100px;
  transition: 0.3s;
}

.btn.btn-sm {
  padding: 7px 21px;
}

.btn.btn-lg {
  padding: 12px 36px;
}

.btn.btn-plus-icon {
  display: flex;
  align-items: center;
  justify-content: center;
  column-gap: 10px;
}

.btn.btn-plus-icon .icon {
  font-size: 22px;
}

.btn:hover {
  background-color: #6be1e1;
}

.flex-between {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 40px;
}

.flex-ver-top {
  align-items: flex-start;
}

.scale-effect:active {
  transform: scale(0.88);
  transition: 0.2s;
}

.section-header {
  text-align: center;
}

.section-header h2 {
  font-size: 35px;
}

@media (max-width: 500px) {
  .section-header h2 {
    font-size: 26px;
  }
}

@media (max-width: 280px) {
  .section-header h2 {
    font-size: 22px;
  }
}

.section-header p {
  width: 50%;
  margin: 7px auto 0;
}

@media (max-width: 992px) {
  .section-header p {
    width: 70%;
  }
}

@media (max-width: 500px) {
  .section-header p {
    width: 100%;
  }
}

.container {
  position: relative;
  width: 78%;
  margin: 0 auto;
}

@media (max-width: 992px) {
  .container {
    width: 90%;
  }
}

.header {
  padding: 45px 0;
}

.header .logo img {
  height: 30px;
}

.header .main-navgation {
  flex: 1;
  gap: 0;
}

@media (max-width: 992px) {
  .header .main-navgation {
    position: absolute;
    top: 150%;
    left: 50%;
    transform: translateX(-50%);
    width: 70%;
    height: 0;
    z-index: 999;
    overflow: hidden;
    flex-direction: column;
    align-items: center;
    padding: 0 33.33333px;
    border-radius: 10px;
    background-color: #3b3054;
    transition: height 0.3s;
  }
}

@media (max-width: 767px) {
  .header .main-navgation {
    width: 90%;
  }
}

@media (max-width: 375px) {
  .header .main-navgation {
    width: 100%;
  }
}

@media (max-width: 280px) {
  .header .main-navgation {
    padding: 0 25px;
  }
}

.header .main-navgation > div {
  display: flex;
  align-items: center;
  gap: 30px;
}

@media (max-width: 992px) {
  .header .main-navgation > div {
    flex-direction: column;
    width: 100%;
    padding: 33.33333px 0;
  }
}

@media (max-width: 280px) {
  .header .main-navgation > div {
    padding: 25px 0;
  }
}

.header .main-navgation div:first-child {
  border-bottom: 1px solid white;
}

.header .nav-buttons .btn {
  color: #fff;
  width: 80%;
}

@media (max-width: 375px) {
  .header .nav-buttons .btn {
    width: 100%;
  }
}

.header .burger-menu {
  font-size: 22px;
  color: #9e9aa7;
  cursor: pointer;
  display: none;
}

@media (max-width: 992px) {
  .header .burger-menu {
    display: block;
  }
}

.main-navgation a {
  font-weight: 700;
  font-size: 14px;
  color: #9e9aa7;
  transition: 0.3s;
}

.main-navgation a:hover {
  color: #232127;
}

@media (max-width: 992px) {
  .main-navgation a {
    width: 100%;
    color: white;
    text-align: center;
    font-size: 16px;
  }
  .main-navgation a:hover {
    color: #2acfcf;
  }
}

.landing {
  display: flex;
  align-items: center;
  padding: 40px 0;
  margin-left: 11%;
  overflow-x: hidden;
}

@media (max-width: 992px) {
  .landing {
    flex-direction: column-reverse;
    margin-left: 0;
    padding-bottom: 80px;
    row-gap: 60px;
  }
}

@media (max-width: 280px) {
  .landing {
    padding-bottom: 40px;
  }
}

.landing .landing-text {
  flex: 1;
  min-width: 465px;
}

@media (max-width: 992px) {
  .landing .landing-text {
    max-width: 95%;
    min-width: 0;
    text-align: center;
  }
}

.landing .landing-text h1 {
  width: 100%;
  font-size: 3.9em;
  line-height: 1.15;
}

@media (max-width: 992px) {
  .landing .landing-text h1 {
    font-size: 3em;
  }
}

@media (max-width: 500px) {
  .landing .landing-text h1 {
    font-size: 2em;
  }
}

.landing .landing-text p {
  font-size: 18px;
  max-width: 500px;
  margin: 0 0 29.41176px;
}

@media (max-width: 992px) {
  .landing .landing-text p {
    font-size: 16px;
    margin: 10px auto 29.41176px;
  }
}

@media (max-width: 500px) {
  .landing .landing-text p {
    font-size: 15px;
  }
}

.landing .landing-image {
  position: relative;
  right: -70px;
}

@media (max-width: 992px) {
  .landing .landing-image {
    flex-basis: initial;
    right: -240px;
  }
}

@media (max-width: 767px) {
  .landing .landing-image {
    right: -170px;
  }
}

@media (max-width: 500px) {
  .landing .landing-image {
    right: -110px;
  }
}

@media (max-width: 375px) {
  .landing .landing-image {
    right: -120px;
  }
}

@media (max-width: 280px) {
  .landing .landing-image {
    right: -70px;
  }
}

@media (min-width: 1100px) {
  .landing .landing-image {
    right: -130px;
  }
}

.landing .landing-image img {
  width: 100%;
}

.features {
  margin-top: 100px;
  background-color: #eff0f5;
}

.url-shorten-form {
  width: 100%;
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  background: #3b3054 url(../images/bg-shorten-desktop.svg) no-repeat right top;
  background-size: cover;
  padding: 45px;
  border-radius: 6px;
  margin-bottom: 20px;
  transform: translateY(-50%);
  transition: gap 0.3s;
}

@media (max-width: 850px) {
  .url-shorten-form {
    flex-direction: column;
    background: #3b3054 url(../images/bg-shorten-mobile.svg) no-repeat right top;
    padding: 25px;
    margin-bottom: 0;
  }
}

@media (max-width: 280px) {
  .url-shorten-form {
    padding: 20px;
  }
}

.url-shorten-form > div {
  position: relative;
  flex: 1;
}

.url-shorten-form .url-input {
  width: 100%;
  font-family: "Poppins", sans-serif, "Segoe UI", Tahoma, Geneva, Verdana;
  font-size: 18px;
  padding: 8px 20px;
  background: white;
  border: 2px solid transparent;
  border-radius: 6px;
  outline: none;
  transition: 0.2s;
}

.url-shorten-form .url-input::placeholder {
  font-family: "Poppins", sans-serif, "Segoe UI", Tahoma, Geneva, Verdana;
  font-size: 16px;
  font-weight: 500;
  color: #9e9aa7;
}

.url-shorten-form .alert {
  position: absolute;
  left: 0;
  top: calc(100% + 4px);
  font-style: italic;
  font-size: 16px;
  color: #f46262;
  opacity: 0;
  transition: 0.2s opacity;
}

@media (max-width: 500px) {
  .url-shorten-form .alert {
    font-size: 14px;
  }
}

.url-shorten-form .btn {
  text-align: center;
  border-radius: inherit;
  white-space: nowrap;
  font-size: 16px;
  cursor: pointer;
}

@media (max-width: 850px) {
  .url-shorten-form .btn {
    font-size: 19px;
    padding: 10px 30px;
  }
}

.url-shorten-form.empty {
  gap: 37px;
}

.url-shorten-form.empty .url-input {
  border-color: #f46262;
}

.url-shorten-form.empty .url-input::placeholder {
  color: #f46262;
  opacity: 0.5;
}

.url-shorten-form.empty .alert {
  opacity: 1;
}

.url-shorten-form.success button {
  background: #30c59b;
}

.url-shorten-results {
  position: relative;
  top: -60px;
}

.url-shorten-results .url-shorten-result {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 15px;
  flex-wrap: wrap;
  padding: 15px 25px;
  background: white;
  border-radius: 6px;
  margin-bottom: 15.15152px;
}

.url-shorten-results .url-shorten-result > div p {
  font-size: 17px;
  word-break: break-word;
}

.url-shorten-results .url-shorten-result > div a:hover {
  text-decoration: underline wavy #30c59b 2px;
}

@media (max-width: 850px) {
  .url-shorten-results .url-shorten-result {
    flex-direction: column;
    align-items: flex-start;
    padding: 0;
    gap: 0;
  }
  .url-shorten-results .url-shorten-result > div {
    width: 100%;
    align-items: flex-start;
    padding: 12px 18px;
  }
}

.url-shorten-results .delete-all-urls {
  display: block;
  margin: auto;
  font-size: 15px;
  background-color: #f24a4a;
}

.url-shorten-results .delete-all-urls:hover {
  background-color: #f46262;
}

.url-shorten-result .old-url p {
  color: #35323e;
  font-weight: 500;
}

.url-shorten-result .old-url a {
  color: inherit;
}

@media (max-width: 850px) {
  .url-shorten-result .old-url {
    border-bottom: 1px solid #bfbfbf;
  }
}

.url-shorten-result .new-url {
  display: flex;
  align-items: center;
  gap: 20px;
}

.url-shorten-result .new-url a {
  color: #2acfcf;
}

@media (max-width: 850px) {
  .url-shorten-result .new-url {
    flex-direction: column;
    gap: 12px;
  }
}

.url-shorten-result .options {
  display: flex;
  gap: 10px;
}

@media (max-width: 850px) {
  .url-shorten-result .options {
    width: 100%;
  }
}

.url-shorten-result .options button {
  width: 95px;
  font-size: 15px;
  border-radius: 6px;
  cursor: pointer;
}

.url-shorten-result .options button.copied {
  background: #3b3054;
}

.url-shorten-result .options button.delete-url {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 35px;
  background: #f46262;
  border: none;
  color: white;
  font-size: 18px;
  transition: 0.2s;
}

.url-shorten-result .options button.delete-url:hover {
  color: #f46262;
  background-color: #eff0f5;
  font-size: 20px;
}

@media (max-width: 850px) {
  .url-shorten-result .options button {
    width: 100%;
    font-size: 18px;
    padding: 10px 30px;
  }
}

.more-features-content {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 25px;
  padding: 80px 0 90px 0;
}

@media (max-width: 666px) {
  .more-features-content {
    gap: 80px;
  }
}

@media (max-width: 280px) {
  .more-features-content {
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  }
}

.more-features-content .feature {
  position: relative;
  background: white;
  border-radius: 6px;
}

.more-features-content .feature:before,
.more-features-content .feature::after {
  position: absolute;
  content: "";
  background: #2acfcf;
}

@media (max-width: 666px) {
  .more-features-content > div:nth-child(2):before,
  .more-features-content > div:nth-child(2)::after {
    width: 6px;
    height: 80px;
    left: 50%;
    transform: translateX(-50%);
  }
  .more-features-content > div:nth-child(2):before {
    top: -80px;
  }
  .more-features-content > div:nth-child(2):after {
    bottom: -80px;
  }
}

@media (min-width: 1130px) {
  .more-features-content {
    align-items: flex-start;
  }
  .more-features-content > div:nth-child(2) {
    margin-top: 30px;
  }
  .more-features-content > div:nth-child(2):before,
  .more-features-content > div:nth-child(2)::after {
    height: 6px;
    width: 25px;
    top: 40%;
  }
  .more-features-content > div:nth-child(2):before {
    left: -25px;
  }
  .more-features-content > div:nth-child(2):after {
    right: -25px;
  }
  .more-features-content > div:nth-child(3) {
    margin-top: 60px;
  }
}

.feature .feature-illustration {
  position: absolute;
  top: -32.5px;
  left: 25px;
  display: grid;
  place-items: center;
  width: 65px;
  height: 65px;
  background: #3b3054;
  border-radius: 50%;
}

@media (max-width: 666px) {
  .feature .feature-illustration {
    left: 50%;
    transform: translateX(-50%);
    width: 80px;
    height: 80px;
  }
}

.feature .feature-illustration img {
  max-width: 50%;
}

.feature .feature-details {
  padding: 0 25px 30px;
  margin-top: 60px;
}

@media (max-width: 666px) {
  .feature .feature-details {
    text-align: center;
    margin-top: 80px;
  }
}

@media (max-width: 280px) {
  .feature .feature-details {
    padding: 0 20px 25px;
  }
}

@media (max-width: 500px) {
  .feature .feature-details h3 {
    font-size: 20px;
  }
}

@media (max-width: 280px) {
  .feature .feature-details h3 {
    font-size: 18px;
  }
}

.feature .feature-details p {
  margin-top: 10px;
  font-size: 14px;
}

.pricing {
  padding: 50px 0;
  background: #3b3054 url(../images/bg-boost-desktop.svg) no-repeat right;
  background-size: cover;
}

@media (max-width: 500px) {
  .pricing {
    padding: 90px 0;
    background-image: url(../images/bg-boost-mobile.svg);
  }
}

.pricing .container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100%;
}

.pricing h2 {
  color: white;
  margin-bottom: 20px;
}

.footer {
  padding-top: 50px;
  background: #232127;
}

.footer .container {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  gap: 70px;
  flex-wrap: wrap;
}

@media (max-width: 705px) {
  .footer .container {
    flex-wrap: nowrap;
    flex-direction: column;
    align-items: center;
    gap: 30px;
  }
}

.footer .logo {
  flex: 1 0 auto;
}

.footer .logo img {
  filter: brightness(10);
}

.footer .quick-links {
  display: flex;
  gap: 60px;
}

@media (max-width: 705px) {
  .footer .quick-links {
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 30px;
  }
}

.footer .quick-links .links-group {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.footer .links-group span {
  color: white;
  font-weight: 700;
}

.footer .links-group > div {
  display: flex;
  flex-direction: column;
  gap: 6.66667px;
}

.footer .links-group a {
  color: #bfbfbf;
  font-size: 13px;
  transition: 0.2s color;
}

.footer .links-group a:hover {
  color: cyan;
}

.footer .social-media {
  display: flex;
  flex-shrink: 0;
  align-items: center;
  gap: 20px;
}

.footer .social-media img {
  max-width: 85%;
  transition: 0.2s transform;
}

.footer .social-media img:hover {
  transform: scale(1.1);
  filter: invert(0%) sepia(59%) saturate(6585%) hue-rotate(125deg)
    brightness(86%) contrast(85%);
}

.attribution {
  padding: 30px 0 25px 0;
  text-align: center;
  font-size: 13px;
  color: #fff;
}

.attribution .outer-link {
  font-size: 15px;
  color: #2acfcf;
  margin-left: 2px;
  cursor: pointer;
}

.attribution .outer-link:hover {
  text-decoration: underline wavy #2acfcf 2px;
}

.attribution .social-media {
  display: inline-flex;
  align-items: center;
  gap: 12px;
  list-style: none;
  margin-left: 5px;
}

.attribution .social-media .icon {
  font-size: 20px;
  color: #fff;
}

.attribution .social-media .image {
  width: 23px;
}

.attribution .social-media .image:hover {
  filter: none;
  background-color: none;
}


JAVASCRIPT CODE::

/*

  ////// NOTE ///////
  
LocalStorage Doesn't Wok On Coden Pen [Access Denied]. So When Refreshing The Browser All The Generated URLs will Be Removed.

To View The Full Functionality Of The Website, You Can Visit My Github Page

https://github.com/MohamedAridah/frontendmentor_url-shortening-api

*/

// Global Variables
let shortURLsWrapper = document.querySelector(".url-shorten-results");
let shortUrlForm = document.querySelector("#url-shorten-form");
let submitButton = shortUrlForm.querySelector("button");
let input = shortUrlForm.querySelector(".url-input");
let alertMessage = shortUrlForm.querySelector(".alert");

// Build Short URL HTML Structure
function generatedShortUrlHtml(id, originalURL, shortUrl) {
  shortURLsWrapper.insertAdjacentHTML(
    "beforeend",
    `
  <div class="url-shorten-result" id='${id}'>
    <div class="old-url">
    <p><a href="${originalURL}" target="_blank">${originalURL}</a></p>
    </div>
    <div class="new-url">
      <p><a href="${shortUrl}" target="_blank">${shortUrl}</a></p>
      <div class="options">
        <button type="button" class="copy-new-url btn btn-sm scale-effect">
          copy
        </button>

        <button type="button" class="delete-url scale-effect">
          <i class="fa-regular fa-trash-can icon"></i>
        </button>
      </div>
    </div>
  </div>`
  );
  removeURL();
  copyURL();
  removeAllGeneratedURLs();
}

// Put Delete Button At The End Of The Generated Links Function
function insertAfter(newNode, existingNode) {
  existingNode.parentNode.insertBefore(newNode, existingNode.nextSibling);
}

// Add Remove All Generated URls
function removeAllGeneratedURLs() {
  // When There Is More Than One Generated URL & Delete Button Is Already Exists Delete It And Then Add It To The End Of The URLs List.
  if (shortURLsWrapper.querySelectorAll(".url-shorten-result").length >= 2) {
    if (shortURLsWrapper.querySelector(".delete-all-urls")) {
      shortURLsWrapper.querySelector(".delete-all-urls").remove();
    }
    // Create Delete Generated URLs Button
    let button = document.createElement("button");
    button.type = "button";
    button.classList = "btn btn-sm delete-all-urls scale-effect";
    button.textContent = "delete all";
    insertAfter(button, shortURLsWrapper.lastElementChild);
    // Delete All Genetared URLs & LocalStorage
    let deleteAll = shortURLsWrapper.querySelector(".delete-all-urls");
    deleteAll.addEventListener("click", () => {
      shortURLsWrapper.innerHTML = "";
      savedURLs = [];
      localStorage.removeItem("saved");
    });
  } else {
    if (shortURLsWrapper.querySelector(".delete-all-urls")) {
      shortURLsWrapper.querySelector(".delete-all-urls").remove();
    }
  }
}

// Remove Sindle URL
function removeURL() {
  let deleteURLButton = shortURLsWrapper.querySelectorAll(".delete-url");
  deleteURLButton.forEach((button) => {
    button.addEventListener("click", () => {
      // Get URL ID
      let linkId = button.closest(".url-shorten-result").id;
      // Remove URL From The List
      button.closest(".url-shorten-result").remove();
      // Get Index Of This URL And Remove It From Array
      const index = savedURLs.findIndex((url) => url.id == linkId);
      // Remove URL From The Array
      savedURLs.splice(index, 1);
      // Resave The Array & LocalStorage
      localStorage.setItem("saved", JSON.stringify(savedURLs));
      removeAllGeneratedURLs();
    });
  });
}

// Copy URl
function copyURL() {
  let copyButtons = shortURLsWrapper.querySelectorAll(".copy-new-url");
  copyButtons.forEach((button) => {
    button.addEventListener("click", () => {
      // Get URL Content
      let urlText = button
        .closest(".url-shorten-result")
        .querySelector(".new-url p").textContent;
      const body = document.querySelector("body");
      const area = document.createElement("textarea");
      body.appendChild(area);
      area.value = urlText;
      area.select();
      document.execCommand("copy");
      button.classList.add("copied");
      button.innerHTML = "copied!";
      setTimeout(() => {
        button.classList.remove("copied");
        button.innerHTML = "copy";
      }, 1500);
      body.removeChild(area);
    });
  });
}

// Generate Random IDs
function reandomIds() {
  let currentTime = Date.now();
  let currentTimeString = currentTime.toString(32).slice(0, 8);
  let reandomNumber = Math.floor(Math.random() * Number.MAX_SAFE_INTEGER)
    .toString()
    .slice(0, 4);
  let reabdomId = `${currentTimeString}-${reandomNumber}`;
  return reabdomId;
}

// shrtcode API
const makeShortURL = async (userUrl) => {
  let apiBaseURL = "https://api.shrtco.de/v2/";
  let shortenQuery = `shorten?url=`;
  let fetchLink = `${apiBaseURL}${shortenQuery}${userUrl}`;

  try {
    let response = await fetch(fetchLink);
    let data = await response.json();
    let status = data.ok;

    // Response With Data
    if (status) {
      let originalURL = data.result.original_link;
      let shortUrl = data.result.full_short_link;
      // Make Object For [originalURL, shortUrl]
      let generatedURL = {
        id: reandomIds(),
        originalURL: originalURL,
        shortUrl: shortUrl
      };
      // Change Submit Button Text & Style
      shortUrlForm.classList.add("success");
      submitButton.innerHTML = `<i class="fa-solid fa-check icon"></i> shortened!`;
      setTimeout(() => {
        shortUrlForm.classList.remove("success");
        submitButton.innerHTML = "shorten it!";
      }, 1700);
      generatedShortUrlHtml(reandomIds(), originalURL, shortUrl);
      // Save [link] Object To Localstorage After Pushing It To The [savedURLs] Array
      savedURLs.push(generatedURL);
      localStorage.setItem("saved", JSON.stringify(savedURLs));
    }
    // Response With Error Message [No Data].
    else {
      // Change Submit Button Text
      submitButton.innerHTML = "shorten it!";
      let errorCode = data.error_code;
      switch (errorCode) {
        // If Input Is Empty
        case 1:
          alerts("Please add a link first");
          break;
        // If URL Is Not Valid
        case 2:
          alerts(data.error.split(",")[0] + ", Please check your link again.");
          break;
        // If URL Is Not Allowed To Be Shortened
        case 10:
          alerts("The link you entered is not allowed to be shortened.");
          break;
        // Any Other Problem
        default:
          alerts(data.error);
      }
    }
  } catch (error) {
    // Incase Can't Connect To The Api [Ex: No Internet Connection]
    alerts("Sorry, unknown error happened please try again later.");
  }
};

shortUrlForm.addEventListener("submit", (e) => {
  e.preventDefault();
  // Get Input Value & Remove Extra Spaces.
  let inputValue = input.value.trim().replace(" ", "");
  // Change Submit Button Text
  submitButton.innerHTML = `<i class="fa-solid fa-spinner icon fa-spin"></i> Generating...`;
  makeShortURL(inputValue);
  // Clear Input
  shortUrlForm.reset();
});

// Show Alerts
function alerts(message) {
  shortUrlForm.classList.add("empty");
  alertMessage.textContent = message;

  setTimeout(() => {
    shortUrlForm.classList.remove("empty");
  }, 5000);
}

// Expand Header Navgation Function
function expandNavgation() {
  let navgation = document.querySelector(".header .main-navgation");
  let toggleMenu = document.querySelector(".header .burger-menu");
  let icon = toggleMenu.querySelector(".icon");
  let closed = true;

  toggleMenu.addEventListener("click", () => {
    // Change Icon
    if (icon.classList.contains("fa-bars")) {
      icon.className = "fa-regular fa-xmark icon";
    } else {
      icon.className = "fa-regular fa-bars icon";
    }

    // Open Or Close Navgation Menu
    let navgationHeight = navgation.scrollHeight;
    if (closed) {
      navgation.style.height = `${navgationHeight}px`;
    } else {
      navgation.style.height = "";
    }
    closed = !closed;
  });
  // Close Navgation For Devices Greater Than 992px Width.
  window.addEventListener("resize", () => {
    if (window.innerWidth > 992) {
      icon.className = "fa-regular fa-bars icon";
      navgation.style.height = "";
      closed = true;
    }
  });
}
expandNavgation();
__________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________



PORTFOLIO CODE::......................... PORTFOLIO CODE IN GOOGLE DRIVE



__________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

TASK TRACKER  CODE::
HTML::...............

<html>
<head>
    <meta charset="UTF-8">
    <title>Task Manager</title>
    
    <link rel="stylesheet" href="src/ij.css">
    <link rel="stylesheet" href="src/animate.css">
</head>
<body>
   <div class="container">
      <h1>Task Manager</h1>
      <hr>	
<!--       TASK FORM-->
        <section><div class="row">
           <form class="animated fadeIn" id="form">
           <div class="">
            <div class="s12 l12 m12">

                <input type="text" id="name" placeholder="Name">
                <input type="text" id="subject" placeholder="Subject">
                <input type="date" id="myDate">
            </div>
               
               <div class="row">
                <div class="s10 l10 m10">
                <textarea id="description" placeholder="Describe the Task" cols="30" rows="10" onClick="myObj.textSelect(this)"> Describe Your Task</textarea>
                               

            </div>
            </div>
            <div class="col s12 l12 m12">
                <div class="btn" onclick="submitInfo()">SUBMIT</div>
                <div class="btn" onclick="myObj.hide()">HIDE</div>
            </div>

            </div>
            </form>
        </div></section>
       <div class="btn" onClick="myObj.show()" id="show">New Task</div>
<!--       TASK LIST-->
  
          <div class="row" style="text-align:center;" id="myTasks">
             

              
          </div>

           
       

       
   </div>
   <script src="src/ObjectApp.js"></script>



    </body>
</html>


CSS CODE::.................................................................................

`  /*Have this font on css and ttf file.*/
@font-face {
    font-family: test Sans;
    src: url('src/OpenSans-Regular.ttf');
}

html {
/*	OPEN SANS FONT PROJECT REQUIREMENT */
font-family: 'Open Sans', sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}



body {
  margin: 0;
	
    background: #0288d1;
    color:white;
/*background Image*/
  background-image: url('https://i.imgur.com/AvhsQod.jpg');
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-color: #464646;
}
	
}

/*MY SHADOW*/

myShadow,  .btn,{
  box-shadow: 0 2px 5px 0 rgba(0, 0, 0, 0.16), 0 2px 10px 0 rgba(0, 0, 0, 0.12);
}
.myShadow-2,.btn:hover {
  box-shadow: 0 8px 17px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.container {
    width: 90%;
	margin-left: auto;
    margin-right: auto;
    text-align: center;
}
/*ROW and COL*/

.row {
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 20px;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

.row .col {
  float: left;
  box-sizing: border-box;
  padding: 0 0.75rem;
}

.row .col[class*="push-"], .row .col[class*="pull-"] {
  position: relative;
}

@media only screen and (max-width: 500px){
.row .col.s6 {
  width: 50%;
  margin-left: auto;
  left: auto;
  right: auto;
}



.row .col.s10 {
  width: 83.3333333333%;
  margin-left: auto;
  left: auto;
  right: auto;
}


.row .col.s12 {
  width: 100%;
  margin-left: auto;
  left: auto;
  right: auto;
}
	}

@media only screen and (min-width: 601px) {

  .row .col.m4 {
    width: 33.3333333333%;
    margin-left: auto;
    left: auto;
    right: auto;
  }

  .row .col.m6 {
    width: 50%;
    margin-left: auto;
    left: auto;
    right: auto;
  }
  
*/
  .row .col.m10 {
    width: 83.3333333333%;
    margin-left: auto;
    left: auto;
    right: auto;
  }

  .row .col.m12 {
    width: 100%;
    margin-left: auto;
    left: auto;
    right: auto;
  }
}

@media only screen and (min-width: 993px) {

  .row .col.l3 {
    width: 25%;
    margin-left: auto;
    left: auto;
    right: auto;
  }

  .row .col.l4 {
    width: 33.3333333333%;
    margin-left: auto;
    left: auto;
    right: auto;
  }
  
  .row .col.l6 {
    width: 50%;
    margin-left: auto;
    left: auto;
    right: auto;
  }
  
  .row .col.l10 {
    width: 83.3333333333%;
    margin-left: auto;
    left: auto;
    right: auto;
  }

  .row .col.l12 {
    width: 100%;
    margin-left: auto;
    left: auto;
    right: auto;
  }
}

/*FORM CONTROL*/
::-webkit-input-placeholder {
  color: #d1d1d1;
}

:-moz-placeholder {
  /* Firefox 18- */
  color: #d1d1d1;
}

::-moz-placeholder {
  /* Firefox 19+ */
  color: #d1d1d1;
}

:-ms-input-placeholder {
  color: #d1d1d1;
}

input:not([type]),
input[type=text],
textarea {
  background-color: transparent;
  border: none;
  border-bottom: 1px solid #9e9e9e;
  border-radius: 0;
  outline: none;
  height: 3rem;
/*  width: 100%;*/
  font-size: 1rem;
  margin: 0 0 15px 0;
  padding: 0;
  box-shadow: none;
  box-sizing: content-box;
  transition: all .3s;
}


textarea{
    overflow-y: hidden;
    padding: 1.6rem 0;
    resize: none;
    min-height: 3rem;
    font-family: sans-serif;
}




input:not([type]) + label:after,
input[type=text] + label:after,
textarea + label:after {
  display: block;
  content: "";
  position: absolute;
  top: 65px;
  opacity: 0;
  transition: .2s opacity ease-out, .2s color ease-out;
}



textarea {
/*  width: 100%;*/
  height: 3rem;
  background-color: transparent;
}



/*BUTTON*/
.btn{
  border: none;
  border-radius: 2px;
  display: inline-block;
  height: 36px;
  line-height: 36px;
  outline: 0;
  padding: 0 2rem;
  text-transform: uppercase;
  vertical-align: middle;
  -webkit-tap-highlight-color: transparent;
}





.btn {
  text-decoration: none;
  color: #fff;
  background-color: #4fc3f7;
  text-align: center;
  letter-spacing: .5px;
  transition: .2s ease-out;
  cursor: pointer;
}

.btn:hover {
  background-color: #81d4fa;
}


hr {
  box-sizing: content-box;
  height: 0;
}

#form {
    display:none;
}
input[type=text]{
	color:white;
}

input[type="date"]{
	border: none;
    background: none;
    border-bottom: 1px solid  #bbdefb;
    padding-bottom: 13.5px;
	color:	white;
}

textarea{
	color:white;
}

.red {
	background-color: #f44336;
}

.red:hover {
	background-color: #ef5350;
}


JAVASCRIPT CODE::.........................................

//My Methods
var myObj= {
    //Select TextArea Func
    textSelect: function(){
        document.getElementById('description').select();
    },

//Hide form Method
    hide: function() {
    document.getElementById("form").style.display = "none";
    document.getElementById("show").style.display = "inline-block";

},
//Show Form Method
    show:function(){

    document.getElementById("form").style.display = "block";
    document.getElementById("show").style.display = "none";
    document.getElementById('myDate').valueAsDate = new Date();
    },
    //Removing task method
    removeTask: function () {
    var id = this.getAttribute('id');
    var myTasks = returnToDo();
    myTasks.splice(id, 1);
    localStorage.setItem('myData', JSON.stringify(myTasks));
    document.getElementById('myTasks').innerHTML = '';
    showMyTasks();
    console.log('delete');

}
};
//Checks if there is already data in LocalStorage
function returnToDo(){
    var myTasks = [];
    var myTasksTemp = localStorage.getItem('myData');
    if(myTasksTemp != null){
        myTasks = JSON.parse(myTasksTemp);
    }
    return myTasks;
}
//Class that creates tasks.
function Task(){
    this.name = document.getElementById('name').value;
    this.subject = document.getElementById('subject').value;
    this.date = document.getElementById('myDate').value;
    this.describe = document.getElementById('description').value;
}
//Insert task properties into the HTML
function newTask(x,y,z,o){
    document.getElementById('myTasks').innerHTML +=
        '<div class="col l3 m4 s12 animated zoomIn"> <h4>'+z+  ':</h1>'+
        '<p>'+y+'</p>' +
        '<p>By: '+x+'</p>' +
        '<p>Due: ' +o +'</p>'+
        '<div class="btn red" >Delete</div>'+
    '</div>'
}
//Gets all the objects from the array.
function showMyTasks(){
    var myTasks = returnToDo();
    document.getElementById('myTasks').innerHTML = '';
    for(var i=0;i<myTasks.length;i++){
        newTask(
            myTasks[i].name,
            myTasks[i].describe,
            myTasks[i].subject,
            myTasks[i].date
        );
    }
    var button = document.getElementsByClassName('red');
    for (var j = 0; j < button.length; j++) {
        button[j].addEventListener('click', myObj.removeTask);
        console.log(button[j].addEventListener('click', myObj.removeTask));

    }
}
function submitInfo(){
    var myTasks = returnToDo();
    myTasks.push(new Task);
    localStorage.setItem('myData',JSON.stringify(myTasks));
    showMyTasks();
    myObj.hide();
}
showMyTasks();



