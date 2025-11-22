## ¿Qué es y que hace la práctica? / ¿Qué aprendimos?
La práctica consistió en crear una aplicación con Tkinter que analiza si un mensaje es SPAM o NO SPAM.
Aprendimos a usar ventanas, etiquetas, botones y entradas de texto, y también a conectar una interfaz gráfica con un modelo de machine learning para hacer predicciones usando un archivo CSV, aprendimos tambien a manejar git, como subir nuestras practicas y a utilizar la consola.

## ¿Cómo lo hicimos? / Tecnologías-Librerías utilizadas 
Usamos:
Tkinter para la interfaz gráfica (ventana, botón, entrada de texto).
pandas para leer datos.
scikit-learn para entrenar el modelo (CountVectorizer, train_test_split, Naive Bayes).
Dos archivos principales:
    screen.py → interfaz
    spam_detector.py → entrenamiento y predicción

## Trabajo futuro / Oportunidades de mejora / Solución de sus posibles errores
Mejorar la interfaz (colores, diseño, botones extras).
Guardar el modelo entrenado para que no se entrene cada vez.
Manejar errores como cuando el archivo CSV no está en la carpeta correcta o cuando el usuario no escribe nada.
Probar modelos más avanzados para mejorar la precisión.
