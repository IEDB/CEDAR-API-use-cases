# CEDAR API Use Cases & Resources

This repository provides practical use cases and resources for the [Cancer Epitope Database and Analysis Resource (CEDAR)](https://cedar.iedb.org) Query API. It includes Python Notebooks and Entity-Relationship Diagrams (ERDs) designed to help users programatically perform novel and complex queries.

This information is complementary to the official documentation:
* **Discussion & Articles:** [CEDAR API Documentation](https://discuss.iedb.org/t/application-programming-interface-api/220)
* **Interactive Endpoints:** [Swagger UI](https://cedar-api.iedb.org/docs/swagger/)

---

## Notebooks

The use cases are implemented as Jupyter Notebooks located in the `/python` directory. They reproduce search scenarios and queries from [Koşaloğlu-Yalçın, Z. et al. (2025)](https://doi.org/10.1007/978-1-0716-4566-6_3).

**Important:** Since CEDAR's database is actively updated with new data, query results vary over time and might not exactly match the outputs documented in the notebooks and book chapter.

### Available Use Cases

* **Notebook 1:** `CEDAR_API_I.ipynb` - Demonstrates how to retrieve all publication references for a specific antigen (e.g., Prostate-specific antigen).
* **Notebook 2:** `CEDAR_API_II.ipynb` - Shows how to investigate the experimental evidence for the immunogenicity of a specific neoepitope (e.g., "SYLDSGIHF").
* **Notebook 3:** `CEDAR_API_III.ipynb` - Provides a method to find viral antigens and epitopes associated with a specific cancer type (e.g., head and neck cancer).
* **Notebook 4:** `CEDAR_API_IV.ipynb` - Explains how to identify neoantigens that have been used in therapeutic cancer vaccines for human patients.

---

## Entity-Relationship Diagrams (ERDs)

To better understand the database structure, the `/diagrams` directory contains ERDs that visualize table keys and relationships. These diagrams are a valuable reference for constructing your own custom queries.

* `cedar_api_epitope_antigen_reference_keys_submodel.png` - EPITOPE / ANTIGEN / REFERENCE Keys Sub-Model
* `cedar_api_tcell_tcr_keys_submodel.png`- TCELL / TCR Keys Sub-Model
* `cedar_api_bcell_bcr_keys_submodel.png` - BCELL / BCR Keys Sub-Model
* `cedar_api_mhc_keys_submodel.png` - MHC Keys Sub-Model

---

## Contact

If you have any questions or feedback, please contact the CEDAR team at **cedar@lji.org**. 
