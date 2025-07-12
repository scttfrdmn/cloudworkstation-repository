# CloudWorkstation Template Repository

This is the official template repository for CloudWorkstation, providing a collection of research domain-specific templates for various scientific and academic use cases.

## Repository Structure

- **base/** - Base templates that serve as foundations for other templates
- **domains/** - Domain-specific templates for various research fields
- **stacks/** - Technology stack templates that can be combined with domain templates

## Available Templates

### Bioinformatics

- **bioinformatics** - Comprehensive genomics research environment with BWA, GATK, Samtools, R Bioconductor, and Galaxy

### Data Science

- **python-research** - Python environment with Jupyter and data science packages
- **r-research** - R environment with RStudio Server and tidyverse packages

### Visualization

- **scientific-visualization** - Scientific visualization environment with ParaView, VisIt, VTK, and related tools

### Desktop

- **desktop-research** - Ubuntu Desktop with NICE DCV, common research tools, and GUI applications

## Usage

To use this repository with CloudWorkstation:

```bash
# Add this repository
cws repository add default https://github.com/scttfrdmn/cloudworkstation-repository

# Update templates from the repository
cws repository update default

# List available templates
cws templates

# Launch an instance using a template
cws launch bioinformatics my-bio-project
```

## Template Specifications

Each template includes:

1. Base operating system and architecture
2. Software installation and configuration steps
3. Validation checks
4. Resource requirements and instance sizing
5. Cost estimates

For more information on creating custom templates, see the [Template Authoring Guide](https://docs.cloudworkstation.dev/templates/authoring).

## Contributing

To contribute to this repository, please submit a pull request with your template additions or modifications.

## License

All templates are provided under the Apache License 2.0.