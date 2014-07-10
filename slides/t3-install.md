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


  First step: Should I install a new instance or duplicate an existing one ?<br />
  What makes a installation: cf. slide<br />
  Since many years pre-installed frameworks florish. You've certainly heard of Twitter bootstrap, Introduction package, Government package... For us, they are wonderfull tools... to make quick demo, but not to start projects. Why?<br />
  The answer is pretty simple. They includes too many futile things! When I start a project, I don't want to remove demo pages, I don't want to clean 2000 lines of CSS. I want to build things. A developer is a creator, not a cleaner. (don't make me say what I didn't say: I love maids :p)<br />
  Maybe, we could make a Inouit package with our typo3 configuration but our needs exceed typo3 boundaries so we have a typo3 almost empty installation (easy to maintain) that we duplicate with a script. What are the differences? cf. slide

Première étape : dois-je installer un typo, où dois-je en dupliquer un ?<br />
Que fait une installation de typo3 ?<br />**BAS**
Depuis quelques années, nous avons vu fleurir des sites pré-construit, des *installation package*, des *twitter bootstrap*, ... <br />
A nos yeux, ce sont d'excellents outils pour une présentation, mais ils sont peu utilisables au moment de commencer un site. Pourquoi ? <br />
Parce qu'ils intègrent beaucoup trop de choses futiles ! Quand j'installe un site, ce qui me préoccupe en premier ne devrait pas être de supprimer des pages, d'assainir une feuille de style. Je n'ai pas non plus envie de configurer un virtual host, de dupliquer mon site sur l'ensemble des serveurs de développement et de test.<br />
Non ! Ce que j'ai envie de faire c'est de commencer le travail de création pour lequel j'apporte une vraie valeur ajoutée.<br />
Nous aurions pu faire un Inouit Package, mais comme je viens de le dire, nos besoins vont bien au-delà du framework. Aussi nous  sommes nous tournés vers un script de duplication. Quelles différences celà fait ?**BAS**
