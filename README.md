# AFCA Sidecar Dataset Repository

This repository hosts special projects and supplementary data for the Alaska Fish Count App (AFCA) that are **NOT** fish count JSON files. This keeps the main fish count data repository clean while providing dedicated space for research projects, GPS data, GeoJSON files, and other supplementary datasets.

## Repository Structure

```
afca-sidecar-dataset/
├── gps-data-projects/          # GPS tracking and movement data
│   ├── kodiak-bear-gps/       # Kodiak bear GPS tracking data
│   └── [other-gps-projects]/  # Future GPS projects
├── geojson-data/              # Geographic data files
│   ├── awc-layers/           # Alaska Water Bodies data
│   └── [other-geojson]/      # Additional geographic datasets
├── research-projects/         # Research and analysis projects
│   └── [project-folders]/    # Individual research initiatives
└── supplementary-data/        # Other non-fish-count datasets
    └── [data-categories]/    # Various supplementary data types
```

## Project Categories

### GPS Data Projects (`gps-data-projects/`)
- **Kodiak Bear GPS**: Bear movement and habitat data
- Future GPS projects for other wildlife species
- Migration pattern analysis data

### GeoJSON Data (`geojson-data/`)
- **AWC Layers**: Alaska Water Bodies geographic data
- Regional boundary files
- Habitat and ecosystem mapping data

### Research Projects (`research-projects/`)
- Academic research collaborations
- Data analysis projects
- Scientific study datasets

### Supplementary Data (`supplementary-data/`)
- Weather and environmental data
- Historical records and archives
- Management area boundaries
- Other non-fish-count datasets

## Usage Guidelines

1. **Data Organization**: Each project should have its own directory with descriptive naming
2. **Documentation**: Include README files for each major project explaining data sources and usage
3. **File Formats**: Use standard formats (JSON, GeoJSON, CSV) for maximum compatibility
4. **Metadata**: Include metadata files describing data collection methods and sources
5. **Version Control**: Tag releases for major dataset updates

## Integration with AFCA

This repository serves as a supplementary data source for the main Alaska Fish Count App. Data from this repository can be:
- Referenced in AFCA research pages
- Used for enhanced mapping features
- Integrated into analysis tools
- Shared with research partners

## Contributing

When adding new projects:
1. Create a descriptive directory name
2. Include comprehensive README documentation
3. Follow AFCA naming conventions
4. Ensure data quality and proper attribution
5. Update this main README with project descriptions

## License

Data in this repository follows the same licensing terms as the main AFCA project, with appropriate attribution to original data sources.
