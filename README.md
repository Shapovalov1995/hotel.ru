# hotel.ru

git push --set-upstream origin dev
https://jakearchibald.github.io/svgomg/

Вёрстка

document.body.contentEditable = true

http://htmlbook.ru/css/nth-child




1 git commit -m "7. Modules Layout Flexbox"

2 git push --set-upstream origin dev

git config --global user.email "werdiktbank@yandex.ru"
git config --global user.name "Shapovalov1995"




git commit –amned

rm -f .git/index.lock

…или создайте новый репозиторий в командной строке
echo "# hotel.ru" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Shapovalov1995/hotel.ru.git
git push -u origin main
…или нажмите существующий репозиторий из командной строки
git remote add origin https://github.com/Shapovalov1995/hotel.ru.git
git branch -M main
git push -u origin main
…или импортировать код из другого репозитория
Вы можете инициализировать этот репозиторий кодом из проекта Subversion, Mercurial или TFS..
Код импорта


...или создайте новый репозиторий в командной строке

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Shapovalov1995/hotel.ru.git
git push -u origin main


...или запустите существующий репозиторий из командной строки
git remote add origin https://github.com/Shapovalov1995/hotel.ru.git
git branch -M main
git push -u origin main






















* {
    box-sizing: border-box;
}

:root {
    --heading-color: #333333;
    --common-text-color: #000000;
    --brand-color: #CC9933;
    --header-link-color: #666666;
    --light-color: #ffffff;
    --add-color:
    rgb(45, 82, 124);
}

body {
    background-color: #E5E5E5;
    padding-bottom: 20px;
}

h2 {
    margin: 0;
    padding: 0;
    font-size: 40px;
    font-style: normal;
    font-weight: 400;
    line-height: 40px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--heading-color)
}

p {
    margin: 0;
    padding: 0;
}

a {
    text-decoration: none;
}

ul {
    margin: 0;
    padding: 0;
    list-style: none;
}

img {
    max-width: 100%;
}

html {
    font-family: 'Muller', sans-serif;
}

.container {
    max-width: 1200px;
    margin-top: 70px;
    margin-right: auto;
    margin-left: auto;
    padding-right: 15px;
    padding-left: 15px;;
}

.btn {
    display: inline-block;
    padding: 13px 20px;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 16px;
    letter-spacing: 0;
    border: 1px solid var(--brand-color);
    color: var(--brand-color);
    border-radius: 10px;
    cursor: pointer;
    transition: color .3s ease;
    position: relative;
    z-index: 0;
    overflow: hidden;
}

.btn:hover {
    color: var(--light-color);
}

.btn:after {
  content: '';
	position: absolute;
	z-index: -1;
	width: 0;
	height: 100%;
	top: 50%;
	left: 50%;
	background: var(--brand-color);
	opacity: 0;
	transform: translateX(-50%) translateY(-50%);
  transition-property: width, opacity;
  transition-duration: .3s;
  transition-timing-function: ease;
}

.btn:hover:after {
	width: 100%;
	opacity: 1;
}

.section-heading {
    font-size: 40px;
    font-style: normal;
    font-weight: 400;
    line-height: 40px;
    letter-spacing: 0;
    text-align: left;
    padding-left:40px;
    padding-bottom: 20px;
}



/* Header */
.header-container {
    margin-top: 30px;
}

.header-top-line {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 30px;
}

.header-top-line-left {
    display: flex;
    align-items: center;
}

.header-main-part {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 70px;
    padding: 27px 45px;
}

.header-main-part-line-left {
    flex: 1 1 60%;
    justify-content: space-around;
}

.header-logo {
    margin-right: 36px;
}

.header-tel {
    font-size: 20px;
    font-style: normal;
    font-weight: 500;
    line-height: 20px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--header-link-color);
    transition: color .3s ease;
}

.header-tel:hover {
    color:var(--brand-color);
}

.header-main-part-line-right {
    display: flex;
    padding-left: 17px;
    border-left: 1px solid #E1E1E1;
}

.header-btn {
    margin-left: 40px;
}
-------------------------------------------------------- 
.header-cabinet {
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 16px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--brand-color);
    background-image: url('../img/header-cabinet.svg');
    background-repeat: no-repeat;
    padding-left: 28px;
    transition-property: background-image, color;
    transition-duration: .3s;
    transition-timing-function: ease;
}
----------------------------------------------------------------
.header-cabinet:hover {
    color: var(--add-color);
    background-image: url('../img/header-cabinet-hover.svg');
}

.header-main-part {
    background-color: var(--light-color);
    border-radius: 15px;
}

.nav-list {
    display: flex;
}

.nav-link {
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 16px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--header-link-color);
    transition: color .3s ease;
}

.nav-link:hover {
    color: var(--brand-color);;
}

.nav-item:not(:last-child) {
    margin-right: 60px;
}



/* Special */
.section-special-list {
    display: flex;
}

.section-special-list-column {
    flex: 1 1 50%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.section-special-item {
    margin-right: 23px;
    position: relative;
    min-height: 260px;
}

.section-special-item:nth-child(2) {
    margin-top: 23px;
}

.section-special-item.darken::before {
    content: '';
    display: block;
    position: absolute;
    z-index: 1;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background: linear-gradient(90deg, rgba(48, 64, 89, 0.84) -2.9%, rgba(53, 65, 83, 0) 65.7%);
    border-radius: 15px;
}

.section-special-item-img {
    width: 100%;
    height: 100%;
    position: absolute;
    object-fit: cover;
    border-radius: 15px;
}

.section-special-item-info {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    position: relative;
    min-height: 100%;
    padding: 40px;
    z-index: 1;
}

.section-special-item-heading {
    width: 295px;
    font-size: 40px;
    font-style: normal;
    font-weight: 700;
    line-height: 40px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--light-color);
}

.section-special-item-price {
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--light-color);
    margin-top: 15px;
}

.section-special-item-see-more {
    display: block;
    width: 105px;
    margin-top: 47px;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 16px;
    letter-spacing: 0em;
    text-align: left;
    color: #FFCC66;
    background-image: url('../img/rectangle_2.svg');
    background-repeat: no-repeat;
    background-position: center right;
    transition-property: background-image, color;
    transition-duration: .3s;
    transition-timing-function: ease;
}

.section-special-item-see-more:hover {
    background-image: url('../img/rectangle_white_2.svg');
    color: #ffffff;
}

.section-special-large {
    height: 100%;
    display: flex;
}

.section-special-large .section-special-item-info {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding-top: 211px;
    padding-bottom: 41px;
}

.section-special-large .section-special-item-heading {
    font-size: 60px;
    line-height: 60px;
}

.section-special-large .section-special-item-price {
    font-size: 30px;
    line-height: 30px;
}



/* About Us */
.section-about-us-text {
    max-width: 888px;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 32px;
    letter-spacing: 0;
    text-align: left;
}



/* Services */
.section-services-list {
    display: flex;
    flex-wrap: wrap;
    margin: -11.5px;
}

.section-services-item {
    flex: 0 1 50%;
    display: flex;
    padding: 11.5px;
}

.section-services-item-container {
    background-color: var(--light-color);
    border-radius: 15px;
}

.section-services-item-img {
    width: 100%
}

.section-services-item-info {
    padding: 26px 45px;
}

.section-services-item-title-link {
    color: var(--brand-color);
    font-size: 20px;
    font-style: normal;
    font-weight: 500;
    line-height: 40px;
    letter-spacing: 0;
    text-align: left;
    background-image: url('../img/rectangle_2.svg');
    background-repeat: no-repeat;
    padding-right: 22px;
    background-position: bottom right;
    transition-property: background-image, color;
    transition-duration: .3s;
    transition-timing-function: ease;
}

.section-services-item-title-link:hover {
    background-image: url('../img/rectangle_dark-blue_2.svg');
    color: var(--add-color);
}

.section-services-item-description {
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 32px;
    letter-spacing: 0;
    text-align: left;
}



/* Advantages */
.section-heading {
    font-size: 40px;
    font-style: normal;
    font-weight: 400;
    line-height: 40px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--heading-color)
}

.section-advantages-list {
    display: flex;
    flex-wrap: wrap;
    margin: -11.5px;
}

.section-advantages-item {
    display: flex;
    flex: 0 1 25%;
    padding: 11.5px;
}

.section-advantages-item-container {
    padding: 43px;
    background-color: var(--light-color);
    border-radius: 15px;
}

.section-advantages-item-description {
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 32px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--common-text-color);
    margin-top: 10.64px;
}



/* Accommodation */
.section-accommodation-list {
    display: flex;
    flex-wrap: wrap;
    margin: -11.5px;
}

.section-accommodation-item {
    flex: 0 1 33.33%;
    display: flex;
    padding: 11.5px;
    /* flex-direction: column; */
}

.section-accommodation-item-container {
    background-color: var(--light-color);
    border-radius: 15px;
}

.section-accommodation-item-img {
    width: 100%;
}

.section-accommodation-item-info {
    padding: 36px 46px 41px 45px;
}

.section-accommodation-item-up-info {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.section-accommodation-item-price-from {
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 16px;
    letter-spacing: 0em;
    text-align: left;
    color: #999999;
}

.section-accommodation-item-price {
    font-size: 20px;
    font-style: normal;
    font-weight: 700;
    line-height: 20px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--common-text-color);
}

.section-accommodation-item-price-period {
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 16px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--common-text-color);
}

.section-accommodation-item-title {
    display: inline-block;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 16px;
    letter-spacing: 0em;
    text-align: left;
    color: var(--common-text-color);
    margin-top: 16px;
}

.section-accommodation-item-places {
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 16px;
    letter-spacing: 0em;
    text-align: left;
    color: #999999;
    margin-top: 16px;
}

.rooms {
    margin-top: 20px;
}

.section-accommodation-see-more {
    height: 100%;
    min-height: 446px;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    position: relative;
    background-image: url('../img/41.png');
    background-repeat: no-repeat;
    background-size: cover;
    align-items: flex-start;
    padding: 40px 50px 40px 50px;
    border-radius: 15px;
}

.section-accommodation-see-more::before {
    content: '';
    display: block;
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    border-radius: 15px;
    background: linear-gradient(90deg, rgba(48, 64, 89, 0.84) -2.9%, rgba(53, 65, 83, 0) 65.7%);
}

.section-accommodation-see-more-link {
    display: inline-block;
    font-size: 20px;
    font-weight: 500;
    color: #ffffff;
    background-image: url('../img/rectangle_white_2.svg');
    background-repeat: no-repeat;
    background-position: center right;
    padding-right: 20px;
    transition-property: background-image, color;
    transition-duration: .3s;
    transition-timing-function: ease;
    z-index: 1;
}

.section-accommodation-see-more-link::before {
    content: '';
    display: block;
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
}

.section-accommodation-see-more-link:hover {
    color: var(--brand-color);
    background-image: url('../img/rectangle_2.svg');
}



/* Form */
.tour-container {
    padding: 38px 45px 71px 45px;
    background: #E9E9E9;
    border-radius: 15px;
}

.tour-form {
    display: flex;
    padding: 28px;
    background: var(--light-color);
    border-radius: 15px;
}

.tour-form-group {
    display: flex;
    flex-direction: column;
    flex: 1 1 16.67%;
    max-width: 190px;
    border-right: 1px solid #E1E1E1;
    padding-left: 20px;
    padding-right: 20px;
}

.tour-form-group:first-child {
    padding-left: 0;
}

.tour-form-group:last-child {
    padding-right: 0;
    border: none;
}

.form-label {
    font-style: normal;
    margin-top: 3px;
    margin-bottom: 15px;
    font-weight: normal;
    font-size: 12px;
    line-height: 12px;
    color: var(--common-text-color);
}

.field-select {
    background-color: transparent;
    border: none;
    appearance: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    -ms-appearance: none;
    background-image: url('../img/for_select_field.svg');
    background-repeat: no-repeat;
    background-position: right center;
}

.field-date {
    border: none;
    background-image: url('../img/for_data_field.svg');
    background-repeat: no-repeat;
    background-position: right top;
}

.field-number {
    border: none;
    border-bottom: 1px solid #cccccc;
    padding-bottom: 3px;
}

.form-group-nights, .form-group-persons {
    max-width: 150px;
}

.submit-form {
    background-color: var(--light-color);
    width: 100%;
    height: 100%;
    margin-left: auto;
    padding: 13px 30px;
}

.field-number::placeholder {
    color: var(--common-text-color);
}



/* Contacts */
.contacts-box {
    display: flex;
    justify-content: space-between;
    padding: 44px 44px 46px 46px;
    background-color: var(--light-color);
    border-radius: 15px;
}

.contacts-box-left {
    padding-right: 45px;
    max-width: 380px;
}

.contacts-box-left-info {
    display: flex;
    justify-content: space-between;
    border-bottom: 1px solid #C4C4C4;
    margin-top: 25px;
    padding-bottom: 23px;
}

.contacts-box-left-info-title {
    flex: 1 1 40%;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    color: var(--common-text-color);
}

.contacts-box-left-info-text {
    flex: 1 1 60%;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 150%;
    color: var(--common-text-color);
}

.contacts-box-link {
    display: inline-block;
    color: var(--brand-color);
    transition: color .3s ease;
}

.contacts-box-link:hover {
    color: var(--add-color);
}

.btn-lg {
    margin-top: 45px;
    padding: 27px 29px;
    background: var(--light-color);
    font-style: normal;
    font-weight: bold;
    font-size: 16px;
    line-height: 16px;
}



/* Footer */
.footer-container {
    display: flex;
    padding: 44px 51px 55px 52px;
    background: #333333;
    background-image: url('../img/Frame_11.svg');
    background-repeat: no-repeat;
    background-position: 75% 100%;
    border-radius: 15px;
}

.footer-info-col {
    flex: 1 1 33.33%;
}

.footer-info-col:nth-child(1) {
    max-width: 320px;
    margin-right: 100px;
}

.footer-info-col:nth-child(2) {
    max-width: 360px;
}

.footer-info-col:last-child {
    max-width: 25px;
    margin-left: auto;
}

.footer-info-col-text {
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 190%;
    color: var(--light-color);
}

.footer-info-col-text:not(:last-child) {
    margin-bottom: 55px;
}

.footer-box-link {
    display: block;
    color: var(--brand-color);
    transition: color .3s ease;
}

.footer-box-link:hover {
    color: #fff;
}

.footer-socials {
    text-align: right;
}

.footer-socials-item:not(:last-child) {
    margin-bottom: 20px;
}

.footer-socials-link path {
    transition: fill .3s ease;
}

.footer-socials-item:hover .footer-socials-link path {
    fill: white;
}
