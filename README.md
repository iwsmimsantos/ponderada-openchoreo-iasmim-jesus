# Atividade Ponderada - OpenChoreo

Repositório da atividade de instalação e validação do [OpenChoreo](https://openchoreo.dev) em ambiente local, utilizando o Quick Start na versão **v1.1.1**.

## Como navegar neste repositório

| O que procurar | Onde está |
|----------------|-----------|
| Documentação completa da atividade | [`docs/instalacao-openchoreo.md`](docs/instalacao-openchoreo.md) |
| Prints e saídas de terminal | [`docs/evidencias/`](docs/evidencias/) |
| Resumo e checklist de entrega | Este `README.md` |

**Caminho escolhido:** A — Instalação completa (máquina com Docker ≥ 4 GB RAM e ≥ 2 CPUs).

## Documentação principal

A documentação técnica cobre ambiente, instalação, validação da interface, deploy da aplicação de exemplo, recursos Kubernetes e limitações encontradas:

**[docs/instalacao-openchoreo.md](docs/instalacao-openchoreo.md)**

## Checklist de entrega

- [x] Repositório organizado (`README.md`, `docs/`, `docs/evidencias/`)
- [x] Documentação do processo em `docs/instalacao-openchoreo.md`
- [x] Evidências de execução (17 prints em `docs/evidencias/`)
- [x] URL da interface: `http://openchoreo.localhost:8080`
- [ ] URL da aplicação de exemplo — deploy não concluído (timeout no `ReleaseBinding`)
- [x] Relato técnico das limitações (seção 6 da documentação)
- [x] Merge Request aberta (`docs/openchoreo` → `main`)

## Estrutura do repositório

```
.
├── README.md
└── docs/
    ├── instalacao-openchoreo.md   # Documentação da atividade
    └── evidencias/                # Prints de evidência
        ├── print-02-macos.png
        ├── print-07-quick-start.png
        ├── print-08-instalacao-final.png
        ├── print-10-login-openchoreo.png
        ├── print-11-deploy-terminal.png
        └── ...
```

## Resumo dos resultados

| Etapa | Resultado |
|-------|-----------|
| Ambiente (macOS + Colima + Docker) | Configurado |
| Instalação (`./install.sh --version v1.1.1`) | Parcial — erro no readiness probe do OpenBao |
| Interface (`http://openchoreo.localhost:8080`) | Acessível |
| Deploy (`./deploy-react-starter.sh`) | Componente e workload criados; publicação não concluída (timeout no ReleaseBinding) |

## Ambiente utilizado

- **SO:** macOS 26.3 (Apple Silicon — M4)
- **Runtime:** Colima + Docker 29.1.3
- **Recursos Docker:** 4 CPUs, ~7,7 GB de memória

## Autora

Iasmim Jesus - Inteli
