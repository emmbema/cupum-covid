<template>
	<div class="meta" >
	<div class="meta" v-bar ref="vbar">
	<div id="enjeux-paysage" class="view-scroll">
		<PageTitle/>
		<div class="center-col">
			<p>Les enjeux du paysage urbain montr&eacute;alais de la phase de confinement ont &eacute;t&eacute; document&eacute;s afin d&rsquo;apporter des r&eacute;ponses face &agrave; un ensemble de pr&eacute;occupations envers l&rsquo;espace public. Pour y arriver, il a &eacute;t&eacute; convenu de documenter ces enjeux en scrutant les contenus des m&eacute;dias montr&eacute;alais du 13 mars au 16 mai 2020.</p>
			<p>Cette section pr&eacute;sente les r&eacute;sultats de cette analyse de veille informationnelle. L&rsquo;&eacute;chantillonnage des articles pour cette veille a &eacute;t&eacute; effectu&eacute; &agrave; partir de douze (12) sources d&rsquo;informations québécoises et montréalaises (de langues fran&ccedil;aise et anglaise) regroup&eacute;es en quatre (4) groupes{{'\xa0'}}:
			</p>
			<p>
				<ol>
					<li>articles de journaux{{'\xa0'}};</li>
					<li>communiqu&eacute;s de presse gouvernementaux{{'\xa0'}};</li>
					<li>plateformes web d&rsquo;organismes &agrave; but non lucratif (OBNL){{'\xa0'}};</li>
					<li>magazines en ligne.</li>
				</ol>
			</p>
			<p>À partir des diverses sources et d’un flux RSS, un échantillonnage de 163 articles a été sélectionné en fonction des mots-clés tirés des questionnements et enjeux sur lesquels la CUPUM et l’UNESCO (SHS) se penchent pour mener à terme sa veille informationnelle. Une fois les articles repérés, une analyse qualitative soulevant les informations de base (titre, date, auteur, type d’article, résumé) et les enjeux abordés (questionnements et mots-clés) de chaque article a été comptabilisée dans un chiffrier. En amont, le logiciel de traitement de données <i>Atlas.ti</i> a permis de dénombrer des données quantitatives sur la veille informationnelle pour émettre des constats sur les attributs urbains (automobile, commerce, parc, rue, ville). </p>
			<p>Cette analyse repose sur les sources de donn&eacute;es suivantes, soit{{'\xa0'}}:</p>
			<p>
				<ul>
					<li>le flux RSS des principales sources m&eacute;diatiques qu&eacute;b&eacute;coises &agrave; partir de Feedly
						<ul>
							<li><i>Le Devoir</i>{{'\xa0'}};</li>
							<li><i>La Presse</i>{{'\xa0'}};</li>
							<li><i>Journal de Montr&eacute;al</i>{{'\xa0'}};</li>
							<li><i>Journal M&eacute;tro</i>{{'\xa0'}};</li>
							<li><i>ICI Radio-Canada</i> et <i>Grand Montr&eacute;al Radio-Canada</i>{{'\xa0'}};</li>
							<li><i>CBC</i>{{'\xa0'}};</li>
							<li><i>The Gazette</i>{{'\xa0'}};</li>
							<li>Communiqu&eacute;s de presse de la <i>Ville de Montr&eacute;al</i>{{'\xa0'}};</li>
						</ul>
					</li>
					<li>les fils de presse consult&eacute;s individuellement{{'\xa0'}}: 
						<ul>
							<li><a class="reference-link" href="http://www.fil-information.gouv.qc.ca/Pages/Articles.aspx" target="_blank">Services Qu&eacute;bec. Fil d&rsquo;information. CNW Telbec</a></li>
						</ul>
					</li>
					<li>les plateformes web d&rsquo;organismes &agrave; but non lucratif (OBNL) et abonnement &agrave; l&rsquo;infolettre{{'\xa0'}}:
						<ul>
							<li><a class="reference-link" href="https://www.missionoldbrewery.ca/fr/" target="_blank">Mission Old Brewery</a></li>
							<li><a class="reference-link" href="http://www.maisondupere.org/" target="_blank">La Maison du P&egrave;re</a></li>
							<li><a class="reference-link" href="https://missionbonaccueil.com/services-fr/?where=google&amp;gclid=Cj0KCQjwhZr1BRCLARIsALjRVQMwEIUcZME_p7dPxM4A90VJmal0w4grl0qQWf4aNssueji6hR3UxAsaAi1VEALw_wcB" target="_blank">Accueil Bonneau</a></li>
							<li><a class="reference-link" href="https://mmfim.ca/" target="_blank">Mouvement pour mettre fin &agrave; l&rsquo;itin&eacute;rance &agrave; Montr&eacute;al</a> (MMFIM)</li>
							<li><a class="reference-link" href="https://www.asf-quebec.org/a-propos/historique-2/" target="_blank">Architectes sans fronti&egrave;res Qu&eacute;bec</a> (ASFQ)</li>
							<li><a class="reference-link" href="https://www.heritagemontreal.org/" target="_blank">H&eacute;ritage Montr&eacute;al</a></li>
							<li><a class="reference-link" href="https://www.cssspnql.com/" target="_blank">Commission de la sant&eacute; et des services sociaux des Premi&egrave;res Nations du Qu&eacute;bec et du Labrador</a></li>
						</ul>
					</li>
					<li>les abonnements aux infolettres des magazines et autres sources{{'\xa0'}}:
						<ul>
							<li><i>Esquisse</i> (magazine mensuel){{'\xa0'}};</li>
							<li><i>Formes</i> (magazine bimestriel){{'\xa0'}};</li>
							<li><i>L&rsquo;actualit&eacute;</i> (magazine bimensuel){{'\xa0'}};</li>
							<li><i>Kollectif</i> (page web).</li>
						</ul>
					</li>
				</ul>
			</p>
			<p>Les recherches de la veille informationnelle se s&eacute;parent en 4 sous-sections pr&eacute;sentant les analyses et r&eacute;sultats de mani&egrave;re qualitatives, quantitatives et graphiques.</p>
			<p>La sous-section <router-link tag="a" class="reference-link" :to="{name: routerDestination(4,1).name}" v-html="routeLabel(4,1)"></router-link> introduit une analyse qualitative &eacute;crite sur les principaux questionnements pos&eacute;s par la CUPUM au cours du confinement de la COVID-19.</p>
			<p>Quant &agrave; la section suivante (<router-link tag="a" class="reference-link" :to="{name: routerDestination(4,2).name}" v-html="routeLabel(4,2)"></router-link>), elle propose &agrave; l&rsquo;aide d&rsquo;outils graphiques une analyse quantitative des occurrences des attributs urbains rep&eacute;r&eacute;s dans l&rsquo;&eacute;chantillonnage.</p>
			<p>Puis, la section <router-link tag="a" class="reference-link" :to="{name: routerDestination(4,3).name}" v-html="routeLabel(4,3)"></router-link> offre une vision globale et territoriale de Montr&eacute;al au temps du confinement de la COVID-19 en identifiant g&eacute;ographiquement et chronologiquement les initiatives mises en place.</p>
			<p>En d&eacute;finitive, la derni&egrave;re section (<router-link tag="a" class="reference-link" :to="{name: routerDestination(4,4).name}" v-html="routeLabel(4,4)"></router-link>) s&rsquo;ouvre sur une analyse graphique quantitative des occurrences des qualificatifs de l&rsquo;humain mettant en lumi&egrave;re sa place dans Montr&eacute;al lors du confinement.</p>

			<ChapterNav :previous="true" :next="true" />
		</div>
	</div>
	</div>
	</div>
</template>

<script>
import PageTitle from '@/components/PageTitle'
import ChapterNav from '@/components/ChapterNav'

export default {
	name: 'EnjeuxPaysageUrbain',
	components: {
		PageTitle,
		ChapterNav
	},
	activated() {
		this.$vuebar.refreshScrollbar(this.$refs.vbar)
	},
	data() {
		return {
		}
	},
	methods: {
		routerDestination(chapter,subChapter) {
			return this.$router.options.routes.find(route => parseInt(route.chapter,10) == parseInt(chapter,10) && (subChapter? route.subChapter==subChapter : !route.isSubChapter))
		},
		routeLabel(chapter,subChapter) {
			var routeEl = this.routerDestination(chapter, subChapter);
			var num = chapter + (subChapter? '.'+subChapter : '')
			var title = routeEl.title;
			return num+' - <i>'+title+'</i>'
		}
	}
}
</script>

<style scoped>
#enjeux-paysage {
	width: 100%;
	height: 100%;
}
</style>