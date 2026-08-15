# Binary Payment Schemes: Moral Hazard and Loss Aversion

[![Status](https://img.shields.io/badge/Status-Completed-green)]
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex)]
[![Course](https://img.shields.io/badge/Course-Market%20Design%20and%20Behaviour-blue)]

Academic literature review presentation on Herweg, Müller, and Weinschenk (2010),
*Binary Payment Schemes: Moral Hazard and Loss Aversion*.

## Project Information

| Item | Details |
|---|---|
| Author | Theo Osterhaus, 7443693 |
| Course | Seminar Market Design and Behaviour, SS 2026 |
| Institution | Universität zu Köln |
| Year | 2026 |
| Format | Academic presentation (literature review) |
| Main paper | Herweg, Müller & Weinschenk (2010), *American Economic Review* |

## Abstract

This project reviews the theoretical and empirical literature on the puzzle of
contractual simplicity in real-world incentive schemes. It focuses on Herweg,
Müller, and Weinschenk (2010), who introduce expectation-based loss aversion
into a standard principal–agent model with moral hazard to explain why simple,
binary bonus contracts are frequently observed instead of the fully contingent
wage schedules predicted by classical contract theory.

## Research Questions

1. Why do real-world contracts tend to be simple (e.g., binary bonus schemes)
   despite classical theory predicting complex, fully contingent contracts?
2. How does expectation-based loss aversion alter the optimal design of
   incentive contracts?
3. What is the trade-off between incentive provision and psychological
   (loss aversion) costs as contract complexity increases?
4. What empirical evidence supports expectation-based reference points in
   effort and labour supply decisions?

## Outline

1. Contract Theory & Incentive Schemes
2. Theoretical Framework
3. Model Results
4. Empirical Support
5. Outlook

## The Central Puzzle

Classical contract theory (Holmström, 1979) predicts that optimal contracts
should be complex, fully exploiting all available information. However,
real-world contracts (e.g., binary bonus schemes, flat wages) are often
remarkably simple.

| Contribution | Insight |
|---|---|
| Baker (1988) | First documented the discrepancy between theory and practice |
| Prendergast (1999) | Established the puzzle; survey-based, no causal identification |
| Lazear & Oyer (2007) | Argues there must be unmodelled benefits to simple contracts |
| Herweg, Müller & Weinschenk (2010) | Provides a behavioural explanation via loss aversion |

## Theoretical Framework

Herweg, Müller, and Weinschenk (2010) build on Kőszegi and Rabin (2006) by
introducing **expectation-based loss aversion** into the principal–agent
moral hazard model.

### Key Concepts

- **Reference point**: Individuals evaluate outcomes relative to their
  entire anticipated probability distribution of wages, not a fixed point.
- **Loss aversion**: Losses loom larger than equivalent gains
  (Kahneman & Tversky, 1979).
- **Choice-Acclimating Personal Equilibrium (CPE)**: The agent correctly
  anticipates the wage distribution induced by his own effort choice, and
  this anticipated distribution becomes the reference point (Kőszegi &
  Rabin, 2007).

## Main Result: Why Binary Schemes?

The model identifies a trade-off between two opposing effects of adding
wage levels to a contract:

| Effect | Description |
|---|---|
| Incentive Gain | More wage levels → finer performance signals → higher marginal returns to effort |
| Loss Aversion Cost | More wage levels → larger support of the reference distribution → more possible unfavourable comparisons → higher expected psychological costs |

### The Optimality Theorem

When loss aversion is sufficiently high, the principal minimises
psychological costs by offering a **base wage plus a single bonus**
(a binary scheme), even when richer performance signals are available —
in contrast to the fully contingent wage schedule predicted by standard
theory (Holmström, 1979).

## Empirical Support

The behavioural foundations of the model are supported by:

| Study | Setting | Finding |
|---|---|---|
| Crawford & Meng (2011) | NYC cab drivers | Expectation-based reference targets outperform the neoclassical labour supply model |
| Abeler et al. (2011) | Lab real-effort experiment | Manipulating expectations shifts effort in the direction predicted by loss aversion models |

## Outlook

- The central prediction — that binary schemes are optimal — has not yet
  been directly tested experimentally (addressed in a follow-up presentation).
- Herweg and Schmidt (2015) extend the framework to dynamic settings,
  showing that expectation-based loss aversion can also explain
  **inefficient renegotiation**, suggesting explanatory power beyond
  static moral hazard.

## Limitations

- The reviewed model relies on the CPE solution concept, which assumes
  agents correctly anticipate the wage distribution their effort induces.
- Direct empirical tests of the binary-scheme prediction are still lacking.
- Behavioural evidence supporting the mechanism comes from related but
  distinct settings (labour supply, lab experiments), not the specific
  contract-design context.

## Materials
- [LaTeX source](./main.tex)
- [Bibliography](./reference.bib)

## Reproducibility

The presentation was created with LaTeX (Beamer). The main source file is
`main.tex`; references are stored in `references.bib`.

## References

- Abeler, J. et al. (2011). *Reference Points and Effort Provision*. American Economic Review, 101(2), 470–492.
- Baker, G. (1988). *Compensation and Incentives: Practice vs. Theory*. The Journal of Finance, 43(3), 593–616.
- Crawford, V. P., & Meng, J. (2011). *New York City Cab Drivers' Labor Supply Revisited*. American Economic Review, 101(5), 1912–1932.
- Herweg, F., Müller, D., & Weinschenk, P. (2010). *Binary Payment Schemes: Moral Hazard and Loss Aversion*. American Economic Review, 100(5), 2451–2477.
- Herweg, F., & Schmidt, K. M. (2015). *Loss Aversion and Inefficient Renegotiation*. The Review of Economic Studies, 82(1), 297–332.
- Holmström, B. (1979). *Moral Hazard and Observability*. The Bell Journal of Economics, 10(1), 74–91.
- Kahneman, D., & Tversky, A. (1979). *Prospect Theory: An Analysis of Decision under Risk*. Econometrica, 47(2), 263–291.
- Kőszegi, B., & Rabin, M. (2006). *A Model of Reference-Dependent Preferences*. The Quarterly Journal of Economics, 121(4), 1133–1165.
- Kőszegi, B., & Rabin, M. (2007). *Reference-Dependent Risk Attitudes*. American Economic Review, 97(4), 1047–1073.
- Lazear, E. P., & Oyer, P. (2007). *Personnel Economics*. NBER Working Paper 13480.
- Prendergast, C. (1999). *The Provision of Incentives in Firms*. Journal of Economic Literature, 37(1), 7–63.

## Disclaimer

This repository contains academic coursework and presentation materials.
The theoretical and empirical results reported here originate from the
referenced studies and are not original contributions by the repository
author unless explicitly stated.