
| $a$ | $b$ | $a\land b$ | $a\underline{◼}b$ | $(a\underline{◼}a)\underline{◼}b$ |     |
| --- | --- | ---------- | ----------------- | --------------------------------- | --- |
| T   | T   | T          | T                 | F                                 |     |
| T   | F   | F          | T                 | T                                 |     |
| F   | T   | F          | F                 | F                                 |     |
| F   | F   | F          | T                 | T                                 |     |

$$
\neg(\neg a\underline{◼}b)\equiv a\land b
$$
$$
a\underline{◼}b\equiv b\implies a
$$
$$
a\underline{◼}b\equiv \neg a\implies \neg b
$$
$$
a\underline{◼}b\equiv\neg b\underline{◼}\neg a
$$
$$
a\underline{◼}a\equiv a\land \neg a\equiv F
$$
$$
(a\underline{◼}a)\underline{◼}a\equiv \neg a
$$
$$
((a\underline{◼}a)\underline{◼}(\neg a\underline{◼}b))\equiv a\land b
$$
$$
((a\underline{◼}a)\underline{◼}((a\underline{◼}a)))
$$
$$
F\underline{◼}a\equiv \neg a
$$