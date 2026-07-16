---
layout: post
title: Job Scraper Python
description: Scraper de ofertas de empleo en Python que consulta Indeed y LinkedIn usando JobSpy, filtra resultados por búsqueda, antigüedad y país, elimina duplicados y guarda los datos en SQLite y CSV.
---

## [🐍 Job Scraper Python](https://github.com/facumedero/job-scraper-python)

## Job Scraper Python

============
Scraper de ofertas de empleo en Python que utiliza [JobSpy](https://github.com/speedyapply/JobSpy) para consultar múltiples plataformas de búsqueda de empleo (actualmente Indeed y LinkedIn), filtrando por término de búsqueda, antigüedad de la publicación y país. Los resultados se consolidan en un único DataFrame, se eliminan duplicados y se almacenan tanto en una base de datos SQLite como en un archivo CSV.

## Características

- Búsqueda simultánea en múltiples sitios de empleo (Indeed, LinkedIn)
- Filtrado por antigüedad de la publicación (`hours_old`) y país
- Eliminación automática de duplicados por ID de oferta
- Exportación a SQLite (`jobs.db`) y CSV (`jobs.csv`)
- CI/CD con GitHub Actions (lint, tests y scraping automatizado)
- Validación automática de código con `pre-commit` + `ruff` antes de cada commit

## Requisitos

- Python 3.11+ (recomendado; evitar 3.14 por posibles incompatibilidades con numpy/pandas)

## 📬 Contact & Links

Find all of my socials, projects, and full resume here:

**[🌐 Linktree & Portfolio](https://linktr.ee/facundomedero)**
  