# Plant Imaging Consortium 
## Scanalyzer Data Processor

![Maintenance](https://img.shields.io/badge/Maintained%3F-no-red.svg)

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

> Warning: this project is no longer maintained and was written to work in Python 2.7.x, which is no longer supported. 

A python-based data processor that converts data exported from Lemnatec Scanalyzer (csv) into an Excel spreadsheet where each sensor is handled specifically and casted into separate data sheets within a single workbook.

## Requirements

- Python 2.7.x
- pipenv (development)


## Installation

```bash
$ pip install -r requirements.txt
```

## Execution

Run by passing the `-p` path parameter and an existing folder where the original raw data is stored. The process will generate an output folder _within_ that folder called `PROCESSED_CSV_DATA`

```bash
$ python main.py -p <path_to_input>
```

## Development

```bash
$ pipenv install --path <python27_path>
```

## Contributing

While contributions and issues are welcome and will receive consideration, it is important to note that this project is no longer maintained and there are no plans to pick up this project.

## Plant Imaging Consortium

The NSF-funded Plant Imaging Consortium (PIC) brings together experts in plant biology, radiochemistry, phenomics, imaging, and computational biology to apply high-throughput phenotyping and molecular imaging techniques to the study of plant stress biology. High-throughput phenotyping (HTP) allows breeders to screen large populations of plants quickly and efficiently, and to quantify numerous complex traits that are not obvious to the naked eye. Molecular imaging (MI) techniques such positron emission tomography (ie. PET scans) utilize radioactive, fluorescent, or luminescent probes to elucidate the physiological processes that govern stress tolerance or susceptibility in plants. Together, these bioimaging technologies have transformative power to link genotype to phenotype and identify genetic sources of stress tolerance for crop improvement.

National Science foundation awards #1430427 and #1430428: Collaborative Research on Plant Stress Response through Innovations in Phenomics and Molecular Imaging Technologies

## Built By

[![CAST](https://logos.cast.uark.edu/logo/logo-text-horizontal-dark-320x104.png)](https://cast.uark.edu)





