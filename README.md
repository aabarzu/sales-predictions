# sales-predictions

El proyecto busca predecier las ventas de productos.

Conclusiones

El mejor score = 58.87con n_estimators = 900, se consiguió Sin utilizar OneHotEncoder en las columnas 'Outlet_Identifier' y 'Outlet_Size' , solo se aplicó LabelEncoder para esas columnas

¿Hay algo que puedas hacer para mejorar el modelo?

Se deberia mejorar la calidad de los datos para lograr un mejor Score, eliminando los datos que quedan como 'Undefined' en el campo Outlet_Size
Outlet_Size = 'High', 'Medium', 'Small', 'Undefined'

¿Qué características están más asociadas con la predicción de ventas mayores?

Las características que influyen mayormente en las ventas son:

Item_MRP
Outlet_Identifier
Outlet_Type
Outlet_Size
Item_Visibility
