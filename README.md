# ice-cream-dataops

## Overview
`ice-cream-dataops` is a project that utilizes Cognite Data Fusion (CDF) to operate and visualize data from an ice cream factory. This repository was created during the Cognite Bootcamp V3, and aims to build a Core Data Model (CDM) based on the factory's data using the CDF toolkit. The project also visualizes data through Cognite Data Fusion’s Charts and Canvas features.

## Project Purpose
- To build a core data model for the ice cream factory's data using the Cognite Data Fusion (CDF) tools
- To leverage CDF’s data visualization features (Charts and Canvas) to derive actionable insights for business operations
- To manage various configuration files such as Hosted Extractors, Transformation, Data Model, Functions, and Workflow using the CDF toolkit

## Technologies Used
- **Cognite Data Fusion (CDF)**: A data integration platform for building data models and utilizing them
- **CDF toolkit**: A set of tools for operating data on Cognite Data Fusion
- **Charts**: A feature for visualizing timeseries data in CDF
- **Canvas**: A feature for creating data visualizations

## Repository Structure
This repository contains various configuration files used with the CDF toolkit. Specifically, for example the following files are included:

- **Authentication**: Configuration files for authentication to CDF
- **Hosted Extractor**: Configuration files for REST API hosted extractor for the ice cream factory's data
- **Transformation**: Configuration files for data transformation from RAW to DataModel
- **DataModel**: The Core Data Model (CDM) definition files
- **Functions**: Definitions of functions used for data manipulation
- **Workflows**: Configuration files defining the data processing flow

## Usage

### Prerequisites
1. **Cognite Data Fusion (CDF) and Microsoft Azure Account**: You will need an account on CDF and Azure for use this project.
2. **CDF toolkit Installation**: Install the CDF toolkit on your local environment.
   - For detailed installation instructions, refer to the [CDF official documentation](https://docs.cognite.com/cdf/deploy/cdf_toolkit/).

## Examples of Definition File Descriptions

### Hosted Extractor
Contains configuration files for REST API hosted extractor. 
### Transformation
Contains scripts and configuration files for transforming data. These files prepare the data to be in the correct format for use in the Core Data Model (CDM).

### DataModel
Defines the Space of the Core Data Model (CDM) for the ice cream factory’s data. 

### Functions
Defines the functions needed for data operations. These functions are used to process and manipulate data within CDF.

### Workflow
Defines the data processing flow. These files specify how data flows through various stages and how it is processed.

## License
This repository is licensed under the [MIT License](LICENSE).

## Additional Information
This repository was created as part of the Cognite Bootcamp V3 and is a useful resource for those interested in working with Cognite Data Fusion to operate and visualize industrial data.

## Author
- **Author (Bootcamp Trainee)**: [Kei Shomura](https://github.com/burbot0831)
