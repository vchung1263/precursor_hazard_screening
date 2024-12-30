# Data

- candidate.csv: the 70 candidate compositions that haven't been synthesized in the literature (prior to 2022). Information includes the bandgap from the Materials Project, calculate band gap based on ALIGNN, and synthesis status. The candidate is based on the result of a positive-unlabeled learning model (more deails in https://github.com/vchung1263/solid_state_synthesizability_public).
- element_ars.csv: the Abundance Risk Score (ARS) of each element. The scores were assigned based on the Abundance of elements in Earth's crust.
- element_hhi.csv: the Herfindahl-Hirschman Index (HHI) score of each element. The scores were assigned based on mcs_ref.csv.
- ghs_hazard.csv: the GHS hazard statements and their assigned score, assuming the most severe category for each hazard statement.
- mcs_reff.csv: the U.S. Geological survey mineral commodity summaries (MCS) production and reserve data of the elements beween 2022-2024.
- precursor_ghs.csv: the hazard statements of the 230 precursors. Information was collected from Sigma Alridh's satefy data sheets.