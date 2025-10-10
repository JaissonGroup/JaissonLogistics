# Jaisson Logistics | Trabalho de Pesquisa Operacional com o Professor Jaisson

---

## Tipos de Contêineres

O termo **"Dry" (Seco)** significa que ele é usado para cargas que **não precisam de controle de temperatura** (ao contrário do contêiner Reefer, que é refrigerado).  
Ele é um modelo fechado e vedado, ideal para proteger a mercadoria de intempéries (chuva, poeira etc.).

O contêiner *Dry* é fabricado em dois tamanhos principais — as unidades de medida universais do comércio: **20 e 40 pés**.

| Característica | Dry Box 20 Pés (20' DC) | Dry Box 40 Pés (40' DC) |
|----------------|--------------------------|--------------------------|
| **Comprimento Externo** | ≈ 6,1 metros | ≈ 12,2 metros |
| **Medida de Capacidade** | 1 TEU (Unidade Base) | 2 TEUs |
| **Capacidade Máx. de Peso** | Alta (até ≈ 28.000 kg) | Média/Alta (até ≈ 30.000 kg) |
| **Uso Ideal** | Cargas densas/pesadas (Ex: Minério, máquinas, matéria-prima) | Cargas volumosas/leves (Ex: Eletrônicos, móveis, roupas) |

---

## Dimensões dos Navios

**Limites do Canal do Panamá**

| Característica | Navio Panamax (Eclusas Originais) | Navio Neopanamax (Eclusas Ampliadas) |
|----------------|------------------------------------|--------------------------------------|
| **Comprimento Máximo (LOA)** | 294 metros | 366 metros |
| **Boca Máxima (Largura)** | 32,3 metros | 49 metros |
| **Calado Máximo (Profundidade)** | 12,04 metros | 15,2 metros |
| **Capacidade de Carga (TEUs)** | Até 5.000 TEUs | Até 14.000 a 15.000 TEUs |

---

## Variáveis de Decisão

| Variável | Carga | Navio Alocado | Lucro por TEU (Cj) | Peso por TEU (A3j) |
|-----------|--------|----------------|---------------------|---------------------|
| **X1** | Carga Seca Padrão | Panamax | US$ 4.000 | 15 Ton |
| **X2** | Carga Seca Padrão | Neopanamax | US$ 5.500 | 15 Ton |
| **X3** | Carga Reefer (Frigorífica) | Neopanamax | US$ 6.500 | 16 Ton |
| **X4** | Carga Alto Valor (Eletrônicos) | Neopanamax | US$ 8.000 | 10 Ton |
| **X5** | Ração Animal | Panamax | US$ 2.500 | 20 Ton |

---

## Descrição da Viagem

**Origem → Destino:**  
Itapoá *(26°10′50,6″ S, 48°36′08,3″ O)* → Los Angeles *(33°43′45″ N, 118°15′43″ O)*

| Item | Navio Panamax (P) | Navio Neopanamax (NP) |
|------|--------------------|------------------------|
| **Capacidade de Carga (TEUs)** | 5.000 | 14.000 |
| **Consumo Diário de Bunker** | 70 Ton/dia | 100 Ton/dia |
| **Custo Operacional Diário (OPEX)** | US$ 20.000 | US$ 30.000 |
| **Duração Via Canal do Panamá** | 27 dias | 27 dias |
| **Duração Via Cabo Horn** | 47 dias | 47 dias |

---

## Rota 1 — Via Canal do Panamá (27 dias)

| Item de Custo | Cálculo (Panamax) | Custo (Panamax) | Cálculo (Neopanamax) | Custo (Neopanamax) |
|----------------|--------------------|-----------------|----------------------|---------------------|
| **1. Custo de Combustível (Bunker)** | 27 × 70 × 1.000 | US$ 1.890.000 | 27 × 100 × 1.000 | US$ 2.700.000 |
| **2. Custo Operacional Diário (OPEX)** | 27 × 20.000 | US$ 540.000 | 27 × 30.000 | US$ 810.000 |
| **3. Pedágio do Canal** | Custo Fixo | US$ 500.000 | Custo Fixo | US$ 1.000.000 |
| **CUSTO TOTAL DA VIAGEM** | — | **US$ 2.930.000** | — | **US$ 4.510.000** |
| **CUSTO POR TEU** | 2.93M / 5.000 | **US$ 586** | 4.51M / 14.000 | **US$ 322** |

---

## Rota 2 — Via Cabo Horn (47 dias)

| Item de Custo | Cálculo (Panamax) | Custo (Panamax) | Cálculo (Neopanamax) | Custo (Neopanamax) |
|----------------|--------------------|-----------------|----------------------|---------------------|
| **1. Custo de Combustível (Bunker)** | 47 × 70 × 1.000 | US$ 3.290.000 | 47 × 100 × 1.000 | US$ 4.700.000 |
| **2. Custo Operacional Diário (OPEX)** | 47 × 20.000 | US$ 940.000 | 47 × 30.000 | US$ 1.410.000 |
| **3. Pedágio do Canal** | Custo Fixo | US$ 0 | Custo Fixo | US$ 0 |
| **CUSTO TOTAL DA VIAGEM** | — | **US$ 4.230.000** | — | **US$ 6.110.000** |
| **CUSTO POR TEU** | 4.23M / 5.000 | **US$ 846** | 6.11M / 14.000 | **US$ 436** |

---

✅ **Resumo:**
- Via Canal do Panamá → **mais rápida e econômica por TEU.**
- Via Cabo Horn → **sem pedágio, mas mais cara pelo tempo e combustível.**
