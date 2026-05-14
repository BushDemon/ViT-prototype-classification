# Vizuálny transformer so sekundárym vynorením
Diplomová práca zameraná na experimentálne prístupy ku klasifikácii obrazu vo Vision Transformeroch pomocou viacvektorového vynorenia kategórií.

## Popis projektu

Vision Transformery (ViT) patria medzi moderné architektúry určené na klasifikáciu obrazu. Štandardne býva klasifikácia realizovaná pomocou klasifikačnej hlavy (MLP head), ktorá zo špeciálneho CLS tokenu vypočítava logaritmy pravdepodobností jednotlivých tried.

Táto diplomová práca sa zaoberá alternatívnym prístupom ku klasifikácii, označovaným ako vynorenie, pri ktorom sa výstupný CLS token porovnáva s vektormi reprezentujúcimi jednotlivé kategórie.

Hlavným cieľom práce je experimentálne overiť prístup, v ktorom môže byť jedna kategória reprezentovaná viacerými vektormi namiesto jedného prototypu. Tento prístup môže umožniť lepšie zachytenie variability objektov v rámci jednej triedy.

---

## Ciele práce

- analyzovať architektúru Vision Transformerov,
- preskúmať klasické klasifikačné hlavy vo Vision Transformeroch,
- implementovať klasifikáciu založenú na vynorení,
- navrhnúť viacvektorovú reprezentáciu kategórií,
- experimentálne porovnať navrhnutý prístup s klasickým MLP head prístupom,
- vyhodnotiť výsledky pomocou metrík klasifikácie.

---

## Predbežný plán experimentov

Experimenty budú zamerané na porovnanie:

- klasického MLP head prístupu,
- klasifikácie založenej na vynorení,
- viacvektorového modelu vynorenia.

Vyhodnocované budú napríklad:

- accuracy,
- validation loss,
- confusion matrix,
- stabilita učenia,
- podobnosť embeddingov.

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

- [x] Schválenie témy diplomovej práce
- [x] Založenie GitHub repozitára
- [x] Príprava LaTeX kostry práce
- [x] Základný prehľad literatúry
- [x] Testovanie knižníc a Vision transformeru z torch vision knižnice 
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
