# Spring Boot REST HATEOAS (Hypermedia-Driven Greeting API)

This project is a small Spring Boot REST API that demonstrates **HATEOAS** (Hypermedia as the Engine of Application State) using **Spring HATEOAS**.

It is based on the official Spring guide: **“Building a Hypermedia-Driven RESTful Web Service”**.

## What it does
The service exposes a single endpoint:

- `GET /greeting`
- Optional query param: `name`

It returns JSON containing:
- `content` (the greeting message)
- `_links.self.href` (a hypermedia link pointing back to the same resource)

The guide uses **HAL-style** hypermedia (`_links`).

---

## Tech Stack
- Java 17+
- Spring Boot
- Spring Web
- Spring HATEOAS
- Maven
