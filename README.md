# CSB320 In-Class Repository

This repository contains materials and exercises for the CSB320 course. To ensure a consistent development environment, it's recommended to use Anaconda to manage dependencies and packages.

## Setting Up the Anaconda Virtual Environment

Follow the steps below to set up the Anaconda virtual environment using the provided `requirements.yml` file:

1. **Clone the Repository**

   Begin by cloning this repository to your local machine:

   ```bash
   git clone https://github.com/NSC-BS-CS/CSB320_InClass.git

Navigate into the repository directory: 
cd CSB320_InClass

2.	**Create the Conda Environment**
Use the requirements.yml file to create a new Conda environment. This file specifies all necessary dependencies and their versions.
Run the following command:

	```bash
	conda env create -f requirements.yml

4.  **Activate the Conda Environment**
	```bash
	conda activate CSB320_InClass

5.  **Verify the Environment**
To confirm that the environment is set up correctly and all packages are installed, list the installed packages:
	```bash
	conda list

**Additional Information**
	•	Updating the Environment
If there are updates to the requirements.yml file or additional packages are needed, update the environment with:
	```bash
	conda env update -f requirements.yml

This code may update regularly, so best to do a git pull and get the latest version.
