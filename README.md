
![detetctor matriculas](https://user-images.githubusercontent.com/124026170/216377953-18ea7ef2-d131-4a4e-af7d-28529115f4d5.png)

<p><strong>Pași de urmat:</strong></p>
<ol>
<li>
<h2><strong> Clonați acest repozitoriu:</strong></h2>
</li>
</ol>
<p><strong><a href="https://github.com/EticalPy/Lector_numere-de-inmatriculare">https://github.com/EticalPy/Lector_numere-de-inmatriculare</a></strong></p>
<p>&nbsp;</p>
<ol start="2">
<li>
<h2><strong> Creați un nou mediu virtual (virtual environment)</strong></h2>
</li>
</ol>
<p>&nbsp;</p>
<p>python -m venv (<strong><em>folosești orice nume</em></strong>)</p>
<p>&nbsp;</p>
<ol start="3">
<li>
<h2><strong> Activați mediul virtual (virtual environment)</strong></h2>
</li>
</ol>
<p>&nbsp;</p>
<p>source (<strong><em>numele mediului creat</em></strong>)/bin/activate # Linux</p>
<p>.\(<strong><em>numele mediului creat</em></strong>)\Scripts\activate # Windows</p>
<p>&nbsp;</p>
<ol start="4">
<li>
<h2><strong> Instalați dependențele și adaugi mediul virtual (virtual environment) la Python Kernel</strong></h2>
</li>
</ol>
<p>&nbsp;</p>
<p>python -m pip install --upgrade pip</p>
<p>pip install ipykernel</p>
<p>python -m ipykernel install --user --name=(<strong><em>numele mediului creat</em></strong>)</p>
<p>&nbsp;</p>
<ol start="5">
<li>
<h2><strong> Creați baza de date de imagini așa cum găsești explicat &icirc;n video.</strong></h2>
</li>
</ol>
<p><strong><img src="https://files.fm/u/6u3zc3tg5" alt="" /></strong></p>
<ol>
<li>a) faceți cont (gratuit) pe https://www.kaggle.com/</li>
</ol>
<p>&nbsp;</p>
<ol>
<li>b) descărcați baza de date pe care o găsiti la link-ul urmator</li>
</ol>
<p>&nbsp; <a href="https://www.kaggle.com/datasets/andrewmvd/car-plate-detection">https://www.kaggle.com/datasets/andrewmvd/car-plate-detection</a></p>
<p>&nbsp;</p>
<ol start="6">
<li>
<h2><strong> &Icirc;mpărțiți manual imaginile colectate &icirc;n două dosare: "train" și "test".</strong></h2>
</li>
</ol>
<p>&nbsp;</p>
<p>\Lector_numere_de_inmatriculare\Tensorflow\workspace\images\train</p>
<p>\Lector_numere_de_inmatriculare\\Tensorflow\workspace\images\test</p>
<p>&nbsp;</p>
<ol start="7">
<li><strong>&Icirc;ncepeți procesul de antrenament</strong> deschiz&acirc;nd fișierul Antrenament_si_detector.ipynb Acest jupyter_notebook vă va ghida pentru instalarea Tensorflow Object Detection, efectuarea de detecții, salvarea și exportul modelului.</li>
</ol>
<p>&nbsp;</p>
<ol start="8">
<li>&Icirc;n timpul acestui proces, notebook-ul va instala Tensorflow Object Detection. &Icirc;n mod ideal, la pasul 8, ar trebui să primiți o notificare care să indice că API-ul a fost instalat cu succes, ultima linie indic&acirc;nd un &bdquo;OK&rdquo;.</li>
</ol>
<p>&Icirc;n caz contrar, rezolvați erorile de instalare cu ajutorul fișierului "Ghid de erori posibile" pe care &icirc;l găsiți &icirc;n acest repozitoriu (și pe care l-ați descarcat odată cu clonarea)</p>
<p>&nbsp;</p>
<ol start="9">
<li>Odată ce ați ajuns la pasul 6 - antrenarea modelului &icirc;n notebook, puteți alege să o faceți din aceleași notebook. Am observat &icirc;nsa că din terminal at&acirc;t &icirc;n Linux cat și &icirc;n Windows, puteți vedea rezultatele &icirc;n direct.</li>
</ol>
<p>&nbsp;</p>
<p>Tutorial complet pe pagina #EticalPy din youtube:</p>
<p>https://youtu.be/0fAp_xtp6o8</p>
<p>&nbsp;</p>



