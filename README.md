Welcome to ToxPrint
==================================================================

[​ToxPrint](http://toxprint.org) is a publicly-available invariant reference set of structural features targeted to cover chemical structures from the large toxicity databases and regulatory inventories (Yang, 2015). ToxPrint chemotypes were developed by Altamira LLC (now part of [​MN-AM](https://www.mn-am.com/)) for US FDA CFSAN’s CERES (Chemical Evaluation and Risk Estimation System) project. Chemotypes including the ToxPrint are implemented in the ChemoTyper, which was contracted from US FDA to Molecular Networks GmbH (now part of [​MN-AM](https://www.mn-am.com/))

Chemotypes
--------------------------------------------------

This site houses the various chemotype files to support knowledge representation. Chemotypes are structural fragments that can encode physicochemical, atomic, and electronic properties in addition to substructural connectivity. They can be associated with biological properties and modes of action in the toxicity pathways or with AOP (adverse outcome) pathways through these encoded properties in addition to the structural motif. Chemotypes use the new CSRML (chemical substructure and reaction mark-up) language to represent both atom-bond connectivity as well as their properties such as pi-system or partial charges.

ToxPrint Chemotypes [¶](#ToxPrintChemotypes "Link to this section")
-------------------------------------------------------------------

The ChemoTyper organizes the current version ToxPrint chemotypes into three functional areas:

1.  Generic Structural Fragments
2.  Structural Rules and Alerts
3.  Category Classifiers

### Generic Structural Fragments [¶](#GenericStructuralFragments "Link to this section")

Generic structural fragments are organized by atom, bond, chain, ring types as well as chemical groups including amino acids, carbohydrates, ligands, and nucleobases based on 729 essential chemotypes of the current ToxPrint\_v2.0\_r1520.xml (whatever the file name). These chemotypes can be generated as chemical fingerprints, either in binary (0/1) or counts data. They can be used to calculate similarity measures or structural feature descriptors for building models. (Yang 2015)

### Structural Rules and Alerts [¶](#StructuralRulesandAlerts "Link to this section")

These can be developed using ToxPrint chemotypes as building blocks. The chemotypes defined in the ToxPrint set can be further refined or coded with properties (atom, bond, molecular, or physicochemical) to constrain the matches in order to enhance the signal-to-noise ratio of ToxPrint chemotypes when profiling the biological observations. To this end, we are developing ChemoType Editor to empower the users with the ability to fluently manipulate the CSRML query definitions graphically in a molecular editor. Please contact MN-AM if you are interested.

*   Ashby-Tennant Genotoxic Carcinogen Alerts
*   DNA binders
*   Protein binders
*   General Liver Alerts

### Category Classifiers [¶](#CategoryClassifiers "Link to this section")

When characterizing different databases, TTC datasets, or inventories to differentiate their chemical spaces, an invariant reference set of structural features are required. In addition, when developing categories for regulatory inventories (cosmetics, drugs, agrochemicals, etc.) or representing particular toxicity or biological patterns within AOP/MOA pathways or ontology networks, designed chemotypes specifically to capture the underlying knowledge can be a powerful set of tools. To this end, we are developing ChemoType Editor to empower the users with the ability to fluently manipulate the CSRML query definitions graphically in a molecular editor. Please contact MN-AM if you are interested.

*   TTC approach
*   [​Organic Flame Retardant Chemotypes](http://www8.nationalacademies.org/onpinews/newsitem.aspx?RecordID=25412)
*   Antimicrobial Chemotypes (Yang 2020)

ToxPrint is implemented in [​CSRML language](https://chemotyper.org/wiki/WikiStart#TheCSRMLReferenceImplementation) and can be applied using the publicly available [​ChemoTyper application](http://chemotyper.org).

ToxPrint chemotypes can be downloaded free-of-charge for public use.

The Chemotype Editor [¶](#TheChemotypeEditor "Link to this section")
--------------------------------------------------------------------

The Chemotype Editor is a graphical user interface (GUI) application for creating and editing chemotypes. Substructures and patterns can be drawn using a molecular editor or imported from an external file. Atoms, bonds, molecular annotations, and properties can be added with the GUI. Edited chemotypes can be saved in the XML-based Chemical Subgraphs and Reactions Mark-up Language (CSRML) and used as alerts or fingerprints.

### Download the Chemotype Editor [¶](#DownloadtheChemotypeEditor "Link to this section")

The Chemotype Editor is available for download at the [​ChemoTyper](http://chemotyper.org) website.

Publications about ToxPrint chemotypes, CSRML language, and ChemTyper application [¶](#PublicationsaboutToxPrintchemotypesCSRMLlanguageandChemTyperapplication "Link to this section")
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

*   [​Paul Friedman, K., Gagne, M., Loo, L.-H., Karamertzanis, P., Netzeva, T., Sobanski, T., Franzosa, J., Richard, A.M., Lougee, R., Gissi, A., Joey Lee, J.-Y., Angrish, M., Dorne, J.-L., Foster, S., Raffaele, K., Bahadori, T., Gwinn, M., Lambert, J., Whelan, M., Rasenberg, M., Barton-Maclaren, T., Thomas, R.S. Utility of In Vitro Bioactivity as a Lower Bound Estimate of In Vivo Adverse Effect Levels and in Risk-Based Prioritization. Toxicol. Sci. 2020, 173:202-225.](https://doi.org/10.1093/toxsci/kfz201)

*   [​Kosnik, M.B., Strickland, J.D., Marvel, S.W., Wallis, D., Wallace, K., Richard, A.M., Reif, D.M., Shafer, T.J. Concentration-Response Evaluation of ToxCast Compounds for Multivariate Activity Patterns of Neural Network Function Archives of Toxicology. Function. Arch. Toxicol. 2019, https://doi.org/10.1007/s00204-019-02636-x.](https://doi.org/10.1007/s00204-019-02636-x)

*   [​Wang, J., Hallinger, D. R., Murr, A. S., Buckalew, A. R., Lougee, R. R., Richard, A. M., ... & Stoker, T. E. (2019). High-throughput screening and chemotype-enrichment analysis of ToxCast phase II chemicals evaluated for human sodium-iodide symporter (NIS) inhibition. Environment International, 126, 377-386.](https://www.sciencedirect.com/science/article/pii/S0160412018321196)

*   [​Nelms, M. D., Lougee, R., Roberts, D. W., Richard, A., & Patlewicz, G. (2019). Comparing and contrasting the coverage of publicly available structural alerts for protein binding. Computational Toxicology, 12, 100100.](https://www.sciencedirect.com/science/article/pii/S2468111319300283)

*   [​Nyffeler, J., Willis, C., Lougee, R., Richard, A., Paul-Friedman, K., & Harrill, J. A. (2020). Bioactivity screening of environmental chemicals using imaging-based high-throughput phenotypic profiling. Toxicology and Applied Pharmacology, 114876.](https://www.sciencedirect.com/science/article/pii/S0041008X19304843)

*   [​Yang C, Tarkhov A, Marusczyk J, et al. "New Publicly Available Chemical Query Language, CSRML, To Support Chemotype Representations for Application to Data Mining and Modeling." J. Chem. Inf. Model.. 2015;55(3):510-528.](http://pubs.acs.org/doi/abs/10.1021/ci500667v)

Updates [¶](#Updates "Link to this section")
--------------------------------------------

*   2014-06-11. The updated release 711 fixes the label assigned to the rule TXP-001-0270-0010-0050-0050 - there was an extra space character in the label, title, and comment. The updated ToxPrint file is available for download.

*   2014-01-27. The updated release 219 fixes the issue with the incorrect structure representation in the rule TXP-004-0020-0200-0150-0150. The updated ToxPrint file is available for download.

**Please note!** The updated file does not replace automatically the ToxPrint in your [​ChemoTyper installation](http://chemotyper.org). In order to use it with your ChemoTyper, please follow these [instructions](/wiki/LatestToxPrintUsageInstructions).

Download [¶](#Download "Link to this section")
----------------------------------------------

The ToxPrint chemotypes (XML file) are available for download for registered users.

Please [login](/login) if you have already an account or [register](/register).

Contact [¶](#Contact "Link to this section")
--------------------------------------------

In technical support issues please contact us through: [​info@toxprint.org](mailto:info@toxprint.org)

Acknowledgement [¶](#Acknowledgement "Link to this section")
============================================================

Visit the [​website](https://www.mn-am.com) of Molecular Networks GmbH and Altamira LLC.

The ChemoTyper application was developed by MN-AM (Molecular Networks GmbH, Nurnberg, Germany and Altamira LLC, Columbus, OH, USA) under a contract from the U.S. FDA, Center for Food Safety and Applied Nutrition (CFSAN), Office of Food Additive Safety. The CSRML-based ToxPrint chemotypes were developed by MN-AM while Chihae Yang was working at US FDA CFSAN, hence both ChemoTyper and ToxPrint Chemotypes are donated for public use.

Chemotype Editor was further developed by MN-AM with partial funds from Cosmetics Europe (ontology project) and IMI eTRANSAFE project. We also recognize the special consultations on using the JSME editor developed by Peter Ertl (Novartis) and Bruno Bienfait (MN-AM).
