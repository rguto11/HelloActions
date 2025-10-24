# Hello Actions - Prática Github Actions
O objetivo disso é bem simples: confirmar que o GitHub Actions está rodando no nosso repositório.

Basicamente, configuramos o workflow que faz o seguinte:
- Gatilho: Sempre que a gente dá um git push para este repositório...
- Ação: ...o GitHub dispara uma máquina virtual do Linux (ubuntu-latest).
- Resultado: Essa máquina executa um comando simples para dizer "Olá, GitHub Actions!".

O arquivo hello.yml define todo o fluxo e está em .github/workflows/hello.yml.
