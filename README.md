# UmbHost.GreenStack.Umbraco (v13)

A dotnet new template for Umbraco 13 (LTS) preconfigured for [GreenStack](https://umbhost.net/sustainable-cloud-hosting/modern-umbraco-hosting) hosting.

> **Note:** This is the v13 LTS branch. For Umbraco 17, see the [main branch](https://github.com/UmbHost/UmbHost.GreenStack.Umbraco/tree/main).

## Installation

```bash
dotnet new install UmbHost.GreenStack.Umbraco::13.*
```

## Usage

```bash
dotnet new greenstack-umbraco -n MyProject
```

This creates a new Umbraco 13 project with:

- Forwarded headers middleware for Traefik proxy
- HTTPS runtime validator removed (SSL terminated by GreenStack)
- Data protection keys persisted to `/app/keys` in production
- Multi-stage Dockerfile exposing port 8080
- Docker launch profile (HTTP)

## Getting started

Follow the [Getting Started with Umbraco 13 on GreenStack](https://umbhost.net/gb/blog/2026/03/getting-started-with-umbraco-13-on-greenstack-with-github) guide.

## Source

The template content comes from [GreenStack.Umbraco-v13](https://github.com/UmbHost/GreenStack.Umbraco-v13), which is also available as a GitHub template repository.

## GreenStack

- [Purchase GreenStack hosting](https://umbhost.net/sustainable-cloud-hosting/modern-umbraco-hosting)
- [GreenStack documentation](https://my.umbhost.net/knowledgebase/17/GreenStack)
- [GreenStack CI/CD samples](https://github.com/UmbHost/GreenStack.CICD.Samples)

## License

MIT
