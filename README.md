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

## Проекты

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/leedcee/restaurant-delivery-microservices">Restaurant Delivery Platform</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Go-0A3069?style=flat-square&logo=go&logoColor=white" alt="Go" />
        <img src="https://img.shields.io/badge/PostgreSQL-1158C7?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/React-1F6FEB?style=flat-square&logo=react&logoColor=white" alt="React" />
      </p>
      <p><strong>Платформа автоматизации заказов и доставки еды</strong>, которую я довожу от дипломного проекта до эксплуатационно готового продукта.</p>
      <ul>
        <li>транзакционный заказ, optimistic locking и защита от overselling;</li>
        <li>transactional outbox, retry/backoff, dead letter и безопасный replay;</li>
        <li>SSE realtime с heartbeat и восстановлением через Last-Event-ID;</li>
        <li>Prometheus, Grafana, Loki, Tempo, OpenTelemetry и ClickHouse;</li>
        <li>E2E, resilience, encrypted backup/restore и security gates в CI.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/leedcee/uplinkwatch">UplinkWatch</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Go-0A3069?style=flat-square&logo=go&logoColor=white" alt="Go" />
        <img src="https://img.shields.io/badge/Prometheus-1158C7?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
        <img src="https://img.shields.io/badge/Grafana-1F6FEB?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
      </p>
      <p><strong>Локальный монитор доступности сайтов</strong>, который проверяет реальный сетевой путь Windows-компьютера и локализует этап сбоя.</p>
      <ul>
        <li>поэтапные DNS, TCP, TLS, HTTP и content checks;</li>
        <li>локальная диагностика, JSON API, health endpoint и dashboard;</li>
        <li>privacy-conscious discovery сайтов из пяти браузеров;</li>
        <li>Prometheus, Grafana, Alertmanager, алерты, runbooks и SLO 99,9%;</li>
        <li>Windows/Linux CI и автоматические Windows-релизы с SHA-256.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="bottom">
      <p align="center">
        <a href="https://github.com/leedcee/restaurant-delivery-microservices"><img src="https://img.shields.io/badge/РЕПОЗИТОРИЙ-0A3069?style=for-the-badge&logo=github&logoColor=white" alt="Репозиторий Restaurant Delivery" /></a>
        <a href="https://github.com/leedcee/restaurant-delivery-microservices/blob/main/api/openapi.yaml"><img src="https://img.shields.io/badge/OPENAPI-155EEF?style=for-the-badge&logo=swagger&logoColor=white" alt="OpenAPI" /></a>
        <a href="https://github.com/leedcee/restaurant-delivery-microservices/tree/main/docs"><img src="https://img.shields.io/badge/ДОКУМЕНТАЦИЯ-1F6FEB?style=for-the-badge&logo=diagramsdotnet&logoColor=white" alt="Документация Restaurant Delivery" /></a>
      </p>
    </td>
    <td width="50%" valign="bottom">
      <p align="center">
        <a href="https://github.com/leedcee/uplinkwatch"><img src="https://img.shields.io/badge/РЕПОЗИТОРИЙ-0A3069?style=for-the-badge&logo=github&logoColor=white" alt="Репозиторий UplinkWatch" /></a>
        <a href="https://github.com/leedcee/uplinkwatch/blob/main/docs/images/local-dashboard.png"><img src="https://img.shields.io/badge/DASHBOARD-155EEF?style=for-the-badge&logo=grafana&logoColor=white" alt="UplinkWatch dashboard" /></a>
        <a href="https://github.com/leedcee/uplinkwatch/tree/main/docs/runbooks"><img src="https://img.shields.io/badge/RUNBOOKS-1F6FEB?style=for-the-badge&logo=bookstack&logoColor=white" alt="UplinkWatch runbooks" /></a>
        <a href="https://github.com/leedcee/uplinkwatch/releases"><img src="https://img.shields.io/badge/RELEASES-388BFD?style=for-the-badge&logo=githubactions&logoColor=white" alt="UplinkWatch releases" /></a>
      </p>
    </td>
  </tr>
</table>

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
