<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1b2a,50:1b4965,100:5eead4&height=220&section=header&text=Nabil%20Yasini-Ardekani&fontSize=42&fontColor=5eead4&fontAlignY=35&desc=BSc%20Chemistry%20%C2%B7%20MSc%20Artificial%20Intelligence&descSize=16&descColor=94a3b8&descAlignY=55&animation=fadeIn"/>

<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3000&pause=1500&color=5EEAD4&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=60&lines=Aspiring+computational+chemist;Building+ML+tools+for+drug+discovery+%26+molecular+simulation" alt="Typing SVG" /></a>

<br/>

![Python](https://img.shields.io/badge/Python-0d1b2a?style=for-the-badge&logo=python&logoColor=5eead4)
![PyTorch](https://img.shields.io/badge/PyTorch-0d1b2a?style=for-the-badge&logo=pytorch&logoColor=5eead4)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1b2a?style=for-the-badge&logo=typescript&logoColor=5eead4)
![RDKit](https://img.shields.io/badge/RDKit-0d1b2a?style=for-the-badge&logoColor=5eead4)
![Next.js](https://img.shields.io/badge/Next.js-0d1b2a?style=for-the-badge&logo=nextdotjs&logoColor=5eead4)

</div>

<br/>

## What I work on

I develop graph neural networks and numerical simulation tools that encode real chemistry — stereochemistry, quantum descriptors, pharmacokinetics — into predictive models. My focus is bridging the gap between physical chemistry and modern ML, where most tools ignore 3D molecular structure entirely.

<br/>

## Drug discovery & ADMET

<table>
<tr>
<td width="50%" valign="top">

### <a href="https://github.com/abinittio/Insilico-Drug-Discovery-Toolkit"><img src="https://img.shields.io/badge/Insilico_Drug_Discovery_Toolkit-5eead4?style=flat-square" height="25"/></a>

Full ADMET prediction platform — monoamine transporter substrate vs blocker classification with stereochemistry-aware GNN.

`0.974 AUC` · GAT + GIN · Deployed on HuggingFace Spaces

</td>
<td width="50%" valign="top">

### <a href="https://github.com/abinittio/Abuse-Liability-Predictor"><img src="https://img.shields.io/badge/Abuse_Liability_Predictor-5eead4?style=flat-square" height="25"/></a>

Drug abuse risk classification combining MAT activity with SMARTS-based structural pattern recognition and SAR pharmacology rules.

Validated on `80` DEA-scheduled compounds · HIGH/MODERATE/LOW risk tiers

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <a href="https://github.com/abinittio/hERG-Cardiotoxicity-GNN"><img src="https://img.shields.io/badge/hERG_Cardiotoxicity_GNN-5eead4?style=flat-square" height="25"/></a>

Cardiac safety prediction via hERG channel inhibition modelling. Focal loss for class imbalance, K-fold ensembling with test-time augmentation.

Trained on `7,000+` ChEMBL compounds

</td>
<td width="50%" valign="top">

### <a href="https://github.com/abinittio/CYP450-Metabolism-Predictor"><img src="https://img.shields.io/badge/CYP450_Metabolism_Predictor-5eead4?style=flat-square" height="25"/></a>

Multi-task GNN for drug-drug interaction screening across 5 cytochrome P450 enzymes (1A2, 2C9, 2C19, 2D6, 3A4).

Shared representation · Task-specific heads

</td>
</tr>
</table>

<br/>

## Applied Materials Chemistry

<table>
<tr>
<td width="50%" valign="top">

### <a href="https://github.com/abinittio/4-MuLation"><img src="https://img.shields.io/badge/4--MuLation-5eead4?style=flat-square" height="25"/></a>

Modified-release dosage form design engine — BCS classification, Noyes-Whitney GI dissolution, multi-model release kinetics, and PDF report generation.

Higuchi · Korsmeyer-Peppas · Zero-order · Bimodal IR+ER · Streamlit UI

</td>
<td width="50%" valign="top">

### <a href="https://github.com/abinittio/SoilIntelligence"><img src="https://img.shields.io/badge/SoilIntelligence-5eead4?style=flat-square" height="25"/></a>

Precision agriculture system — soil analysis, Monte Carlo yield prediction, and fertiliser recommendations.

`244,000+` soil samples · Real-time market data · Uncertainty quantification

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <a href="https://github.com/abinittio/ComputationalDentMat"><img src="https://img.shields.io/badge/ComputationalDentMat-5eead4?style=flat-square" height="25"/></a>

Physics-based dental composite property predictor — rule of mixtures density engine with Bayesian Monte Carlo uncertainty quantification over shrinkage and void content.

Rule of mixtures · Noyes-Whitney · Monte Carlo · Streamlit UI

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

<br/>

## BBB permeability & quantum descriptors

<table>
<tr>
<td width="50%" valign="top">

### <a href="https://github.com/abinittio/StereoAwareGNN"><img src="https://img.shields.io/badge/StereoAwareGNN-5eead4?style=flat-square" height="25"/></a>

Blood-Brain Barrier permeability predictor — hybrid GAT → GCN → GraphSAGE with focal loss and stereo-aware encoding.

`0.9612 AUC` on 7,807-compound external validation · Outperforms ADMETlab 2.0

</td>
<td width="50%" valign="top">

### <a href="https://github.com/abinittio/BBB-Quantum-ADMET"><img src="https://img.shields.io/badge/BBB--Quantum--ADMET-5eead4?style=flat-square" height="25"/></a>

Quantum-enhanced GNN with 34-dimensional features from 3D conformers — HOMO/LUMO, Fukui indices, chemical hardness.

GATv2 + TransformerConv · Pretrained on `320k` ZINC molecules

</td>
</tr>
</table>

<br/>

## Simulation & PK/PD

<table>
<tr>
<td width="50%" valign="top">

### <a href="https://github.com/abinittio/DoseTrack"><img src="https://img.shields.io/badge/DoseTrack-5eead4?style=flat-square" height="25"/></a>

PK/PD simulation engine solving coupled ODEs for prodrug systems with saturable enzymatic conversion.

RK4 · Michaelis-Menten · Sigmoid Emax · Bayesian personalisation

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

<br/>

## Technical stack

```
Molecular ML        PyTorch · PyTorch Geometric · RDKit · DGL
Quantum descriptors HOMO/LUMO · Fukui indices · Gasteiger charges · ETKDG conformers
Numerical methods   RK4 · Michaelis-Menten · Hill equation · Sigmoid Emax
Languages           Python · TypeScript
Frameworks          Streamlit · Gradio · Next.js · React
Deployment          HuggingFace Spaces · Vercel
```

<br/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=abinittio&show_icons=true&hide_border=true&bg_color=0d1b2a&title_color=5eead4&text_color=94a3b8&icon_color=5eead4&ring_color=5eead4" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abinittio&layout=compact&hide_border=true&bg_color=0d1b2a&title_color=5eead4&text_color=94a3b8" height="165"/>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:5eead4,50:1b4965,100:0d1b2a&height=120&section=footer&text=ab%20initio%20%E2%80%94%20from%20first%20principles&fontSize=14&fontColor=5eead4&fontAlignY=65&animation=fadeIn"/>
