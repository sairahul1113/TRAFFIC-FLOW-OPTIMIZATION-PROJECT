Prerequisites

To run this traffic flow optimization program, you need the following:
Python (version 3.7 or higher)

Libraries:

NumPy
TensorFlow

Library Installation

To install the required libraries, run the following commands in your terminal or command prompt:
pip install numpy tensorflow

Download Links

Download Python
NumPy Documentation
TensorFlow Documentation

Setting Up a Virtual Environment
It’s a good practice to use a virtual environment to manage dependencies without affecting your global Python installation.

Step 1: Install venv (if not already installed)
For most Python distributions, venv comes pre-installed. To check, run:

python3 -m venv --help  # or python -m venv --help
If you encounter errors, make sure to install Python with the "Add to PATH" option enabled.

Step 2: Create a Virtual Environment
Navigate to your project directory:

cd traffic-flow-optimization

Create the virtual environment:
python3 -m venv env  # or python -m venv env

This will create a folder named env containing the virtual environment files.

Step 3: Activate the Virtual Environment

On Windows:
.\env\Scripts\activate

On macOS/Linux:
source env/bin/activate

Once activated, you will see the environment name in your terminal prompt, e.g., (env).

Step 4: Install Dependencies Inside the venv

After activating the venv, install the required libraries:
pip install numpy tensorflow

This ensures that the packages are installed only within your virtual environment.

Step 5: Run the Program

Now you can execute the script:
python traffic_optimization.py

Deactivating the Virtual Environment

When you’re done, deactivate the venv by running:

deactivate

Removing the Virtual Environment
If you no longer need it, simply delete the env folder:

rm -rf env  # On macOS/Linux
rmdir /S /Q env  # On Windows

Running the Program

Step 1: Clone the Repository

Clone the GitHub repository to your local machine:

git clone https://github.com/yourusername/traffic-flow-optimization.git
cd traffic-flow-optimization

Step 2: Install Required Libraries

If you haven’t installed the libraries yet, run:

pip install numpy tensorflow

Step 3: Run the Program

Execute the Python script to see the output:

python traffic_optimization.py

Step 4: Customize the Input

To test with different traffic data, modify the test_input variable in the script:

test_input = np.array([[15, 25, 5, 10]])  # Replace with your own values

After editing, save the script and run it again.

Step 5: Understand the Output

The program will print the direction that should get the green signal based on the current traffic density. It will also show the probability distribution among all four directions.

Troubleshooting

If you encounter any errors related to library installation, make sure you have installed the latest version of Python and used the correct pip version (pip or pip3).

For TensorFlow compatibility issues, visit the TensorFlow Installation Guide.
