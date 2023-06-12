# Transformer-based Large Language Models in Chemistry
  
  
>*The history of philosophy is the history of forgetting. Problems and ideas once examined fall out of sight and out of mind only to resurface later as novel and new. - R. Jacoby*
  
## Encoder-Decoder Models (T5, BART, Molecular Transformer, BLM, etc.)
- Multitask Text and Chemistry T5: Unifying Molecular and Textual Representations via Multi-task Language Modelling. [[PAPER]](https://arxiv.org/abs/2301.12586) [[REPO]](https://github.com/GT4SD/multitask_text_and_chemistry_t5)
- MolT5: Translation between Molecules and Natural Language. [[PAPER]](https://blender.cs.illinois.edu/paper/molt5.pdf) [[REPO]](https://github.com/blender-nlp/MolT5)
- Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction. [[PAPER]](https://arxiv.org/abs/1811.02633) [[REPO]](https://github.com/pschwllr/MolecularTransformer)
  - Unassisted Noise-Reduction of Chemical Reactions Data Sets. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/60c75487842e65e86ddb4161)
  - Automated Extraction of Chemical Synthesis Actions from Experimental Procedures. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/60c749fbee301c10e1c79b75)
  - Predicting retrosynthetic pathways using a combined linguistic model and hyper-graph exploration strategy. [[PAPER]](https://arxiv.org/abs/1910.08036)
  - Reagent Prediction with a Molecular Transformer Improves Reaction Data Quality. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/636ea2dcfbfd385fefda8e13) [[REPO]](https://github.com/Academich/reagents)
  - Leveraging Infrared Spectroscopy for Automated Structure Elucidation. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/645df5cbf2112b41e96da616)
- Uni-Mol: A Universal 3D Molecular Representation Learning Framework. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/6402990d37e01856dc1d1581) [[REPO]](https://github.com/dptech-corp/Uni-Mol)
- T5 Chem: Unified Deep Learning Model for Multitask Reaction Predictions with Explanation. [[PAPER]](https://pubmed.ncbi.nlm.nih.gov/35266390/) [[REPO]](https://yzhang.hpc.nyu.edu/T5Chem)
- MolGen: Domain-Agnostic Molecular Generation with Self-feedback. [[PAPER]](https://arxiv.org/pdf/2301.11259.pdf) [[REPO]](https://github.com/zjunlp/MolGen)
- TransformMolecules: Can We Quickly Learn to “Translate” Bioactive Molecules with Transformer Models? [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/639c9de1e9d0fd49a41f6d30) [[REPO]](https://github.com/pfizer-opensource/transform-molecules)
- A Pre-trained Conditional Transformer for Target-specific De Novo Molecular Generation. [[PAPER]](https://arxiv.org/abs/2210.08749)
- Transformer-CNN: Swiss knife for QSAR modeling and interpretation. [[PAPER]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00423-w#Sec2) [[REPO]](https://github.com/bigchem/transformer-cnn)
- SMILES Transformer: Pre-trained Molecular Fingerprint for Low Data Drug Discovery. [[PAPER]](https://arxiv.org/abs/1911.04738) [[REPO]](https://github.com/DSPsleeporg/smiles-transformer)
- Chemformer: a pre-trained transformer for computational chemistry. [[PAPER]](https://iopscience.iop.org/article/10.1088/2632-2153/ac3ffb) [[REPO]](https://github.com/MolecularAI/Chemformer)
- FragNet: Contrastive Learning-Based Transformer Model for Clustering, Interpreting, Visualizing, and Navigating Chemical Space. [[PAPER]](https://www.mdpi.com/1420-3049/26/7/2065)
- PanGu Drug Model: Learn a Molecule Like a Human. [[PAPER]](https://www.biorxiv.org/content/10.1101/2022.03.31.485886v1.full)
- State-of-the-art augmented NLP transformer models for direct and single-step retrosynthesis. [[PAPER]](https://www.nature.com/articles/s41467-020-19266-y#Sec27) [[REPO]](https://github.com/bigchem/synthesis)
- Struct2IUPAC: Transformer-based artificial neural networks for the conversion between chemical notations. [[PAPER]](https://www.nature.com/articles/s41598-021-94082-y) [[REPO]](https://github.com/sergsb/IUPAC2Struct)
- Transformer-based Approach for Predicting Chemical Compound Structures. [[PAPER]](https://aclanthology.org/2020.aacl-main.19/)
- Crystal Transformer: Self-learning neural language model for Generative and Tinkering Design of Materials. [[PAPER]](https://arxiv.org/abs/2204.11953)
  - Material Transformer Generator: Discovery of 2D materials using Transformer Network based Generative Design. [[PAPER]](https://arxiv.org/abs/2301.05824)
- MolBART. [[REPO]](https://github.com/MolecularAI/MolBART) [[MODEL]](https://catalog.ngc.nvidia.com/orgs/nvidia/teams/clara/models/megamolbart)

## Encoder Only Models (BERT, XLNet, etc.)
- Regression Transformer enables concurrent sequence regression and generation for molecular language modelling. [[PAPER]](https://arxiv.org/abs/2202.01338) [[REPO]](https://github.com/IBM/regression-transformer)
- MOFormer: Self-Supervised Transformer model for Metal-Organic Framework Property Prediction. [[PAPER]](https://arxiv.org/abs/2210.14188) [[REPO]](https://github.com/zcao0420/MOFormer)
- RXNFP: Mapping the Space of Chemical Reactions using Attention-Based Neural Networks. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/60c753a0bdbb89acf8a3a4b5) [[REPO]](https://github.com/rxn4chemistry/rxnfp)
- KV-PLM: A deep-learning system bridging molecule structure and biomedical text with comprehension comparable to human professionals. [[PAPER]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8844428/) [[REPO]](https://github.com/thunlp/KV-PLM)
- ChemBERTa: Large-Scale Self-Supervised Pretraining for Molecular Property Prediction. [[PAPER]](https://arxiv.org/abs/2010.09885) [[REPO]](https://github.com/seyonechithrananda/bert-loves-chemistry)
  - ChemBERTa-2: Towards Chemical Foundation Models. [[PAPER]](https://arxiv.org/abs/2209.01712)
- MolBERT: Molecular representation learning with language models and domain-relevant auxiliary tasks. [[PAPER]](https://arxiv.org/abs/2011.13230) [[REPO]](https://github.com/BenevolentAI/MolBERT)
- Mole-BERT: Rethinking Pre-training Graph Neural Networks for Molecules. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/64361823a41dec1a56e75135) [[REPO]](https://github.com/junxia97/Mole-BERT)
- MoLFormer: Large-Scale Chemical Language Representations Capture Molecular Structure and Properties. [[PAPER]](https://arxiv.org/abs/2106.09553) [[REPO]](https://github.com/IBM/molformer)
- TransPolymer: a Transformer-based language model for polymer property predictions. [[PAPER]](https://www.nature.com/articles/s41524-023-01016-5#Sec9) [[REPO]](https://github.com/ChangwenXu98/TransPolymer)
- DeLiCaTe: Chemical transformer compression for accelerating both training and inference of molecular modeling. [[PAPER]](https://arxiv.org/ftp/arxiv/papers/2205/2205.07582.pdf) [[REPO]](https://github.com/YiYuDL/DeLiCaTe)
- MatSciBERT: A materials domain language model for text mining and information extraction. [[PAPER]](https://www.nature.com/articles/s41524-022-00784-w) [[REPO]](https://github.com/M3RG-IITD/MatSciBERT)
- SolvBERT for solvation free energy and solubility prediction: a demonstration of an NLP model for predicting the properties of molecular complexes. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/633d6bbfea6a225b1809e24e) [[REPO]](https://github.com/su-group/SolvBERT)
- Transformer Quantum State: A Multi-Purpose Model for Quantum Many-Body Problems. [[PAPER]](https://arxiv.org/abs/2208.01758) [[REPO]](https://github.com/yuanhangzhang98/transformer_quantum_state)
- Taiga: Molecule generation using transformers and policy gradient reinforcement learning. [[PAPER]](https://pubmed.ncbi.nlm.nih.gov/37258546/) [[REPO]](https://github.com/eyalmazuz/MolGen)
- SMILES-BERT: Large Scale Unsupervised Pre-Training for Molecular Property Prediction. [[PAPER]](https://par.nsf.gov/servlets/purl/10168888) [[REPO]](https://github.com/uta-smile/SMILES-BERT)
- MM-Deacon: Multilingual Molecular Representation Learning via Contrastive Pre-training. [[PAPER]](https://arxiv.org/abs/2109.08830)
- MEMO: A Multiview Contrastive Learning Approach to Molecular Pretraining. [[PAPER]](https://openreview.net/pdf?id=Pm1Q1X3avx1)
- Molecule Attention Transformer. [[PAPER]](https://arxiv.org/abs/2002.08264) [[REPO]](https://github.com/gmum/MAT)
  - SolTranNet: A machine learning tool for fast aqueous solubility prediction. [[PAPER]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8900744/) [[REPO]](https://github.com/gnina/SolTranNet)
- MaterialBERT for natural language processing of materials science texts. [[PAPER]](https://www.tandfonline.com/doi/abs/10.1080/27660400.2022.2124831)
- Adaptive Language Model Training for Molecular Design. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/64362fa70784a63aeef63ac1)
  
## Decoder Only Models (GPT, etc.)
- MolGPT: Molecular Generation Using a Transformer-Decoder Model. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/60c7588e469df48597f456ae) [[REPO]](https://github.com/devalab/molgpt)
- ChemGPT: Neural Scaling of Deep Chemical Models. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/627bddd544bdd532395fb4b5) [[REPO]](https://github.com/ncfrey/litmatter)
- OptoGPT: A Foundation Model for Inverse Design in Optical Multilayer Thin Film Structures. [[PAPER]](https://arxiv.org/abs/2304.10294)
- SGPT-RL: Optimization of binding affinities in chemical space with generative pretrained transformer and deep reinforcement learning. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/64272436a029a26b4cb49451)
- MolXPT: Wrapping Molecules with Text for Generative Pre-training. [[PAPER]](https://arxiv.org/abs/2305.10688)
- Material transformers: deep learning language models for generative materials design. [[PAPER]](https://iopscience.iop.org/article/10.1088/2632-2153/acadcd/meta) [[REPO]](https://github.com/usccolumbia/MTransformer)
- XYZTransformer: Language models can generate molecules, materials, and protein binding sites directly in three dimensions as XYZ, CIF, and PDB files. [[PAPER]](https://arxiv.org/abs/2305.05708)
- Galactica: A Large Language Model for Science. [[PAPER]](https://arxiv.org/abs/2211.09085) [[REPO]](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
- cMolGPT: A Conditional Generative Pre-Trained Transformer for Target-Specific De Novo Molecular Generation. [[PAPER]](https://www.mdpi.com/1420-3049/28/11/4430) [[REPO]](https://github.com/VV123/cMolGPT)
- PrefixMol: Target- and Chemistry-aware Molecule Design via Prefix Embedding. [[PAPER]](https://arxiv.org/abs/2302.07120)
- LigGPT: Molecular Generation using a Transformer-Decoder Model. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/60c7588e469df48597f456ae) [[REPO]](https://github.com/VirajBagal/LigGPT)
- X-MOL: large-scale pre-training for molecular understanding and diverse molecular analysis. [[PAPER]](https://www.biorxiv.org/content/10.1101/2020.12.23.424259v2)

## Other architectures
- GROVER: Self-Supervised Graph Transformer on Large-Scale Molecular Data. [[PAPER]](https://papers.nips.cc/paper_files/paper/2020/file/94aef38441efa3380a3bed3faf1f9d5d-Paper.pdf)
- DMP: Dual-view Molecule Pre-training. [[PAPER]](https://arxiv.org/abs/2106.10234) [[REPO]](https://github.com/dual-view-molecule-pretraining/dmp)
- MICER: a pre-trained encoder–decoder architecture for molecular image captioning. [[PAPER]](https://academic.oup.com/bioinformatics/article/38/19/4562/6656348) [[MODEL]](https://github.com/Jiacai-Yi/MICER)
- Fragment-based t-SMILES for de novo molecular generation. [[PAPER]](https://arxiv.org/abs/2301.01829) [[REPO]](https://github.com/juanniwu/t-SMILES/)
- DrugGen: Target Specific De Novo Design of Drug Candidate Molecules with Graph Transformer-based Generative Adversarial Networks. [[PAPER]](https://arxiv.org/abs/2302.07868) [[REPO]](https://github.com/HUBioDataLab/DrugGEN)
- Graphormer: Do Transformers Really Perform Badly for Graph Representation? [[PAPER]](https://openreview.net/forum?id=OeWooOxFwDa) [[REPO]](https://github.com/microsoft/Graphormer)
- KPGT: Knowledge-Guided Pre-training of Graph Transformer for Molecular Property Prediction. [[PAPER]](https://arxiv.org/abs/2206.03364) [[REPO]](https://github.com/lihan97/KPGT)
- GIMLET: A Unified Graph-Text Model for Instruction-Based Molecule Zero-Shot Learning. [[PAPER]](https://www.biorxiv.org/content/10.1101/2023.05.30.542904v2) [[REPO]](https://github.com/zhao-ht/GIMLET)
- rIOP: Testing the Limits of SMILES-based De Novo Molecular Generation with Curriculum and Deep Reinforcement Learning. [[PAPER]](https://doi.org/10.1101/2022.07.15.500218) [[REPO]](https://github.com/m-mokaya/riop)
- Discovery of structure-property relations for molecules via hypothesis-driven active learning over the chemical space. [[PAPER]](https://arxiv.org/abs/2301.02665) [[REPO]](https://github.com/aghosh92/SISSO_sGP)
- REINVENT 2.0 – an AI Tool for De Novo Drug Design. [[PAPER]](https://www.biorxiv.org/content/biorxiv/early/2023/05/31/2023.02.17.529000.full.pdf) [[REPO]](https://github.com/MolecularAI/Reinvent)
  - A Simple Way to Incorporate Target Structural Information in Molecular Generative Models. [[PAPER]](https://www.biorxiv.org/content/biorxiv/early/2023/05/31/2023.02.17.529000.full.pdf) [[REPO]](https://github.com/JingHuangLab/SWIT)
- Improving Chemical Autoencoder Latent Space and Molecular De novo Generation Diversity with Heteroencoders. [[PAPER]](https://arxiv.org/abs/1806.09300)
- CDDD: Learning continuous and data-driven molecular descriptors by translating equivalent chemical representations. [[PAPER]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6368215/) [[REPO]](http://https://github.com/jrwnter/cddd)
- Unsupervised Representation Learning for Proteochemometric Modeling. [[PAPER]](https://www.mdpi.com/1422-0067/22/23/12882)
- UnCorrupt SMILES: a novel approach to de novo design. [[PAPER]](https://link.springer.com/article/10.1186/s13321-023-00696-x) [[REPO]](https://github.com/LindeSchoenmaker/SMILES-corrector)
- Leveraging molecular structure and bioactivity with chemical language models for de novo drug design. [[PAPER]](https://www.nature.com/articles/s41467-022-35692-6#Sec11) [[REPO]](https://zenodo.org/record/7370858)
- STOUT: SMILES to IUPAC names using neural machine translation. [[PAPER]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00512-4#Sec123) [[MODEL]](https://github.com/Kohulan/Smiles-TO-iUpac-Translator)
  
## General works of Interest
- A Systematic Survey of Chemical Pre-trained Models. [[PAPER]](https://sxkdz.github.io/files/publications/IJCAI/CPM/CPM.pdf)
- Machine intelligence for chemical reaction space. [[PAPER]](https://wires.onlinelibrary.wiley.com/doi/full/10.1002/wcms.1604)
- Exploring Chemical Space using Natural Language Processing Methodologies for Drug Discovery. [[PAPER]](https://arxiv.org/abs/2002.06053)
- Comparative Study of Deep Generative Models on Chemical Space Coverage. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/60c755389abda285f4f8e2d1)
- Explainability Techniques for Chemical Language Models. [[PAPER]](https://arxiv.org/abs/2305.16192)
- Unified 2D and 3D Pre-Training of Molecular Representations. [[PAPER]](https://arxiv.org/abs/2207.08806)
- Exploring chemical space — Generative models and their evaluation. [[PAPER]](https://www.sciencedirect.com/science/article/pii/S2667318523000089)
- Difficulty in learning chirality for Transformer fed with SMILES. [[PAPER]](https://arxiv.org/abs/2303.11593) [[REPO]](https://github.com/mizuno-group/2023)
- Molecular language models: RNNs or transformer? [[PAPER]](https://academic.oup.com/bfg/advance-article-abstract/doi/10.1093/bfgp/elad012/7109964?redirectedFrom=fulltext)
- Artificial intelligence in multi-objective drug design. [[PAPER]](https://scholarlypublications.universiteitleiden.nl/access/item%3A3590044/view)
- Evaluating the roughness of structure-property relationships using pretrained molecular representations. [[PAPER]](https://arxiv.org/abs/2305.08238)
- Reconstruction of lossless molecular representations from fingerprints. [[PAPER]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-023-00693-0)
- Neural Scaling of Deep Chemical Models. [[PAPER]](https://chemrxiv.org/engage/chemrxiv/article-details/627bddd544bdd532395fb4b5)
- The Druglike molecule pretraining strategy for drug discovery. [[PAPER]](https://www.researchsquare.com/article/rs-2492051/v1)
- Accelerating the design and development of polymeric materials via deep learning: Current status and future challenges. [[PAPER]](https://doi.org/10.1063/5.0131067)
- Materials Transformers Language Models for Generative Materials Design: a benchmark study. [[PAPER]](https://arxiv.org/abs/2206.13578)
- A [note](https://archive.md/OvucI) on transformer architectures.
- Social Amnesia (History did not start in 2017) [[BOOK]](https://cominsitu.files.wordpress.com/2021/08/russell-jacoby-social-amnesia-a-critique-of-contemporary-psychology-from-adler-to-laing.pdf)
- Malta – Sweet Magic (1984) [[ALBUM]](https://www.youtube.com/watch?v=vcRTQ_Jj7vw)
