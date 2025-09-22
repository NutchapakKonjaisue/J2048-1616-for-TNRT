# A Study of Single Pulse Fluence Distribution of PSR J2048-1616 for Commissioning The Thai National Radio Telescope (TNRT)

A Jupyter notebook to reproduce the analyses and figures which appeared in the study. 

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

Required libraries can be found in the [requirements.txt](requirements.txt) file

## Usage

To fully reproduce the values and figures in the study, the observation data shall be preprocessed into subintegrations; rid of RFI (preferably using an automated pipeline); polarization and flux calibrated; restricted to the frequency bandwidth of the TNRT L-band receiver (1.0–1.8 MHz); frequency scrunched; and combined into a single file. Then, they can be exported as a .csv file.

For ease of use, the ready-to-use modified data in .csv format is provided herewith (licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).

## Dependencies

This project depends on the following open-source Python libraries:

- ArviZ (0.15.1) — Apache License 2.0
- Matplotlib (3.8.5) — Matplotlib License
- NumPy (1.24.4) — BSD 3-Clause
- Polars (1.8.2) — MIT License
- PyMC (5.6.1) — Apache License 2.0
- PyTensor (2.12.3) — BSD 3-Clause
- SciPy (1.10.1) — BSD 3-Clause
- Seaborn (0.13.2) — BSD 3-Clause

Please see the respective project websites for full license texts.

## License

### Jupyter Notebook
This project Jupyter Notebook is licensed under the BSD 3-Clause License. See the [LICENSE](LICENSE) file for details.

### Data
This project uses observation data modified from [*Parkes observations for project PX500 semester 2020OCTS_16*](https://doi.org/10.25919/szds-6x44) by Li D. et al., licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). All Rights (including copyright) CSIRO 2021.

## Acknowledgements

We sincerely thank the National Astronomical Research Institute of Thailand for granting us access to the institute’s high-performance computing infrastructure. We further express gratitude towards Mahidol Wittayanusorn School for funding this research. Our appreciation also goes to the Australia Telescope National Facility that made the archival data from the Parkes Radio Telescope (Murriyang) publicly available. Murriyang, CSIRO’s Parkes radio telescope, is part of the Australia Telescope National Facility (https://ror.org/05qajvd42) which is funded by the Australian Government for operation as a National Facility managed by CSIRO.
