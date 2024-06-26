# FarmCollector Java Coding Task

## Description

FarmCollector is an organization that aims to collect information from farmers for every field for every season, per farm. The organization requires two APIs for data collection:

1. **Planted API**:
   - Collects information about the planting activity.
   - Includes fields for planting area (in acres), type of crops planted, and amount of expected product (in tons).

2. **Harvested API**:
   - Collects information about the harvested activity.
   - Includes fields for the actual amount of harvested product.

FarmCollector also wants to generate reports for every season, showing the expected versus actual amount of product. The reports should provide insights into the performance of each farm and each type of crop.


## Endpoints

1. **Farm API**:
   - Endpoint: `/api/farm`
   - Method: `POST`
   - Description: Collects information about the farmer activity..
  
2. **Planted API**:
   - Endpoint: `/api/plant`
   - Method: `POST`
   - Description: Collects information about the planting activity, including the planting area, type of crops planted, and amount of expected product.

3. **Harvested API**:
   - Endpoint: `/api/harvest`
   - Method: `POST`
   - Description: Collects information about the harvested activity, including the actual amount of harvested product.

## Reports
 **Reports API**:
   - Endpoint: `/api/reports/seasons/{seasonId}`
   - Method: `POST`
   - Description: Each report provides insights into the expected versus actual product for each farm

## Getting Started

To run the FarmCollector application locally, follow these steps:

1. Clone the repository.
2. Build the application using Maven.
3. Run the application using the provided Maven or Spring Boot commands.
4. Access the endpoints and reports via a [Postman](https://documenter.getpostman.com/view/7330864/2sA35LX191) 


