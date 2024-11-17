Modelo original: https://github.com/JACantoral/DL_fundamentals/blob/main/DL_fundamentals_transformer_model.ipynb  <----


Transformers para un conjunto de oraciones de prueba, generando las traducciones oraciones. 
Se utiliza el modelo previamente entrenado, junto con diccionarios que mapean palabras en inglés a índices y viceversa,
 para traducir las oraciones. El proceso se realiza en los siguientes pasos:

    Se toma una oración  del conjunto de prueba.
    Se traduce utilizando el modelo Transformer.
    Se imprime la oración original  y su traducción generada.
    La traducción incluye símbolos especiales <sos> (inicio de secuencia) y <eos> (fin de secuencia).

El código también incluye algunos ejemplos de oraciones y cómo se traducen,
 mostrando las limitaciones del modelo en el manejo de algunas estructuras gramaticales y 
repetición de palabras, como se puede observar en los ejemplos como "estoy aprendiendo inteligencia inteligencia inteligencia".