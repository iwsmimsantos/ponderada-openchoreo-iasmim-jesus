# Atividade Ponderada - OpenChoreo

Repositório da atividade de instalação e validação do [OpenChoreo](https://openchoreo.dev) em ambiente local, utilizando o Quick Start na versão **v1.1.1**.

## Como navegar neste repositório

| O que procurar | Onde está |
|----------------|-----------|
| Documentação completa da atividade | [`docs/instalacao-openchoreo.md`](docs/instalacao-openchoreo.md) |
| Saídas de terminal (evidências) | [`docs/evidencias/`](docs/evidencias/) |
| Resumo e checklist de entrega | Este `README.md` |

**Caminho escolhido:** A — instalação completa via Quick Start (macOS + Docker Desktop, 10 CPUs, 7,7 GB RAM).

## Documentação principal

**[docs/instalacao-openchoreo.md](docs/instalacao-openchoreo.md)**

## Checklist de entrega

- [x] Repositório organizado (`README.md`, `docs/`, `docs/evidencias/`)
- [x] Documentação do processo em `docs/instalacao-openchoreo.md`
- [x] Evidências de execução em `docs/evidencias/`
- [x] URL da interface: `http://openchoreo.localhost:8080`
- [x] URL da aplicação de exemplo: `http://http-react-starter-development-default-cde5190f.openchoreoapis.localhost:19080`
- [x] Instalação completa com todos os componentes READY
- [x] Merge Request aberta (`docs/openchoreo` → `main`)

## Estrutura do repositório

```
.
├── README.md
└── docs/
    ├── instalacao-openchoreo.md        # Documentação da atividade
    └── evidencias/
        ├── print-01-recursos-docker.png
        ├── print-02-instalacao-sucesso.png
        ├── print-03-check-status.png
        ├── print-04-deploy-react-starter.png
        ├── print-05-kubectl-recursos.png
        ├── print-06-interface-openchoreo.png
        └── print-07-react-app-rodando.png
```

## Resumo dos resultados

| Etapa | Resultado |
|-------|-----------|
| Ambiente (macOS 26.3 + Docker Desktop) | Configurado |
| Instalação (`./install.sh --version v1.1.1`) | **Completa** — todos os componentes READY |
| Interface (`http://openchoreo.localhost:8080`) | Acessível |
| Deploy (`./deploy-react-starter.sh`) | **Publicado com sucesso** (HTTP 200) |
| URL da aplicação | `http://http-react-starter-development-default-cde5190f.openchoreoapis.localhost:19080` |

## Ambiente utilizado

- **SO:** macOS 26.3 (Apple Silicon — M4)
- **Runtime:** Docker Desktop 4.55.0
- **Docker Client:** 29.5.1
- **Recursos Docker:** 10 CPUs, ~7,7 GB de memória

## Autora

Iasmim Jesus - Inteli
