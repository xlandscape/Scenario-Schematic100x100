## Table of Contents
* [About the project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)


## About the project
A schematic scenario consisting of a field and an adjacent off-field habitat.
This documentation was automatically created on 2021-02-22.

### Built with
* Landscape Model core version 1.4.1


## Getting Started
### Prerequisites
Make sure you use the latest version of the Landscape Model.

### Installation
Copy the complete scenario folder unaltered into the `scenario` sub-directory of your model. The scenario can then be 
used by he model. For details how to reference the scenario from the user parameterization, see the `README` of the 
model.


## Usage
The scenario adds the following macros to the Landscape Model:
* `:weather_mars-97100` (version 1.3.5)
* `:LandscapeScenario` (version 0.1.4)
* `:VfsMod_lookup_table` (version 1)

    
## Roadmap
The scenario is considered final and will not be developed further. However, it will be updated to reflect new 
requirements by the Landscape Model core and individual Landscape Model variants.


## Contributing
Contributions are welcome. Please contact the authors (see [Contact](#contact)).


## License
The scenario is distributed under the CC0 License. See the `LICENSE` file for more information.


## Contact   
* Thorsten Schad - thorsten.schad@bayer.com
* Sascha Bub - sascha.bub.ext@bayer.com


## Acknowledgements
* Joachim Kleinmann and Magnus Wang for the VfsMod lookup table
* MARS 25km x 25km gridded weather data for MARS grid cell 97100
