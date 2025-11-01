# Helical Vortex Cosmology: 6.2% Excess Alignment in DESI DR1 Filaments

**E. Rudy Westerneng**  
Independent Researcher | rwesterneng@gmail.com  
*October 23, 2025*

**Paper**: [Vortex-2.pdf](docs/paper.pdf) | **arXiv**: *pending*  
**Data**: DESI DR1 (18.7M redshifts) | **Filaments**: 8,472  
**Result**: 6.2% helical skewness → **2.5σ** evidence for spacetime torsion (ω = 1.2×10⁻¹⁸ s⁻¹)

---

## 🌌 Key Findings
- **6.2% excess helicity** in filament spin axes (p = 0.006)
- Stronger signal at **z > 0.6**
- Compatible with **LIGO O4**, **JWST plane peaks**, **Planck B-modes**
- Predicts **Δz ≈ 120 Mpc** brane separation

---

## 🚀 Quick Start

```bash
# Clone repo
git clone https://github.com/helical-vortex-desi/helical-vortex-desi.git
cd helical-vortex-desi

# Create environment
conda env create -f environment.yml
conda activate helical-vortex

# Run full pipeline
python -m src.helicity_analysis --run-all
