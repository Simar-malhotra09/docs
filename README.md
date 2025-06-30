

This repository is a (personally) curated collection of notes, blogs, and resources across several domains.



### 🧠 Contents

- [**Code**](#code)
  - [Computer Vision](#computer-vision)
  - [Software Optimization](#software-optimization)
  - [Git](#git)

- [**Quant**](#quant)
  - [General](#general)
  - [Risk Management](#risk-management)
  - [Indian Markets](#indian-markets)

- [**Material Science**](#material-science)
  - [2D Materials & TEM](#2d-materials--tem)

---

## Code 

### Computer Vision
1. [The Chan-Vese Algorithm](https://arxiv.org/abs/1107.2782) – [PAPER] An active contour segmentation method effective for objects without well-defined edges. [skimage API](https://scikit-image.org/docs/0.25.x/auto_examples/segmentation/plot_chan_vese.html#sphx-glr-auto-examples-segmentation-plot-chan-vese-py)
2. [Accelerating Chan-Vese Model with Cross Modality Guided
Contrast Enhancement for Liver Segmentation](https://helvia.uco.es/xmlui/bitstream/handle/10396/30548/Author_copy_Chan_vese.pdf?isAllowed=y&sequence=3)- [PAPER] contrast enhancement as preprocessing step and gpu implementation of Chan-Vese. They do not provide any code, only the design.

### Software Optimization
1. [Software optimization resources](https://www.agner.org/optimize/) – [WEBPAGE] Manuals on optimizing C++ and assembly for different platforms (Linux, Windows, macOS), guides to Intel and AMD CPU architectures, and more.
2. [What does it mean for code to be "cache-friendly"?](https://stackoverflow.com/questions/16699247/what-does-it-mean-for-code-to-be-cache-friendly) – [FORUM]
3. [On memory optimization (by the folks over at Sony)](https://web.archive.org/web/20160422113037/http://www.research.scea.com/research/pdfs/GDC2003_Memory_Optimization_18Mar03.pdf) – [PDF]
4. [C++ Design Patterns for Low-latency Applications Including High-frequency Trading](https://arxiv.org/abs/2309.04259) – [PAPER] Cache warming, `constexpr`, and more.
5. [Follow-up discussion on 4](https://news.ycombinator.com/item?id=40908273) – [FORUM] Hacker News thread with helpful commentary.

### Git
1. [Git fetch vs pull](https://longair.net/blog/2009/04/16/git-fetch-and-merge/) – [BLOG] Why you should use `git fetch` + merge/rebase instead of `pull`. Probably the clearest explanation of Git I’ve encountered.



## Quant

### General
1. [arXiv Quantitative Finance archive](https://arxiv.org/archive/q-fin) – [PAPER]
2. [AQR Capital](https://www.aqr.com/Insights/Research) – [WEBPAGE] One of the few management firms consistently publishing high-quality, research-driven blogs.
3. [Quantocracy](https://quantocracy.com/) – [WEBPAGE] Curated mashup of quantitative trading links.

### Risk Management
1. [A Full Guide to Risk Management](https://www.vertoxquant.com/p/a-full-guide-to-risk-management) – [BLOG] Covers risk metrics like VaR, volatility modeling, and more—with code.

### Indian Markets 
1. [SEBI's working papers](https://www.sebi.gov.in/sebiweb/home/HomeAction.do?doListing=yes&sid=4&ssid=81&smid=104)- [WEBPAGE]
2. [SEBI's links for market data](https://www.sebi.gov.in/Curation_Links_for_Securities_Market_Data.html)- [WEBPAGE]
   

## Material Science

### 2D Materials & TEM
1. [Transmission Electron Microscopy](https://www.nanoscience.com/techniques/transmission-electron-microscopy/) – [WEBPAGE] A guide to the science behind the setup and interactions of a TEM.
2. [Two-dimensional MoS₂: Properties, preparation, and applications](https://www.sciencedirect.com/science/article/pii/S2352847815000040) – [PAPER]
3. [Graphene as a sample support in TEM](https://arxiv.org/pdf/1204.6647) – [PAPER]
4. [Analyzing 2D material microstructure via TEM](https://appmicro.springeropen.com/articles/10.1186/s42649-019-0013-5) – [PAPER]
5. [Deep learning for defect analysis in TEM](https://www.sciencedirect.com/science/article/pii/S258900422302059X) – [PAPER]
6. [DefectTrack: real-time defect tracking in in-situ TEM](https://pmc.ncbi.nlm.nih.gov/articles/PMC9489724/) – [PAPER]
7. [STEM image analysis with deep learning](https://arxiv.org/pdf/2206.04272) – [PAPER] CNNs for identifying sulfur vacancies & MoS₂ polymorphs.

