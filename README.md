<p align="center">
  <h1 align="center">SCI-CAST</h1>
  <p align="center"><b>Scientific Computing & Academic Casting Toolkit</b></p>
  <p align="center"><i>Bridge your science with the right cast.</i></p>
</p>

<p align="center">
  <a href="https://github.com/ye-zi-ming/SCI-CAST/releases/tag/v3.2.0">
    <img src="https://img.shields.io/badge/Download-v3.2.0_Windows_x64-blue?style=for-the-badge&logo=windows" alt="Download v3.2.0">
  </a>
  &nbsp;&nbsp;
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-GPL--3.0-green?style=for-the-badge" alt="GPL-3.0">
  </a>
</p>

<p align="center">
  <b>
    <a href="https://github.com/ye-zi-ming/SCI-CAST/releases/download/v3.2.0/SCI-CAST_v3.2.0_Windows_x64.zip">
      >>> Download SCI-CAST v3.2.0 (Windows x64) <<<
    </a>
  </b>
</p>

> Download, unzip, and double-click SCI-CAST.exe — no install required.
>
> 下载、解压、双击 SCI-CAST.exe — 无需安装。

---

## Modules / 功能模块

![SCI-CAST home page](assets/screenshots/home.png)

**v3.2.0 includes five modules / 内置五个模块:**

| Module | Description | 描述 |
|--------|-------------|------|
| **Crys-CAST** | Search 10,000+ zeolite, MOF & COF crystal structures | 搜索 10,000+ 沸石、MOF 和 COF 晶体结构 |
| **CIF-CAST** | Convert crystal structure files (10+ formats) with charge calculation | 晶体结构格式转换（10+ 格式）+ 电荷计算 |
| **Grid-CAST** | Batch convert volumetric grid files (.cube, .grd, .xsf, CHGCAR) | 批量转换体积网格文件 |
| **Pub-CAST** | Journal matching & reviewer discovery | 期刊匹配与审稿人推荐 |
| **Ref-CAST** | Reference fetching, cleanup & export (10+ citation styles) | 文献获取、清洗与导出（10+ 引用样式） |

### Crys-CAST — Crystal Structure Database / 晶体结构数据库

![Crys-CAST](assets/screenshots/cryscast.png)

Browse and search crystal structure databases with advanced filtering:

浏览和搜索晶体结构数据库，支持高级筛选：

- **Zeolite**: 200+ framework topologies, idealized pure-silica CIFs / 200+ 种框架拓扑
- **MOF**: 10,000+ metal-organic framework structures / 10,000+ 金属有机框架结构
- **COF**: 1,000+ covalent organic framework structures / 1,000+ 共价有机框架结构

Features / 功能: search by common name (MOF-5, HKUST-1, UiO-66, ZIF-8 …), crystal system filter (with FCC/BCC primitive cell detection), cell parameter tolerance search (±%), topology/metal/element filters, single-CIF download, batch CSV+CIF zip export.

按常用名搜索，晶系筛选（含 FCC/BCC 原胞识别），晶胞参数容差搜索，拓扑/金属/元素筛选，单 CIF 下载，批量 CSV+CIF 导出。

### CIF-CAST — Structure File Converter / 结构文件转换

![CIF-CAST](assets/screenshots/cifcast.png)

Convert crystal structure files across 10+ formats:

转换 10+ 种晶体结构文件格式：

- **Input / 输入**: CIF, POSCAR, XDATCAR, XYZ, ExtXYZ, PDB, MOL, SDF, RES, LAMMPS dump
- **Output / 输出**: CIF, POSCAR, RES, PDB, ExtXYZ, XYZ, MOL, SDF
- **Features / 功能**: Symmetry expansion (P1), supercell, periodic/non-periodic modes, multi-file batch / 对称性展开、超胞、周期/非周期模式、多文件批量转换
- **Charge calculation / 电荷计算**: EQeq (built-in / 内置) and PACMAN (DDEC6/Bader/CM5/REPEAT)

### Grid-CAST — Grid File Converter / 网格文件转换

![Grid-CAST](assets/screenshots/gridcast.png)

Batch convert volumetric grid files: .cube ↔ .grd ↔ .xsf ↔ CHGCAR/LOCPOT. Progress bar + ETA + cancel support.

批量转换体积网格文件，支持进度条、预计时间和取消操作。

### Pub-CAST — Journal Matching / 期刊匹配

![Pub-CAST](assets/screenshots/pubcast.png)

- **Pub-Match**: Paste title + abstract → journal candidates + reviewer shortlists / 粘贴标题 + 摘要 → 候选期刊 + 审稿人推荐
- **Ref-Filter**: Browse 22,000+ journals by field, impact factor, quartile, zone / 浏览 22,000+ 期刊分区数据库

### Ref-CAST — Reference Manager / 文献管理

![Ref-CAST](assets/screenshots/refcast.png)

- 4 input methods / 输入方式: DOI, title search, file import (RIS/BibTeX/XML), manual form / DOI、标题搜索、文件导入、手动录入
- 4 reference types / 引用类型: article, book, patent, webpage / 期刊、书籍、专利、网页
- 10+ citation styles / 引用样式: ACS, RSC, Wiley, Elsevier, Nature, Science, Springer, Frontiers, MDPI, Cell Press ...
- Red/yellow/green quality audit / 红黄绿质量审核
- Export / 导出: EndNote XML, RIS, BibTeX

---

## Quick Start / 快速上手

### Download Release (Recommended / 推荐)

**[Download SCI-CAST v3.2.0 (Windows x64)](https://github.com/ye-zi-ming/SCI-CAST/releases/download/v3.2.0/SCI-CAST_v3.2.0_Windows_x64.zip)**

1. Download and extract the zip / 下载并解压
2. Double-click **SCI-CAST.exe** / 双击 SCI-CAST.exe
3. Done / 完成

Requirements / 系统要求: Windows 10/11 (64-bit), WebView2 Runtime (pre-installed on most systems / 多数系统已自带).

---

## Roadmap / 开发计划

- [x] v1.0–v2.x — Initial modules: Grid-CAST, Ref-CAST, Pub-CAST, CIF-CAST
- [x] v3.0 — Full rewrite: React/Vite/TypeScript + FastAPI
- [x] v3.2.0 — Crys-CAST database overhaul, encrypted release builds
- [ ] PXRD-CAST — Powder XRD pattern simulation & matching
- [ ] More database integrations

---

## License / 许可证

SCI-CAST is licensed under the [GNU General Public License v3.0](LICENSE).

Free for personal, academic, and research use. For commercial licensing, please contact the author.

本软件采用 [GPL-3.0](LICENSE) 许可证，个人、学术和科研用途免费。商业授权请联系作者。

---

## Citation / 引用

If SCI-CAST is useful in your research, please cite:

如果 SCI-CAST 对您的研究有帮助，请引用：

```
YeZM. SCI-CAST: Scientific Toolkit for Computational Chemistry
& Publication Workflows, v3.2.0, 2026.
https://github.com/ye-zi-ming/SCI-CAST
```

---

## Author / 作者

**YeZM** — Fujian Normal University / 福建师范大学

[Google Scholar](https://scholar.google.com/citations?user=LQAiqTIAAAAJ&hl=en) · [ORCID](https://orcid.org/0000-0001-6728-2952)

Researcher in computational chemistry and materials science, working with metal-organic frameworks since 2014. SCI-CAST grew out of years of small scripts and scattered tools that I wished were in one place — a practical toolkit built by a researcher, for researchers.

计算化学与材料科学研究者，2014 年起从事金属有机框架研究。SCI-CAST 源于多年来零散的脚本和工具——我一直希望把它们整合到一处。这是一个研究者为研究者打造的实用工具箱。

© 2026 YeZM
