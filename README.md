# Meta-CY Quantum Computing

## 🌌 Overview (EN)

**Meta-CY Quantum Computing** is a new computational paradigm that extends quantum information theory beyond qubits and qudits.  
Instead of states living in simple Hilbert spaces, information is carried by **CYbits** — states defined on Calabi–Yau (CY) manifolds.  

- **CYbit**: Local state on a CY manifold (generalization of a qudit).  
- **CYlinks**: Connections between CYbits via CY topology and graph structures.  
- **Meta-CYbit**: Higher-level functional over CY states.  

## 📖 Description
This project is dedicated to the study of **spectral properties of graphs on Calabi–Yau (CY) manifolds**.  
The central hypothesis is that as the number of discretization points $N$ increases, the spectrum of the discrete Laplacian converges to the spectrum of the Laplace–Beltrami operator on $M$. Moreover, spectral features (degeneracies, gaps) encode information about the topology of CY spaces (e.g., Hodge numbers).  

The project is part of the **LLC "VOSCOM ONLINE" Research Initiative** and aims to develop the concept of **CYbits** and their meta-extensions.  

- A **CYbit** is defined as a wavefunction over a Calabi–Yau manifold, with Hilbert space  
  $\mathcal{H}_{CY} = L^2(M, \mathbb{C}^d)$.  
- A **Meta-CYbit** is defined at the next level of quantization, with wave functionals living in  
  $\mathcal{H}_{Meta} = L^2(\mathcal{H}_{CY}, \mathcal{D}\psi)$.  

This hierarchy (bit → qubit → qudit → CYbit → Meta-CYbit) opens a new class of computational models, where quantum principles are embedded directly into the structure of computation.

This approach unifies:
- Higher-dimensional qudits,  
- Topology of Calabi–Yau manifolds,  
- Quantum graphs.  

➡️ Potential: exponential expansion of computational space.  

For example, with only 10 nodes:  
- Qubits (2D): ~10³ states  
- Qudits (d=10): 10¹⁰ states  
- CY-3D (m=10): 10³⁰ states  
- CY-6D (m=10): 10⁶⁰ states  
- **Meta-CYbits**: super-exponential functional space  
  ($\mathcal{H}_{Meta} = L^2(\mathcal{H}_{CY}, \mathcal{D}\psi)$)


---

## 🚀 Обзор (RU)

**Meta-CY квантовый компьютер** — это новая вычислительная парадигма, в которой носителями информации выступают состояния на многообразиях Калаби–Яу.  

- **CYбит**: локальное состояние на CY-многообразии (обобщение кудита).  
- **CYlinks**: связи между CYбитами через топологические циклы CY.  
- **Meta-CYбит**: функционал на пространстве CY-состояний.  

Идея объединяет:
- Кудиты высокой размерности,  
- Топологию многообразий Калаби–Яу,  
- Квантовые графы.  
## 📖 Описание
Этот проект посвящён исследованию **спектральных свойств графов на многообразиях Калаби–Яу (CY)**.  
Основная гипотеза: при увеличении числа точек дискретизации $N$ спектр дискретного лапласиана сходится к спектру лапласиана–Бельтрами на $M$. При этом особенности спектра (разрывы, вырождения) несут информацию о топологии CY (например, числа Ходжа).  

Проект является частью инициативы **LLC "VOSCOM ONLINE" Research** и направлен на построение концепции **CY-битов** и их мета-расширений.  

- **CYбит** определяется как волновая функция на многообразии Калаби–Яу с гильбертовым пространством  
  $\mathcal{H}_{CY} = L^2(M, \mathbb{C}^d)$.  
- **Мета-CYбит** задаётся на следующем уровне квантования: это волновые функционалы в пространстве  
  $\mathcal{H}_{Meta} = L^2(\mathcal{H}_{CY}, \mathcal{D}\psi)$.  

Эта иерархия (бит → кубит → кудит → CYбит → Мета-CYбит) открывает новый класс вычислительных моделей, где квантовые принципы встроены в саму структуру вычислений.


➡️ Потенциал: экспоненциальное расширение пространства вычислений.  

Например, для всего лишь 10 узлов:  
- Кубиты (2D): ~10³ состояний  
- Кудиты (d=10): 10¹⁰ состояний  
- CY-3D (m=10): 10³⁰ состояний  
- CY-6D (m=10): 10⁶⁰ состояний  
- **Мета-CYбиты**: суперэкспоненциальное функциональное пространство  
  ($\mathcal{H}_{Meta} = L^2(\mathcal{H}_{CY}, \mathcal{D}\psi)$)


## 📂 Repository Structure

- `paper/(en|ru)` — LaTeX source of the research overview.  
- `slides/` — Beamer presentation (RU).  
- `README.md` — This document.  
- `CITATION.cff` — Citation information.  
- `LICENSE` — Open license for the materials.  

---

## 📄 Citation (BibTeX - EN)

```bibtex
@misc{cy_spectral_graphs_2025,
  author       = {Evgeny Monakhov and LCC "VOSCOM ONLINE" Research Initiative},
  title        = {Spectral Graphs on Calabi--Yau Manifolds},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.17050352},
  url          = {https://doi.org/10.5281/zenodo.17050352}
  orcid		   = {0009-0003-1773-5476}
  url_orcid    = {https://orcid.org/0009-0003-1773-5476}
  organization = {https://voscom.online/}
}
