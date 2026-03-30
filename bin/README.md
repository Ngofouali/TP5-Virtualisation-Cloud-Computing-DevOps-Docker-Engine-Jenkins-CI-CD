<h1>TP5 – Virtualisation, Cloud Computing & DevOps</h1>
<h2>Description</h2>
Ce TP a pour objectif de mettre en place une chaîne CI/CD (Intégration Continue / Déploiement Continu) avec Jenkins, Docker et GitHub.
Nous allons :<br/>
<ul>
<li>Créer une application web simple (page index.html) servie par Nginx dans un conteneur Docker.</ul>
<li>Versionner le code sur GitHub.</ul>
<li>Automatiser la construction et le déploiement d’images Docker via des jobs Jenkins (freestyle et pipeline).</ul>
<li>Observer le déclenchement automatique des builds à chaque modification du code.</ul>
<li>Déployer l’image sur un moteur Docker local.
</ul>
<h2>Prérequis</h2>
<ul>
<li>Jenkins installé et accessible (http://localhost:8080)</ul>
<li>Docker installé sur la machine hôte</ul>
<li>Un compte Docker Hub (pour publier les images)</ul>
<li>Un compte GitHub (pour héberger le code)</ul>
<li>Plugins Jenkins installés :
<ul>
<li>CloudBees Docker Build and Publish</li>
<li>Docker Commons</li>
<li>Docker Pipeline</li>
<li>Git plugin</li>
</ul>
</ul>

