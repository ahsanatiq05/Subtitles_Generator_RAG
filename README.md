# Subtitles Generator RAG

Subtitles Generator RAG is a project for automatic subtitle generation using Retrieval-Augmented Generation (RAG) techniques. It utilizes Jupyter notebooks for demonstration and experimentation, making it easy to understand and adapt the workflow for your own use.

## Features

- **Automatic subtitle generation**: Generate subtitles from audio or video using state-of-the-art NLP.
- **Retrieval-Augmented Generation**: Improves subtitle accuracy by retrieving relevant context, especially for technical or complex topics.
- **Notebook-based workflow**: Explore and modify the pipeline easily using Jupyter notebooks.
- **Extensible**: Adapt the pipeline for different languages, domains, or subtitle formats.

## How To Use

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ahsanatiq05/Subtitles_Generator_RAG.git
    cd Subtitles_Generator_RAG
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Open the provided `.ipynb` files in your browser.

4. **Follow the notebook instructions:**
   - Step through the cells in order.
   - Configure paths to your audio/video files as instructed in the notebook.
   - Modify parameters or pipeline settings as needed.

## Project Structure

- `*.ipynb` — Main Jupyter notebooks for subtitle generation and experimentation.
- `requirements.txt` — Python package dependencies.
- `rag_pipeline/` — Core modules for retrieval-augmented generation (if present).
- `examples/` — Sample files and outputs.

## Contributing

Contributions are welcome! Open issues or submit pull requests to improve notebooks, add features, or suggest enhancements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Hugging Face Transformers
- OpenAI Whisper
- PyTorch & TensorFlow

---

For questions or support, please contact [Ahsan Atiq](https://github.com/ahsanatiq05).
