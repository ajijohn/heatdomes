
# Forest Canopy Cover Affects Microclimate Buffering During an Extreme Heat Event

## 📄 Citation  
John, A., Pradhan, K., Case, M. J., Ettinger, A. K., & Hille Ris Lambers, J. (2024).  
**Forest canopy cover affects microclimate buffering during an extreme heat event.**  
*Environmental Research: Communications*, **6**(9), 091015.  
https://doi.org/10.1088/2515-7620/ad7705  
[📄 Full PDF](https://iopscience.iop.org/article/10.1088/2515-7620/ad7705/pdf)

---

## 🌲 Overview

This study investigates whether temperate coastal forests in the Pacific Northwest (PNW) can buffer understory temperatures during **extreme heat events**, such as the June 2021 heat dome. The authors find that forests significantly cool understory environments—even under extreme heat—by as much as **4°C** relative to regional macroclimate and **3°C** relative to adjacent clear-cuts.

Key findings include:
- **Greater canopy cover leads to stronger thermal buffering.**
- **Thinned forests** provide significantly less cooling than un-thinned or old-growth stands.
- **Vertical variation** exists in buffering, with the coolest temperatures measured at the forest floor.

---

## 🧪 Methods Summary

- **Study Site**: Ellsworth Creek Preserve, Washington, USA.
- **Sensors**: HOBO loggers (ground and 1.5–2m height) and Micromet stations.
- **Data Sources**:  
  - In-situ microclimate data  
  - GridMET regional climate data  
  - Canopy data from The Nature Conservancy plots
- **Metrics**: Mean, min, max, and diel temperature variation; temperature offset (plot vs regional or clear-cut).
- **Statistical Approach**: Linear mixed-effects models using `lme4` in R.

---

## 📈 Key Results

| Temperature Metric | Forest vs. Clear-Cut | Forest vs. Regional Climate |
|--------------------|----------------------|-----------------------------|
| Mean Temp Offset   | up to 3.8°C cooler   | up to 4.0°C cooler          |
| Max Temp Offset    | up to 5.6°C cooler   | up to 5.4°C cooler          |
| Diel Variation     | 7.6–8.3°C lower      | Similar trend               |
| Ground vs. Air     | Ground up to 10°C cooler than air at peak heat |

- **Old-growth forests** showed the highest buffering, especially for max temps and diel variation.
- **Thinned forests** showed reduced buffering, sometimes approaching clear-cut temperatures on the hottest day.

---

## 📁 Repository 

🔗 [https://github.com/ajijohn/heatdomes](https://github.com/ajijohn/heatdomes)

---

## 📬 Contact

**Lead Author**:  
Dr. Aji John  
Department of Biology, University of Washington  
✉️ [ajijohn@uw.edu](mailto:ajijohn@uw.edu)  
🔗 [ORCID](https://orcid.org/0000-0002-4401-1401)

---

## 🧾 How to Cite

```bibtex
@article{john2024canopy,
  title={Forest canopy cover affects microclimate buffering during an extreme heat event},
  author={John, Aji and Pradhan, Kavya and Case, Michael J and Ettinger, Ailene K and Hille Ris Lambers, Janneke},
  journal={Environmental Research: Communications},
  volume={6},
  number={9},
  pages={091015},
  year={2024},
  publisher={IOP Publishing},
  doi={10.1088/2515-7620/ad7705}
}
```
