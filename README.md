# Tableau Drug Microbiota Dashboard

An interactive Tableau dashboard built to analyze how drugs interact with gut microbiota and how these interactions influence bioavailability, stability, metabolism, and drug effectiveness.

This project transforms a pharmacology and microbiota interaction dataset into a visual analytics dashboard that helps users explore drug-bacteria relationships, compare drug classes, detect stability patterns, and understand the biological factors that affect drug behavior.

---

## Project Summary

**Built an interactive pharmacology analytics dashboard** by designing a Tableau-based visual system for drug microbiota interaction analysis.

**Enabled users to explore relationships between drugs, bacteria, enzymes, bioavailability, and stability** through multiple linked visualizations.

**Did this by** structuring the dashboard around key analytical objectives, selecting appropriate chart types for each question, and combining them into a logical and readable Tableau layout. :contentReference[oaicite:1]{index=1}

---

## Objective

**Improved interpretability of drug microbiota interaction data** by presenting it through a focused dashboard experience.

**Created a visual analysis workflow** to examine how bacterial species, enzyme activity, metabolism pathways, and drug properties influence degradation, stability, and altered efficacy.

**Did this by** using Tableau to build comparative, distribution-based, and relationship-driven views that support both category-level and numeric analysis. :contentReference[oaicite:2]{index=2}

---

## Dataset Overview

The dataset describes how different drugs interact with gut bacteria and how these interactions may affect metabolism, effectiveness, stability, and overall drug behavior in the body.

### Domain
- pharmacology
- drug microbiota interactions
- precision medicine

### Example variables
- Drug_Name
- Drug_Class
- Bacteria_Species
- Enzyme
- Metabolism_Pathway
- Solubility_Ph
- Bioavailability
- Half_Life_hrs
- Plasma_protein_binding
- Excretion
- Depletion_Probability
- Altered_Efficacy
- Stability_Score

The dataset supports analysis of how microbiota can activate, absorb, deactivate, degrade, or otherwise influence drugs biologically. :contentReference[oaicite:3]{index=3}

---

## Project Goals

**Identified meaningful patterns in drug microbiota interactions** to support better understanding of drug behavior.

**Analyzed variation across drug classes, bacterial species, enzymes, and pharmacological properties** to uncover stability and efficacy trends.

**Did this by** focusing on key analytical goals, including:
- identifying common drug-bacteria interaction patterns
- comparing drug classes on bioavailability and stability
- analyzing correlations between drug properties and microbiota indicators
- identifying enzymes and bacteria strongly associated with degradation or altered efficacy
- highlighting vulnerable drug-bacteria combinations
- evaluating the role of metabolism and excretion pathways. :contentReference[oaicite:4]{index=4}

---

## Dashboard Components

### 1. Bioavailability vs Drug Class
**Compared bioavailability across major drug classes** to understand how absorption patterns vary by category.

**Built a stacked bar chart** to show how different drug classes contribute to total bioavailability across drugs.

**Did this by** encoding drug classes using color and representing bioavailability through bar height, allowing quick visual comparison of composition patterns. The report notes that antibiotics and antidiabetic drugs contribute strongly to bioavailability across many drugs. :contentReference[oaicite:5]{index=5}

### 2. Drugs vs Microbiota Interactions
**Revealed which drugs and bacteria interact most frequently** through grouped categorical comparison.

**Built a grouped bar chart** to compare interaction counts between bacterial species and individual drugs.

**Did this by** grouping bars by bacterial species and differentiating drugs through color, making it easier to detect microbiota-sensitive drugs and bacteria that interact with many drugs. :contentReference[oaicite:6]{index=6}

### 3. Bioavailability vs Half-Life Hours
**Exposed relationships between absorption and persistence in the body** using a quantitative comparison view.

**Built a scatter plot** to analyze how bioavailability and half-life move together across drugs.

**Did this by** plotting each drug as a point, using color to represent clusters and size to encode stability score. The report highlights that high-performing drugs tend to have both higher bioavailability and longer half-life. :contentReference[oaicite:7]{index=7}

### 4. Drug Class vs Stability of Enzymes
**Highlighted enzyme stability patterns across drug classes** to understand which enzyme interactions appear strongest.

**Built a treemap** to compare enzyme-drug class combinations using both area and color intensity.

**Did this by** using rectangle size and luminance to encode stability-related patterns, allowing quick identification of higher-stability enzyme interactions such as Beta-glucuronidase and Sulfurtransferase. :contentReference[oaicite:8]{index=8}

---

## Dashboard Design

**Created a dashboard with a logical analytical flow** so users can move naturally from broad interactions to deeper biochemical patterns.

**Arranged the visuals to support progressive exploration** from drug-bacteria interactions to class-level bioavailability, quantitative drug behavior, and enzyme stability.

**Did this by** placing the charts in a balanced Tableau layout designed for readability, comparison, and multi-angle interpretation. The report states that the dashboard was intentionally structured to guide the viewer through the full picture of drug microbiota interactions. :contentReference[oaicite:9]{index=9}

---

## Key Outcomes

**Delivered a complete visual analytics solution for drug microbiota analysis** through a multi-chart Tableau dashboard.

**Enabled users to explore trends, compare categories, detect correlations, and identify outliers** across drug stability and microbiota interaction variables.

**Did this by** combining categorical comparisons, scatter-based relationship analysis, and enzyme stability mapping into a single interactive dashboard. :contentReference[oaicite:10]{index=10}

---

## Business and Analytical Value

**Improved insight generation in a pharmacology context** by turning raw microbiota interaction data into a structured dashboard.

**Made complex biological relationships easier to analyze** for users studying drug absorption, degradation, and stability.

**Did this by** using visual analytics to connect drugs, bacteria, enzymes, and pharmacokinetic properties in a way that supports informed analysis and decision-making. :contentReference[oaicite:11]{index=11}

---

## Tech Stack

- Tableau
- Excel
- PDF reporting
- Data visualization
- Dashboard design

---

## Repository Structure

```text
Tableau_Drug_Microbiota_Dashboard/
│
├── Group 6.twb
├── drug_microbiota.xlsx
├── Tableau finalee.pdf
├── Tableau images/
└── README.md
