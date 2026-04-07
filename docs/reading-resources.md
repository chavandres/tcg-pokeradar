## Foundation — Architecture Thinking

### "Fundamentals of Software Architecture" — Mark Richards & Neal Ford<br>

The best modern book on architecture patterns. Covers microservices, event-driven, and how to make architectural decisions. This is your primary reference for understanding why the system is shaped the way it is.<br>

### "Designing Data-Intensive Applications" — Martin Kleppmann<br>

Covers distributed systems, databases, event streams, and reliability at depth. The Redis, PostgreSQL, and event bus decisions in your architecture all have chapters here.<br>

## Event-Driven Architecture

### "Enterprise Integration Patterns" — Gregor Hohpe & Bobby Woolf

The canonical reference for messaging patterns including pub/sub, event buses, and message routing. Heavy but invaluable for understanding how your trade matching engine is designed.<br>

### Redis documentation — redis.io/docs

Specifically the pub/sub and streams sections. Free, practical, and directly maps to your event bus implementation.<br>

## Python Backend & FastAPI

### FastAPI official documentation — fastapi.tiangolo.com

### "Architecture Patterns with Python" — Harry Percival & Bob Gregory

## AI Integration
### Anthropic API documentation — docs.anthropic.com

Start here for the Vision API you'll use for card scanning. The messages API with image support is straightforward and well documented.

### "Building LLM-Powered Applications" — Valentina Alto

Practical guide to integrating LLMs into real production systems including RAG patterns and vision use cases.

## Geospatial & PostgreSQL
### PostGIS documentation — postgis.net/documentation

Free and comprehensive. Focus on the ST_DWithin and ST_Distance functions — these are the two queries that power your proximity matching.

### "PostgreSQL: Up and Running" — Regina Obe & Leo Hsu

Solid practical reference for PostgreSQL including PostGIS extensions.

## Kubernetes & Deployment
### "Kubernetes in Action" — Marko Luksa

The clearest book on Kubernetes for developers. Covers deployments, services, and scaling — everything you need to deploy this project.

### "The DevOps Handbook" — Gene Kim et al.

Covers CI/CD, pipelines, and deployment culture. Pairs well with your GitHub Actions setup.

## Suggested Reading Order

1. FastAPI docs — get building immediately
2. Architecture Patterns with Python — shapes how you structure the code
3. Designing Data-Intensive Applications — deepens your understanding of every data decision
4. Fundamentals of Software Architecture — elevates your architectural thinking
5. Everything else as needed when you hit that layer of the build
