# Avesta Framework

> A lightweight, Laravel-inspired MVC framework built from scratch — currently undergoing a full rebuild.

---

## 🔄 Status: Full Rebuild in Progress

The original Avesta is functional, but after significant growth in experience and knowledge, I've decided to rebuild it from the ground up.

The goal is not just a framework — it's a deeper understanding of how modern PHP frameworks actually work under the hood: routing, dependency injection, ORM, middleware, and more.

---

## What is Avesta?

Avesta is a lightweight PHP MVC framework inspired by Laravel's elegance, but intentionally minimal. It's built for developers who want to understand the internals of a framework rather than just use one.

**Core philosophy:**
- No magic. Everything is explicit and traceable.
- Lightweight by design — no unnecessary dependencies.
- Educational first, production-ready second.

---

## What's Being Rebuilt

| Component | Old Version | Rebuild Plan |
|---|---|---|
| Router | Basic | Regex-based, named routes, middleware support |
| ORM | Simple query builder | Active Record pattern with relationships |
| Migrations | Incomplete | Full up/down migrations with schema builder |
| Container | None | PSR-11 compatible DI container |
| Templating | Basic | Blade-inspired with template inheritance |
| CLI | None | Artisan-inspired command runner |

---

## Why Rebuild Instead of Patch?

Writing a framework once teaches you how frameworks work.  
Rebuilding it teaches you **why** they work that way.

The first version answered *"can I build this?"*  
The rebuild answers *"how should this actually be built?"*

---

## Roadmap

- [ ] Core HTTP layer (Request, Response, Router)
- [ ] Service Container (DI)
- [ ] Middleware pipeline
- [ ] Database abstraction & ORM
- [ ] Migration system
- [ ] Templating engine
- [ ] CLI tool
- [ ] Documentation

---

## Name

**Avesta** is the name of one of the oldest surviving texts of human civilization — a Zoroastrian scripture that guided generations. The name was chosen as a reminder that good foundations outlast everything built on top of them.

---

## Contact

- Telegram: [@Octawian](https://t.me/Octawian)
- Email: arashebi777@gmail.com

---

![building](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExNXMwNjlseWJtaWZzeGs0cmJnNWw3eXpzdDExdzV4MXljcXAxbjVnaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/MVuTi2LcjWTew/giphy.gif)

*Good code is not written — it's rewritten.*
