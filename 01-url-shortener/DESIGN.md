# URL Shortener: Design Doc

> Write every section in your own words. Guiding questions are in comments; delete them as you answer.

## 1. Requirements
<!-- Functional: what must the system do? Non-functional: latency, availability, read/write ratio? What is OUT of scope for v1? -->

## 2. Estimates (back-of-envelope)
<!-- Writes/sec, reads/sec, storage over 5 years, and how many characters the short code needs. Show your math. -->

## 3. API
<!-- Endpoints, methods, request/response bodies, status codes (success and error). -->

## 4. Data Model
<!-- Table(s), columns, types, keys, indexes. Why does each index exist? -->

## 5. Short-Code Generation
<!-- Which option (hash / counter+base62 / key service) and WHY? What are the downsides, and what would you change at 100x scale? -->

## 6. Read Path & Caching
<!-- Walk through GET /{code} step by step. Which caching pattern, what TTL, 301 or 302, and why? What happens if Redis is down? -->
