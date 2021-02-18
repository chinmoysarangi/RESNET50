This is a project to showcase a RESNET50 neural network for Flower identification via a Flask inteface, which is hosted on Azure Web Services.

1. Download the Kaggle Dataset from: https://www.kaggle.com/alxmamaev/flowers-recognition

2. Run the Jupyter Notebook named RESNET50.ipynb provided in this code. Make sure that Data_Splitting.ipynb notebook is also present in the same folder.

3. The notebook splits the input files into training, testing and validation files.

4. The notebook also runs the code and creates a model in .H5 format which is what will get used for further steps.

5. Open an IDE Terminal or a Python enabled command prompt, run: pip install Flask to install the flask module.

6. Then create html, css and javascript files for designing the webpage.

7. Then create an app.py file which contains the flask code which invokes the webpage files created above.

8. In the IDE Terminal window, run: python app.py within the same folder which contains the .py file and also the H5 model file for the flask application to launch.

9. After running above command, the script is executed and a link which comes up for clicking: http://127.0.0.1:5000/ This link hosts the web app.

10. Clcicking on the link opens the web app, upload flower images for identification.

11. When done, come back to the IDE terminal and use Ctrl+C to end the flask session run.