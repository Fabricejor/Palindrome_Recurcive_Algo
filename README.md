# Palindrome_Recurcive_Algo
Algorithme récursive qui permet de savoir si un mot est palindrome ( mot qui peut se lire dans les deux sens) 

on ecrit un mot  on  place 2 index i et j respectivement au premier et dernier charactere
puis on compare tab[i] et tab[j] si c'est le meme charactere on pousse i et j vers le centre du mot i+1 et j-1
et on rapelle la fonction recursive en le passant comme parametre i et j apres iteration
tant que tab[i] == tab[j] et que i!=j alors on continue d'appeller la fonction en changant les valeurs de i et j
jusqu'a atteindre le centre du mot 