
# KnowledgeGraph

## Overview
This project is a paper-based implementation that demonstrates how knowledge can be represented in AI systems. It allows users to represent data in a structured knowledge base using a CSV file, where data is stored in the form of triplets: **Subject → Predicate → Object**. Rules for reasoning are defined in the `grammar.py` file, enabling intelligent queries and reasoning over the data via a user interface. This small-scale AI system provides an idea of how larger AI systems function, particularly in terms of knowledge representation, reasoning, and query processing.

## Features
1. **Knowledge Representation**:  
   Data is stored in a CSV file (`Book1.csv`) in triplet form, which forms the backbone of the knowledge graph.
   
2. **Reasoning with Rules**:  
   Rules are implemented in the `grammar.py` file, allowing the system to perform reasoning based on predefined logic.

3. **Interactive Querying**:  
   The system provides a simple interface for querying knowledge and visualizing results.

4. **Visualization**:  
   The generated graphs visually represent relationships and reasoning, making it easier to understand connections between entities.

---

## Screenshots and Examples

### Example Knowledge Graph
Below is an example showing how "Qaiser" is represented in the system as a student with various attributes:

![Qaiser Knowledge Graph](https://raw.githubusercontent.com/Qaiserfarooq285/KnowledgeGraph/refs/heads/main/KRR/ScreenShots/Screenshot%202024-12-14%20163113.png)

---

### Different Types of Queries
The system supports reasoning and querying over graphs in three different ways. The image below highlights these query types:

![Query Examples](https://raw.githubusercontent.com/Qaiserfarooq285/KnowledgeGraph/refs/heads/main/KRR/ScreenShots/Screenshot%202024-12-14%20152752.png)

---

### System Workflow
The following diagram showcases the overall implementation, from knowledge graph creation to querying and reasoning:

![System Workflow](https://raw.githubusercontent.com/Qaiserfarooq285/KnowledgeGraph/refs/heads/main/KRR/ScreenShots/1_Y-TMvn7pQM4vxQOVbxrACg.png)

---

## Usage
To run the project:
1. Clone the repository.
2. Ensure all dependencies are installed (`Flask`, `pygtrie`, etc.).
3. Load the knowledge base from `Book1.csv`.
4. Define or modify rules in `grammar.py` to customize reasoning.
5. Run the Flask server and start querying knowledge using the interface.

This project is an excellent starting point for understanding how knowledge representation and reasoning can be implemented in AI systems.

feel free to contact : qaiserfarooq285@gmail.com
