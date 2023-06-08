### Database: parking-control-db

---
## Examples


### POST
http://localhost:8080/parking-spot

```json
{
	"parkingSpotNumber": "A080",
	"licensePlateCar": "ACB1234",
	"brandCar": "Chevrolet",
	"modelCar": "Astra",
	"colorCar": "Silver",
	"responsibleName": "John Smith",
	"apartment": "121",
	"block": "C"
}
```

### GET
http://localhost:8080/parking-spot

### GET
http://localhost:8080/parking-spot/{id}

### PUT
http://localhost:8080/parking-spot/{id}

### DELETE
http://localhost:8080/parking-spot/{id}

```json
{
	"parkingSpotNumber": "A080",
	"licensePlateCar": "A1B2C3",
	"brandCar": "Chevrolet",
	"modelCar": "Cruze",
	"colorCar": "Blue",
	"responsibleName": "John Smith",
	"apartment": "121",
	"block": "C"
}
```