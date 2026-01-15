# Municipal Development Decision Support System

This repository contains the research code for a decision support system (DSS) aimed at analyzing and supporting socio-economic development of municipal entities in the Russian Federation.

The system combines:
- socio-economic and demographic indicators,
- migration statistics,
- large-scale news data,
- machine learning and NLP methods,

to produce interpretable recommendations for municipal development.

---

## Project Structure

The repository is organized as a sequence of Jupyter notebooks reflecting the full research pipeline:

1. **ClusterAnalysis**  
   Clustering of municipalities based on socio-economic and demographic indicators.  
   Identification of typologically similar municipal groups.

2. **NewsCollector**  
   News collection pipeline (parser for `bezformata.com`) with regional attribution.

3. **InitialTopicModeling**  
   Exploratory topic modeling experiments (LDA), preprocessing, and parameter analysis.

4. **SemanticFiltering**  
   Semantic filtering of news headlines using sentence embeddings to retain policy-relevant content.

5. **TopicModeling**  
   Topic modeling with BERTopic, topic interpretation and aggregation.

6. **SentimentAnalysis**  
   Sentiment and zero-shot classification of news headlines into policy-relevant categories.

7. **Recommendations**  
   Core decision support logic:
   - identification of underperforming municipalities,
   - comparison with successful neighbors,
   - generation of quantitative recommendations,
   - integration of news-based contextual explanations.

8. **Metrics**  
   Evaluation of clustering quality, topic coherence and diversity,  
   correlations between topics and migration indicators,  
   assessment of news classification quality.

---

## Data

The project uses:
- aggregated municipal-level socio-economic indicators,
- migration statistics,
- regional and municipal news headlines.

Due to data licensing and size constraints, raw datasets are not included in the repository.

---

## Research Context

This repository accompanies a course research project focused on:
- modeling values and needs of municipalities,
- integrating structured and unstructured data,
- building interpretable decision support systems for territorial development.

---

## Citation
Citation information will be provided after publication.

