# Knowledge Graph for Mapping Foods to Nutrients and Essential Amino Acids

## Project Overview
This project constructs a **Knowledge Graph (KG) to map foods to their nutrient compositions**, particularly focusing on **essential amino acids**. The KG is built using structured data obtained from **MyFoodData** and integrates existing ontologies to ensure interoperability and semantic accuracy. The project involves **data extraction, ontology creation, and query analysis**.

## Repository Structure
The repository consists of three main Jupyter notebooks:

1. **`webscraping.ipynb`**
   - This notebook contains the code for extracting food-nutrient data from MyFoodData.
   - The last cell executes the scraping process.
   - The extracted data serves as the foundation for constructing the Knowledge Graph.

2. **`knowledgeGraph.ipynb`**
   - Defines the ontology and maps the extracted data to relevant concepts.
   - Links newly created properties to **existing ontologies** (e.g., FoodOn, nutritional standards).
   - Incorporates food source data into the Knowledge Graph.

3. **`Analysis.ipynb`**
   - Utilizes **SPARQL** queries to extract meaningful insights from the KG.
   - Performs **nutrient-based analysis** and **food classification**.
   - Demonstrates how the KG can be queried for real-world use cases.

## Technologies Used
- **Python** (Jupyter Notebooks)
- **BeautifulSoup / Selenium** (for Web Scraping)
- **OWL / RDF / SPARQL** (for Knowledge Graph construction and querying)
- **Protégé** (for ontology design)
- **FoodOn Ontology** (for linking food-related data)

## How to Use
1. Run `webscraping.ipynb` to collect data.
2. Use `knowledgeGraph.ipynb` to construct and enrich the ontology.
3. Execute `Analysis.ipynb` to run SPARQL queries and analyze results.

## Future Improvements
- Expanding the dataset to include **more food categories**.
- Enhancing semantic linking with additional **ontologies (e.g., USDA, Wikidata)**.
- Improving query performance for large-scale data exploration.

For any questions or contributions, feel free to reach out!

