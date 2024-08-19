### Cloning Repositories and Activating Your Virtual Environment

#### Step 1: Navigate to Your `labs` Directory

First, let's navigate to the `labs` directory you created during setup. This is where you'll store all your lab assignments.

1. Open your terminal.
2. Run the following command to navigate to your `labs` directory:

   ```bash
   cd ~/code/ga/labs
   ```

#### Step 2: Clone the Repository

Now that you're in the `labs` directory, you can clone the repository containing your starter code or notebook exercises.

1. Copy the repository URL from your course materials or assignment.
2. Run the following command, replacing `<repository-url>` with the actual URL:

   ```bash
   git clone <repository-url>
   ```

3. This will create a new folder within `labs` with the contents of the repository.

#### Step 3: Navigate to the Cloned Repository

After cloning, navigate into the directory of the repository you just cloned:

```bash
cd repository-name
```

Replace `repository-name` with the name of the folder created by the clone operation.

#### Step 4: Activate Your Virtual Environment

Before running any code or notebooks, you need to activate the virtual environment to ensure you're using the correct version of Python and all required packages.

1. Run the following command to activate your `ga-env` environment:

   ```bash
   conda activate ga-env
   ```

2. You should see `(ga-env)` at the beginning of your terminal prompt, indicating that the environment is active.

#### Step 5: Open and Run the Notebooks

With the virtual environment activated, you can now open and run the Jupyter Notebooks.

1. Open the folder containing the cloned repository in Visual Studio Code.
2. Once the folder is open, navigate to the notebook file you want to work on and open it.

   - If you haven't already, make sure you have installed the **Jupyter** extension for VS Code as instructed during the setup.

3. Run the code cells in the notebook. The virtual environment you activated will ensure that all necessary packages and the correct Python version are used.
