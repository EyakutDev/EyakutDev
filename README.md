<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./banner-mobile-dark.svg">
  <source media="(max-width: 600px)" srcset="./banner-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./banner-dark.svg">
  <img alt="Enver Yakut — a request travels from the client through the API to the server and the database, and the response comes back" src="./banner-light.svg" width="100%">
</picture>

### `GET /enver`

```json
{
  "name": "Enver Yakut",
  "role": "Backend & Mobile Developer",
  "focus": ["APIs", "databases", "real-time servers", "mobile apps"],
  "status": "Final-year student, open to internships"
}
```

### `GET /projects`

| Project | What I built | Stack |
| --- | --- | --- |
| [**Tomar**](https://github.com/EyakutDev/tomar) · [live](https://tomar.169-58-194-231.sslip.io/) | API + database + web interface | Fastify · PostgreSQL · Docker |
| [**Küçük Konuşma**](https://github.com/EyakutDev/kucuk-konusma) · [live](https://kucukkonusma.169-58-194-231.sslip.io) | Real-time server + database + web | Node.js · Socket.IO · PostgreSQL |
| [**Sosyo-Bel**](https://github.com/EyakutDev/sosyo-bel) | API + database + mobile app, KPS identity check | ASP.NET Core · SQL Server · Flutter |
| [**Paydaş**](https://github.com/EyakutDev/paydas_repo) | Backend: data model + services (team) | Firebase · Flutter |

### `GET /skills`

`Go` · `ASP.NET Core (C#)` · `Node.js` · `REST API` · `Socket.IO` · `PostgreSQL` · `SQL Server` · `Firebase` · `Docker` · `Flutter`

### `GET /cv`

[Türkçe](https://enveryakut.com/assets/cv.pdf) · [English](https://enveryakut.com/assets/cv-en.pdf)

### `POST /contact`

[enveryakut.com](https://enveryakut.com) · [yakutenver@gmail.com](mailto:yakutenver@gmail.com)

### `DELETE /enver`

```http
HTTP/1.1 403 Forbidden
```
