# Research Methodology Package v1

## 1. Назначение пакета

`Research Methodology Package v1` является интегрированной версией методологической части исследования, сформированной по итогам третьей недели.

Пакет объединяет следующие артефакты:

1. `Research Design Overview v1`
2. `Research Methods Matrix v2`
3. `Data & Evidence Matrix v1`
4. `Research Procedure Map v1`
5. `Measurement & Evaluation Framework v1`
6. `Methodological Scheme v1`

Основная задача пакета — зафиксировать единый операционный исследовательский дизайн, который может использоваться в дальнейшей эмпирической работе.

Итоговая логика:

**Research Problem**

→

**Research Objective**

→

**Research Tasks**

→

**Research Questions**

→

**Research Design**

→

**Methods**

→

**Data / Evidence**

→

**Procedures**

→

**Measurements**

→

**Evaluation**

→

**Research Findings**

→

**Research Conclusion**

---

# 2. Методологическая позиция исследования

Исследование имеет прикладной, эмпирико-аналитический и проектно-экспериментальный характер.

Оно сочетает:

- исследование предметной области;
- case study;
- документальный анализ;
- наблюдение;
- экспертное взаимодействие;
- моделирование процессов;
- анализ событий и данных;
- problem and root cause analysis;
- KPI и measurement analysis;
- анализ существующего информационного обеспечения;
- обзор и сравнительный анализ методов;
- GAP analysis;
- requirements engineering;
- концептуальное проектирование;
- controlled / scenario-based evaluation.

При этом конкретная технология не рассматривается как исходная точка исследования.

Технологический выбор определяется последовательностью:

**Problem → Evidence → GAP → Requirements → Method → Solution.**

---

# 3. Объект и предмет исследования

## 3.1. Объект

Бизнес-процессы технического обслуживания и ремонта авиационной техники.

## 3.2. Предмет

Методы и информационные средства анализа, мониторинга и интеллектуальной поддержки управления бизнес-процессами технического обслуживания и ремонта авиационной техники.

---

# 4. Цель исследования

Исследовать проблемы наблюдаемости и управления бизнес-процессами ТОиР, определить требования к их аналитической поддержке и разработать дополнительную подсистему интеллектуального управления на основе анализа фактического выполнения процессов с последующей экспериментальной оценкой её применимости.

---

# 5. Центральная исследовательская проблема

Исследование рассматривает предполагаемую проблему ограниченной наблюдаемости фактического выполнения процессов ТОиР, связанную с распределённостью информации между различными источниками, ручным контролем и недостаточной интеграцией событий, состояний и отклонений в единое аналитическое представление.

Наличие и степень выраженности этой проблемы должны устанавливаться в эмпирической части исследования.

Следовательно:

**предполагаемая проблема**

не считается автоматически

**доказанной проблемой**.

---

# 6. Исследовательская логика

Основная последовательность исследования:

```text
Research Problem
      ↓
Research Objective
      ↓
Research Tasks
      ↓
Research Questions
      ↓
Domain / Case Understanding
      ↓
Normative Process
      ↓
AS-IS Reconstruction
      ↓
Events / States
      ↓
Problems / Deviations
      ↓
Root Causes
      ↓
Measurement / KPI
      ↓
Information Landscape
      ↓
State of the Art / Methods
      ↓
GAP
      ↓
Requirements
      ↓
Conceptual Solution
      ↓
Baseline vs Proposed
      ↓
Experimental Evaluation
      ↓
H1 / H2 / H3
      ↓
RQ Closure
      ↓
Research Conclusion
```

---

# 7. Research Questions

Методологический пакет использует актуальную систему:

**RQ0–RQ13.**

## RQ0

Центральный интеграционный вопрос исследования.

Ответ формируется на основании совокупности результатов всех остальных исследовательских вопросов.

## RQ1–RQ3

Формируют представление о:

- предметной области;
- процессе;
- событиях;
- состояниях;
- информационных объектах.

## RQ4–RQ6

Формируют представление о:

- проблемах;
- отклонениях;
- причинах;
- KPI;
- измеримости.

## RQ7–RQ8

Исследуют:

- существующее информационное обеспечение;
- существующие методы и классы решений.

## RQ9–RQ11

Формируют:

- GAP;
- требования;
- концептуальную модель решения.

## RQ12–RQ13

Обеспечивают экспериментальную оценку:

- наблюдаемости;
- своевременности;
- информационной нагрузки.

---

# 8. Методологическая матрица

Главная трассировка исследования:

| Уровень | Артефакт |
|---|---|
| Research Problem | Problem Package |
| Research Objective | Research Passport |
| Research Tasks | Research Tasks |
| Research Questions | Research Questions |
| Research Design | Research Design Overview |
| Methods | Research Methods Matrix |
| Data | Data & Evidence Matrix |
| Procedures | Research Procedure Map |
| Measurement | Measurement & Evaluation Framework |
| Integrated Methodology | Research Methodology Package |
| Visual Architecture | Methodological Scheme |

Эта структура обеспечивает согласованность между концептуальным и операциональным уровнями исследования.

---

# 9. Основная методологическая матрица

| RQ | Primary Method | Evidence | Output | Evaluation |
|---|---|---|---|---|
| RQ1 | Domain Research + Case Study | documents, roles, expert evidence | Domain Map | completeness |
| RQ2 | Observation + Process Modelling | observations, process records | AS-IS | evidence coverage |
| RQ3 | Event/Data Analysis | events, timestamps, states | Event/State Model | observability sufficiency |
| RQ4 | Problem Analysis | deviations, delays, rework | Problem Register | evidence support |
| RQ5 | Root Cause Analysis | observations, interviews, process evidence | RCA | triangulation |
| RQ6 | KPI / Measurement Analysis | timestamps, counts, statuses | KPI Catalog | reproducibility |
| RQ7 | Functional IS Analysis | systems, files, reports | Information Landscape | information coverage |
| RQ8 | Literature + Comparative Analysis | scientific and technical sources | Methods Comparison | explicit criteria |
| RQ9 | GAP Analysis | problems + information + methods | GAP Matrix | traceability |
| RQ10 | Requirements Engineering | GAPs, problems, KPI | Requirements Set | requirement traceability |
| RQ11 | Conceptual Modelling | events, states, requirements | Conceptual Model | requirement coverage |
| RQ12 | Controlled Experiment | baseline/proposed evidence | H1/H2 Evaluation | completeness + TTD |
| RQ13 | Controlled Task Experiment | task-performance data | H3 Evaluation | time + effort + correctness |

---

# 10. Evidence Architecture

Исследовательские доказательства делятся на:

## Empirical Evidence

- реальные события;
- системные записи;
- наблюдение;
- timestamps;
- process instances;
- operational records.

## Structured Evidence

- BPMN;
- process maps;
- KPI;
- problem registers;
- GAP matrices;
- requirements matrices.

## Expert Evidence

- интервью;
- экспертные оценки;
- верификация моделей.

## Documentary Evidence

- нормативные документы;
- инструкции;
- регламенты;
- техническая документация.

## Scientific Evidence

- научная литература;
- исследования;
- существующие методы.

## Experimental Evidence

- baseline;
- proposed approach;
- контролируемые сценарии;
- тестовые результаты;
- синтетические данные, если необходимы.

---

# 11. Evidence Hierarchy

При интерпретации результатов используется следующая иерархия:

**Direct Evidence**

↓

**Structured Evidence**

↓

**Expert Evidence**

↓

**Documentary / Secondary Evidence**

↓

**Working Assumption**

Рабочее предположение не должно быть представлено как эмпирически установленный факт.

---

# 12. Triangulation

Для ключевых выводов по возможности используется несколько источников evidence.

Например:

**наблюдение**

+

**системная запись**

+

**документ**

+

**экспертное объяснение**

могут использоваться вместе для проверки фактической ситуации.

Однако разные источники не являются автоматически эквивалентными.

Экспертное мнение может объяснить наблюдаемую проблему, но само по себе не заменяет количественное доказательство её частоты.

---

# 13. Research Procedure Architecture

Все исследовательские процедуры строятся по единому шаблону:

**Input**

→

**Preparation**

→

**Procedure**

→

**Analysis**

→

**Output**

→

**Validation**

→

**Limitation**

→

**Traceability**

Это обеспечивает воспроизводимость.

---

# 14. Основные исследовательские фазы

## Phase 1 — Understand

**RQ1**

Domain Research + Case Study.

Результат:

**Domain Map + Process Hierarchy + Case Boundary.**

---

## Phase 2 — Reconstruct

**RQ2–RQ3**

Observation + Process Modelling + Event Analysis.

Результат:

**Normative Model + AS-IS + Event/State Model.**

---

## Phase 3 — Diagnose

**RQ4–RQ6**

Problem Analysis + RCA + KPI Analysis.

Результат:

**Problems + Causes + Measurements.**

---

## Phase 4 — Compare

**RQ7–RQ8**

Information Systems Analysis + Literature Review + Comparative Analysis.

Результат:

**Information Landscape + Methods Comparison.**

---

## Phase 5 — Specify

**RQ9–RQ10**

GAP Analysis + Requirements Engineering.

Результат:

**GAP Matrix + Requirements Set.**

---

## Phase 6 — Design

**RQ11**

Conceptual Modelling.

Результат:

**Conceptual Analytical and Intelligent Support Model.**

---

## Phase 7 — Evaluate

**RQ12–RQ13**

Controlled / Scenario-Based Evaluation.

Результат:

**H1/H2/H3 Assessment.**

---

# 15. Основные конструкты оценки

Методология использует три центральных конструкта.

## 15.1. Observability

Способность видеть и интерпретировать фактическое состояние и выполнение процесса.

Основная гипотеза:

**H1.**

---

## 15.2. Timeliness

Способность своевременно обнаруживать релевантные отклонения после появления достаточного evidence.

Основная гипотеза:

**H2.**

---

## 15.3. Information Load

Объём времени и действий, необходимых для поиска, сведения и обработки информации.

Основная гипотеза:

**H3.**

---

# 16. Measurement Framework

## H1 — Observability

Основная метрика:

**Detection Completeness**

\[
DC =
\frac{N_{detected}}
{N_{actual}}
\]

Дополнительные:

- Event Coverage;
- State Coverage;
- Deviation Coverage;
- Precision / Recall, если возможно определить reference labels.

---

## H2 — Timeliness

Основная метрика:

**Median Time-to-Detection**

\[
TTD =
T_{detection}
-
T_{observable}
\]

Дополнительные:

- P95 TTD;
- Early Detection Rate;
- Detection Before Critical Event.

---

## H3 — Information Load

Основная метрика:

**Task Completion Time**

\[
TCT =
T_{finish}
-
T_{start}
\]

Дополнительные:

- Number of Actions;
- Number of Sources;
- Context Switches;
- Manual Transformations;
- Accuracy;
- Completeness.

---

# 17. Основное правило измерения

Улучшение должно оцениваться не только по скорости.

Для каждого результата необходимо учитывать:

**Efficiency**

и одновременно

**Quality**.

Например:

сокращение времени выполнения задачи не считается положительным результатом H3, если при этом падает корректность ответа.

---

# 18. Baseline и Proposed Approach

## Baseline

Существующий или реалистично реконструированный способ выполнения задачи.

Может включать:

- ручной поиск;
- использование нескольких информационных источников;
- ручное сопоставление;
- просмотр статусов;
- постфактум анализ.

## Proposed Approach

Дополнительный аналитический и интеллектуальный контур, формируемый на основании:

**GAP → Requirements → Conceptual Design.**

Baseline и proposed должны быть сопоставимыми по исходным условиям.

---

# 19. Experimental Design

Для H1–H3 используются контролируемые или сценарные эксперименты.

Общая схема:

```text
Same Scenario
      │
 ┌────┴────┐
 ▼         ▼
Baseline  Proposed
 ▼         ▼
Measure   Measure
 └────┬────┘
      ▼
   Compare
      ▼
H1 / H2 / H3
```

При наличии достаточной выборки используются количественные методы анализа.

При ограниченной выборке применяются:

- descriptive statistics;
- case comparison;
- scenario analysis;
- median comparison;
- effect direction;
- structured qualitative interpretation.

---

# 20. Правила оценки гипотез

Для каждой гипотезы возможны четыре результата:

### Supported

Ожидаемый эффект обнаружен и подтверждён соответствующими показателями.

### Partially Supported

Эффект существует только для части сценариев или условий.

### Not Supported

Ожидаемого эффекта не обнаружено.

### Inconclusive

Evidence недостаточно для обоснованного вывода.

Использование такой шкалы предпочтительнее принудительного бинарного `accepted/rejected`.

---

# 21. Guard Metrics

Основной показатель не используется изолированно.

Для H1:

**Detection Completeness**

дополняется проверкой ложных обнаружений, если это возможно.

Для H2:

**TTD**

сопоставляется с корректностью обнаружения.

Для H3:

**Task Completion Time**

сопоставляется с Accuracy и Completeness.

Таким образом, нельзя получить положительный результат только за счёт ухудшения качества.

---

# 22. Ограничения методологии

Методологический пакет явно учитывает потенциальные ограничения:

- неполные event logs;
- отсутствие timestamps;
- неоднородность источников;
- экспертную субъективность;
- ограниченный размер выборки;
- недоступность корпоративной архитектуры;
- ограниченную воспроизводимость отдельных операционных процессов;
- использование синтетических данных;
- ограниченную внешнюю валидность кейса.

Ограничение не является основанием для сокрытия результата.

Оно должно быть отражено в интерпретации.

---

# 23. Работа с отсутствующими данными

Если полноценные данные недоступны, применяются уровни:

### Level 1

Реальные обезличенные данные.

### Level 2

Комбинация реальных данных, наблюдения, документов и экспертной информации.

### Level 3

Синтетические данные и контролируемые сценарии.

Результаты разных уровней evidence не должны смешиваться без явного обозначения.

---

# 24. Условие применения Process Mining

Process mining не является обязательным методом.

Он применяется только при наличии данных, из которых возможно построить пригодный event log, содержащий, как минимум:

**Case ID + Activity + Timestamp.**

При недостатке данных применяются другие методы:

- observation;
- process modelling;
- document analysis;
- event reconstruction;
- expert methods.

---

# 25. Условие применения AI / Machine Learning

Использование AI/ML определяется не формулировкой темы, а исследовательской необходимостью.

Перед применением AI/ML должны быть определены:

- исследовательская задача;
- тип входных данных;
- ожидаемый результат;
- критерий оценки;
- необходимая data basis;
- преимущества по сравнению с более простым методом.

Если задача может быть решена интерпретируемым rule-based или аналитическим подходом без потери исследовательской ценности, более сложный метод не является обязательным.

---

# 26. Research Traceability

Ключевая трассировка всего исследования:

```text
Problem
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
Finding
  ↓
GAP
  ↓
Requirement
  ↓
Solution
  ↓
Evaluation
  ↓
Hypothesis
  ↓
Conclusion
```

Для каждого итогового вывода должна существовать возможность двигаться по этой цепочке в обратную сторону.

---

# 27. Двусторонняя трассировка

## Forward

**Problem → Conclusion**

Позволяет проверить, что исследование отвечает исходной проблеме.

## Backward

**Conclusion → Evidence**

Позволяет проверить обоснованность каждого существенного утверждения.

Обе формы трассировки являются обязательными для критических исследовательских выводов.

---

# 28. Quality Control

Перед использованием конкретного результата необходимо проверить:

### Relevance

Относится ли evidence к соответствующему RQ?

### Reliability

Насколько надёжен источник?

### Completeness

Достаточно ли evidence?

### Consistency

Не противоречит ли оно другим источникам?

### Reproducibility

Можно ли повторить процедуру?

### Traceability

Можно ли связать результат с исходными данными?

---

# 29. Итоговая проверка методологии

| Проверка | Статус |
|---|---|
| Research Problem определена | ✅ |
| Objective определена | ✅ |
| Tasks определены | ✅ |
| RQ0–RQ13 определены | ✅ |
| Methods назначены для RQ | ✅ |
| Evidence определено | ✅ |
| Procedures определены | ✅ |
| Constructs H1–H3 определены | ✅ |
| Metrics определены | ✅ |
| Baseline определён концептуально | ✅ |
| Proposed Approach определён концептуально | ✅ |
| Evaluation logic определена | ✅ |
| Traceability определена | ✅ |
| Работа с missing data определена | ✅ |
| Synthetic data rules определены | ✅ |
| Process Mining не навязан заранее | ✅ |
| AI/ML не навязан заранее | ✅ |
| Возможен inconclusive result | ✅ |
| Ограничения методологии учтены | ✅ |

---

# 30. Методологическая схема

Итоговая схема исследования:

```text
                    RESEARCH PROBLEM
                           ↓
                    RESEARCH OBJECTIVE
                           ↓
                     RESEARCH TASKS
                           ↓
                    RESEARCH QUESTIONS
                           ↓
              ┌────────────┴────────────┐
              ↓                         ↓
       DOMAIN / CASE              STATE OF THE ART
       INVESTIGATION                  / METHODS
              ↓                         ↓
         AS-IS PROCESS            METHODS LANDSCAPE
              └────────────┬────────────┘
                           ↓
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
                  ↓        ↓        ↓
                 H1       H2       H3
            Observability Timeliness Information Load
                  └────────┼────────┘
                           ↓
                       RQ CLOSURE
                           ↓
                  RESEARCH CONCLUSION
```

---

# 31. Методологический принцип исследования

Основной принцип пакета:

> **Сначала устанавливается, что происходит в реальном процессе; затем определяется, почему возникает проблема и как она измеряется; после этого исследуется существующий информационный и методологический контур; далее определяется GAP, выводятся требования и только затем формируется и оценивается предлагаемое решение.**

Это предотвращает technology-first подход.

---

# 32. Что является результатом третьей недели

К концу третьей недели сформирована следующая методологическая система:

### Research Design

Определяет архитектуру исследования.

### Research Methods Matrix v2

Определяет методы для каждого RQ.

### Data & Evidence Matrix v1

Определяет evidence и данные.

### Research Procedure Map v1

Определяет последовательность исследовательских процедур.

### Measurement & Evaluation Framework v1

Определяет операционализацию H1–H3 и критерии оценки.

### Methodological Scheme v1

Представляет единую методологическую архитектуру.

### Research Methodology Package v1

Объединяет все перечисленные компоненты в единый рабочий пакет.

---

# 33. Критерий завершения недели 3

Третья неделя считается методологически завершённой, если:

1. каждый RQ имеет метод;
2. каждый метод имеет соответствующее evidence;
3. каждая процедура имеет вход и результат;
4. каждый ключевой результат имеет критерий проверки;
5. H1–H3 операционализированы;
6. baseline/proposed определены;
7. GAP связан с requirements;
8. requirements связаны с solution;
9. solution связана с evaluation;
10. вся система трассируема до Research Problem.

---

# 34. Финальная формула Research Methodology Package

Методологический пакет фиксируется следующей формулой:

**Problem**

→

**Questions**

→

**Methods**

→

**Evidence**

→

**Procedures**

→

**Measurements**

→

**Design**

→

**Evaluation**

→

**Conclusion**.

Или в более операциональном виде:

**RQ → Method → Data → Procedure → Result → Metric → Evaluation.**

---

# 35. Статус

**Название:** Research Methodology Package v1

**Версия:** v1

**Статус:** интегрированный методологический пакет третьей недели.

**Назначение:** основной рабочий reference для проведения дальнейшей эмпирической части исследования.

**Зависимости:**

- Research Passport;
- Research Problem Package;
- Research Tasks;
- Research Questions;
- Research Design Overview v1;
- Research Methods Matrix v2;
- Data & Evidence Matrix v1;
- Research Procedure Map v1;
- Measurement & Evaluation Framework v1;
- Methodological Scheme v1.

**Следующий этап исследования:** переход к предметной области по плану 4-й недели.

Основные ближайшие результаты:

**Glossary v1**

→

**Domain Map v1**

→

**Stakeholder Map v1**

→

**Process Hierarchy v1**

→

**выбор и окончательное описание исследуемого процесса.**