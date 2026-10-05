# LP-MVP
<div align="center">

# 🍽️ SmartBuffet

### Produza só o **necessário**.

**Tecnologia para produção sob demanda em buffets, restaurantes e cozinhas.**

📊 Fluxo em tempo real • 🍲 Menos desperdício • ⚡ Decisões rápidas

</div>

---

## 🚀 O que é o SmartBuffet?

O **SmartBuffet** é um MVP criado para ajudar cozinhas e buffets a decidirem **quanto produzir durante a operação**.

Em vez de depender apenas da experiência ou do *feeling* da equipe, o sistema utiliza o **fluxo de entrada e saída de clientes** para indicar se a cozinha deve:

> 🟢 **AUMENTAR PRODUÇÃO**  
> 🟡 **MANTER RITMO**  
> 🔴 **DIMINUIR PRODUÇÃO**

O objetivo é produzir a quantidade mais adequada para o movimento do momento, reduzindo sobras sem deixar faltar comida nos horários de maior movimento.

---

# 💡 O problema

Em buffets e cozinhas, produzir a quantidade certa de comida pode ser difícil.

### Produzir demais

Pode gerar:

- 🗑️ desperdício de alimentos;
- 💰 prejuízo com matéria-prima;
- 💧 desperdício de água;
- ⚡ maior consumo de energia;
- 🚚 custos de logística;
- 👨‍🍳 desperdício de mão de obra.

### Produzir de menos

Também gera problemas:

- pratos vazios;
- demora na reposição;
- sobrecarga da cozinha;
- pior experiência para o cliente.

### ❌ O problema principal

Muitas decisões ainda podem ser tomadas no **“olhômetro”**, sem informações em tempo real sobre o movimento do estabelecimento.

---

# ✅ A solução

O SmartBuffet transforma o **movimento de clientes** em uma orientação simples para a cozinha.

```text
👤 Cliente entra ou sai
          ↓
📊 Sistema registra o fluxo
          ↓
⏱️ Analisa os últimos 15 minutos
          ↓
🕒 Verifica a faixa de horário
          ↓
🧠 Calcula a situação atual
          ↓
🍳 Envia um comando para a cozinha
```

A cozinha não precisa interpretar gráficos complexos.

Ela recebe uma orientação direta:

```text
┌──────────────────────────┐
│   🟢 AUMENTAR PRODUÇÃO   │
└──────────────────────────┘

┌──────────────────────────┐
│    🟡 MANTER RITMO      │
└──────────────────────────┘

┌──────────────────────────┐
│   🔴 DIMINUIR PRODUÇÃO   │
└──────────────────────────┘
```

---

# ⚙️ Como funciona?

A recepção registra:

```text
+1 👤 Cliente entrou
-1 👤 Cliente saiu
```

O SmartBuffet calcula o **saldo do fluxo dos últimos 15 minutos** e combina essa informação com o horário de funcionamento.

### Exemplo do MVP

| Saldo recente | Recomendação |
|---|---|
| Acima de `+5` | 🟢 **Aumentar produção** |
| Entre `-5` e `+5` | 🟡 **Manter ritmo** |
| Abaixo de `-5` | 🔴 **Diminuir produção** |

Além disso, o sistema considera diferentes períodos da operação, como:

**Pico • Normal • Baixa**

Em períodos de baixa, a proposta é reduzir o ritmo de produção.

---

# 🖥️ Duas telas. Zero complicação.

## 👥 1. Tela da Recepção

A recepção registra o movimento dos clientes.

### Principais funções

✅ Registrar entradas  
✅ Registrar saídas  
✅ Visualizar o saldo recente  
✅ Acompanhar métricas dos últimos 15 minutos  
✅ Configurar horários de pico e baixa  
✅ Configurar diferentes dias da semana

---

## 👨‍🍳 2. Tela da Cozinha

A equipe da cozinha recebe a decisão do sistema de forma clara e fácil de enxergar.

### A tela mostra

🍳 **Comando atual**

📊 **Saldo do fluxo**

🕒 **Faixa de horário**

🔔 **Aviso quando o comando muda**

A proposta é permitir que a equipe veja rapidamente o que precisa ser feito, inclusive à distância.

---

# 🌟 Principal diferencial

O SmartBuffet busca agir **antes que o desperdício aconteça**.

Enquanto outras abordagens podem analisar ou lidar com a sobra depois da produção, o SmartBuffet utiliza o fluxo de pessoas para tentar evitar que o excesso seja produzido.

### SmartBuffet

> **Prevenção durante a operação.**

```text
Outras abordagens

Produção → Excesso → Sobra → Análise
                         ↑
                    problema já ocorreu


SmartBuffet

Fluxo → Análise → Ajuste → Produção
                 ↑
          prevenção do excesso
```

---

# 🏆 Por que SmartBuffet?

| Característica | SmartBuffet |
|---|:---:|
| ⚡ Atua durante a operação | ✅ |
| 👥 Usa fluxo de clientes | ✅ |
| ⏱️ Analisa os últimos 15 minutos | ✅ |
| 📱 Pode ser usado em celular/tablet/monitor | ✅ |
| 🍳 Envia instruções para a cozinha | ✅ |
| 📊 Produção baseada em dados | ✅ |
| 🗑️ Busca evitar superprodução | ✅ |
| 🏢 Suporte conceitual a várias unidades | ✅ |

---

# 📈 Impacto esperado

O SmartBuffet busca gerar três resultados principais:

### 🗑️ Menos sobra

Produzir de acordo com o movimento real pode ajudar a diminuir alimentos produzidos sem necessidade.

### 💰 Menos recursos desperdiçados

Menos superprodução significa reduzir o uso desnecessário de matéria-prima, água, energia e mão de obra.

### 😊 Melhor experiência

Ao identificar crescimento no fluxo de clientes, a cozinha pode acelerar antes que os pratos fiquem vazios.

---

# 🏢 Pensado para diferentes operações

A Landing Page apresenta o MVP para operações como:

- 🍽️ **Buffets**
- 🍴 **Restaurantes**
- 🏭 **Cozinhas industriais**
- 🏢 **Refeitórios**
- ➕ **Outras operações de alimentação**

---

# 🌐 Múltiplas unidades

O conceito do SmartBuffet também considera redes com mais de uma filial.

```text
SmartBuffet
│
├── 🏢 Unidade 01
│   └── Dados e histórico próprios
│
├── 🏢 Unidade 02
│   └── Dados e histórico próprios
│
└── 🏢 Unidade 03
    └── Dados e histórico próprios
```

Cada unidade pode trabalhar com seu próprio canal e histórico sem interferir nas demais.

---

# 🛠️ Tecnologias utilizadas

A Landing Page do MVP foi desenvolvida utilizando tecnologias web simples:

<p>
  <strong>HTML5</strong> •
  <strong>CSS3</strong> •
  <strong>JavaScript</strong>
</p>

Também utiliza:

- **Google Fonts**
- **Barlow**
- **Barlow Condensed**

A demonstração funciona diretamente no navegador.

---

# 📱 Responsividade

A Landing Page possui adaptação para telas menores.

Pode ser visualizada em:

💻 Desktop  
💻 Notebook  
📱 Smartphone  
📲 Tablet  

Em telas menores, os conteúdos organizados em colunas passam a ser exibidos verticalmente.

---

# ♿ Acessibilidade

O código também possui cuidados básicos com acessibilidade, incluindo:

- `aria-live`;
- `aria-selected`;
- `role="status"`;
- `role="tabpanel"`;
- destaque visual ao navegar pelo teclado;
- suporte a `prefers-reduced-motion`;
- textos alternativos nas imagens.

---

# 📂 Estrutura atual

A Landing Page está concentrada principalmente em um único arquivo:

```text
📦 SmartBuffet
│
├── 📄 SmartBuffet — Landing page do MVP.html
│
└── 📘 README.md
```

O arquivo HTML contém:

```text
HTML
├── 🎨 CSS
├── ⚙️ JavaScript
└── 🖼️ Imagens incorporadas
```

---

# ▶️ Como executar

Não é necessário instalar bibliotecas ou dependências.

### 1. Baixe o projeto

```bash
git clone URL-DO-REPOSITORIO
```

### 2. Entre na pasta

```bash
cd SmartBuffet
```

### 3. Abra

```text
SmartBuffet — Landing page do MVP.html
```

no navegador.

Você também pode utilizar o **Live Server** no VS Code.

---

# 🧪 MVP

O objetivo desta versão é demonstrar o funcionamento principal da ideia:

```mermaid
flowchart TD
    A[👤 Entrada e saída de clientes]
    B[📊 Fluxo dos últimos 15 minutos]
    C[🕒
