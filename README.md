# Practica Recuperatorio

Desarrollar una aplicación destinada al consumo de productos financieros. Cada usuario tendrá asociada una
billetera, la cual tiene un saldo, el cual se puede ir cargando en la medida que se necesite, o utilizar
para hacer compras, de las cuales resulta interesante almacenar un historial. 

El sistema ofrece un conjunto de productos financieros, que el usuario puede comprar, y agregar 
a su billetera. Los mismos afectarán, instantaneamente, o a lo largo del tiempo, el saldo de la billetera.

Los productos pueden ser:
- Inversión simple: Se "compra" por un valor determinado. Tiene un plazo de vencimiento y un porcentaje de retorno
de la inversión hecha. Es decir, si se invierten $100, tiene un 10% de retorno y vence en 30 días, en el día
31 al saldo de la billetera se le tienen que sumar $110.
- Regalo Instantaneo: Es un "regalo" que se cobra en el momento, sumando un valor fijo a la billetera.
- Regalo diferido: Tiene un plazo de vencimiento también, y sumara un valor fijo a la billetera una vez que se 
cumpla dicho plazo.

El sistema contendrá el registro de todas las billeteras registradas, y se tiene que poder simular el paso 
de los días a través de un método.
