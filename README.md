# **Unveiling the Culprit: An Interdisciplinary Approach Combining Graph Theory and NLP for Suspense Narrative Analysis**

## Overview  
This repository dives into **Agatha Christie's *The Murder of Roger Ackroyd***, using **graph theory** and **NLP** to predict the potential murderer. Through techniques like **Named Entity Recognition (NER)**, **community detection**, and **sentiment analysis**, the project builds a character interaction graph and analyzes it to narrow down suspects.  

---

## Features  
1. **Named Entity Recognition (NER)**: Extracts characters and their interactions.  
2. **Graph Construction**: Nodes represent characters, and edges represent their interactions.  
3. **Sentiment Analysis**: Determines emotional tones in character interactions.  
4. **Clustering**: Groups characters based on interaction patterns using **K-Means**.  
5. **Murderer Prediction**: Ranks characters using features like degree centrality, sentiment, and proximity to the victim.  

---

## Data  
- **Source**: [Project Gutenberg](https://www.gutenberg.org/cache/epub/69087/pg69087.txt)  
- **Novel**: *The Murder of Roger Ackroyd*  
- **Format**: `.txt`  

---

## Steps  
1. **Character Extraction**: Using NER to identify key characters and normalize names (e.g., "Poirot" → "Hercule Poirot").  
2. **Interaction Mapping**: Builds pairs of co-occurring characters in sentences.  
3. **Graph Refinement**:  
   - **Degree Centrality**: Filters nodes by importance.  
   - **Community Detection**: Identifies tightly connected groups.  
4. **Feature Engineering**: Adds attributes like sentiment, suspicious keywords, and proximity to the victim.  
5. **Clustering and Ranking**: Applies **K-Means** clustering to group suspects and ranks them by suspicion.  

---

## Results  
The analysis identified **James Sheppard**, the actual murderer in the novel, within the cluster of top suspects.  

---

## Future Work  
- **Enhance NLP**: Improve sentiment and interaction analysis for nuanced relationships.  
- **Leverage GNNs**: Use Graph Neural Networks to predict suspects more effectively.  

---

**Team Rasgulla Warriors**  
Harsha V | Namita A | Shusrith S | Siddhi Z  

Find the **[repo here](https://github.com/rasgulla-warriors/GitAwayWithMurder)**!
