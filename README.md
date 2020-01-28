# brain-networks-across-the-web
Data across the world wide web ready to be downloaded for your brainhacking pleasure; an aggregation of brain networks, brain data that can be easily massaged into an NxN matrix, and other data helpful for brain network stuff.

Feel free to add to this (incomplete) list via a pull request! 

## Learn
Because networks can be confusing, and learning is fun. 

* [A tutorial](https://www.dynamic-connectome.org/t/tutorial/) in connectome analysis: topological and spatial features of brain networks
* [An	introduction](https://www.humanbrainmapping.org/files/2017/ED%20Courses/Course%20Materials/BrainGraphs_Fornito_Alex.pdf)	to	brain	networks
* [A Scholarpedia](http://www.scholarpedia.org/article/Brain_connectivity) entry on brain connectivity.
* [Building connectomes using diffusion MRI: why, how and but](https://ora.ox.ac.uk/objects/uuid:81f726ca-d1f1-48f3-b686-82f3d6a198ba)
* [The first chapter](http://scitechconnect.elsevier.com/wp-content/uploads/2017/02/An-Introduction-to-Brain-Network-Analysis.pdf) to the *wonderful* book: [Fundementals of Brain Network Analysis](https://www.amazon.com/Fundamentals-Brain-Network-Analysis-Fornito-ebook/dp/B01CRIU886).
* [Connected Brains: introduction to graph theory](https://home.kpn.nl/stam7883/graph_introduction.html)

## Downloads
### Non-human Animals
Typically micro-scale infomation, gene expression, informatically collated connectivity, & other stuff

* [Allen Mouse Brain Connectivity Atlas](https://connectivity.brain-map.org/static/brainexplorer) - Allen Institute contiunes to comprehensively map the mouse brain 
  * [Oh (2014)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5102064/) - Landmark paper has a bunch of supplementary data, including some matrices. 
  * [Knox (2019)](https://www.mitpressjournals.org/doi/10.1162/netn_a_00066) - Paper describes models incorporating more voxel information to obtain mouse connectivity; includes [github repo](https://github.com/AllenInstitute/mouse_connectivity_models)
* [BCT](https://sites.google.com/site/bctnet/datasets/) - Brain connectivity toolbox: a personal favorite, with a selection of:
  * [Felleman (1991)](https://www.ncbi.nlm.nih.gov/pubmed/1822724) - macaque visual cortex
  * [Young (1992)](https://www.nature.com/articles/358152a0) - macaque
  * [Scannell (1999)](https://academic.oup.com/cercor/article/9/3/277/428916) - cat cortex
* [C. elegans](http://wormwiring.org/) - A classic connectome. See [Cook (2019)](https://doi.org/10.1038/s41586-019-1352-7) for a re-analysis/processing of the [White (1986)](https://www.semanticscholar.org/paper/The-structure-of-the-nervous-system-of-the-nematode-White-Southgate/62d36f23580ae0c822ebc7de69ae603d85441bfc) data.
  * Also check out [Open Worm](http://openworm.org/downloads.html) for more worm connectome work.
  * [Arnatkevic̆iūtė (2018)](https://figshare.com/s/797199619fbabdab8c86) - Worm data in a nicely organized figshare repo, from paper [Arnatkevic̆iūtė (2018)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005989).
* [Ciona intestinalis](https://elifesciences.org/articles/16962#fig16) - A tadpole larva connectome, from paper [Ryan (2016)](https://elifesciences.org/articles/16962). 
* [Calabrese (2015)](http://www.civm.duhs.duke.edu/mouseconnectome/#download) - Mouse tractography data from the paper [Calabrese (2015)](https://academic.oup.com/cercor/article/25/11/4628/2367615).
* [Choi (2019)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006978) - Can download the 244 region Allen Mouse network through the resources in this paper.
* [Drosophila medulla full connectome](https://figshare.com/articles/Drosophila_medulla_full_connectome/1249735) - Data from [Takemura (2013)](https://www.nature.com/articles/nature12450) extracted and bundled up.
* [Grandjean (2017)](http://www.jneurosci.org/content/37/34/8092) - Paper contains some mouse func connectivity data. 
* [Mouse synaptome atlas](https://www.cell.com/neuron/fulltext/S0896-6273(18)30581-6) - Synaptome, a similarity matrix of the synaptome maps for each of >700 regions, more info [here](http://synaptome.genes2cognition.org/). 
* [Marmoset brain](http://analytics.marmosetbrain.org/) - weighted and directed, based on monosynaptic retrograde fluorescent tracers.
* [Neurodata.io](https://neurodata.io/project/connectomes/) - A bunch of goodies here, in graphml format:
  * Cat - from [de Reus (2013)](http://www.jneurosci.org/content/33/32/12929.full)
  * Fly - from [Takemura (2013)](https://www.nature.com/articles/nature12450)
  * Macaque - from [Harriger (2012)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0046497)
  * Mouse - from [Helmstaedter (2013)](https://www.nature.com/articles/nature12346)
  * Rat - from an old USC website
  * Worm - from [Jarrell (2012)](https://science.sciencemag.org/content/337/6093/437.full)
* [Platynereis dumerilii](https://elifesciences.org/articles/26000/figures#SD8-data) - The larva of the Platynereis dumerilii, from the paper [Verasztó (2017)](https://elifesciences.org/articles/26000).
* [Rat connectome](https://www.pnas.org/highwire/filestream/624512/field_highwire_adjunct_files/2/pnas.1712928114.sd03.xlsx) - Informatically collated data from Larry Swanson, used in a series of PNAS papers, like [Swanson 2017](https://www.pnas.org/content/114/45/E9692)
* [The Virtual Macaque Brain](https://zenodo.org/record/1471588#.XEDwPc9Kj9U) - Macaque data from the paper [Shen (2019)](https://www.sciencedirect.com/science/article/pii/S1053811919301041). See also [Shen (2019)](https://doi.org/10.1038/s41597-019-0129-z)
* [Transcriptional map of primate brain development](https://github.com/AllenBrainAtlas/DevRhesusLMD) - Can use this github repo to make some gene expression maps, from [Bakken (2016)](https://www.nature.com/articles/nature18637)
* [USC Mouse Connectome](http://www.mouseconnectome.org/MCP/page/tables/supplementary?paperId=17) - Cortico-cortical mouse networks from [Fig2](http://www.mouseconnectome.org/MCP/page/documents/figures?paperId=17) of the [Zingg (2014) Cell](https://www.cell.com/abstract/S0092-8674%2814%2900222-0) paper.
* [Wang (2019)](https://www.biorxiv.org/content/10.1101/701755v1) - Adjacecny matrices from multiple inbred strains of mice in this paper. 

### Human Animals 
Typically macro-scale information, neuroimages (MRI, EEG), whole brain coverage, & other stuff

* [35_methods_MICCAI_2017](https://github.com/lodurality/35_methods_MICCAI_2017) - Test-retest tractography networks, with 5 different methods, from paper [Petrov (2017)](https://link.springer.com/chapter/10.1007/978-3-319-66182-7_59). 
* [ACPI](http://fcon_1000.projects.nitrc.org/indi/ACPI/html/index.html) - Addiction connectome preprocessed initiative. 
* [AUDADAPT](https://osf.io/28r57/) - Func networks from people resting and listening, from [Alavash 2019](https://www.pnas.org/content/116/2/660).
* [BCT](https://sites.google.com/site/bctnet/datasets/) - Brain connectivity toolbox also has some human data:
  * [Crossley (2013)](https://www.pnas.org/content/110/28/11583) coactivation network & group func network
* [braingraph.org](http://braingraph.org/cms/download-pit-group-connectomes/) - Structural networks made from HCP images, described in [Kerepesi (2017)](https://link.springer.com/article/10.1007%2Fs11571-017-9445-1)
* [Cheng (2019)](https://datadryad.org/resource/doi:10.5061/dryad.736t01r) - Data of 831 HCP func networks shared from [this paper](https://elifesciences.org/articles/40765).
* [CNI Challenge 2019](http://www.brainconnectivity.net/challenge.html) - Miccai workshop challenge with [train](https://github.com/mdschirmer/2019_CNI_TrainingRelease) and [test](https://github.com/mdschirmer/2019_CNI_ValidationRelease) data (incl. timeseries) for predicting ADHD dx.
* [Cobre Connectomes](https://figshare.com/articles/Cobre_Connectomes_GZ/1328237) - Functional networks of healthy and schizophrenia subjects.
* [Complex Systems Lab](https://complexsystemsupenn.com/codedata) - Some data shared by Dani Bassett's group.
* [Dynamic Connectome Lab](https://www.dynamic-connectome.org/?page_id=25) - Some brain networks from Marcus Kaiser.
* [DSI Studio Downloads](http://dsi-studio.labsolver.org/download-images) - DSI studio team has an assortment of fun data.
* [Dutch Connectome Lab](http://www.dutchconnectomelab.nl/) - Some downloads here from Martijn van den Heuvel's group.
* [Faskowitz (2019)](https://figshare.com/articles/Faskowitz2018wsbmLifeSpan_data/6983018) - NKI structural connectivity data from paper [Faskowitz (2019)](https://www.nature.com/articles/s41598-018-31202-1). 
* [Gibbsconnectome](https://www.nitrc.org/projects/gibbsconnectome/) - Really dense voxelwise func and sturct data.
* [Hagmann Connectomes](https://zenodo.org/record/2872624#.XYEcfdVKiUl) - Structure+function matrices used in many papers including [Vázquez-Rodríguez (2019)](https://www.pnas.org/content/early/2019/09/27/1903403116). 
* [Hernan Makse lab](http://www-levich.engr.ccny.cuny.edu/webpage/hmakse/brain/) - Hosting some brain networks used in publications here.
* [Human Tractography Atlas](http://brain.labsolver.org/tractography/download) - DSI studio-based tractography data, from [Yeh (2018)](https://www.sciencedirect.com/science/article/pii/S1053811918304324).
* [ICBM_aging_connectome](https://figshare.com/articles/ICBM_aging_connectome/) - Some sort of data here... not much description.
* [Keerativittayayut (2018)](https://elifesciences.org/articles/32696#fig4) - Two func mats (224 ROIs) across memory encoding tasks, from paper [Keerativittayayut (2018)](https://elifesciences.org/articles/32696).
* [Mattar (2015)](https://datadryad.org/resource/doi:10.5061/dryad.94t53) - Task and rest func data from paper [Mattar (2015)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004533).
* [Neuro Beureau](https://www.nitrc.org/frs/?group_id=383) - Many preprocessed connectomes here, related to the [Preprocessed Connectomes Project](http://preprocessed-connectomes-project.org/datasets.html): 
  * Beijing Enhanced dwi networks
  * ADHD200 func networks with different preprocessing strategies
* [Paris & HCP brain connectivity data](https://figshare.com/articles/Paris_HCP_brain_connectivity_data/3749595) - Data used in [Marrelec G (2016)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005031).
* [Patania (2019)](https://github.com/alpatania/AHBA_microarray_Mapper) - Github repo to make microarray data from paper [Patania (2019)](https://www.mitpressjournals.org/doi/abs/10.1162/netn_a_00094).
* [PsychEncode](http://resource.psychencode.org/#Pipeline) - Download some gene expression matricies for the PFC here.
* [SLIM](http://fcon_1000.projects.nitrc.org/indi/retro/southwestuni_qiu_index.html) - Func networks from a test-retest sample from China.
* [The R-fMRI Network](http://rfmri.org/DownloadRfMRIMaps) - Lots of func networks from Chinese mega-consortium.
* [UMCD](http://umcd.humanconnectomeproject.org/) - USC Multimodal Connectivity Database, with brain networks constructed from a wide range of datasets
  * A list of the available datasets in the UMCD can be found [here](http://umcd.humanconnectomeproject.org/umcd/default/browse_studies). 
* [Váša (2020)](https://figshare.com/articles/Data_for_Conservative_and_disruptive_modes_of_adolescent_change_in_human_brain_functional_connectivity_/11551602) - Func developmental data from paper investigating modes of adolescent change, [Váša (2020)](https://www.pnas.org/content/early/2020/01/27/1906144117)
* [Vertes2016_PhilTransB_data.mat](https://figshare.com/articles/Vertes2016_PhilTransB_data_mat/3363433) - 38 brain networks in this big mat file, from [Vertes (2016)](https://royalsocietypublishing.org/doi/10.1098/rstb.2015.0362).
* [Yaesoubi (2017)](https://figshare.com/articles/Network_time-courses_for_multiple_subjects/4595308) - Timecourses from 405 subjects, 50 ica-derived nodes, from paper [Yaesoubi (2017)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0171647).

### Parcellations
Slicing up the brain into regions of interest

* [Brain Parcellation Survey](https://biomedia.doc.ic.ac.uk/brain-parcellation-survey/) - Brain parcellation data used in [Arslan (2017)](https://www.sciencedirect.com/science/article/pii/S1053811917303026).
* [Brainnetome](http://atlas.brainnetome.org/download.html) - Atlas baed on multimodal (fMRI, DWI) information, from paper [Fan (2016)](https://academic.oup.com/cercor/article/26/8/3508/2429104).
* [Craddock 2011](http://ccraddock.github.io/cluster_roi/atlases.html) - A parcellation made via spatially constrained spetrcal clustering. 
* [Gordon atlas](https://mail.nmr.mgh.harvard.edu/pipermail//freesurfer/2017-April/051470.html) - FreeSurfer version of the gordon atlas, attached at the bottom of this thread.
* [LEADS-DBS](https://www.lead-dbs.org/helpsupport/knowledge-base/atlasesresources/cortical-atlas-parcellations-mni-space/) - A page covering a wide-range of cortical parcellations.
* [maTT](https://github.com/faskowit/multiAtlasTT) - A Github repo with code to use FreeSurfer tools to fit various parcellations in the subject's T1w space.  
* [MIST](https://mniopenresearch.org/articles/1-3) - Multi-resolution parcellation of functional brain networks.
* [Schaefer2018](https://github.com/ThomasYeoLab/CBIG/tree/master/stable_projects/brain_parcellation/Schaefer2018_LocalGlobal) - Local global parcellations from paper [Schaefer (2018)](http://people.csail.mit.edu/ythomas/publications/2018LocalGlobal-CerebCor.pdf)
* [Shen atlas](https://www.nitrc.org/projects/bioimagesuite) - Resting state parcellation from paper [Shen (2013)](https://www.sciencedirect.com/science/article/pii/S1053811913005818).

## Visualization
Make your brains look nice

* [Keiriz (2018)](https://www.mitpressjournals.org/doi/10.1162/netn_a_00044) - Paper describing [NeuroCave](https://github.com/CreativeCodingLab/NeuroCave) and related visualization work.
* [LaPlante (2014)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0113838) - The Connectome Visualization Utility, which is implemented in Python; repo [here](https://github.com/aestrivex/cvu).
* [Margulies (2013)](https://www.sciencedirect.com/science/article/pii/S1053811913004709) - A paper on connectome viz, highlighting more examples and resources. 
* [NeuroMArVL](https://immersive.erc.monash.edu/neuromarvl/) - Makes network pictures on a brain surface, in a circle diagram, or as a spring-embedding (2D or 3D).
* [Nilearn](https://nilearn.github.io/auto_examples/index.html#visualization-of-brain-images) - Plenty of brain visualization inspiration to be had here.  
* [Xia (2013)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0068910) - BrainNet Viewer, which can also be found [on NITRC](https://www.nitrc.org/projects/bnv/).

## Other (fun stuff)

* [Network Repositroy](http://networkrepository.com/index.php) - Lot's of network downloads (including brain networks), but also more fun stuff too.
* [o3d](https://brainlife.io/home/o3d) - A place to make brain networks; additionally, a repository with some networks made from a standard set of subjects, from preprint [Avesani (2018)](https://psyarxiv.com/y82n7/).
* [The Virtual Brain](https://www.thevirtualbrain.org/tvb/zwei/home) - Brain dynamics simulators based on neural mass models and other fun equations.
