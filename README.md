# Vizuálny transformer so sekundárym vynorením
Diplomová práca zameraná na experimentálne prístupy ku klasifikácii obrazu vo Vision Transformeroch pomocou viacvektorového vynorenia kategórií.

## Popis projektu

Vision Transformery (ViT) patria medzi moderné architektúry určené na klasifikáciu obrazu. Štandardne býva klasifikácia realizovaná pomocou vynorenia kde sa výstupný CLS token porovnáva s reprezentantmi tried.

Hlavným cieľom práce je experimentálne overiť prístup, v ktorom môže byť jedna kategória reprezentovaná viacerými vektormi namiesto jedného.

---

## Ciele práce

- analyzovať architektúru Vision Transformerov,
- preskúmať klasické klasifikačné hlavy vo Vision Transformeroch,
- implementovať klasifikáciu založenú na vynorení,
- porovnať navrhnutý prístup s klasickým prístupom,
- vyhodnotiť výsledky

---

## Predbežný plán experimentov

Experimenty budú zamerané na porovnanie:

- klasifikácie založenej na vynorení
- viacvektorového modelu vynorenia


---

## Použité technológie

- Python
- PyTorch
- torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Aktuálny progres

- [x] Založenie GitHub repozitára
- [x] Príprava LaTeX kostry práce
- [x] Základný prehľad literatúry
- [x] Testovanie knižníc a Vision transformeru z torch vision knižnice
- [x] Príprava prezentácie na Projektový seminár 1
- [ ] Implementácia baseline Vision Transformer modelu
- [ ] Implementácia klasického classification head
- [ ] Implementácia klasifikácie založenej na vynorení
- [ ] Implementácia viacvektorového modelu vynorenia
- [ ] Experimentálne vyhodnotenie
- [ ] Finalizácia diplomovej práce

---

## Štruktúra repozitára

```text
.
├── docs/           # diplomová práca, literatúra, PDF a .bib súbor
├── experiments/    # experimenty a notebooky
├── src/            # implementácia modelov
├── data/           # datasety
├── results/        # výsledky experimentov
└── README.md
```

---

## Literatúra

- Dosovitskiy et al. — An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale
- Vaswani et al. — Attention Is All You Need

---

## Autor

Bc. Matej Miškovčík  
FMFI UK Bratislava
