# Methodological Scheme v1

## 1. Назначение схемы

`Methodological Scheme v1` визуально и логически представляет полный исследовательский дизайн магистерской работы.

Схема показывает, как исследование переходит:

**от проблемы**

к

**evidence**

затем к

**анализу**

далее к

**требованиям и решению**

и заканчивается

**экспериментальной оценкой**.

Схема является верхнеуровневым представлением методологии и не заменяет подробные процедуры, описанные в `Research Procedure Map v1`.

---

# 2. Основная методологическая схема

```text
┌─────────────────────────────────────────────────────────────┐
│                    RESEARCH PROBLEM                          │
│  Limited observability, delayed detection, information load │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                  RESEARCH OBJECTIVE                          │
│ Investigate problems → define requirements → develop        │
│ conceptual analytical support → evaluate applicability       │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                    RESEARCH TASKS                            │
│                 Task 1 ───────────── Task 11                │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                 RESEARCH QUESTIONS                           │
│                    RQ0 ───────── RQ13                        │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
╔═════════════════════════════════════════════════════════════╗
║                 PHASE 1 — UNDERSTAND                       ║
╠═════════════════════════════════════════════════════════════╣
║ Domain Research                                              ║
║ Case Study                                                   ║
║ Document Analysis                                            ║
║ Expert Evidence                                              ║
║                                                             ║
║ Output:                                                      ║
║ Domain Map → Process Hierarchy → Case Boundary              ║
╚══════════════════════════════╤══════════════════════════════╝
                               │
                               ▼
╔═════════════════════════════════════════════════════════════╗
║              PHASE 2 — RECONSTRUCT                          ║
╠═════════════════════════════════════════════════════════════╣
║ Observation                                                  ║
║ Process Modelling                                             ║
║ Document Analysis                                            ║
║ Event / State Identification                                 ║
║                                                             ║
║ Output:                                                      ║
║ Normative Model → AS-IS Model → Event/State Model            ║
╚══════════════════════════════╤══════════════════════════════╝
                               │
                               ▼
╔═════════════════════════════════════════════════════════════╗
║                  PHASE 3 — DIAGNOSE                         ║
╠═════════════════════════════════════════════════════════════╣
║ Problem Analysis                                             ║
║ Bottleneck Analysis                                          ║
║ Root Cause Analysis                                          ║
║ KPI / Measurement Analysis                                   ║
║                                                             ║
║ Output:                                                      ║
║ Problems → Causes → Metrics → Measurement Model              ║
╚══════════════════════════════╤══════════════════════════════╝
                               │
                               ▼
╔═════════════════════════════════════════════════════════════╗
║                PHASE 4 — COMPARE                             ║
╠═════════════════════════════════════════════════════════════╣
║ Information Systems Analysis                                 ║
║ Literature Review                                            ║
║ Comparative Analysis                                         ║
║                                                             ║
║ Output:                                                      ║
║ Information Landscape + Methods Comparison                   ║
╚══════════════════════════════╤══════════════════════════════╝
                               │
                               ▼
╔═════════════════════════════════════════════════════════════╗
║                  PHASE 5 — GAP                              ║
╠═════════════════════════════════════════════════════════════╣
║ GAP Analysis                                                 ║
║                                                             ║
║ Need → Required Capability → Existing Capability             ║
║       → Limitation → GAP                                    ║
║                                                             ║
║ Output: GAP Matrix                                            ║
╚══════════════════════════════╤══════════════════════════════╝
                               │
                               ▼
╔═════════════════════════════════════════════════════════════╗
║               PHASE 6 — SPECIFY                              ║
╠═════════════════════════════════════════════════════════════╣
║ Requirements Engineering                                     ║
║ Traceability Analysis                                         ║
║                                                             ║
║ Problem/GAP → Requirement → Acceptance Criterion              ║
║                                                             ║
║ Output: Requirements Set + RTM                               ║
╚══════════════════════════════╤══════════════════════════════╝
                               │
                               ▼
╔═════════════════════════════════════════════════════════════╗
║                 PHASE 7 — DESIGN                            ║
╠═════════════════════════════════════════════════════════════╣
║ Conceptual Modelling                                          ║
║ Event / State Representation                                  ║
║ Analytical Design                                             ║
║                                                             ║
║ Output:                                                      ║
║ Conceptual Analytical & Intelligent Support Model             ║
╚══════════════════════════════╤══════════════════════════════╝
                               │
                               ▼
                    ┌───────────────────────┐
                    │   BASELINE SCENARIO   │
                    │ Existing approach     │
                    └───────────┬───────────┘
                                │
                                │      COMPARISON
                                │
                    ┌───────────▼───────────┐
                    │ PROPOSED APPROACH     │
                    │ Analytical support    │
                    └───────────┬───────────┘
                                │
                                ▼
╔═════════════════════════════════════════════════════════════╗
║                 PHASE 8 — EVALUATE                          ║
╠═════════════════════════════════════════════════════════════╣
║ Controlled / Scenario-Based Evaluation                       ║
║                                                             ║
║ H1 — Observability                                           ║
║ H2 — Timeliness                                              ║
║ H3 — Information Load                                        ║
╚══════════════════════════════╤══════════════════════════════╝
                               │
               ┌───────────────┼────────────────┐
               ▼               ▼                ▼
        ┌─────────────┐ ┌─────────────┐ ┌─────────────┐
        │     H1      │ │     H2      │ │     H3      │
        │ Observability│ │ Timeliness │ │ Info Load   │
        ├─────────────┤ ├─────────────┤ ├─────────────┤
        │ Detection   │ │ Median TTD │ │ Task Time   │
        │ Completeness│ │ P95 TTD    │ │ Actions     │
        │ Event Cover │ │ Early Rate │ │ Sources     │
        │ State Cover │ │ Before Crit│ │ Manual Ops  │
        └──────┬──────┘ └──────┬──────┘ └──────┬──────┘
               │               │                │
               └───────────────┼────────────────┘
                               ▼
╔═════════════════════════════════════════════════════════════╗
║                    RQ CLOSURE                               ║
║ Every RQ → Method → Evidence → Finding → Answer             ║
╚══════════════════════════════╤══════════════════════════════╝
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                  RESEARCH CONCLUSION                         │
│ Integrated answer to RQ0 + hypothesis assessment             │
└─────────────────────────────────────────────────────────────┘
```

---

# 3. Методологическая архитектура

Визуально исследование состоит из четырёх уровней.

## Level 1 — Research Framing

**Problem**

→

**Objective**

→

**Tasks**

→

**RQ**

Этот уровень определяет:

> **что исследуется и зачем.**

---

## Level 2 — Empirical Investigation

**Domain**

→

**Process**

→

**Events**

→

**Problems**

→

**Causes**

→

**Metrics**

Этот уровень отвечает:

> **что происходит в реальном процессе.**

---

## Level 3 — Design

**Information Landscape**

→

**Methods**

→

**GAP**

→

**Requirements**

→

**Conceptual Solution**

Этот уровень отвечает:

> **что необходимо изменить и каким требованиям должно соответствовать решение.**

---

## Level 4 — Evaluation

**Baseline**

vs.

**Proposed Approach**

→

**Metrics**

→

**H1/H2/H3**

→

**Conclusion**

Этот уровень отвечает:

> **даёт ли предложенный подход измеримый эффект.**

---

# 4. Центральный цикл методологии

Основной цикл:

```text
PROBLEM
   ↓
OBSERVE
   ↓
MODEL
   ↓
MEASURE
   ↓
DIAGNOSE
   ↓
COMPARE
   ↓
IDENTIFY GAP
   ↓
SPECIFY REQUIREMENTS
   ↓
DESIGN
   ↓
EVALUATE
   ↓
CONCLUDE
```

Однако исследовательский процесс является итеративным.

Допускаются обратные переходы:

```text
EVALUATE ─────→ MEASURE
     ↑             ↓
DESIGN ←──── GAP ← INFORMATION
     ↑             ↓
REQUIREMENTS ← PROBLEM ANALYSIS
     ↑             ↓
AS-IS ←──── OBSERVATION
```

То есть обнаружение нового evidence может привести к уточнению предыдущего этапа.

---

# 5. Evidence Layer

Все основные этапы поддерживаются evidence.

```text
                   RESEARCH EVIDENCE
                          │
        ┌─────────────────┼─────────────────┐
        ▼                 ▼                 ▼
   Empirical          Documentary        Expert
        │                 │                 │
        ├────────────┬────┴────┬────────────┤
        ▼            ▼         ▼            ▼
    Events       Documents  Observation  Interviews
        │
        ▼
 Process / State Evidence
        │
        ▼
 Findings
```

Для экспериментальной части добавляется:

```text
Baseline / Proposed Results
            │
            ▼
      Experimental Evidence
```

---

# 6. Measurement Layer

Measurement layer связывает фактические наблюдения с гипотезами.

```text
Observed Process
       ↓
Observable Variables
       ↓
Metrics
       ↓
Baseline / Proposed Comparison
       ↓
Hypothesis Assessment
```

Основные конструкты:

```text
Observability
     ↓
Detection Completeness

Timeliness
     ↓
Time-to-Detection

Information Load
     ↓
Task Completion Time
```

---

# 7. Traceability Layer

Вся методология должна поддерживать двунаправленную трассировку.

### Forward traceability

```text
Problem
  ↓
Objective
  ↓
Task
  ↓
RQ
  ↓
Method
  ↓
Data
  ↓
Procedure
  ↓
Result
  ↓
Evaluation
```

### Backward traceability

```text
Conclusion
   ↑
Finding
   ↑
Analysis
   ↑
Method
   ↑
Evidence
   ↑
Source
```

Это позволяет для каждого итогового вывода ответить на вопрос:

> **«На основании какого evidence и какой исследовательской процедуры он получен?»**

---

# 8. Связь с гипотезами

Методологическая схема должна отдельно выделять три проверяемых направления.

### H1

```text
Process
   ↓
Events / States
   ↓
Observable Deviations
   ↓
Detection
   ↓
Detection Completeness
   ↓
H1
```

### H2

```text
Observable Problem
   ↓
Detection
   ↓
Detection Timestamp
   ↓
Time-to-Detection
   ↓
Early Detection
   ↓
H2
```

### H3

```text
Management Task
   ↓
Information Search
   ↓
Information Reconciliation
   ↓
Task Execution
   ↓
Time / Actions / Sources
   ↓
H3
```

---

# 9. Роль baseline

Baseline является обязательной частью evaluation layer.

```text
                    SAME SCENARIO
                         │
              ┌──────────┴──────────┐
              ▼                     ▼
         BASELINE              PROPOSED
              │                     │
              ▼                     ▼
        Measurement             Measurement
              │                     │
              └──────────┬──────────┘
                         ▼
                      Compare
                         ↓
                 Evaluate H1–H3
```

Baseline не должен быть намеренно ухудшенным.

Он должен отражать реальный существующий способ выполнения соответствующей задачи.

---

# 10. Роль proposed approach

Proposed approach является результатом предыдущих исследовательских этапов:

```text
Problems
   +
Information Landscape
   +
Methods
   +
GAP
   +
Requirements
        ↓
Conceptual Solution
```

То есть решение не появляется в начале исследования.

Оно является результатом:

**Problem → GAP → Requirements → Design.**

---

# 11. Методологические границы

Схема не требует заранее:

- конкретного программного стека;
- конкретной СУБД;
- конкретного AI-моделя;
- конкретного алгоритма ML;
- обязательного process mining.

Конкретная технологическая реализация выбирается только после:

**Problem Analysis**

→

**Data Assessment**

→

**GAP**

→

**Requirements**

→

**Method Comparison**.

---

# 12. Итоговая компактная схема

Для возможного использования непосредственно в тексте магистерской работы:

```text
                RESEARCH PROBLEM
                       ↓
                 RESEARCH GOAL
                       ↓
                RESEARCH TASKS
                       ↓
                RESEARCH QUESTIONS
                       ↓
        ┌──────────────┴──────────────┐
        │                             │
        ▼                             ▼
   DOMAIN / CASE                 LITERATURE /
   INVESTIGATION                METHODS REVIEW
        │                             │
        ▼                             ▼
   AS-IS PROCESS                 METHODS LANDSCAPE
        │                             │
        └──────────────┬──────────────┘
                       ▼
              PROBLEM / KPI ANALYSIS
                       ↓
                    GAP
                       ↓
                REQUIREMENTS
                       ↓
              CONCEPTUAL SOLUTION
                       ↓
             BASELINE vs PROPOSED
                       ↓
                EXPERIMENT
                       ↓
              ┌────────┼────────┐
              ▼        ▼        ▼
             H1       H2       H3
        Observability Timeliness Info Load
              └────────┼────────┘
                       ↓
                 RQ0 / CONCLUSION
```

---

# 13. Статус схемы

**Название:** Methodological Scheme v1

**Версия:** v1

**Статус:** рабочая верхнеуровневая схема методологии.

**Назначение:**

- визуальное представление исследовательского дизайна;
- контроль логической последовательности исследования;
- основа для рисунка в диссертации;
- связующий элемент между `Research Design`, `Methods`, `Evidence`, `Procedures` и `Evaluation`.

**Ключевая формула схемы:**

> **Problem → Evidence → Analysis → GAP → Requirements → Design → Evaluation → Conclusion**

**Исследование является итеративным**, однако каждый переход должен оставаться трассируемым к соответствующему RQ, evidence и исследовательской задаче.