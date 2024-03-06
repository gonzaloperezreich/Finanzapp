# Finanzapp

## Spanish
Finanzapp es una aplicación web creada utilizando Django, que permite al usuario llevar registro de sus movimientos financieros, así como ayudarlo a organizarlos de manera intuitiva.

Actualmente permite al usuario crear una cuenta, con la cual puede ingresar transacciones al sistema, que pueden ser ingresos o gastos, y asignarles un valor, una descripción y una categoría. En la vista principal, se le muestra al usuario el saldo global de su cuenta, el formulario usado para ingresar transacciones al sistema y un resumen del estado de sus categorías. Estas categorías son creadas por el usuario desde la sección *Organizate*, desde donde puede asignarles un nombre y un presupuesto, además de poder ajustar su presupuesto global.

Si se desea ver un listado de todas las transacciones que el usuario ha ingresado a la aplicación, puede hacerlo desde la sección *Transacciones*. Esta presenta todas las transacciones separadas por categorías, y permite editarlas o eliminarlas. También cuenta con filtros de fecha o de categoría, por si se necesita buscar una transacción específica.

Por último, para cerrar la sesión hay que hacer click en la sección *Logout*.

Para correr la aplicación se necesita tener instaladas las librerías indicadas en el archivo *requirements.txt*, o instalarlas en un entorno virtual y activarlo para ejecutar la aplicación. Luego, se debe entrar a la carpeta *finanzapp_proj* ejecutar el comando.

```
python manage.py runserver
```

Esto iniciará la aplicación en la dirección *http://127.0.0.1:8000/*. Al acceder a la dirección se mostrará el formulario de inicio de sesión. Si no se tiene una cuenta, hay un link al formulario de registro bajo el formulario. Una vez registrado, se inicia sesión y se redirige al usuario a la vista principal, desde donde se puede acceder a todas las funcionalidades de Finanzapp.

## English

Finanzapp is a web application created using Django, which allows the user to keep track of their financial transactions and helps them organize them in an intuitive manner.

Currently, it allows the user to create an account, through which they can input transactions into the system, which can be either income or expenses, and assign them a value, a description, and a category. On the main view, the user is shown the overall balance of their account, the form used to input transactions into the system, and a summary of their category status. These categories are created by the user from the Organize section, where they can assign them a name and a budget, as well as adjust their overall budget.

If the user wishes to see a list of all the transactions they have entered into the application, they can do so from the Transactions section. This section displays all transactions separated by categories and allows the user to edit or delete them. It also features date or category filters, in case a specific transaction needs to be searched for.

Finally, to log out, one must click on the Logout section.

To run the application, the libraries indicated in the requirements.txt file need to be installed, or they can be installed in a virtual environment and activated to run the application. Then, one must navigate to the finanzapp_proj folder and execute the following command:

```
python manage.py runserver
```

This will start the application at the address http://127.0.0.1:8000/. Upon accessing the address, the login form will be displayed. If one does not have an account, there is a link to the registration form below the form. Once registered, one logs in and is redirected to the main view, from where all Finanzapp functionalities can be accessed.