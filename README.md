# POC ML project

_Author: Sophie Karmel_

_Date: November 2021_

## Code base organisation

### Data 
    `/data`: storage link with activated version control under 
    - `/ingestion`: scripts for data ingestion
    - `/preprocessing`: scripts for data-preprocessing
    - `/notebooks`: data exploration and data wrangling

### Models
    - `models`: checkpoints and pretrained models

### Tests
    - `\tests`: test directory

### Release
    - `\release`: ML pipeline for deployment

## Testing configuration
    - pytest configuration

## git configuration
    - `.gitignore`

## DVC configuration
    - `.dvc`

## conda configuration
    -`\requirements\.conda`

## mlfow configuration
    -`\setup\.mlflow`

## logging configuration and tensorboard setup
    -`logs`

## CI/CD pipeline
    -`\setup`

## Docker configuration
    -`\setup`

## API endpoint
    -`\release`
