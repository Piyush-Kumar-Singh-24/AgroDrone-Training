# AgroDrone-Training

# 1. Collecting data

I have downloaded the data about the leaves, i.e healthy and diseased leaf
from kaggle which is about 7GB which is store in the plant folder which is not present here.

# 2. Required packages

I used python 3.10 and made a virtual environment
using the CMD "Pip install virtualenv"
- virtualenv myenv -p python3.10
- activate myenv\Scripts\activate.bat
Then I installed all required packages using pip:
- "Pip install -r requirements.txt"

basic packages are:
- opencv
- numpy
- tensorflow
- keras
- matplotlib

# 3. Model training

To train the model we need to run the following command on terminal or cmd :
- "jupyter notebook"
- open the proper_train.ipynb
- run the code
The model will be saved as .keras file named 'saved.keras'

# 4. Detection

To detect the disease from an video you can use detection.ipynb

You can watch everything in this short video:
- https://youtu.be/M18CNhGitGM