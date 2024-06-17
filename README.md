## Democratizing Cheminformatics: Interpretable Chemical Grouping Using an Automated KNIME Workflow
Thank you for your interest in this MoViz workflow! As a reminder, if you only want to use the workflow, you can access it online from the [NIEHS KNIME Server](https://knime.niehs.nih.gov/knime/webportal/space/). However, if you are interested in running the workflow locally, either to make edits or just see how it works, follow the directions below to install it on your computer.

### Installation
#### Prerequisites
Before you can use the workflow, you will need to install its dependencies with Anaconda.
If you don't have it already, download [miniconda3](https://docs.anaconda.com/free/miniconda/).
To install the dependencies:
1. Download the environment.yml file from the repository.
2. Open the Anaconda/Miniconda terminal.
   ![image](https://github.com/joseteofilo/Chemical-grouping-workflow/assets/21991409/e362c152-d549-4cfb-8065-999252ab6254)
3. Navigate to the folder containing environment.yml using `cd /path/to/environment.yml`.
4. Run the following command: `conda env create -f environment.yml`. Press `y` to confirm the install if prompted.
   ![image](https://github.com/joseteofilo/Chemical-grouping-workflow/assets/21991409/5e5506d7-c535-4321-a3db-832175e7f24c)
6. Wait for the packages to install (this may take a while).
   
PaDEL-descriptor also requires Java JRE version 6 or above, which you can get [here](https://www.oracle.com/java/technologies/downloads/#java8).
#### Running the workflow
To set up the workflow on your computer:
1. Clone or download the repository from GitHub.
2. In KNIME Analytics Platform, select your **Local Space**.
   ![image](https://github.com/joseteofilo/Chemical-grouping-workflow/assets/21991409/1765d986-d691-4750-810c-1520b216113b)
3. In your local space, select **Import Workflow**
   ![image](https://github.com/joseteofilo/Chemical-grouping-workflow/assets/21991409/0f4e2625-6deb-44d0-b43a-7c3dea39b7ca)
4. Browse to the workflow file you downloaded; it will have the **.knwf** extension.
5. KNIME may prompt you to install extensions; follow the on-screen instructions to do so. You may need to restart KNIME when done.
   ![image](https://github.com/joseteofilo/Chemical-grouping-workflow/assets/21991409/5ac9ac10-38ac-4528-8b51-258ee2b2cfc9)
   ![image](https://github.com/joseteofilo/Chemical-grouping-workflow/assets/21991409/42661b35-8a4a-4b7b-bfde-524e0f6fc430)
6. Run the workflow with your data!

