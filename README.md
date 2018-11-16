Implementation façade about Minimo1 using Singleton pattern. I also create a REST service that implements the functions delcared in the interface ProductManager

Explanation about API:

Services:

1.electricalbikes/ bikes Methods: 1. GET: - Get bikes of a stations sorted by kms asc /sortedbikesbykm/:idStation - Get bike /getbike - Get bikes by user /getbikes/:idUser 2. POST: - Add user /adduser - Add station /addstation - Add bike /addbike - Place an order /placeanorder/:user

Models:

Bike: String idBike; String description; double kms; String idStation;

Station: String idStation; String description; int max; double lat; double lon;

User: String idUser; String name; String surname;Implementation façade about Minimo1 using Singleton pattern. I also create a REST service that implements the functions delcared in the interface ProductManager

