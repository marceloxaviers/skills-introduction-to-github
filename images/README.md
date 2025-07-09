# 🚀 Deploy do Projeto SSAS Tabular - DWLeme

Este repositório contém o projeto do modelo Tabular `DWLeme`, desenvolvido no Visual Studio/SQL Server Data Tools (SSDT) para processamento e análise de dados.

## 🌐 Ambientes

- **Homologação**
  - Servidor: `SRV-HMG-AS`
  - Database: `DWLeme_HMG`
  - Conexão: `DWFLeme_Snapshot_HMG`

- **Produção**
  - Servidor: `SRV-PRD-AS`
  - Database: `DWLeme`
  - Conexão: `DWFLeme_Snapshot`

---

## 🛠️ Pré-requisitos

- Visual Studio 2022 com extensão **Analysis Services Projects** instalada
- Permissão de Deploy no Analysis Services
- Acesso ao servidor de origem de dados

---

## 📦 Etapas do Deploy

### 1. Abra o projeto `.smproj` no Visual Studio

```bash
cd DWLemeTabular
start DWLeme.smproj
