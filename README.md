la fonction password_hash() : permet de hasher un mot de passe en utilisant un certain algorithme et un certain sel
la fonction password_verify() : permet de vérifier si un mot de passe en clair et un mot de passe hashé correspondent
la fonction random_bytes() : permet d'obtenir un certain nombre d'octets aléatoires sécurisés, c'est une sorte de super fonction rand(), suffisament sécurisée pour qu'on puisse s'en servire en cryptographie.
la fonction bin2hex() : qui va nous permettre de convertir les octets aléatoires de random_bytes() en code hexa, pour notre sel, c'est quand même plus lisible pour nous humains... quoique.
