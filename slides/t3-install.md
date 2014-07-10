<!-- .slide: data-breadcrumb="Installation VS Duplication" -->
# Première étape :

<table class="reveal">
	<thead>
		<tr>
			<th width="48%"><img src="img/ico_install.png" width="50" alt=""/> Installation</th>
			<th width="4%" class="vs">VS</th>
			<th width="48%"><img src="img/ico_clone.png" width="50" alt=""/> Script de duplication</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>
				<ul class="fragment fade-in">
					<li>3 à 5 étapes simples</li>
					<li>Installation d'un package</li>
				</ul>
			</td>
			<td>
				<ul class="fragment fade-in">
					<li>2 questions (nom d'utilisateur, nom de projet)</li>
					<li>Configuration des extensions systèmatiques</li>
					<li>Configuration Typoscript de base (menus, logo, favicon, ...)</li>
					<li>Déploiement sur plusieurs postes</li>
					<li>Configuration serveur, versionning, fichiers locaux, ...</li>
				</ul>
			</td>
		</tr>
	</tbody>
</table>

<img src="img/demo-install.gif" alt="" class="fragment fade-in"/>

note:
	Première étape : installer une nouvelle instance de typo3 ou en dupliquer une ?<br />
	Que fait une installation ? (cf. slide)<br />
	Depuis de nombreuses années, nous avons vu débarquer de nombreux systèmes de sites pré-configurés : Twitter bootstrap, Introduction et Government package, ... Si ce sont de formidables outils pour construire des sites de démo mais pas pour démarrer de vrais projet d'agence. Pourquoi ?<br />
	Parce que beaucoup trop de choses futiles sont installées ! Quand je commence un projet, je n'ai pas envie de supprimer des pages de démo, de nettoyer les 2000 lignes de CSS que je n'utuliserai pas. J'ai envie de construire des choses. Un développeur est un créateur à sa façon, pas une femme de ménage (et je n'ai rien contre les agents de nettoyage :p)<br />
	Nous aurions pu envisager de créer un Inouit Package pour Typo3, mais nos besoins excèdent largement le domaine du simple framework aussi nous avons choisi de contruire un site presque vide (très facile à maintenir) que nous dupliquons via un script. Quest-ce que ça change ? (cf. slide)