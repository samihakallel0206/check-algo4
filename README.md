
# check-algo4
Probleme:

Déscription:
Teste si un mot est un palindrome. Un mot est un palindrome ne serait-ce que s'il peut
se lire de gauche à droite ou de droite à gauche : gag ; kayak; php; radar;....

Instructions:
Répartition du traitement : on compare les caractères situés en fin de mot :
si égalité on teste le reste du mot
si différence on s'arrête
Condition d'arrêt : un mot vide ou un mot contenant un seul caractère est un palindrome.

Solution
On commenece par la condition d'arrêt, ie, si on trouve un mot d'une lettre ou le mot vide cela veut dire que c'est un palindrome
Sinon plusieurs caractere on verifie: si on a pas dépasser les indices qu'on va incrémenter et décéementer par la suite, 
on teste l'égalité des caractères si cest egale on fait un appel de fonction (récursivite), 
en décrementant et incrémentant les indices respectivement pour décaler et refaire le même travail
Sinon, ie, ya pas d'égalté de caractères on sort avec un return false: ce nest pas un palindrome.
