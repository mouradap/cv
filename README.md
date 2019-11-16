# mouradap.github.io
<!DOCTYPE html>
<html>
<head>
<title>Denis Moura - Resumé</title>

<meta name="viewport" content="width=device-width"/>
<meta name="description" content="Denis Moura's Curriculum Vitae"/>
<meta charset="UTF-8"> 

<link type="text/css" rel="stylesheet" href="style.css">
<link href='http://fonts.googleapis.com/css?family=Rokkitt:400,700|Lato:400,300' rel='stylesheet' type='text/css'>

<!--[if lt IE 9]>
<script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>
<body id="top">
<div id="cv" class="instaFade">
	<div class="mainDetails">
		<div id="headshot" class="quickFade">
			<img src="headshot.jpg" alt="Denis Moura" />
		</div>
		
		<div id="name">
			<h1 class="quickFade delayTwo">Denis Moura</h1>
			<h2 class="quickFade delayThree">Bioinformatician</h2>
			<h2 class="quickFade delayThree">Data Scientist</h2>
			<h4 class="quickFade delayThree">February, 24th 1992</h4>
		</div>
		
		<div id="contactDetails" class="quickFade delayFour">
			<ul>
				<li><img src="gmail.jpg"/> e-mail: <a href="mailto:drmouradap@gmail.com" target="_blank">drmouradap@gmail.com</a></li>
				<li><img src="lattes.jpg" /> lattes: <a href="http://lattes.cnpq.br/0608815230607754">lattes.cnpq.br/0608815230607754</a></li>
				<li><img src="github.jpg" /> github: <a href="https://www.github.com/mouradap">github.com/mouradap</a></li>
				<li><img src="researchgate.jpg" /> researchgate: <a href="https://www.researchgate.net/profile/Denis_Moura">researchgate.net/profile/denis_moura</a></li>
				<li><img src="linkedin.jpg" /> linkedin: <a href="https://www.linkedin.com/in/drmoura/">linkedin.com/in/drmoura/</a></li>
				<li><img src="phone.jpg" /> phone: +55 (81) 998238814</li>
			</ul>
		</div>
		<div class="clear"></div>
		
	</div>

	<div class="mainDetails">
		<p><a href=indexpt.html>Clique para o currículo em Português</a></p>
		<div class="sectionTitle">
					<h1>Quick Links</h1>
		</div>

		<ul class="keySkills">
			<li><a href=#personalProfile>Personal Profile</a></li>
			<li><a href=#keySkills>Key Skills</a></li>
			<li><a href=#projects>Projects</a></li>
			<li><a href=#publications>Publications</a></li>
			<li><a href=#education>Education</a></li>
		</ul>

	</div>
	
	<div id="mainArea" class="quickFade delayFive">
		<section id="personalProfile">
			<article>
				<div class="sectionTitle">
					<h1>Personal Profile</h1>
				</div>
				
				<div class="sectionContent">
					<p>Master in Biology and Ph.D candidate in Applied Biology to Health. Denis worked with data analysis for over five years, since his undergrad research. Using genomics and transcriptomics datasets such as Allen Institute's <a href="https://portal.brain-map.org/">Brain-Map</a>, resulted in the publication of several scientific papers in the area of Neurogenetics. Hungry for new challenges, Denis now desires to bring his academic skillset to the private sector.</p>
				</div>
			</article>
			<div class="clear"></div>
		</section>

		<section id="keySkills">
			<div class="sectionTitle">
				<h1>Key Skills</h1>
			</div>
			
			<div class="sectionContent">
				<ul class="keySkills">
					<li>Python</li>
					<li>Statistics</li>
					<li>Genomics</li>
					<li>R</li>
					<li>Artifical Intelligence</li>
					<li>Proteomics</li>
					<li>SQL</li>
					<li>Machine Learning</li>
					<li>Data Communication</li>
				</ul>
			</div>
			<div class="clear"></div>
		</section>

		
		<section id="projects">
			<div class="sectionTitle">
				<h1>Projects</h1>
			</div>
			
			<div class="sectionContent">
				<article>
					<h2>Transcriptomics of Dementia</h2>
					<p class="subDetails">R, Python, DESeq2, randomForest, Machine Learning</p>
					<p>This project led to the presentation "What do our brains tell us about dementia? Machine Learning applied to Aging, Dementia and Traumatic Brain Injury Study". This study attempted to find transcriptome patterns of dementia in aged human brains. Random Forest models with 10 classifier genes chosen from Importance Analysis were able to correctly identify around 82% of dementia samples based solely on transcriptome profiles. This was the Denis' first Machine Learning project and granted the third best presentation award at the X International Symposium on
Diagnostics and Therapeutics (SINATER, 2019).</p>
				</article>

				<article>
					<h2>ABraOM Analysis</h2>
					<p class="subDetails">Python, Pandas, Jupyter Notebook</p>
					<p>This project aimed to extract clinical information of variants within the ABraOM database. In this project we analyzed which variant annotations of the five Primary Familial Brain Calcification genes are present in the SABE609 South-American cohort. This project resulted in the presentation 'Markers of Longevity: The Absence of Pathogenic Variants of Primary Familial Brain Calcification in Brazilian Elderly', presented at the 1st EBIO-UFPE.</p>
				</article>

				<article>
					<h2>FamilyTree DNA Genotype Analysis</h2>
					<p class="subDetails">Python, Pandas, matplotlib, jQuery, Jupyter Notebook</p>
					<p>This project resulted in a program to extract information from Genographic and FamilyTree DNA genotyping data, translating it into clinically relevant data.</p>
				</article>

				<article>
					<h2>Gene/Protein Interactome Analysis of PFBC</h2>
					<p class="subDetails">Clustering, GeneMania, STRING protein interactome database</p>
					<p>A project to generate and visualize a gene/protein interaction network of Primary Familial Brain Calcification-causing genes. This proejct resulted in the presentation 'A SPARC of Hope: Molecular Network Analysis Points to Osteonectin as Central Node for Basal Ganglia Calcifications.', granting the best presentation award at the IX International Symposium on
Diagnostics and Therapeutics (SINATER, 2018).</p>
				</article>

				<article>
					<h2>Protein's Functional Susceptibility to Variations</h2>
					<p class="subDetails">Database, R, Statistics, Function Predition Algorithms</p>
					<p> This project was the main focus of Denis's Dissertation. It's objective was to use dbNSFP database to profile the PiT2 variation susceptibility by overlaying different prediction algorithms. The project turned to Denis' dissertation entitled 'Análise preditiva in silico da susceptibilidade funcional a alterações da proteína PiT2.', awarding him the title of Master in Applied Biology to Health. And was presented at the VIII International Symposium on
Diagnostics and Therapeutics (SINATER, 2017), as 'Profiling PiT2 Protein Variants Effect On Functionality By Prediction Algorithms', and being awarded as the second best presentation of the event. </p>
				</article>


				<article>
					<h2>Identification of New Candidate Genes for PFBC</h2>
					<p class="subDetails">Database, Microsoft Excel, Statistics</p>
					<p> Using the Anatomic Gene Expression Atlas (AGEA) database, Denis studied the patterns of expression within calcification-prone areas of mice brains. This project was presented as 'Identification of three new candidate genes for Primary Familial Brain Calcification', and awared as the second best presentation at VII International Symposium on
Diagnostics and Therapeutics (SINATER, 2016). </p>
				</article>


				

				

			</div>
			<div class="clear"></div>
		</section>
		
	
		<section id="publications">
			<div class="sectionTitle">
				<h1>Publications</h1>
			</div>
			
			<div class="sectionContent">
				<article>
					<h3>Brain calcifications and PCDH12 variants</h3>
					<p class="subDetails">Neurology Genetics, v. 3, p. e166, 2017. <a href=https://doi.org/10.1212/NXG.0000000000000166> doi.org/10.1212/NXG.0000000000000166</a> </p>
					<p>Objective: To assess the potential connection between PCDH12 and brain calcifications in a patient carrying a homozygous nonsense variant in PCDH12 and in adult patients with brain calcifications.

Methods: We performed a CT scan in 1 child with a homozygous PCDH12 nonsense variant. We screened DNA samples from 53 patients with primary familial brain calcification (PFBC) and 26 patients with brain calcification of unknown cause (BCUC).

Results: We identified brain calcifications in subcortical and perithalamic regions in the patient with a homozygous PCDH12 nonsense variant. The calcification pattern was different from what has been observed in PFBC and more similar to what is described in in utero infections. In patients with PFBC or BCUC, we found no protein-truncating variant and 3 rare (minor allele frequency <0.001) PCDH12 predicted damaging missense heterozygous variants in 3 unrelated patients, albeit with no segregation data available.

Conclusions: Brain calcifications should be added to the phenotypic spectrum associated with PCDH12 biallelic loss of function, in the context of severe cerebral developmental abnormalities. A putative role for PCDH12 variants remains to be determined in PFBC.</p>
				</article>
				
				<article>
					<h3>New Data from Pdfgbret/ret Mutant Mice Might Lead to a Paradoxical Association Between Brain Calcification, Pericytes Recruitment and BBB Integrity.</h3>
					<p class="subDetails">Journal of Molecular Neuroscience, v.1, p.1-3, 2017. <a href=https://doi.org/10.1007/s12031-017-0992-z>doi.org/10.1007/s12031-017-0992-z</a> </p>
					<p>Data of mice with PDGF-B-truncating mutation (Pdgfb ret/ret) from different research groups indicate that the malfunction of this protein leads to reduced pericyte recruitment, loss of Blood-Brain Barrier (BBB) integrity and bilateral brain calcification. This makes these mice important models for Primary Brain Calcification and pericyte-BBB correlation studies. The global brain pericyte count is reduced in Pdgfb ret/ret mice, with higher BBB permeability. We have overlapped the data from other research groups into a figure to further analyze the findings. Calcifications form within midbrain, interbrain, basal forebrain, and pons. Interestingly, these calcification-prone regions have a comparably higher pericyte count and lower BBB leakage in relation to other non-calcifying regions of the Pdgfb ret/ret mouse (such as the cortex and striatum). A comparatively higher BBB integrity in regions prone to calcification seems paradoxical and indicates that other region-specific changes are the cause of the calcifications.</p>
				</article>

				<article>
					<h3>Clarifying samples in Zika analyses</h3>
					<p class="subDetails">Science  29 Jul 2016: Vol. 353, Issue 6298, pp. 452 <a href=https://science.sciencemag.org/content/353/6298/452.1>10.1126/science.aah3733</a> </p>
					<p>A letter in response to the Zika outbreak and putatively related microcephaly cases in Brazil, regarding the re-utilization of the same samples in multiple studies, and overreporting of cases.</p>
				</article>

				<article>
					<h3>XPR1: a Gene Linked to Primary Familial Brain Calcification Might Help Explain a Spectrum of Neuropsychiatric Disorders</h3>
					<p class="subDetails">Journal of Molecular Neuroscience, v.57, p.519-521, 2015.<a href=https://doi.org/10.1007/s12031-015-0631-5>doi.org/10.1007/s12031-015-0631-5</a> </p>
					<p>Primary familial brain calcifications (PFBC) compose a rare neurologic condition characterized by a bilateral pattern of hydroxyapatite deposits in basal ganglia, dentate nuclei, and thalamus. PFBC is identified through neuroimaging screenings such as computerized tomography. Patients with PFBC might present a wide variety of neurological symptoms such as mental and motor impairments, often misdiagnosed as Parkinson’s disease, schizophrenia, Alzheimer’s disease, and migraine. Four genes were confirmed as causative of PFBC: SLC20A2, PDGFB, PDGFRB, and XPR1. Curiously, other studies made occasional links between XPR1 variations or expression changes, in a few neuropsychiatric models. This letter is an assembly on XPR1 variants and expression change pattern data that were published in recent scientific reports, even before the current connection between that gene and brain calcification.</p>
				</article>


			</div>
			<div class="clear"></div>
		</section>


		<section id="education">
			<div class="sectionTitle">
				<h1>Education</h1>
				<br>
				<h5>Click for certificates.</h4>
			</div>
			
			<div class="sectionContent">
				<article>
					<h2>Ph.D Candidate </h2>
					<p class="subDetails">Universidade Federal de Pernambuco (2018 - current)</p>
					<p>Continuing his research on the genetics of Primary Familial Brain Calcification, Denis joined the doctorate program in the same institution, the Programa de Pós-Graduação em Biologia Aplicada à Saúde (PPGBAS) of the Laboratório de Imunopatologia Keizo Asami, also supervised by Prof. Dr. João Ricardo Mendes de Oliveira MD, Ph.D. In this new comprehensive project, stronger analytical programming skills were necessary. Denis dove deep into Data Science, improving and learning crucial data skills. Several projects were developed in order to train and gain experience in the field, which awarded Denis the best presentations of PPGBAS's yearly international scientific symposiums since 2018.</p>
				</article>
				
				<article>
					<h2>Master in Applied Biology to Health</h2>
					<p class="subDetails">Universidade Federal de Pernambuco (2016 - 2018)</p>
					<p>After graduating from college, Denis was promptly accepted to a Master's degree program through the Programa de Pós-Graduação em Biologia Aplicada à Saúde of the Laboratório de Imunopatologia Keizo Asami. During this time, he worked with the dissertation project 'Análise preditiva in silico da susceptibilidade funcional a alterações da proteína PiT2.', also supervised by Prof. Dr. João Ricardo Mendes de Oliveira MD, Ph.D. In this project, Denis was able to further develop his data analytical skills, and improved his knowledge of R language. Several parallel small projects were also developed, resulting in scientific publications of high impact, such as the need to clarify Zika samples, during the Zika Epidemy in Brazil (Science Magazine).</p>
				</article>

				<article>
					<h2>Undergraduate Visiting Student</h2>
					<p class="subDetails">Columbia University in the City of New York (2014)</p>
					<p>As an awardee of Brazil's Scientific Mobility Program (Ciência sem Fronteiras), Denis was chosen by Columbia University to study during the 2014 terms. During his stay, he focused on Advanced Biology courses, such as Biotechnology, Genomics of Gene Regulation and Molecular Ecology. This was when Denis was first introduced to programming languages such as R, which proved to be an important foundation for his following data analysis projects.</p>
				</article>

				<article>
					<h2>Bachelor of Science - Biology</h2>
					<p class="subDetails">Universidade Federal de Pernambuco (2010 - 2015)</p>
					<p>Denis majored Biology, focusing on Genetics, Human Genetics and Physiology. His monography was entitled 'Análise dos Padrões de Expressão e Correlações dos Genes Envolvidos na Calcificação Cerebral Familiar Primária Através do Allen Brain Atlas.', supervised by Prof. Dr. João Ricardo Mendes de Oliveira MD, Ph.D.</p>
				</article>

				

			</div>
			<div class="clear"></div>
		</section>
		
	</div>
</div>
<script type="text/javascript">
var gaJsHost = (("https:" == document.location.protocol) ? "https://ssl." : "http://www.");
document.write(unescape("%3Cscript src='" + gaJsHost + "google-analytics.com/ga.js' type='text/javascript'%3E%3C/script%3E"));
</script>
<script type="text/javascript">
var pageTracker = _gat._getTracker("UA-3753241-1");
pageTracker._initData();
pageTracker._trackPageview();
</script>
</body>
</html>
