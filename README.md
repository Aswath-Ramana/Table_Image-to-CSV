# Table_Image-to-CSV

Tesseract has unicode (UTF-8) support, and can recognize more than 100 languages "out of the box".This project does not include a GUI application. If you need one, please see the 3rdParty documentation.Tesseract can be trained to recognize other languages. See Tesseract Training for more information.

### WARNING:

##### Tesseract should be either installed in the directory which is suggested during the installation or in a new directory. The uninstaller removes the whole installation directory. If you installed Tesseract in an existing directory, that directory will be removed with all its subdirectories and files.

The latest installers can be downloaded here:

[tesseract-ocr-w32-setup-v5.0.0-alpha.20201127.exe (32 bit)](https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w32-setup-v5.0.0-alpha.20201127.exe) and

[tesseract-ocr-w64-setup-v5.0.0-alpha.20201127.exe (64 bit)](https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-v5.0.0-alpha.20201127.exe) resp.


### Installing Requirements:
Install requirements from requirements.txt

pip install -r requirements.txt

pip install kracken (***if kraken is not installed from requirements.txt)

python tabular_image-to-csv.py --img-path images/patient.png


### Project Structure:-

a)[images](https://github.com/Aswath-Ramana/Table_Image-to-Excel/tree/main/images) :- This folder contains images to be used for OCR.

b)[output_csv](https://github.com/Aswath-Ramana/Table_Image-to-Excel/tree/main/output_csv) :- It contains result of tabular image in csv file.

c)[processed_image](https://github.com/Aswath-Ramana/Table_Image-to-Excel/tree/main/processed_image) :- Contains images generated while pre-processing.

d)[en-default.mlmodel](https://github.com/Aswath-Ramana/Table_Image-to-Excel/blob/main/en-default.mlmodel) :- Trained english language model.

e)[requirements.txt](https://github.com/Aswath-Ramana/Table_Image-to-Excel/blob/main/requirements.txt) :- Requirement file.

f)[tabular_image-to-csv.py](https://github.com/Aswath-Ramana/Table_Image-to-Excel/blob/main/tabular_image-to-csv.py) :- Code file.

g)[Table_image_csv.ipynb](https://github.com/Aswath-Ramana/Table_Image-to-Excel/blob/main/Table_Image%20to%20CSV.ipynb)- This notebook is small queries to convert the imag file to text and rearrange them as csv file.It doesn't find the table and extract,but it extract text and sort them as table file.
