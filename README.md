# ColPali
A Vanilla RAG with ColPali using VLM

✅ Project Structure (for .ipynb-only setup)
bash
Copy
Edit
colpali-visual-rag/
├── Visual_RAG_Colpali.ipynb    
└── README.md        



📄 README.md for Notebook

# 🧠 ColPali Visual RAG - PDF QA with ColPali

This notebook allows users to upload a PDF and ask natural language questions, powered by the `vidore/colpali-v1.2` multimodal RAG model.

## 💡 What It Does

- Uploads a PDF file
- Uses `byaldi`’s `RAGMultiModalModel` to index and search
- Displays the most relevant page as an image using base64
- Lightweight interface, easily extendable to Gradio/Streamlit

## 🛠️ How to Use

1. Clone the repository or open the notebook in Colab
2. Install the dependencies:

Run the notebook cells step-by-step:

Set Hugging Face token

Load the model

Index your PDF

Ask questions and view visual answers

🔐 Note
Set your Hugging Face token inside the notebook:

os.environ["HF_TOKEN"] = "your_hf_token_here"

📦 Requirements
byaldi
Pillow

🤖 Model Used
vidore/colpali-v1.2
