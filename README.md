# ivoire-BD
Création de dessin animé profes

// Déclaration des variables nécessaires
var dessin = new Dessin(); // instance de la classe Dessin, qui contiendra tous les dessins créés
var outilCourant = null; // outil courant sélectionné par l'utilisateur
var couleurCourante = "noir"; // couleur courante sélectionnée par l'utilisateur
var tailleCourante = 1; // taille courante sélectionnée par l'utilisateur 

// Déclaration des classes nécessaires
class Dessin {
constructor() {
this.dessins = []; // tableau pour stocker tous les dessins créés par l'utilisateur
} 

} 

ajouterDessin(dessin) {
this.dessins.push(dessin); // ajouter un dessin au tableau des dessins
}
} 

class Outil {
constructor(nom) {
this.nom = nom; // nom de l'outil
this.enCours = false; // booléen pour savoir si l'outil est en cours d'utilisation
} 

activer() {
this.enCours = true; // activer l'outil
} 

désactiver() {
this.enCours = false; // désactiver l'outil
} 

dessiner(x, y) {
// à implémenter dans chaque classe d'outil
}
} 

class Crayon extends Outil {
dessiner(x, y) {
// dessiner une ligne avec le crayon
dessin.context.beginPath();
yon
dessin.context.beginPath();
dessin.context.moveTo(x, y);
dessin.context.lineTo(x + 1, y + 1);
dessin.context.strokeStyle = couleurCourante;
dessin.context.lineWidth = tailleCourante;
dessin.context.stroke();
}
} 

class Gomme extends Outil {
dessiner(x, y) {
// effacer une partie du dessin avec la gomme
dessin avec la gomme
