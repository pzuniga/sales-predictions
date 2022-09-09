# sales-predictions

**uál es el desafío?**

Apoyar a la empresa distribuidora de productos alimenticios usando modelos de aprendizaje automático para hacer predicciones futuras de las ventas, basándose en los datos proporciones por él.

**¿Cuáles son los datos proporcionados?**

* oductos alimenticios
    Identificador único: 1.555 productos.
    Categoría de productos: 16 categorías
    Peso unitario
    Contenido de grasas: bajo en grasas y regular.
    Porcentaje de visibilidad (superficie)
    Precio máximo de venta al público según tiendas (USD/producto)
* Tiendas
    Identificador único: 10 tiendas.
    Año de apertura: 1895->2009.
    Tamaño (según superficie): grandes, medianas y pequeñas.
    Localización: 3 zonas.
    Tipo de tienda: 4 tipos.
    Ventas de un producto en una tienda particular: En total 18,58 millones USD.
Nota: Información obtenida sobre conjunto de datos limpios (8.519 filas y 12 columnas).


¿Qué muestran los datos sobre la oferta de productos?

![image](https://user-images.githubusercontent.com/106708017/189439017-290ac470-8fee-415f-a51e-37131768215d.png)
+ Alimentos bajos en grasas (64,76%)

![image](https://user-images.githubusercontent.com/106708017/189439118-d62757f2-c00e-4a87-9913-7a69910a12fc.png)
+ 10 Categorías más relevantes (84.06%) Fruits and Vegetables → Meat


**¿Qué muestran los datos sobre los precios?**
![image](https://user-images.githubusercontent.com/106708017/189439205-839e3c35-02ad-49de-9fcd-7e9c20253f42.png)

+ Mayor dispersión de precios en categorías de productos, aunque sin diferencias significativas!

¿Qué muestran los datos sobre las ventas?
![image](https://user-images.githubusercontent.com/106708017/189439283-bcf0feaf-702e-45a2-ae64-28f4672a8a93.png)
+ 18,58 MUSD en ventas → 84% distribuido en 9 categorías de productos

![image](https://user-images.githubusercontent.com/106708017/189439332-5c8c6123-9c5c-4658-a922-0c7c2ce2a5b4.png)
Correlación (0,57) entre las ventas de un producto y su precio máximo de catálogo!


Predicción de ventas – Desempeño ML

Aplicando el criterio de selección de >r2 y <RMSE se eligió el modelo predictivo Árbol de decisiones

![image](https://user-images.githubusercontent.com/106708017/189439427-32a65bcf-0b43-4930-af0d-507887092016.png)

Conclusiones

* Para apoyar a la empresa distribuidora de productos alimenticios usando modelos de aprendizaje automático para hacer predicciones futuras de las ventas, basándose en los datos proporciones por él. Se recomienda lo siguiente:
    + Utilizar modelo de Árbol de decisiones para predecir ventas futuras.
    + Monitorear las tendencias de ventas introduciendo nuevas características del negocio, como por ejemplo: atributos sociales y ambientales de productos, público objetivo, campañas de marketing. De esta manera enriquecer con nuevos datos el modelo y mejorar su desempeño predictivo.



























