<!-- ============================================================= -->
<!-- Swaphix — README                                              -->
<!-- ============================================================= -->

<p align="center">
  <img alt="Swaphix Logo" width="360px" src="https://www.swaphix.com/_next/static/media/logo-claro.4c843da3.png" />
</p>

<p align="center">
  <b>The financial bridge between Web2 and Web3.</b><br/>
  <sub>El puente financiero entre Web2 y Web3.</sub>
</p>

<p align="center">
  Businesses charge in digital assets and receive traditional money instantly — through a single integration.<br/>
  <sub>Las empresas cobran con activos digitales y reciben dinero tradicional de forma inmediata, con una sola integración.</sub>
</p>

<p align="center">
  <a href="https://www.swaphix.com"><img alt="Website" src="https://img.shields.io/badge/Website-swaphix.com-6E5BFF?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.linkedin.com/company/swaphix/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Swaphix-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://twitter.com/Swaphix_team"><img alt="Twitter" src="https://img.shields.io/badge/Twitter-@Swaphix__team-1DA1F2?style=flat-square&logo=twitter&logoColor=white" /></a>
  <a href="https://www.youtube.com/@Swaphix"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-Swaphix-FF0000?style=flat-square&logo=youtube&logoColor=white" /></a>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-informational?style=flat-square" />
  <img alt="Status" src="https://img.shields.io/badge/status-active-brightgreen?style=flat-square" />
</p>

---

## 🌐 Overview / Descripción

**EN** — Swaphix orchestrates financial APIs, banking on/off-ramps and core banking systems together with regulatory compliance, so any business can accept crypto and settle in local currency — no blockchain expertise required.

**ES** — Swaphix orquesta APIs financieras, rampas bancarias y sistemas de banca central junto con el cumplimiento normativo, para que cualquier empresa acepte cripto y liquide en moneda local — sin necesidad de conocimientos en blockchain.

---

## 🧩 Solutions / Soluciones

| | Solution / Solución | Description / Descripción |
|---|---|---|
| 💸 | **Remittances / Remesas** | Fast, secure cross-border transfers with stablecoins via API interconnection. <br/><sub>Transferencias internacionales rápidas y seguras con stablecoins mediante su API.</sub> |
| 🏪 | **Payment Terminals / Terminales de Pago** | Physical & digital infrastructure for merchants to accept crypto and stablecoins. <br/><sub>Infraestructura física y digital para aceptar cripto y stablecoins.</sub> |
| 🧾 | **Stablecoin Billing / Pago de Facturación** | Clients pay invoices in stablecoins; the business receives MXN in its bank account in minutes, not days. <br/><sub>El cliente paga en stablecoins y la empresa recibe MXN en su cuenta en minutos, no en días.</sub> |

---

## ⚙️ Billing Integration Options / Opciones de Integración de Facturación

| Option / Opción | Description / Descripción |
|---|---|
| **1. Manual upload / Carga manual** | Upload the invoice XML directly to the platform. <br/><sub>Subir el archivo XML de la factura a la plataforma.</sub> |
| **2. ERP integration / Integración ERP** | Connect the company's internal planning system. <br/><sub>Conectar el sistema interno de planificación (ERP).</sub> |
| **3. PAC consumption / Consumo de PACs** | Use the addenda compatible with Authorized Certification Providers. <br/><sub>Usar la addenda compatible con Proveedores Autorizados de Certificación.</sub> |

---

## 🏗️ How it works / Cómo funciona

```
  Client / Cliente            Swaphix Core                Business / Empresa
  ────────────────           ───────────────             ──────────────────
   Pays in stablecoins  ──▶   APIs · Ramps · KYC/AML  ──▶   Receives MXN
   Paga en stablecoins        Compliance · Settlement       Recibe en su banco
        (Web3)                     (bridge)                     (Web2)
```

---

## 🚀 Quickstart

> Requirements / Requisitos: **Node.js ≥ 18**

```bash
# Clone / Clonar
git clone https://github.com/<org>/swaphix.git
cd swaphix

# Install / Instalar
npm install

# Configure / Configurar
cp .env.example .env   # add your API keys / agrega tus llaves

# Run / Ejecutar
npm run dev
```

### API example / Ejemplo de API

```bash
curl -X POST https://api.swaphix.com/v1/invoices \
  -H "Authorization: Bearer $SWAPHIX_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "amount": 1000.00,
    "currency": "MXN",
    "settlement": "stablecoin",
    "reference": "INV-2025-001"
  }'
```

📚 Full documentation / Documentación completa → [docs.swaphix.com](https://www.swaphix.com)

---

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" alt="Solidity">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
</p>

**Blockchain infrastructure:** Polygon · Vara Network · Bitcoin · and additional EVM-compatible networks.

---

## 👥 Team / Equipo

| Role / Rol | Name / Nombre | Links |
|---|---|---|
| **Founder** | Rocío Álvarez | [LinkedIn](https://www.linkedin.com/in/rocio-alvarez-avelino-b35945167/) · [GitHub](https://github.com/ChioAA) |
| Co-founder | Arturo | [Twitter](https://twitter.com/ARTUROH94339882) |
| Co-founder | Héctor | [GitHub](https://github.com/Hectorc70) |
| Co-founder | Luis | — |

---

<p align="center"><sub>Made with ❤️ by the Swaphix team.</sub></p>
