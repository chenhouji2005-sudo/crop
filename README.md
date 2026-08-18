# GBCA-Ensemble: Gradient Boosted Cross-Attention Ensemble Network

An end-to-end framework for multi-temporal remote sensing agricultural land-cover classification based on a hybrid Gradient Boosted Cross-Attention (GBCA) Deep Learning network and tree-based ensemble models.

---

## 📁 Project Structure

```text
crop/
├── Featurebuild                # GEE feature extraction & fusion pipeline script
├── train.py                    # GBCA & Ensemble model training & cross-validation script
├── predict.py                  # Tile-based inference & classification map generation script
├── requirements.txt            # Python dependencies list
├── .gitignore                  # Git ignore rule file
└── README.md                   # Project documentation
