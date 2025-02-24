# Wildfire Burnt Area Mapping

This repository offers an in-depth analysis of the Palisades Forest Fire's burn severity through advanced remote sensing techniques. By leveraging satellite imagery and state-of-the-art deep learning models, the project aims to accurately map and assess the extent of the burned areas, providing essential data for forest management and rehabilitation efforts.

## Overview

Wildfires pose significant threats to ecosystems, property, and human lives. Precise mapping of burnt areas is crucial for effective response and recovery. This project centers on the Palisades Forest Fire, utilizing satellite data combined with deep learning methodologies to evaluate burn severity and generate detailed maps of the affected regions.

## Methodology

The analysis is conducted using a Jupyter Notebook and encompasses the following steps:

1. **Data Acquisition**: Retrieval of pre- and post-fire satellite images from relevant sources.
2. **Preprocessing**: Calibration and alignment of images to ensure consistency.
3. **Burn Severity Assessment**: Calculation of spectral indices, such as the Normalized Burn Ratio (NBR), to quantify burn severity.
4. **Deep Learning Integration**: Application of U-Net based convolutional neural networks for precise segmentation and mapping of burned areas.
5. **Visualization**: Generation of maps and visual representations of burn severity across the affected area.

## Requirements

To replicate the analysis, the following Python libraries are required:

- `numpy`
- `pandas`
- `matplotlib`
- `rasterio`
- `geopandas`
- `earthpy`
- `tensorflow` or `pytorch` (for deep learning models)

Install the necessary packages using:

```bash
pip install numpy pandas matplotlib rasterio geopandas earthpy tensorflow
```

or

```bash
pip install numpy pandas matplotlib rasterio geopandas earthpy torch
```

## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/praveenpankaj/WildFireBurntAreaMapping.git
   cd WildFireBurntAreaMapping
   ```

2. **Open the Jupyter Notebook**:

   Launch Jupyter Notebook and open `Palisades_Forest_Fire_Burn_Severity.ipynb` to explore the analysis.

## Results

The analysis yields detailed maps highlighting varying levels of burn severity within the Palisades Forest. These maps are instrumental for:

- Assessing ecological impact
- Planning reforestation and rehabilitation
- Informing policy and management decisions

## References

For further reading on wildfire burnt area mapping, especially focusing on U-Net architectures and contrastive learning methods, consider the following recent studies:

- **Two Scalable Approaches for Burned-Area Mapping Using U-Net and Landsat Imagery**: This study explores two U-Net-based approaches for automating and optimizing the burned-area mapping process using Landsat imagery. citeturn0search1

- **Burned-Area Mapping Using Post-Fire PlanetScope Images and a Convolutional Neural Network**: This research utilizes a U-Net model to produce burned-area maps from single post-fire PlanetScope images, demonstrating high accuracy in mapping efforts. citeturn0search6

- **Unsupervised Wildfire Change Detection Based on Contrastive Learning**: This study proposes an unsupervised model employing contrastive learning techniques to detect burned area changes, enhancing feature extraction in wildfire scenarios. citeturn0search2

- **Total-Variation Regularized U-Net for Wildfire Burned Area Mapping Using Sentinel-1 SAR Data**: This research introduces a novel approach using a Total-Variation regularized U-Net model to enhance the accuracy and connectivity of SAR-based burned area delineation. citeturn0search11

- **Unsupervised Bushfire Burn Severity Mapping Using Aerial and Satellite Imagery**: This study employs contrastive learning frameworks for feature extraction in bushfire severity mapping, utilizing both aerial and satellite imagery. citeturn0search14

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Note: This README format is inspired by the structure used in the [plant-disease-classification](https://github.com/praveenpankaj/plant-disease-classification) repository.* 
