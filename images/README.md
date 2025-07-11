# 🚀 Deploy do Projeto SSAS Tabular - DWLeme

Este repositório contém o projeto do modelo do Cubo Tabular `DWLeme`, desenvolvido no Visual Studio/SQL Server Data Tools (SSDT) para processamento e análise de dados.

## 🌐 Ambientes

- **Homologação**
  - Servidor: `10.1.100.203\SSASTB`
  - Database: `DWLeme`
  - Conexão: `DWFLeme_Snapshot_HMG`

- **Produção**
  - Servidor: `10.1.100.167\SSASTB`
  - Database: `DWLeme`
  - Conexão: `DWFLeme_Snapshot_HMG`

---

## 🛠️ Pré-requisitos

- Visual Studio 2022 com extensão **Analysis Services Projects** instalada
- Permissão de Deploy no Analysis Services
- Acesso ao servidor de origem de dados

---

## 📦 Etapas do Deploy

### 1. Abra o projeto `.smproj` no Visual Studio

### 1. Abra

```bash
cd DWLemeTabular
start DWLeme.smproj
