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

## Citation & Attribution Standards

**🏆 GOLD STANDARD REQUIRED**: All projects in this repository must follow the comprehensive citation and attribution standards documented in `CITATION_STANDARDS.md`. This represents the highest possible level of data source documentation and attribution.

### Mandatory Requirements
- **Complete Data Source Attribution**: Every dataset must include comprehensive source documentation
- **Academic Citation Standards**: Full academic citation formats required
- **Technical Documentation**: Complete methodology and technical specifications
- **Legal & Ethical Framework**: Permits, compliance, and usage rights documentation
- **Quality Assurance**: Data validation and quality control documentation
- **Contact Information**: Complete contact details for all data sources

### Reference Implementation
See `gps-data-projects/kodiak-bear-gps/README.md` for a complete implementation of the gold standard citation requirements.

## Contributing

When adding new projects:
1. **MANDATORY**: Follow the gold standard citation template in `CITATION_STANDARDS.md`
2. Create a descriptive directory name
3. Include comprehensive README documentation using the mandatory template
4. Follow AFCA naming conventions
5. Ensure data quality and proper attribution to the highest standards
6. Update this main README with project descriptions
7. **VERIFY**: All citations are complete, accurate, and verifiable

## License

Data in this repository follows the same licensing terms as the main AFCA project, with appropriate attribution to original data sources.
