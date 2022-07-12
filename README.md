# Information_Extraction_From_Business_Card
NER extraction from scanned business cards

In this project we will extract information from scanned business cards.

1. Before running the project, please create a virtual environment using below command:

    ``` conda create -n info_extraction ```

2. Now activate the conda env using below command:

    ``` conda activate info_extraction ```

<b>Note:</b>  I'm using conda to manage my environments. you can use any other tool also to manage your environments and dependencies like poetry, venv,etc.

3. Now install the required python packages using below command:

    ``` pip install -r requirements.txt ```

4. Install [GOOGLE Tessaract OCR](https://github.com/tesseract-ocr/tesseract) and add the path in your system variables. 

    or you can set the path on windows as below:

    ``` set PATH=%PATH%;C:\Program Files\Tesseract-OCR\tesseract.exe ```

Additional info regarding pytesseract can be found at pytesseract's [GitHub page](https://github.com/madmaze/pytesseract).

5. We will also use pretrained model of [spacy](https://spacy.io/usage) to extract the information from the business card. you need to download the pretrained model from the link below.

    ``` https://spacy.io/models/en_core_web_sm ```

    Or you can directly download the model using below command:

    ``` python -m spacy download en_core_web_sm ```



