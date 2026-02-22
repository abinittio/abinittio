<div align="center">

# Nabil Yasini-Ardekani

**Computational Chemist** · BSc Chemistry · MSc Artificial Intelligence

Building physics-informed machine learning for drug discovery and molecular simulation.

</div>

---

### What I work on

I develop graph neural networks and numerical simulation tools that encode real chemistry — stereochemistry, quantum descriptors, pharmacokinetics — into predictive models. My focus is bridging the gap between physical chemistry and modern ML, where most tools ignore 3D molecular structure entirely.

---

### Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### [Insilico Drug Discovery Toolkit](https://github.com/abinittio/Insilico-Drug-Discovery-Toolkit)
Comprehensive ADMET prediction platform with monoamine transporter classification, abuse liability scoring, hERG cardiotoxicity, and CYP450 metabolism prediction.
- **0.974 AUC** on transporter substrate/blocker classification
- Stereochemistry-aware GNN (GAT + GIN)
- Deployed on HuggingFace Spaces

</td>
<td width="50%" valign="top">

#### [BBB-Quantum-ADMET](https://github.com/abinittio/BBB-Quantum-ADMET)
Quantum-enhanced GNN for multi-task ADMET prediction using 34-dimensional molecular features derived from 3D conformers.
- HOMO/LUMO approximations, Fukui indices, chemical hardness
- GATv2 + TransformerConv with residual connections
- Pretrained on 320k ZINC molecules

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [StereoAwareGNN](https://github.com/abinittio/StereoAwareGNN)
Blood-Brain Barrier permeability predictor using a hybrid GAT → GCN → GraphSAGE architecture with focal loss and stereo-aware feature encoding.
- **0.9612 AUC** on 7,807-compound external validation
- Outperforms ADMETlab 2.0, AttentiveFP, and pkCSM
- Dual pathway: classification + continuous LogBB

</td>
<td width="50%" valign="top">

#### [DoseTrack](https://github.com/abinittio/DoseTrack)
Pharmacokinetic/pharmacodynamic simulation engine solving coupled ODEs for prodrug systems with saturable enzymatic conversion.
- RK4 integrator, Michaelis-Menten kinetics, Sigmoid Emax
- Dose-dependent peak timing from saturation
- Bayesian adaptive personalisation with IQR outlier rejection

</td>
</tr>
</table>

---

### Technical stack

```
Molecular ML        PyTorch · PyTorch Geometric · RDKit · DGL
Quantum descriptors HOMO/LUMO · Fukui indices · Gasteiger charges · ETKDG conformers
Numerical methods   RK4 · Michaelis-Menten · Hill equation · Sigmoid Emax
Languages           Python · TypeScript
Frameworks          Streamlit · Gradio · Next.js · React
Deployment          HuggingFace Spaces · Vercel
```

---

<div align="center">
<sub>ab initio — from first principles</sub>
</div>
