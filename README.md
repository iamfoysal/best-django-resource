

---

# Awesome Django [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> A carefully curated list of the most useful packages, tools, and resources for Django developers. Whether you're building a simple web app or a complex enterprise-grade system, this guide will help you find the best tools to make Django development more efficient and enjoyable.

---

## Table of Contents
- [Essentials](#essentials)
- [Admin Interface](#admin-interface)
- [Authentication](#authentication)
- [API](#api)
- [Database and ORM](#database-and-orm)
- [Forms](#forms)
- [Security](#security)
- [Testing](#testing)
- [Email](#email)
- [File and Media Handling](#file-and-media-handling)
- [Internationalization and Localization](#internationalization-and-localization)
- [Search](#search)
- [Caching](#caching)
- [Performance](#performance)
- [Monitoring and Logging](#monitoring-and-logging)
- [Job Queue & Background Tasks](#job-queue--background-tasks)
- [Third-party Integration](#third-party-integration)
- [CMS & E-commerce](#cms--e-commerce)
- [Deployment](#deployment)
- [Miscellaneous](#miscellaneous)
- [Resources](#resources)
- [Learning Resources](#learning-resources)

---

## Essentials
- **[Django](https://www.djangoproject.com/)** - A high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **[Django REST Framework](https://www.django-rest-framework.org/)** - A powerful and flexible toolkit for building Web APIs with Django.
- **[Channels](https://github.com/django/channels)** - Asynchronous support for Django to handle WebSockets and background tasks.

## Admin Interface
- **[django-grappelli](https://github.com/sehmaschine/django-grappelli)** - A sleek and modern skin for the Django admin interface with additional features.
- **[django-suit](https://github.com/darklow/django-suit)** - A customizable and responsive admin theme for Django.

## Authentication
- **[django-allauth](https://github.com/pennersr/django-allauth)** - Comprehensive user registration, management, and social authentication.
- **[django-oauth-toolkit](https://github.com/jazzband/django-oauth-toolkit)** - OAuth2 provider for Django to handle third-party app authorization.
- **[django-two-factor-auth](https://github.com/Bouke/django-two-factor-auth)** - Complete two-factor authentication for Django via SMS or tokens.

## API
- **[Django REST Framework](https://www.django-rest-framework.org/)** - Build Web APIs using Django's models and views in a RESTful way.
- **[graphene-django](https://github.com/graphql-python/graphene-django)** - Django integration for building GraphQL APIs.
- **[django-tastypie](https://github.com/django-tastypie/django-tastypie)** - A framework for creating RESTful APIs in Django.
- **[drf-spectacular](https://github.com/tfranzel/drf-spectacular)** - OpenAPI 3.0 (Swagger) generation for Django REST Framework with minimal setup.

## Database and ORM
- **[django-environ](https://github.com/joke2k/django-environ)** - Handles environment variables and settings management in Django projects.
- **[django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar)** - A set of configurable panels for viewing debug information about Django requests and SQL queries.
- **[django-mptt](https://github.com/django-mptt/django-mptt)** - Provides utilities for creating tree-like structures in your database models.
- **[django-sql-explorer](https://github.com/groveco/django-sql-explorer)** - A SQL query builder and viewer for your Django models.

## Forms
- **[django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms)** - The best way to build and manage Django forms in a DRY (Don't Repeat Yourself) way.
- **[django-bootstrap-v5](https://github.com/zostera/django-bootstrap-v5)** - Bootstrap 5 integration with Django forms.

## Security
- **[django-axes](https://github.com/jazzband/django-axes)** - Prevents brute-force login attempts by tracking failed authentication attempts.
- **[django-guardian](https://github.com/django-guardian/django-guardian)** - Adds per-object permissions for Django's built-in authentication system.
- **[django-secure](https://github.com/carljm/django-secure)** - Enhances security in Django with middleware that enforces SSL, HSTS, and other settings.
- **[django-security](https://github.com/sdelements/django-security)** - Additional security features like headers and secure cookies.

## Testing
- **[pytest-django](https://github.com/pytest-dev/pytest-django)** - A plugin for using Pytest in Django projects.
- **[factory-boy](https://github.com/FactoryBoy/factory_boy)** - A flexible factory library for generating test data.
- **[django-nose](https://github.com/jazzband/django-nose)** - Extends Django’s test suite using the Nose test runner.

## Email
- **[django-anymail](https://github.com/anymail/django-anymail)** - A unified API for sending email via various transactional email services.
- **[django-templated-email](https://github.com/vintasoftware/django-templated-email)** - Send beautifully templated emails using Django’s templating engine.

## File and Media Handling
- **[django-storages](https://github.com/jschneier/django-storages)** - A collection of storage backends for Django, including Amazon S3 and Google Cloud Storage.
- **[django-cleanup](https://github.com/un1t/django-cleanup)** - Automatically deletes old files when updating a `FileField` or `ImageField` in Django.
- **[django-versatileimagefield](https://github.com/WGBH/django-versatileimagefield)** - Powerful image processing and dynamic image generation in Django.

## Internationalization and Localization
- **[django-modeltranslation](https://github.com/deschler/django-modeltranslation)** - Translates Django model fields into multiple languages.
- **[django-parler](https://github.com/django-parler/django-parler)** - Easy multilingual support for Django models.

## Search
- **[django-haystack](https://github.com/django-haystack/django-haystack)** - A powerful search framework that integrates with various search engines like Elasticsearch and Solr.
- **[wagtail](https://github.com/wagtail/wagtail)** - Built-in search with a highly extensible CMS.

## Caching
- **[django-redis](https://github.com/jazzband/django-redis)** - A full-featured Redis cache backend for Django.
- **[django-cacheops](https://github.com/Suor/django-cacheops)** - ORM-level caching with automatic invalidation, using Redis.

## Performance
- **[django-silk](https://github.com/jazzband/django-silk)** - Live profiling, SQL query analysis, and HTTP request profiling for Django.
- **[django-compressor](https://github.com/django-compressor/django-compressor)** - Compresses linked and inline JavaScript or CSS into a single cached file.
- **[django-async-orm](https://github.com/gorilla-xyz/django-async-orm)** - Asynchronous ORM operations to improve performance.

## Monitoring and Logging
- **[sentry-python](https://github.com/getsentry/sentry-python)** - Sentry integration for error tracking and monitoring.
- **[django-watchman](https://github.com/mwarkentin/django-watchman)** - Monitoring endpoints for checking system health in Django.

## Job Queue & Background Tasks
- **[django-celery-beat](https://github.com/celery/django-celery-beat)** - A Celery extension for scheduling periodic tasks in Django.
- **[django-background-tasks](https://github.com/arteria/django-background-tasks)** - Lightweight background task runner for Django.

## Third-party Integration
- **[django-payments](https://github.com/django-oscar/django-payments)** - A universal payment solution for Django e-commerce applications.
- **[django-social-auth-app](https://github.com/python-social-auth/social-app-django)** - Easy social authentication with OAuth for platforms like Facebook, Twitter, and Google.

## CMS & E-commerce
- **[django-oscar](https://github.com/django-oscar/django-oscar)** - A comprehensive e-commerce framework built on Django.
- **[wagtail](https://github.com/wagtail/wagtail)** - A powerful and flexible open-source CMS for Django.

## Deployment
- **[PythonAnywhere](https://www.pythonanywhere.com/)** - An easy-to-use cloud platform to host Django projects.
- **[Railway](https://railway.app/)** - A flexible platform to deploy and scale Django applications with Git integration.
- **[Heroku](https://www.heroku.com/)** - A popular cloud platform that allows you to deploy, manage

## Miscellaneous
- **[django-extensions](https://github.com/django-extensions/django-extensions)** - A collection of custom extensions for the Django Framework.
- **[django-statsd](https://github.com/etsy/django-statsd)** - StatsD integration for Django.
---
## Resources
- **[Official Django Documentation](https://docs.djangoproject.com/en/stable/)** - Comprehensive guide and documentation for Django.
- **[Two Scoops of Django](https://www.twoscoopspress.com/collections/django/products/two-scoops-of-django-3-x)** - Best practices for Django development.
- **[Django Packages](https://djangopackages.org/)** - A directory of reusable apps, sites, tools, and more.
- **[Django REST Framework Docs](https://www.django-rest-framework.org/)** - Full documentation for Django REST Framework.
- **[Django Deployment Checklist](https://docs.djangoproject.com/en/stable/howto/deployment/checklist/)** - An essential checklist for deploying Django projects.
- **[Real Python Django Tutorials](https://realpython.com/tutorials/django/)** - Comprehensive tutorials and guides on Django development.
- **[TestDriven.io](https://testdriven.io/courses/)** - Paid courses and tutorials on Django with a focus on Test-Driven Development (TDD).
- **[Simple is Better Than Complex](https://simpleisbetterthancomplex.com/)** - Useful Django tutorials and guides for both beginners and advanced developers.
- **[Wagtail CMS Documentation](https://docs.wagtail.org/en/stable/)** - Full documentation for Wagtail CMS.
---
