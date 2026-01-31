# Vector Databases 101

This repository accompanies a short educational talk for the [UP Data Science Society](https://www.facebook.com/updatasciencesociety).

Slides can be found [here](https://docs.google.com/presentation/d/1ucp88yX1EVEFKIXVw6rO_jrdgOAtIhTfAYdIxR-uBzg/edit?usp=sharing).

It introduces **vector databases from first principles**—what they are, what they are not, and where they fit in modern data science and AI pipelines.

The focus is on **understanding similarity, retrieval, and limitations**, not hype or vendor tools.

---

## What You’ll Learn

- How data is encoded into vectors (embeddings)
- How similarity search works
- What FAISS does (and does not do)
- When vector databases help—and when they don’t
- How vector retrieval fits into RAG-style pipelines

---

## Quick Start (Recommended: Google Colab)

You can run everything **without local setup** using Google Colab.

Start here:
- **04_Semantic_Search_End_to_End.ipynb** ← main demo notebook

Open any notebook in Colab by replacing `github.com` with `colab.research.google.com/github` in the URL.

Example:
```

[https://colab.research.google.com/github/ogbinar/vector-databases-101/blob/main/04_Semantic_Search_End_to_End.ipynb](https://colab.research.google.com/github/ogbinar/vector-databases-101/blob/main/04_Semantic_Search_End_to_End.ipynb)

````

---

## Running Locally (Optional)

```bash
git clone https://github.com/ogbinar/vector-databases-101.git
cd vector-databases-101
pip install -r requirements.txt
jupyter lab
````

---

## Recommended Learning Order

1. `01_Embeddings_and_Encoding_Basics.ipynb`
2. `02_Similarity_Metrics_Intuition.ipynb`
3. `03_FAISS_Building_a_Vector_Index.ipynb`
4. `04_Semantic_Search_End_to_End.ipynb`
5. `05_Failure_Cases_and_Limitations.ipynb`

The remaining notebooks explore evaluation, metadata, and retrieval-augmented generation (RAG).

---

## Notes

* FAISS is used to **make similarity search explicit**
* LLM usage (via Ollama) is optional and intentionally minimal
* Examples are designed for learning, not production deployment

---

## License

Educational use. See repository for details.
