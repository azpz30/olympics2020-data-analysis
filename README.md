# Olympics 2020 Data Analysis and Engineering Project

## Overview
This GitHub repository hosts the code and resources for an extensive data analysis and engineering project focused on the Olympics 2020. Leveraging the power of Azure cloud services and data processing tools, this project dives deep into the Olympics 2020 dataset to extract valuable insights and visualize key metrics. My main aim of this project was to get a basic understanding of the services and resources provided my Microsoft cloud services for data analysis.

## Key Features
- **Data Ingestion:** Utilizes Azure Data Factory to ingest and process raw Olympics 2020 data.
<img width="2560" alt="azure_data_factory" src="https://github.com/azpz30/olympics2020-data-analysis/assets/76789643/8c86cea5-6c7b-496b-8f2c-7f21454b5c81">

- **Data Transformation:** Cleans, transforms, and enriches the data using Azure Databricks.
<img width="2560" alt="azure_resource_group" src="https://github.com/azpz30/olympics2020-data-analysis/assets/76789643/c9a2d899-2365-41c9-aae4-44ee1ae402e0">

- **Storage:** Stores organized data in Azure Data Lake Gen-2 and Azure Data Storage.
<img width="2560" alt="azure_storage_account" src="https://github.com/azpz30/olympics2020-data-analysis/assets/76789643/1fd80edd-8946-4c8c-a30b-70c71061be8e">

- **Analytics:** Utilizes Azure Synapse Analytics for SQL queries to create charts and graphs for visualization.
<img width="2560" alt="azure_synapse_analytics" src="https://github.com/azpz30/olympics2020-data-analysis/assets/76789643/e3733fbb-510c-47c4-87bc-711ed0fa87b6">

- **Insights:** Extracts various insights, including top-performing countries, gender-based entry statistics, medal distributions, and more.
<img width="2560" alt="azure_databricks" src="https://github.com/azpz30/olympics2020-data-analysis/assets/76789643/044373fd-e829-4996-8dc9-07c4029476e1">

- **GitHub Structure:** The repository is organized with initial data files in the 'initialData' folder and post-transformation data in the 'postTransformationData' folder.

## Insights Extracted
- Top countries by the number of gold medals won.
![medals_country_wise](https://github.com/azpz30/olympics2020-data-analysis/assets/76789643/d72a24d8-76fc-4f1d-ab69-ade3cc4dfdf3)

- Average entries by gender for each discipline.
![male vs female](https://github.com/azpz30/olympics2020-data-analysis/assets/76789643/2c608140-216e-4f07-a8f3-25bc84f289d4)

- Distribution of all medals (gold, silver, and bronze) by country.
![medal_distribution_by_country](https://github.com/azpz30/olympics2020-data-analysis/assets/76789643/096fee00-78d0-47af-87ee-b6d44e08ed1e)

- Percentage breakdown of gold, silver, and bronze medals for each country.
- Medal distribution by country and discipline.
- Total medals awarded for each discipline.
- The discipline with the most medals awarded.
- Correlation analysis between total entries and total medals
![reg_plot_entriesVSmedals](https://github.com/azpz30/olympics2020-data-analysis/assets/76789643/613a61d8-8284-483b-b53a-e12c469bc356)


## Project Structure
The project is structured to maintain clarity and ease of use, making it an excellent resource for anyone interested in analyzing large-scale sporting event data.

## Technologies Used
- Azure Data Factory
- Azure Databricks
- Azure Data Lake Gen-2
- Azure Data Storage
- Azure Synapse Analytics
- GitHub for version control and collaboration

## How to Use
1. **Azure VM (Virtual Machine):**
   - Create an Azure VM.
   - Access the VM using SSH.
   - Clone this repository by running the following commands in the VM terminal:
     ```bash
     git clone https://github.com/yourusername/your-repo.git
     ```

2. **Azure Databricks:**
   - Create an Azure Databricks workspace.
   - Navigate to your workspace and click on the "Workspace" tab.
   - Select "Import" to clone a Git repository.
   - Provide your GitHub repository URL and follow the prompts to clone the repository.

3. Explore the Jupyter notebooks for data transformation and analysis.
4. Visualize insights using Azure Synapse Analytics.

## Contributor
- Aziz Mehedi

## Acknowledgments
We would like to acknowledge the valuable support and resources provided by Azure and the open-source community, making this project possible.
Feel free to contribute, open issues, or provide feedback to help improve this project further.
