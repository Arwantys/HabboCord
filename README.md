# Habbo Cord

## Installation

```bash
npm install
```

## Configuration

Vous devez configurer la base de données de votre rétro-habbo pour que l'application accède aux données de celui-ci.

```javascript
var database = mysql.createConnection({
	host: "localhost",
	user: "habbo",
	password: "root",
	database: "habbo",
	charset: "utf8mb4",
});
```

## Usage 

```bash
node server.js
```
