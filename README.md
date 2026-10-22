<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Константин Дьяков — Go Backend Developer" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1200&color=58A6FF&center=true&vCenter=true&width=760&lines=Building+reliable+backend+systems;Clean+architecture+%C2%B7+Distributed+systems+%C2%B7+Observability;From+university+project+to+production-ready+product" alt="Typing animation" />
</p>

<p align="center">
  <a href="https://t.me/leedcee"><img src="https://img.shields.io/badge/Telegram-0B74DE?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="mailto:i.waytodied.i@gmail.com"><img src="https://img.shields.io/badge/Email-155EEF?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/leedcee/leedcee/blob/main/assets/resume.pdf"><img src="https://img.shields.io/badge/Резюме-0A3069?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Резюме" /></a>
</p>

## Обо мне

Я **Константин**, Go backend-разработчик. Проектирую API и сервисы, которые остаются предсказуемыми под нагрузкой, переживают сбои зависимостей и дают достаточно телеметрии, чтобы проблему можно было найти до пользователя.

Учусь на направлении «Информатика и вычислительная техника» в СамГТУ. Учебные проекты для меня не заканчиваются на работающем happy path: я довожу их до миграций, CI, E2E, security gates, метрик, трассировки и проверяемого восстановления данных.

<table>
  <tr>
    <td width="33%" valign="top"><strong>Architecture</strong><br><br>Модульные границы, REST и event contracts, state machines, идемпотентность.</td>
    <td width="33%" valign="top"><strong>Reliability</strong><br><br>PostgreSQL, transactional outbox, retry/backoff, recovery и resilience tests.</td>
    <td width="33%" valign="top"><strong>Observability</strong><br><br>Prometheus, Grafana, Loki, Tempo, OpenTelemetry и ClickHouse.</td>
  </tr>
</table>

## Технологии

<h3 align="center">Backend & Data</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=go,postgres&theme=dark" alt="Go и PostgreSQL" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/chi-0A3069?style=flat-square" alt="chi" />
  <img src="https://img.shields.io/badge/pgx-1158C7?style=flat-square" alt="pgx" />
  <img src="https://img.shields.io/badge/REST-1F6FEB?style=flat-square" alt="REST" />
  <img src="https://img.shields.io/badge/SSE-388BFD?style=flat-square" alt="SSE" />
  <img src="https://img.shields.io/badge/OpenAPI-58A6FF?style=flat-square" alt="OpenAPI" />
  <img src="https://img.shields.io/badge/ClickHouse-79C0FF?style=flat-square&logo=clickhouse&logoColor=081426" alt="ClickHouse" />
</p>

<h3 align="center">Frontend</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,ts,vite,nginx&theme=dark" alt="React, TypeScript, Vite и Nginx" />
</p>

<h3 align="center">Infrastructure, Observability & Quality</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,githubactions,linux,grafana,prometheus&theme=dark" alt="Docker, GitHub Actions, Linux, Grafana и Prometheus" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/OpenTelemetry-0A3069?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
  <img src="https://img.shields.io/badge/Loki-1158C7?style=flat-square&logo=grafana&logoColor=white" alt="Loki" />
  <img src="https://img.shields.io/badge/Tempo-1F6FEB?style=flat-square&logo=grafana&logoColor=white" alt="Tempo" />
  <img src="https://img.shields.io/badge/Playwright-388BFD?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/E2E-58A6FF?style=flat-square" alt="E2E" />
</p>

## Главный проект

<a href="https://github.com/leedcee/restaurant-delivery-microservices">
  <img align="right" width="42%" src="https://github-readme-stats.vercel.app/api/pin/?username=leedcee&repo=restaurant-delivery-microservices&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&text_color=C9D1D9&description_lines_count=3" alt="Restaurant Delivery Platform" />
</a>

### [Restaurant Delivery Platform](https://github.com/leedcee/restaurant-delivery-microservices)

Платформа автоматизации заказов и доставки еды, которую я последовательно довожу от дипломного проекта до эксплуатационно готового продукта.

- Go API, React frontend и отдельный demo restaurant;
- PostgreSQL как источник истины, миграции и optimistic locking;
- идемпотентное создание заказов и защита от overselling;
- transactional outbox, retry/backoff, dead letter и replay;
- SSE с heartbeat и восстановлением через `Last-Event-ID`;
- Prometheus, Grafana, Loki, Tempo, OpenTelemetry и ClickHouse;
- unit, race, backend E2E, Playwright, resilience и restore tests;
- dependency, secret, configuration и OCI image scanning в CI.

<p>
  <a href="https://github.com/leedcee/restaurant-delivery-microservices#readme"><img src="https://img.shields.io/badge/README-0A3069?style=for-the-badge&logo=github&logoColor=white" alt="README проекта" /></a>
  <a href="https://github.com/leedcee/restaurant-delivery-microservices/blob/main/api/openapi.yaml"><img src="https://img.shields.io/badge/OpenAPI-155EEF?style=for-the-badge&logo=swagger&logoColor=white" alt="OpenAPI" /></a>
  <a href="https://github.com/leedcee/restaurant-delivery-microservices/tree/main/docs"><img src="https://img.shields.io/badge/Architecture-1F6FEB?style=for-the-badge&logo=diagramsdotnet&logoColor=white" alt="Архитектура" /></a>
</p>

<br clear="right" />

## GitHub-активность

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=leedcee&show_icons=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&text_color=C9D1D9&ring_color=58A6FF&locale=ru" alt="GitHub stats" />
  <img width="49%" src="https://streak-stats.demolab.com?user=leedcee&hide_border=true&background=0D1117&ring=58A6FF&fire=1F6FEB&currStreakLabel=58A6FF&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B949E&locale=ru" alt="GitHub streak" />
</p>

## Связаться

Открыт к стажировке, junior-позиции и совместной разработке на Go. Особенно интересны backend, распределённые системы, надёжность и observability.

<p align="center">
  <strong>Написать:</strong>
  <a href="https://t.me/leedcee">Telegram</a> ·
  <a href="mailto:i.waytodied.i@gmail.com">Email</a> ·
  <a href="https://github.com/leedcee/leedcee/blob/main/assets/resume.pdf">Резюме</a>
</p>

<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="Синий декоративный footer" />
</p>
