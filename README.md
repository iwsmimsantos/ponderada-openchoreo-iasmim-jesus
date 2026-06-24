# Atividade Ponderada - OpenChoreo

Repositório da atividade de instalação e validação do [OpenChoreo](https://openchoreo.dev) em ambiente local, utilizando o Quick Start na versão **v1.1.1**.

## Documentação

A documentação completa, com comandos executados, resultados, explicações dos recursos Kubernetes e evidências (prints), está em:

**[docs/instalacao-openchoreo.md](docs/instalacao-openchoreo.md)**

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
