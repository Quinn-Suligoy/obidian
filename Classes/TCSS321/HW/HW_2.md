# 2
$p$: you prepare your taxes carefully
$q$: you will pay more taxes than you need to
$r$: you will be thrown in jail for tax evasion
$\neg p\implies(q\lor r)$
# 3
## a
$p$: it is raining in Minneapolis
$q$: it is snowing in Buffalo
$r$: it is foggy in Seattle
## b
$(p\land \neg q)\implies r$
$r\iff \neg q$
$q$
## c

| $p$   | $q$   | $r$   | $\neg q$ | $(p\land \neg q)$ | $(p\land \neg q)\implies r$ | $r\iff \neg q$ | $q$   |
| ----- | ----- | ----- | -------- | ----------------- | --------------------------- | -------------- | ----- |
| T     | T     | T     | F        | F                 | T                           | F              | T     |
| **T** | **T** | **F** | **F**    | **F**             | **T**                       | **T**          | **T** |
| T     | F     | T     | T        | T                 | T                           | T              | F     |
| T     | F     | F     | T        | T                 | F                           | F              | F     |
| F     | T     | T     | F        | F                 | T                           | F              | T     |
| **F** | **T** | **F** | **F**    | **F**             | **T**                       | **T**          | **T** |
| F     | F     | T     | T        | F                 | T                           | T              | F     |
| F     | F     | F     | T        | F                 | T                           | F              | F     |
No we cannot, assuming all statements are true $p$ can either be true or false. For all statements to be true either it is raining in Minneapolis, it is snowing in Buffalo, and it is not foggy in Seattle. Or it is not raining in Minneapolis, it is snowing in Buffalo, and it is not foggy in Seattle.
# 4
## a
$p$: Priya joins the computer science club
$q$: Quienten joins the computer club
$r$: Rosalita joins the computer club
## b
$(p\lor q)\implies r$
$q\implies \neg p$
$p \iff r$

| $p$   | $q$   | $r$   | $p\lor q$ | $(p\lor q)\implies r$ | $q\implies \neg p$ | $p \iff r$ |
| ----- | ----- | ----- | --------- | --------------------- | ------------------ | ---------- |
| T     | T     | T     | T         | T                     | F                  | T          |
| T     | T     | F     | T         | F                     | F                  | F          |
| **T** | **F** | **T** | **T**     | **T**                 | **T**              | **T**      |
| T     | F     | F     | T         | F                     | T                  | F          |
| F     | T     | T     | T         | T                     | T                  | F          |
| F     | T     | F     | T         | F                     | T                  | T          |
| F     | F     | T     | F         | T                     | F                  | F          |
| F     | F     | F     | F         | T                     | F                  | T          |

# c
Yes, if Priya and Rosalita join and Quienten does not, then all three statements are true
# 5

| $p$ | $q$ | $r$ | $\neg r$ | $q\land \neg r$ | $\neg p$ | $(q\land \neg r)\lor \neg p$ |
| --- | --- | --- | -------- | --------------- | -------- | ---------------------------- |
| T   | T   | T   | F        | F               | F        | F                            |
| T   | T   | F   | T        | T               | F        | T                            |
| T   | F   | T   | F        | F               | F        | F                            |
| T   | F   | F   | T        | F               | F        | F                            |
| F   | T   | T   | F        | F               | T        | T                            |
| F   | F   | T   | T        | F               | T        | T                            |
| F   | T   | F   | F        | F               | T        | T                            |
| F   | F   | F   | T        | F               | T        | T                            |
$\neg p\land()$
# 6
