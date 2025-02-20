<?php
// Récupérer les variables d'environnement définies dans docker-compose
$db_host = getenv("DB_HOST");
$db_user = getenv("DB_USER");
$db_pass = getenv("DB_PASS");
$db_name = getenv("DB_NAME");

// Connexion à la base de données MySQL
$conn = new mysqli($db_host, $db_user, $db_pass, $db_name);

// Vérification de la connexion
if ($conn->connect_error) {
	die("Erreur de connexion: " . $conn->connect_error);
}

// Exécuter une requête simple
$sql = "SELECT 'Hello from the database!' AS message";
$result = $conn->query($sql);

if ($result->num_rows > 0) {
	$row = $result->fetch_assoc();
	echo "<h1>" . $row['message'] . "</h1>";
} else {
	echo "<h1>Aucun résultat</h1>";
}
$conn->close();
?>
