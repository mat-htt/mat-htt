<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Matsvei Vaitsiakhovich — Python Backend Developer" src="assets/header-light.svg" width="100%">
</picture>

<p>
  <a href="mailto:matsvei.v@gmail.com"><img src="https://img.shields.io/badge/Email-matsvei.v%40gmail.com-555?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://t.me/mt_voyt"><img src="https://img.shields.io/badge/Telegram-%40mt__voyt-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <img src="https://img.shields.io/badge/Open%20to-backend%20%2F%20full--stack%20roles-2bb7a6?style=flat-square" alt="Open to work">
  <img src="https://img.shields.io/badge/English-B2-7c5cff?style=flat-square" alt="English B2">
</p>

I build backend services and REST APIs with Django and DRF, and take features end to end when they need a React frontend. Right now I lead the development team of a beauty-salon booking platform: planning tasks, reviewing pull requests and writing a large part of the backend. At hackathons I work on backend services, ML and computer vision parts of the product.

## Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=python,django,fastapi,postgres,sqlite,redis,rabbitmq,docker,nginx,git,github,linux&perline=12" alt="Python, Django, FastAPI, PostgreSQL, SQLite, Redis, RabbitMQ, Docker, Nginx, Git, GitHub, Linux">
</p>
<p>
  <img src="https://skillicons.dev/icons?i=react,ts,js,tailwind,html,css,vite,figma,postman,pycharm&perline=12" alt="React, TypeScript, JavaScript, Tailwind, HTML, CSS, Vite, Figma, Postman, PyCharm">
</p>

## Featured projects

### Beauty Booking &nbsp;·&nbsp; [API](https://github.com/mat-htt/beauty-single-backend) · [Web](https://github.com/mat-htt/beauty-booking-frontend)

Website for a beauty salon with online booking: service catalog, masters' schedules, client and master accounts, reviews, promotions and an admin panel. Team project — I lead the team of 17 and own most of the backend.

- Booking rules: slot limits, no booking in the past, confirmation by link, loyalty bonuses
- Auth and accounts for clients and masters, masters' social links, promotions API
- Whole project starts with one `docker compose up`

<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"> <img src="https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white" alt="DRF"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/Tailwind-0F172A?style=flat-square&logo=tailwindcss&logoColor=38BDF8" alt="Tailwind"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">

<img src="assets/beauty-booking.gif" alt="Beauty Booking: home page and online booking flow" width="100%">

### Family in Moby &nbsp;·&nbsp; <sub>private team repo, code on request</sub>

MTBank Hackathon 2026. Family banking inside the bank's mobile app: parents manage their kids' money, set limits and approve requests; kids save for goals and learn through mini-lessons.

- Backend: 12 FastAPI microservices behind a gateway, events over RabbitMQ, PostgreSQL per service
- ML service: anti-fraud scoring of kids' payments, merchant auto-categorization, "will the money last until the end of the week" forecast
- Frontend in React + TypeScript, designed to fit the Moby app

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">

<p align="center"><img src="assets/family-in-moby.gif" alt="Family in Moby: limits, savings and family screens" width="80%"></p>

### ScribeTrace &nbsp;·&nbsp; <sub>private team repo, code on request</sub>

MTS Hackathon, product name Dogovor.AI. Platform that transcribes calls and meetings, writes a summary and pulls out decisions and tasks with owners and deadlines; every processing stage is visible live.

- Worked on the backend and on connecting the speech-to-text and summary models to the pipeline
- Built the web client: upload, history, live progress over WebSocket, transcript and summary views

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ"> <img src="https://img.shields.io/badge/WebSocket-555?style=flat-square" alt="WebSocket"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">

<img src="assets/scribetrace-demo.gif" alt="ScribeTrace: sign-in, records, client card, calendar, microphone, AI models" width="100%">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/scribetrace-dark.svg">
  <img alt="ScribeTrace processing pipeline" src="assets/scribetrace-light.svg" width="100%">
</picture>

### Ustno &nbsp;·&nbsp; <sub>private team repo, code on request</sub>

<table>
<tr>
<td width="62%" valign="top">
<p>Hackathon project, November 2026. Live checking of oral answers at history lessons: a student retells a paragraph, speech is recognized in real time and compared with the textbook by terms, dates and meaning. The teacher sees the accuracy score and which parts students miss.</p>
<ul>
<li>Speech service on FastAPI over WebSocket: Silero VAD, speaker filtering with ReDimNet, GigaAM-v3 speech-to-text</li>
<li>Scoring on Django: lemmatization, fuzzy term matching, sentence-level semantic similarity (BERTA)</li>
<li>React web app for teachers and students, Docker Compose, Nginx, deploy via GitHub Actions and Cloudflare Tunnel</li>
<li>I wrote most of the platform</li>
</ul>
<p><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"> <img src="https://img.shields.io/badge/WebSocket-555?style=flat-square" alt="WebSocket"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"></p>
</td>
<td width="38%" valign="top" align="center">
<img src="assets/ustno.gif" alt="Ustno: live answer, accuracy score, terms and dates" width="260">
</td>
</tr>
</table>

### Where is the truck — 3D tracking &nbsp;·&nbsp; [repo](https://github.com/mat-htt/3dtracking-absolute)

Peleng hackathon, November 2026. Online 3D position of a moving truck from five calibrated cameras: detection and segmentation in each camera, rays and triangulation, fitting of the truck's CAD model, Kalman filtering. Result on the test sequence: MAE 2.46 m with an answer on every frame.

- My part: single-camera "cab ray" before the first multi-camera fix (first-second error 5.0 m → 1.7 m) and gap filling when the tracker loses the truck in dust or occlusions
- Input parser for new data, metrics without ground truth, detector fine-tuning, demo video

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"> <img src="https://img.shields.io/badge/YOLO-111?style=flat-square" alt="YOLO"> <img src="https://img.shields.io/badge/SAM_2-0467DF?style=flat-square&logo=meta&logoColor=white" alt="SAM 2"> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">

<img src="assets/peleng-tracking.gif" alt="Top view with ground truth and online 3D track, five camera feeds" width="100%">

## More projects

<table>
<tr>
<td width="50%" valign="top">

<b>Sad &amp; Stroy</b> — online store for tools and garden equipment
<p>Catalog with categories, tags and price filters, product variants with their own SKU, price and stock, cart and checkout, favorites, profile with order history, dark theme. Demo catalog loads with one command.</p>

<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"> <img src="https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white" alt="DRF"> <img src="https://img.shields.io/badge/JWT-555?style=flat-square" alt="JWT"> <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/Tailwind-0F172A?style=flat-square&logo=tailwindcss&logoColor=38BDF8" alt="Tailwind">

<img src="assets/sad-stroy.gif" alt="Sad & Stroy: catalog, product variants, cart" width="100%">

</td>
<td width="50%" valign="top">

<b>Ў Нескаладовае</b> — discount store for tools and repair goods
<p>Catalog with categories, manufacturers, sorting and pagination, related products, JWT registration, cart and checkout that turns the cart into an order. Swagger docs for the whole API.</p>

<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"> <img src="https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white" alt="DRF"> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black" alt="Swagger"> <img src="https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">

<img src="assets/neskladovae.gif" alt="Neskaladovae: catalog, filters, cart" width="100%">

</td>
</tr>
</table>

## Experience

**Team Lead / Backend Developer** — beauty booking platform · *present*<br>
Lead a team of 17: task planning, code review on GitHub, regular syncs. Backend on Django/DRF: booking logic, authentication for clients and masters, promotions API, Docker setup.

**Full-Stack Developer** — [CourseHub](https://coursehub.it.com), online learning platform · *2025*<br>
Joined after the internship and worked on the product: navigation bar, settings page with theme switching, mobile layout, video player built from Figma designs in React and connected to the DRF backend. Commercial code, not public.

**Telegram bots & Mini Apps** — commercial projects · *until 2026*<br>
Bots and mini apps on aiogram.

**Education** — Minsk State Radio Engineering College, Information Systems Development and Maintenance *(in progress)*

**Связь:** [matsvei.v@gmail.com](mailto:matsvei.v@gmail.com) · Telegram [@mt_voyt](https://t.me/mt_voyt)
---

<details>
<summary><b>На русском</b></summary>
<br>

**Python backend-разработчик** · Django · DRF · PostgreSQL · Минск

Пишу бэкенд и REST API на Django и DRF, при необходимости закрываю задачу целиком вместе с фронтендом на React. Сейчас руковожу командой разработки платформы онлайн-записи для салона красоты: ставлю задачи, делаю ревью pull request'ов и пишу значительную часть бэкенда. На хакатонах занимаюсь бэкендом и ML-частью продукта.

**Проекты**
- **Beauty Booking** — сайт салона красоты с онлайн-записью к мастерам, кабинетами клиента и мастера, отзывами и акциями. Django/DRF + React, запуск через Docker Compose. Командный проект, я тимлид.
- **«Семья в Moby»** — хакатон МТБанка 2026. Семейный банкинг внутри приложения банка: 12 микросервисов на FastAPI, RabbitMQ, PostgreSQL; ML-сервис (антифрод-скоринг, автокатегоризация трат, прогноз «хватит ли денег до конца недели»); фронт на React + TypeScript.
- **ScribeTrace** — хакатон МТС. Расшифровка аудио и видео с автоматическим конспектом: бэкенд, подключение моделей распознавания речи и саммари, веб-клиент с прогрессом в реальном времени.
- **«Сад & Строй»** и **«Ў Нескаладовае»** — интернет-магазины инструмента на Django REST Framework + React: каталог с фильтрами, варианты товаров, корзина, заказы, JWT.
- **«Устно»** — хакатон, ноябрь 2026. Живая проверка устных ответов на уроках истории: распознавание речи (FastAPI, WebSocket, GigaAM), оценка по терминам, датам и смыслу (Django), веб-приложение на React.
- **«Где грузовик»** — хакатон Пеленга, ноябрь 2026. 3D-трекинг грузовика по пяти камерам: YOLO, SAM 2, триангуляция, фильтр Калмана; MAE 2,46 м.
- **CourseHub** — образовательная платформа: навигация, настройки с темами, адаптив, видеоплеер (React + DRF). Коммерческий код, не публикуется.

**Связь:** [matsvei.v@gmail.com](mailto:matsvei.v@gmail.com) · Telegram [@mt_voyt](https://t.me/mt_voyt)

</details>
