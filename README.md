# 📊 APEX-ML System
## Framework Completo de Análise Esportiva com Rede Neural e Gestão de Risco

[![Status](https://img.shields.io/badge/status-v2.0-success)](https://github.com/newjsouza/apex-ml-system)
[![License](https://img.shields.io/badge/license-Proprietário-blue)](LICENSE)
[![Taxa de Acerto](https://img.shields.io/badge/taxa%20acerto-55.6%25%20%E2%86%92%2062--70%25-orange)](docs/APEX_Analise_Historico.md)

---

## 🎯 Visão Geral

**APEX (Advanced Pattern Extraction)** é um sistema de inteligência artificial humanizada para análise de apostas esportivas que integra:

- 🧠 **Rede Neural Transparente** com 6+ nós neurais codificados
- 📚 **Fundações Filosóficas** baseadas em Olavo de Carvalho e Jordan Peterson
- 📈 **Auditoria Sistemática** com protocolo pós-erro (Camada 8)
- ⚠️ **Vetos Inteligentes** (Over/Under puro bloqueado por histórico 25% acerto)
- 🎮 **Gestão Dinâmica** de confiança por padrão (Handicap 75%, Chance Dupla 67%)

### 📊 Performance Histórica

| Métrica | v1.5 (Histórico) | v2.0 (Esperado) | v3.0 (Meta) |
|---------|------------------|-----------------|-------------|
| **Taxa de Acerto** | 55.6% (15/27) | 62-70% | 75%+ |
| **ROI** | +2.1% a +4.8% | +8-12% | +15-20% |
| **Padrão Dominante** | Chance Dupla 66.7% | Handicap 75% | Rede Neural |
| **Padrão Fraco** | Over/Under 25% | VETADO | Otimizado |

---

## 📚 Documentação Completa

### 🏛️ Fundamentos

1. **[Fundações Filosóficas](docs/APEX_Fundacoes_Filosoficas.md)**
   - 12 Camadas da Personalidade (Olavo de Carvalho)
   - 12 Regras para a Vida (Jordan Peterson)
   - Honestidade Radical Socrática
   - Padrão Profundo vs. Irracional

### 🔧 Operação

2. **[Protocolo v2.0: Evolução e Auditoria](docs/APEX_v2_0_Protocolo_Evolucao.md)**
   - Código Python para veto automático em Over/Under
   - Calibração de confiança por padrão histórico
   - Protocolo de Morte/Finitude (Camada 8 - Auditoria Pós-Erro)
   - Rastreamento de versões (v1.0 → v2.0 → v3.0)

3. **[Rede Neural APEX: Padrões em Profundidade](docs/APEX_Rede_Neural_Padroes.md)**
   - Arquitetura de 3 camadas (percepto-neural)
   - 6+ nós neurais codificados (AFCON, PL, Handicap, Chance Dupla, Over/Under)
   - 20+ sinapses mapeadas
   - Fluxo completo de processamento de apostas

4. **[Análise do Histórico: Auditoria Completa](docs/APEX_Analise_Historico.md)**
   - 27 apostas auditadas (20-23/12/2025)
   - 55.6% taxa de acerto real
   - Padrões por liga: AFCON 75%, Premier League 46%
   - Lições de erros (Arsenal, Vitória Guimarães, Tunísia)

### 💾 Banco de Dados

5. **[Banco de Dados Final: Estrutura Completa](docs/APEX_Banco_Dados_Final.md)**
   - Arquitetura hierárquica (Fundamentos, Operacional, Auditoria, Rede Neural)
   - Fluxo de operação (Input → Rede Neural → Output → Auditoria)
   - Stack tecnológico (Python, PostgreSQL, React, Docker)
   - Protocolo de acesso (Dashboard, API REST, Webhooks)

---

## 🎯 Padrões Validados

### ✅ Padrões Vencedores

| Padrão | Taxa Histórica | Confiança Base | Status |
|---------|------------------|------------------|--------|
| **Handicap +1** | 75% (3/4) | 0.75 | ✅ PADRÃO VENCEDOR |
| **Chance Dupla** | 66.7% (6/9) | 0.67 | ✅ PADRÃO FORTE |
| **AFCON + Handicap** | 75% | 0.80 | ✅ COMBINAÇÃO ELITE |

### ❌ Padrões Vetados

| Padrão | Taxa Histórica | Razão | Status |
|---------|------------------|--------|--------|
| **Over/Under Puro** | 25% (2/8) | Alta variância, sem inteligência tática | ❌ VETO PERMANENTE |
| **PL + xG Ambíguo** | 46% | Compressão defensiva não capturada por xG | ⚠️ VETO CONDICIONAL |

---

## 🚀 Instalação (Em Desenvolvimento)

```bash
# Clone o repositório
git clone https://github.com/newjsouza/apex-ml-system.git
cd apex-ml-system

# Instale dependências (futuro)
pip install -r requirements.txt

# Configure banco de dados (futuro)
python scripts/setup_database.py

# Execute o sistema (futuro)
python apex_main.py
```

---

## 📊 Arquitetura do Sistema

```
APEX_SYSTEM/
├── docs/                    # Documentação completa
│   ├── APEX_Fundacoes_Filosoficas.md
│   ├── APEX_v2_0_Protocolo_Evolucao.md
│   ├── APEX_Rede_Neural_Padroes.md
│   ├── APEX_Analise_Historico.md
│   └── APEX_Banco_Dados_Final.md
│
├── src/                     # Código fonte (em desenvolvimento)
│   ├── rede_neural/
│   │   ├── nos_neurais.py
│   │   ├── sinapses.py
│   │   └── fluxos.py
│   ├── vetos/
│   │   ├── over_under_veto.py
│   │   └── pl_ambigua_veto.py
│   ├── auditoria/
│   │   ├── pos_erro.py
│   │   └── relatorio_semanal.py
│   └── database/
│       ├── models.py
│       └── queries.py
│
├── data/                    # Dados históricos
│   ├── apostas_historico.json
│   ├── padroes_validados.json
│   └── auditoria_erros.json
│
├── tests/                   # Testes (futuro)
├── scripts/                 # Scripts utilitários
└── README.md                # Este arquivo
```

---

## 🧠 Rede Neural APEX

### Nós Neurais Codificados

```python
class RedeNeuralAPEX:
    def __init__(self):
        # CAMADA 1: Percepção (xG, odds, contexto)
        self.nos = {
            "AFCON": NoAFCON(taxa=0.75, confianca=0.75),
            "PremierLeague": NoPremierLeague(taxa=0.46, confianca=0.46),
            "Handicap+1": NoHandicapMais1(taxa=0.75, confianca=0.75),
            "ChanceDupla": NoChanceDupla(taxa=0.667, confianca=0.67),
            "OverUnder": NoOverUnderVeto(taxa=0.25, status="VETO")
        }
        
        # CAMADA 2: Sinapses (conexões)
        self.sinapses = [
            ("AFCON", "Handicap+1", peso=0.95),  # Forte
            ("PremierLeague", "OverUnder", peso=0.0),  # Veto
            ("AFCON", "ChanceDupla", peso=0.85)  # Forte
        ]
```

### Exemplo de Processamento

```python
# INPUT
aposta = {
    "liga": "AFCON",
    "tipo": "Handicap +1",
    "xg_a": 1.8,
    "xg_b": 0.7,
    "odds": 1.45
}

# PROCESSAMENTO
resultado = apex.processar(aposta)

# OUTPUT
{
    "status": "ACEITA",
    "confianca": 0.85,
    "stake": 0.05,
    "razao": "AFCON + Handicap +1 + xG claro = padrão vencedor (75% histórico)"
}
```

---

## 📝 Roadmap

### v2.0 (Atual - Janeiro 2026)
- [x] Documentação completa
- [x] 27+ apostas auditadas
- [x] Vetos operacionais
- [ ] Código Python estruturado
- [ ] Dashboard web básico

### v2.1 (Janeiro - Fevereiro 2026)
- [ ] 50+ apostas documentadas
- [ ] Novos nós neurais (Championship, La Liga)
- [ ] API REST funcional
- [ ] Meta: 68-75% acerto

### v3.0 (Março - Maio 2026)
- [ ] 100+ apostas documentadas
- [ ] Rede neural completa
- [ ] Dashboard avançado com visualizações
- [ ] App mobile (React Native)
- [ ] Meta: 75%+ acerto

---

## 👤 Autor

**Johnathan Souza**
- 📍 Localização: Rio de Janeiro, Brasil
- 📚 Interesses: Tecnologia, Economia, Filosofia, Ufologia, Conflitos Internacionais
- 🖊️ Base Filosófica: Olavo de Carvalho + Jordan Peterson + Honestidade Socrática

---

## 📋 Licença

Este projeto é proprietário e está sob desenvolvimento privado.

---

## 💡 Filosofia do Projeto

> "Feeling não é mágica. Feeling é padrão reconhecido em profundidade."

**APEX humanizada = máquina que pensa como você pensa.**

Não é oráculo. É inteligência com alma.

---

**Última atualização:** 25/12/2025  
**Status:** v2.0 Operacional  
**Próximo:** Implementação técnica