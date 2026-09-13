# Research Methods Matrix v2

## 1. Назначение документа

`Research Methods Matrix v2` является интегрированной версией методологической матрицы исследования и объединяет результаты:

- `Research Design Overview v1`;
- `Research Methods Matrix v1`;
- `Data & Evidence Matrix v1`;
- `Research Procedure Map v1`;
- `Measurement & Evaluation Framework v1`.

Документ фиксирует не только используемые методы, но и полную трассировку:

**Research Task → Research Question → Research Construct → Method → Data/Evidence → Procedure → Output → Evaluation → Hypothesis/Conclusion.**

Основная задача документа — обеспечить методологическую согласованность всего исследования до перехода к эмпирической работе.

---

# 2. Сквозной принцип

Для каждого исследовательского вопроса должна существовать цепочка:

**RQ**

→ **что необходимо узнать**

→ **какой метод это позволяет установить**

→ **какие данные необходимы**

→ **какая процедура выполняется**

→ **какой результат получается**

→ **как результат проверяется**

→ **какому более высокому исследовательскому уровню он соответствует**.

Таким образом:

> **метод не является самостоятельным элементом исследования; он является средством получения evidence для конкретного исследовательского вопроса.**

---

# 3. Итоговая Research Methods Matrix

| RQ | Task | Тип вопроса | Что необходимо установить | Основной метод | Дополнительные методы | Data / Evidence | Основная процедура | Output | Evaluation / Validation | Связь |
|---|---|---|---|---|---|---|---|---|---|---|
| **RQ0** | 11 | интеграционный | Как повысить наблюдаемость и своевременность управления процессом? | Research synthesis | comparative evaluation | результаты RQ1–RQ13 | интеграция findings, evaluation и hypothesis assessment | Integrated Research Answer | consistency + evidence support | H1–H3 |
| **RQ1** | 1, 2 | описательный | Как устроена предметная область и исследуемый процесс? | Domain Research + Case Study | Document Analysis, Expert Interview | документы, роли, правила, process descriptions | domain scoping → process decomposition → boundary definition | Domain Map, Process Hierarchy | completeness + expert/document verification | Problem Context |
| **RQ2** | 2, 3 | описательно-аналитический | Как фактически выполняется процесс? | Observation + Process Modelling | Document Analysis, Interview | observation records, documents, system records | observation → comparison with normative process → AS-IS reconstruction | AS-IS BPMN | evidence coverage + validation | T2, RQ4 |
| **RQ3** | 3, 5 | аналитический | Какие события, состояния и переходы делают процесс наблюдаемым? | Event/Data Analysis | State Modelling, Information Flow Analysis | events, timestamps, states, attributes | event identification → state definition → transition mapping → data quality assessment | Event/State Model, Event Log Specification | observability sufficiency | H1/H2 |
| **RQ4** | 4 | диагностический | Где возникают проблемы, отклонения и узкие места? | Problem Analysis | Bottleneck Analysis, Observation | deviations, delays, rework, waiting, manual operations | deviation identification → classification → impact analysis | Problem Register, Bottleneck Matrix | evidence attached to each problem | H1 |
| **RQ5** | 4 | причинно-аналитический | Каковы наиболее вероятные корневые причины проблем? | Root Cause Analysis | Ishikawa, 5 Why, Expert Assessment | process evidence, observations, interviews | symptom → candidate causes → evidence → validation | Root Cause Analysis | alternative explanations + triangulation | Problem Explanation |
| **RQ6** | 5 | измерительный | Как измерять состояние процесса, отклонения и своевременность? | KPI / Measurement Analysis | Statistical Analysis where applicable | timestamps, counts, statuses, event records | construct definition → variable definition → metric definition → calculation rule | KPI Catalog, Measurement Model | reproducibility | H1/H2/H3 |
| **RQ7** | 6 | описательно-аналитический | Как существующий информационный контур поддерживает процесс? | Functional Information Systems Analysis | Document Analysis, Observation, Interview | systems, files, reports, manual operations | source mapping → function mapping → information-flow analysis | Information Landscape, Manual Operations Map | coverage of key information operations | H3/GAP |
| **RQ8** | 8 | сравнительный | Какие методы и классы решений применимы? | Literature Review + Comparative Analysis | Benchmark Analysis | scientific literature, solution documentation | search → selection → classification → comparison | Methods Comparison Matrix | explicit comparison criteria | GAP/Solution |
| **RQ9** | 7 | GAP-аналитический | Какой функциональный и информационный GAP существует? | GAP Analysis | Comparative Analysis | problems, KPI, information landscape, methods | need → required capability → existing capability → limitation → GAP | GAP Matrix | traceability to evidence | Requirements |
| **RQ10** | 9 | проектный | Какие требования должна удовлетворять подсистема? | Requirements Engineering | Expert Assessment, Traceability Analysis | GAPs, problems, KPI, user needs | GAP → requirement → acceptance criterion → traceability | Requirements Set, RTM | requirement completeness + traceability | Solution |
| **RQ11** | 10 | концептуально-проектный | Как преобразовать события и состояния в аналитическую и интеллектуальную поддержку? | Conceptual Modelling | Solution Mapping, Method Comparison | event/state model, requirements, methods | data → event → state → analytics → detection → decision support | Conceptual Analytical Model | requirement coverage | H1/H2/H3 |
| **RQ12** | 11 | верификационный | Позволяет ли подход обнаруживать отклонения раньше или полнее? | Controlled / Scenario-Based Experiment | Event Analysis, Statistical Comparison | baseline/proposed results, reference deviations, timestamps | scenario definition → baseline run → proposed run → metric calculation → comparison | H1/H2 Evaluation | Detection Completeness, TTD, EDR | H1/H2 |
| **RQ13** | 11 | верификационный | Сокращается ли информационная нагрузка? | Controlled Task Experiment | Task Analysis, Expert Assessment | task performance data | baseline task → proposed task → measure time/actions/sources → comparison | H3 Evaluation | TCT, Actions, Sources, Manual Transformations | H3 |

---

# 4. Связь методов с исследовательскими задачами

| Task | Исследовательская функция | Основные методы |
|---|---|---|
| **1** | определить границы предметной области | Domain Research, Case Study |
| **2** | понять структуру и фактическое выполнение процесса | Process Analysis, Observation, BPMN |
| **3** | формализовать события и состояния | Event Analysis, State Modelling |
| **4** | выявить проблемы и причины | Problem Analysis, RCA |
| **5** | определить измеримые характеристики | KPI Analysis |
| **6** | исследовать существующее информационное обеспечение | Functional IS Analysis |
| **7** | определить GAP | GAP Analysis |
| **8** | сравнить существующие методы | Literature Review, Comparative Analysis |
| **9** | сформировать требования | Requirements Engineering |
| **10** | разработать концептуальное решение | Conceptual Modelling |
| **11** | подготовить и провести проверку подхода | Experimental Evaluation |

---

# 5. Связь RQ с типом знания

## Descriptive Knowledge

**RQ1, RQ2, RQ7**

Необходимо установить:

**что существует и как оно устроено.**

---

## Analytical Knowledge

**RQ3, RQ4, RQ5, RQ6**

Необходимо установить:

**что происходит, где, почему и как это измерить.**

---

## Comparative Knowledge

**RQ8**

Необходимо установить:

**какие существующие методы и решения потенциально применимы.**

---

## Design Knowledge

**RQ9, RQ10, RQ11**

Необходимо установить:

**что необходимо изменить и каким требованиям должно соответствовать решение.**

---

## Evaluation Knowledge

**RQ12, RQ13**

Необходимо установить:

**даёт ли предлагаемая концепция измеримый эффект.**

---

# 6. Связь RQ с основными evidence

| RQ | Основное evidence |
|---|---|
| RQ1 | Documents + Expert Evidence |
| RQ2 | Observation + Process Records |
| RQ3 | Events + Timestamps + States |
| RQ4 | Deviations + Process Evidence |
| RQ5 | Cause Evidence + Expert Evidence |
| RQ6 | Quantitative Process Data |
| RQ7 | System / File / Manual Operation Evidence |
| RQ8 | Scientific and Comparative Evidence |
| RQ9 | Combined Problem + Information + Method Evidence |
| RQ10 | GAP + Requirements Evidence |
| RQ11 | Requirements + Event/State Evidence |
| RQ12 | Experimental Evidence |
| RQ13 | Task Performance Evidence |
| RQ0 | Integrated Evidence Base |

---

# 7. Связь RQ с ожидаемыми артефактами

| RQ | Artifact |
|---|---|
| RQ1 | Domain Map + Process Hierarchy |
| RQ2 | AS-IS BPMN |
| RQ3 | Event/State Model |
| RQ4 | Problem Register |
| RQ5 | Root Cause Analysis |
| RQ6 | KPI Catalog |
| RQ7 | Information Landscape |
| RQ8 | Methods Comparison Matrix |
| RQ9 | GAP Matrix |
| RQ10 | Requirements Set + RTM |
| RQ11 | Conceptual Analytical Model |
| RQ12 | H1/H2 Evaluation |
| RQ13 | H3 Evaluation |
| RQ0 | Integrated Research Answer |

---

# 8. Связь методов с H1–H3

## H1 — Наблюдаемость

Основная трассировка:

**RQ2**

→ фактическое выполнение

**RQ3**

→ события и состояния

**RQ4**

→ отклонения

**RQ6**

→ measurement

**RQ12**

→ experimental evaluation.

Основная метрика:

**Detection Completeness**

Дополнительные:

- Event Coverage;
- State Coverage;
- Deviation Coverage.

---

## H2 — Своевременность

Основная трассировка:

**RQ3**

→ observable evidence

**RQ4**

→ relevant deviations

**RQ6**

→ temporal measurement

**RQ11**

→ conceptual detection mechanism

**RQ12**

→ evaluation.

Основная метрика:

**Median Time-to-Detection**

Дополнительные:

- P95 TTD;
- Early Detection Rate;
- Detection Before Critical Event.

---

## H3 — Информационная нагрузка

Основная трассировка:

**RQ7**

→ information landscape

**RQ9**

→ information GAP

**RQ10**

→ requirements

**RQ11**

→ aggregated analytical support

**RQ13**

→ task experiment.

Основная метрика:

**Task Completion Time**

Дополнительные:

- Number of Actions;
- Number of Sources;
- Context Switches;
- Manual Transformations;
- Accuracy;
- Completeness.

---

# 9. Правило выбора конкретного метода

Конкретный метод выбирается через:

**RQ**

→ **тип знания**

→ **требуемое evidence**

→ **характер доступных данных**

→ **метод**.

Это означает, что:

### Process Mining

является условным методом.

Он применяется только при наличии пригодного event log.

### Machine Learning / AI

является условным методом.

Он используется только при наличии задачи, где интеллектуальный метод действительно необходим и есть достаточная data basis.

### BPMN

используется как инструмент процессного моделирования и формализации.

### Statistical Analysis

применяется только при соответствующем объёме, качестве и типе данных.

---

# 10. Воспроизводимость

Для каждого ключевого исследовательского результата должны быть доступны:

**Input**

→

**Method**

→

**Procedure**

→

**Transformation**

→

**Output**

→

**Validation**.

Особенно это относится к:

- KPI;
- event analysis;
- baseline/proposed comparison;
- эксперименту;
- hypothesis assessment.

---

# 11. Трассировка требований

Каждое ключевое требование должно иметь цепочку:

**Problem**

→

**Evidence**

→

**GAP**

→

**Requirement**

→

**Solution Component**

→

**Evaluation Criterion**.

Это позволяет проверить, что проектируемая подсистема не содержит функций, которые возникли без исследовательского основания.

---

# 12. Трассировка оценки

Каждый экспериментальный показатель должен иметь обратную связь:

**Metric**

→ **Construct**

→ **Hypothesis**

→ **RQ**

→ **Research Problem**.

Например:

**Median TTD**

→ **Timeliness**

→ **H2**

→ **RQ12**

→ **Delayed Detection Problem**.

---

# 13. Контрольные правила

## Rule 1

Нет RQ без метода.

## Rule 2

Нет метода без исследовательской функции.

## Rule 3

Нет критического вывода без evidence.

## Rule 4

Нет KPI без raw data definition.

## Rule 5

Нет требования без Problem/GAP rationale.

## Rule 6

Нет Solution Component без Requirement linkage.

## Rule 7

Нет гипотезы без evaluation path.

## Rule 8

Нет экспериментального результата без baseline comparison.

## Rule 9

Нет количественного улучшения без одинаковых правил измерения.

## Rule 10

Неопределённость должна фиксироваться, а не скрываться.

---

# 14. Взаимосвязь пяти методологических документов

Эта версия матрицы фиксирует следующие зависимости:

**Research Design Overview**

отвечает:

> Что представляет собой исследование?

**Research Methods Matrix v2**

отвечает:

> Какими методами исследуются RQ?

**Data & Evidence Matrix**

отвечает:

> На каких данных или evidence основаны результаты?

**Research Procedure Map**

отвечает:

> Как выполняется исследовательская процедура?

**Measurement & Evaluation Framework**

отвечает:

> Как измеряется результат и как принимается решение по гипотезе?

Их совместный результат:

# Operational Research Methodology

---

# 15. Контрольная таблица методологической полноты

| Проверка | Статус |
|---|---|
| RQ0–RQ13 имеют методы | ✅ |
| Все RQ связаны с Tasks | ✅ |
| Для всех RQ определено evidence | ✅ |
| Для всех RQ задан output | ✅ |
| H1 имеет evaluation path | ✅ |
| H2 имеет evaluation path | ✅ |
| H3 имеет evaluation path | ✅ |
| KPI связаны с constructs | ✅ |
| Требования связаны с GAP | ✅ |
| Solution связана с requirements | ✅ |
| Experimental comparison определён | ✅ |
| Baseline/proposed разделены | ✅ |
| Process Mining не навязан заранее | ✅ |
| AI не навязан заранее | ✅ |
| Реальные и синтетические данные разделяются | ✅ |
| Возможна triangulation | ✅ |
| Возможна фиксация inconclusive results | ✅ |

---

# 16. Финальная версия методологической цепочки

**Research Problem**

↓

**Research Objective**

↓

**Research Tasks**

↓

**Research Questions**

↓

**Domain / Case Study**

↓

**AS-IS Reconstruction**

↓

**Event / State Analysis**

↓

**Problem & Root Cause Analysis**

↓

**Measurement**

↓

**Information Landscape**

↓

**Methods / State of the Art**

↓

**GAP**

↓

**Requirements**

↓

**Conceptual Solution**

↓

**Baseline / Proposed Approach**

↓

**Experimental Evaluation**

↓

**H1 / H2 / H3**

↓

**RQ Closure**

↓

**Research Conclusion**

---

# 17. Статус документа

**Название:** Research Methods Matrix v2

**Версия:** v2

**Статус:** интегрированная рабочая версия методологической матрицы.

**Назначение:** основной операционный методологический документ для проведения дальнейшего эмпирического исследования.

**Следующий уровень:** визуальная `Methodological Scheme v1`.