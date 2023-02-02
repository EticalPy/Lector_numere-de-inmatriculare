<b>Eroare:</b> No module named ‘xxxxxx’<br/>
<b>Solutie:</b> Instalati Modulul
<pre>!pip install xxxxxx</pre>

<i>Exemplu:</i><br/>
Eroare: No module named typeguard<br/>
Solutie: pip install typeguard  # rețineți că numele modulului nu este întotdeauna acelasi cu numele pachetului.

<b>Eroare:</b> AttributeError: module 'sip' has no attribute 'setapi'<br/>
<b>Solutie:</b> Faceti un downgrade pentru matplotlib la versiunea 3.2 cu următoara comanda
<pre>!pip install matplotlib==3.2</pre>

<b>Eroare:</b> ValueError: numpy.ndarray size changed, may indicate binary incompatibility. Expected 88 from C header, got 80 from PyObject<br/>
<b>Solutie:</b>  Reinstalati pycocotools
<pre>Pip uninstall pycocotools -y
Pip install pycocotools</pre>

<b>Eroare:</b> ValueError: 'images' must have either 3 or 4 dimensions.<br/>
<b>Solutie:</b> Reporniți notebook-ul jupyter deoarece camera web nu este disponibilă. In cazul imaginilor, acest lucru înseamnă în mod normal că numele sau ruta imaginii este incorectă.

<b>Eroare:</b>error: (-2:Unspecified error) The function is not implemented. Rebuild the library with Windows, GTK+ 2.x or Cocoa support. If you are on Ubuntu or Debian, install libgtk2.0-dev and pkg-config, then re-run cmake or configure script in function 'cvDestroyAllWindows'<br/>
<b>Solutie:</b> Reinstalati opencv si dezinstalati opencv-headless
<pre>
pip uninstall opencv-python-headless -y
pip install opencv-python --upgrade
</pre>

<b>Eroare:</b>Atunci când executați scriptul GenerateTFRecords primiți o eroare de tipul celei de mai jos:
  File "Tensorflow\scripts\generate_tfrecord.py", line 132, in create_tf_example
    classes.append(class_text_to_int(row['class']))
  File "Tensorflow\scripts\generate_tfrecord.py", line 101, in class_text_to_int
    return label_map_dict[row_label]
KeyError: 'ThumbsDown' # YOUR LABEL HERE
 <br/>
<b>Solutie:</b> Acest lucru se datorează probabil neconcordanțelor dintre adnotările dvs. și harta etichetelor. Asigurați-vă că numele etichetelor din adnotările dvs. corespund exact cu harta etichetelor, rețineți că este sensibil la majuscule și minuscule. 

<b>Eroare:</b>Atunci când executați scriptul de antrenament din linia de comandă, primiți o eroare de tip "No module...". ex: ModuleNotFoundError: No module named 'cv2'
 <br/>
<b>Solutie:</b> Nu uitați că trebuie să vă activați ambientul (virtual environment) din terminal pentru a putea folosi toate pachetele pe care le-ați instalat în acesta. 

<b>Eroare:</b> În timpul antrenamentului, se utilizează doar procesorul CPU, iar GPU este ignorat. 
<br/>
<b>Solutie:</b> Asigurați-vă că aveți instalată o versiune CUDA si cuDNN corespunzătoare versiunii Tensorflow. Windows:https://www.tensorflow.org/install/source_windows, Linux/macOS: https://www.tensorflow.org/install/source

<b>Eroare:</b>CUBLAS_STATUS_ALLOC_FAILED or CUDNN_STATUS_ALLOC_FAILED <br/>
<b>Solutie:</b> Acest lucru se datorează faptului că VRAM-ul disponibil pe computerul dvs. este complet ocupat și nu mai există memorie disponibilă pentru antrenament. Închideți toate programele Python și opriți serverul Jupyter Notebook pentru a elibera VRAM și rulați din nou comanda. 
