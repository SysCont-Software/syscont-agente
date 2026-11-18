# SysCont Agente

Programa para Windows que trabalha junto com o [SysCont](https://syscont-app.web.app), o sistema para escritórios de contabilidade.

O agente roda no computador do escritório e faz o que precisa do certificado digital: busca de NFS-e no Ambiente Nacional, emissão de NF-e, inutilização de numeração e consulta de cadastro na SEFAZ. Os certificados ficam guardados com criptografia e só o agente consegue abri-los.

## Baixar

**[Baixar a versão mais recente (SysCont-Agente.exe)](https://github.com/SysCont-Software/syscont-agente/releases/latest/download/SysCont-Agente.exe)**

Versões anteriores e o que mudou em cada uma: [Releases](https://github.com/SysCont-Software/syscont-agente/releases).

## Instalar

1. Baixe e abra o `SysCont-Agente.exe`.
2. Se o Windows mostrar "O Windows protegeu o computador", clique em **Mais informações** → **Executar assim mesmo**.
3. Abra o agente e conecte com o código gerado no SysCont, em **Controle Geral → Agentes**.

Para atualizar, é só instalar a versão nova por cima. Os certificados e a conexão continuam.

## Requisitos

- Windows 10 ou 11 (64 bits)
- Conta ativa no SysCont

## Suporte

syscontsoftware@gmail.com

---

Este repositório contém apenas o instalador. O código do SysCont é privado.
