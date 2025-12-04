# 🧠 OBrain Hub - Ecossistema de Dropshipping Inteligente

> **A ponte definitiva entre produtos globais validados e lojistas de alta performance.**

O **OBrain Hub** não é apenas uma plataforma de e-commerce; é um **motor de inteligência e infraestrutura** para operações de dropshipping. Nós centralizamos a curadoria de produtos, a negociação com fornecedores (CJ Dropshipping) e o processamento de pagamentos, permitindo que lojistas foquem apenas em vender.

---

## 💡 O Conceito

No modelo tradicional de dropshipping, cada lojista precisa garimpar produtos, negociar com fornecedores e configurar gateways de pagamento complexos. O **OBrain Hub** resolve isso:

1.  **Curadoria Centralizada:** Nossos algoritmos e especialistas selecionam os melhores produtos da CJ Dropshipping.
2.  **Ranking Inteligente:** Classificamos produtos em **S, A, B, C** com base em tendências globais e margem de lucro.
3.  **Infraestrutura Pronta:** O lojista recebe uma loja pronta (ou integra via API) com produtos já cadastrados e precificados.
4.  **Gestão Financeira Unificada:** O Hub processa 100% das vendas. O custo do produto e as taxas são descontados automaticamente, e o lucro líquido é creditado na **Wallet** do lojista.

---

## � Funcionalidades Principais

### 🛍️ Para o Lojista (User)
*   **Catálogo Premium:** Acesso imediato a centenas de produtos vencedores.
*   **Importação em 1 Clique:** Adicione produtos à sua vitrine instantaneamente.
*   **Precificação Inteligente:** Sugestão automática de preço de venda baseada no seu plano (Free, Pro, Premium, Enterprise).
*   **Carteira Digital (Wallet):** Acompanhe seu saldo em tempo real e solicite saques via PIX.
*   **Dashboard de Vendas:** Métricas detalhadas de performance e lucro.

### 🏢 Para o Administrador (Hub)
*   **Gestão de Produtos:** Importação em massa da CJ Dropshipping, definição de Rankings e Markups.
*   **Controle de Usuários:** Gestão de assinaturas, bloqueio de contas e upgrades.
*   **Painel Financeiro:** Aprovação de saques, visualização de fluxo de caixa e lucro da plataforma.
*   **Configuração Global:** Ajuste de taxas e limites de planos em tempo real.

---

## � Modelo de Negócio & Planos

A plataforma monetiza de duas formas: **Assinaturas (SaaS)** e **Taxas sobre Vendas (Take Rate)**.

| Plano | Acesso a Produtos | Limite de Vendas | Taxa do Hub (Markup) |
| :--- | :--- | :--- | :--- |
| **Free** | Rank C (Básicos) | R$ 499/mês | Alta |
| **Pro** | Rank B + C | R$ 750/mês | Média |
| **Premium** | Rank A + B + C | R$ 1.000/mês | Baixa |
| **Enterprise** | **Todos (Rank S)** | **Ilimitado** | **Mínima** |

---

## 🛠️ Arquitetura Técnica (Modern Stack)

O projeto foi construído utilizando as tecnologias mais modernas e escaláveis do mercado, focando em performance (Edge Computing) e baixo custo de infraestrutura.

### 🎨 Frontend (`/frontend`)
*   **Framework:** React 18 + Vite (SPA de alta performance).
*   **UI Kit:** Shadcn/UI + TailwindCSS (Design system profissional e responsivo).
*   **Estado:** TanStack Query (Gerenciamento de cache e requisições assíncronas).
*   **Hospedagem:** Cloudflare Pages (CDN Global).

### ⚡ Backend (`/backend-worker`)
*   **Serverless:** Rodando em **Cloudflare Workers** (Latência zero, escala infinita).
*   **Framework:** Hono (Framework web ultraleve para Edge).
*   **Banco de Dados:** **Cloudflare D1** (SQLite distribuído na Edge).
*   **ORM:** Drizzle ORM (Type-safe, leve e rápido).
*   **Storage:** Cloudflare R2 (Armazenamento de imagens compatível com S3).

### 🤖 Automação (`/cj-matcher`)
*   Scripts em Node.js para:
    *   Buscar produtos na API da CJ Dropshipping.
    *   Enriquecer dados (imagens, descrições, variantes).
    *   Calcular custos de envio em tempo real.
    *   Atualizar o banco de dados do Hub.

---



## 🔒 Segurança
*   **Autenticação JWT:** Sessões seguras e stateless.
*   **Role-Based Access Control (RBAC):** Permissões estritas para Lojistas vs. Admins.
*   **Validação de Dados:** Zod schemas em todas as entradas de API.

---

## 📝 Licença
Proprietário. Todos os direitos reservados a OBrain Hub.
