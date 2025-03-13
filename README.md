\documentclass{article}
\usepackage{hyperref}
\usepackage{listings}

\title{Knowledge Graph for Mapping Foods to Nutrients and Essential Amino Acids}
\author{}
\date{}

\begin{document}

\maketitle

\section{Project Overview}
This project constructs a \textbf{Knowledge Graph (KG) to map foods to their nutrient compositions}, particularly focusing on \textbf{essential amino acids}. The KG is built using structured data obtained from \textbf{MyFoodData} and integrates existing ontologies to ensure interoperability and semantic accuracy. The project involves \textbf{data extraction, ontology creation, and query analysis}.

\section{Repository Structure}
The repository consists of three main Jupyter notebooks:

\subsection{webscraping.ipynb}
\begin{itemize}
    \item Contains the code for extracting food-nutrient data from MyFoodData.
    \item The last cell executes the scraping process.
    \item The extracted data serves as the foundation for constructing the Knowledge Graph.
\end{itemize}

\subsection{knowledgeGraph.ipynb}
\begin{itemize}
    \item Defines the ontology and maps the extracted data to relevant concepts.
    \item Links newly created properties to \textbf{existing ontologies} (e.g., FoodOn, nutritional standards).
    \item Incorporates food source data into the Knowledge Graph.
\end{itemize}

\subsection{Analysis.ipynb}
\begin{itemize}
    \item Utilizes \textbf{SPARQL} queries to extract meaningful insights from the KG.
    \item Performs \textbf{nutrient-based analysis} and \textbf{food classification}.
    \item Demonstrates how the KG can be queried for real-world use cases.
\end{itemize}

\section{Technologies Used}
\begin{itemize}
    \item \textbf{Python} (Jupyter Notebooks)
    \item \textbf{BeautifulSoup / Selenium} (for Web Scraping)
    \item \textbf{OWL / RDF / SPARQL} (for Knowledge Graph construction and querying)
    \item \textbf{Protégé} (for ontology design)
    \item \textbf{FoodOn Ontology} (for linking food-related data)
\end{itemize}

\section{How to Use}
\begin{enumerate}
    \item Run \texttt{webscraping.ipynb} to collect data.
    \item Use \texttt{knowledgeGraph.ipynb} to construct and enrich the ontology.
    \item Execute \texttt{Analysis.ipynb} to run SPARQL queries and analyze results.
\end{enumerate}

\section{Future Improvements}
\begin{itemize}
    \item Expanding the dataset to include \textbf{more food categories}.
    \item Enhancing semantic linking with additional \textbf{ontologies (e.g., USDA, Wikidata)}.
    \item Improving query performance for large-scale data exploration.
\end{itemize}

For any questions or contributions, feel free to reach out!

\end{document}

