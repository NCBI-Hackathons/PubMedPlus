# Improving Usability of Pubmed

### Goal

### Concept Map

### Phase I - PubMed Query using Mesh Ontology terms

1. Download PubMed Dump from [https://www.nlm.nih.gov/databases/download/pubmed_medline.html]
2. Convert the data to JSON format
3. Store the data in MongoDB [https://www.mongodb.com/]
3. Download MeSH Ontology [https://www.nlm.nih.gov/mesh/filelist.html]
4. MeSH terms are queried from the search Query provided by the User
..*These MeSH terms are then used to find all the related articles from the PubMed
