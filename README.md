# Densworld Datasets

Central repository for all datasets used in Densworld courses.

## Usage

All course notebooks load data from this repository using:

```python
BASE_URL = "https://raw.githubusercontent.com/buildLittleWorlds/densworld-datasets/main/data/"
df = pd.read_csv(BASE_URL + "filename.csv")
```

## Dataset Categories

### Core Datasets
General-purpose datasets used across multiple courses:
- `creatures.csv` - Yeller Quarry creature catalog
- `scholars.csv` - Capital Archive scholar records
- `manuscripts.csv` - Archive manuscript collection
- `densworld_places.csv` - Geographic locations

### Philosophy Series (Levin-Aragon)
Datasets for the 8-course philosophy series exploring cognitive architectures:
- `levin_aragon_morphospace_catalog.csv` - Form Library morphospace
- `levin_aragon_basin_measurements.csv` - Attractor basin data
- `levin_aragon_agent_registry.csv` - Federation agent records
- `levin_aragon_ghost_observations.csv` - Memory persistence data
- ... and 30+ more

### Spatial Series
Datasets for the spatial reasoning courses:
- `surveyor_logs.csv` - Surveyor field observations
- `spatial_predictions.csv` - Keth's prediction records
- `expedition_*.csv` - Cartographer expedition data

### Puzzle Series
Datasets for formal language and pattern recognition:
- `puzzle_pieces.csv` - Puzzle artifact catalog
- `lpn_*.csv` - Linguistic puzzle notation system

### HuggingFace Series
Datasets for ML/NLP courses:
- `manuscript_texts.csv` - Full text corpus
- `expedition_logs.csv` - Unstructured log data

## Contributing

To add new datasets:
1. Place CSV in `data/` directory
2. Update this README
3. Ensure dataset is referenced in course notebooks with correct filename
