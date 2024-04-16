# Create a virtual environment
python -m venv myenv

# Activate the virtual environment
# On Windows
myenv\Scripts\activate

# On macOS/Linux
source myenv/bin/activate

# Install required packages
pip install -r requirements.txt

# Deactivate after doing all jobs done. Do not close it untill you are done.
# Deactivate the virtual environment
deactivate
