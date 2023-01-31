<p><strong><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">Pași de urmat:</span></span></strong></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">1. Clonați</span></span> <span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">acest repozitoriu:</span></span></p>
<p><a href="https://github.com/EticalPy/Lector_numere-de-inmatriculare"><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">https://github.com/EticalPy/Lector_numere-de-inmatriculare</span></span></a></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">2. Creați un nou mediu virtual (virtual environment)</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">python -m venv (</span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;"><em><strong>folosești orice nume</strong></em></span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">)</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">3. Activați mediul virtual (virtual environment)</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">source (</span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;"><em><strong>numele mediului creat</strong></em></span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">)/bin/activate # Linux</span></span></p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">.\(</span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;"><em><strong>numele mediului creat</strong></em></span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">)\Scripts\activate # Windows </span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">4. Instalați</span></span> <span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">dependențele și adaugi mediul virtual (virtual environment) la Python Kernel</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">python -m pip install --upgrade pip</span></span></p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">pip install ipykernel</span></span></p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">python -m ipykernel install --user --name=(</span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;"><em><strong>numele mediului creat</strong></em></span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">)</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">5. Creați</span></span> <span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">baza de date de imagini așa cum găsești explicat &icirc;n video.</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">a) faceți cont (gratuit) pe https://www.kaggle.com/</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">b) descărcați baza de date pe care o găsiti la link-ul urmator</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;"><a href="https://www.kaggle.com/datasets/andrewmvd/car-plate-detection">https://www.kaggle.com/datasets/andrewmvd/car-plate-detection</a></span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">6. &Icirc;mpărțiți manual imaginile colectate &icirc;n două dosare: "train" și "test".</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">\Lector_numere_de_inmatriculare\Tensorflow\workspace\images\train</span></span></p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">\Lector_numere_de_inmatriculare\\Tensorflow\workspace\images\test</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">7. &Icirc;ncepeți procesul de antrenament deschiz&acirc;nd </span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">fișierul </span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">Antrenament_si_detector.ipynb </span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">A</span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">cest jupyter_notebook vă va ghida </span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">pentru instalarea </span></span><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">Tensorflow Object Detection, efectuarea de detecții, salvarea și exportul modelului.</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">8. &Icirc;n timpul acestui proces, notebook-ul va instala Tensorflow Object Detection. &Icirc;n mod ideal, la pasul 8, ar trebui să primiți o notificare care să indice că API-ul a fost instalat cu succes, ultima linie indic&acirc;nd un &bdquo;OK&rdquo;.</span></span></p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">&Icirc;n caz contrar, rezolvați erorile de instalare cu ajutorul fișierului "Ghid de erori posibile" pe care &icirc;l găsiți &icirc;n acest repozitoriu (și pe care l-ați descarcat odată cu clonarea)</span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: FreeSans, sans-serif;"><span style="font-size: large;">9. Odată ce ați ajuns la pasul 6 - antrenarea modelului &icirc;n notebook, puteți alege să o faceți din aceleași notebook. Am observat &icirc;nsa că din terminal at&acirc;t &icirc;n Linux cat și &icirc;n Windows, puteți vedea rezultatele &icirc;n direct. </span></span></p>


