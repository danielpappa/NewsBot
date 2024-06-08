# NewsBot
Project for the Bachelor Thesis in [Economics, Management and Computer Science](https://www.unibocconi.it/en/programs/bachelor-science/economics-management-and-computer-science) at Università Bocconi, Milan.

This repo deploys a reference-integrated RAG (RIRAG) model adapted to the news domain. The dataset accessed by the retriever was created by myself accessing news articles from The Guardian and The New York Times through the publisher's respective APIs on their developer portals.
The following pictures show a potential conversation with the model:

<img center alt="rag_answer" src="https://github.com/danielpappa/NewsBot/assets/142378123/d3f33d4b-53aa-4dc3-9557-f786d9cfc4f6">

When the user query cannot be answered based on the provided articles in the intenal database, the model will admit this lack of information in order to minimize the risk of hallucination and providing factually incorrect responses:

<img center alt="rag_answer_nr" src="https://github.com/danielpappa/NewsBot/assets/142378123/804c8418-fb95-42ec-8e96-826c21d0ed80">
