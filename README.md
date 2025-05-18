Práctica #6
En esta práctica se exploró el proceso de conformación de pulsos (waveforming) aplicando filtros de tipo coseno alzado (RC) y raíz de coseno alzado (RRC), con el objetivo de analizar su impacto en la eficiencia espectral y la calidad de la señal en sistemas de comunicación digital.

Se utilizaron herramientas como GNU Radio y GitHub para implementar y documentar los experimentos. Las señales generadas fueron analizadas tanto en el dominio temporal como en el frecuencial, así como mediante diagramas de ojo y constelaciones, para estudiar fenómenos como la interferencia intersimbólica (ISI).

Los experimentos se dividieron en 5 configuraciones:

1.Forma de onda rectangular sin filtrado: Para observar el comportamiento ideal sin ISI.
2.Forma rectangular con filtrado: Introduciendo ancho de banda igual a la tasa de símbolos para evidenciar ISI.
3.Filtro coseno alzado con distintos valores de roll-off (β=1,0,0.5): Se evaluó el ancho de banda teórico y medido, observando el equilibrio entre eficiencia espectral y calidad de señal.
4.Filtro raíz de coseno alzado: Se identificó la pérdida del instante libre de ISI en el diagrama de ojo, lo cual impacta en la temporización y detección de símbolos.
5.Repetición de los casos anteriores con ruido y modulación 16-QAM: Para evaluar la robustez de las configuraciones ante degradación por canal.1
