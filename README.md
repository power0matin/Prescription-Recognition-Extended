# 💊 Prescription Recognition

Extract text from handwritten prescription images using Python and deep learning.
Designed for researchers, developers, and medical professionals to automate and improve prescription digitization with high accuracy.

## ✨ Features

- 🧠 Evaluate multiple OCR models (EasyOCR, PaddleOCR, TROCR, Tesseract) for handwritten Persian & English text.
- 🖼️ Image preprocessing to enhance OCR accuracy.
- 🧹 Text cleaning tailored to medical prescription language.
- 📊 Comprehensive evaluation metrics: precision, recall, edit distance, match rate.
- 📁 Batch processing of large datasets with ground truth labels.
- 📈 Phase-wise project development for systematic improvements.

## 🛠 Usage & Configuration

- **Input Images:** Put prescription images in `data/` folder or configure paths accordingly.
- **Labels:** Ground truth labels stored in `labels.xlsx`.
- **Modify OCR & Preprocessing:** Edit `utils.py` to customize OCR engines, preprocessing, or cleaning steps.

## 📂 Project Structure

| File/Directory      | Description                            |
| ------------------- | -------------------------------------- |
| `main.py`           | Run OCR on single images               |
| `batch_evaluate.py` | Evaluate OCR models on entire dataset  |
| `utils.py`          | Preprocessing, OCR wrappers, utilities |
| `labels.xlsx`       | Ground truth labels for evaluation     |
| `data/`             | Sample prescription images             |
| `README.md`         | Project documentation                  |
| `requirements.txt`  | Python dependencies                    |
| `report.md`         | Evaluation results and summary         |

## 📈 Project Phases & Roadmap

| Phase   | Description                                             | Status         |
| ------- | ------------------------------------------------------- | -------------- |
| Phase 1 | Compare OCR models on small dataset (5-10 images)       | ✅ Completed   |
| Phase 2 | Full dataset evaluation with detailed metrics           | 🔄 In Progress |
| Phase 3 | Final evaluation, model selection, and reporting        | 🔜 Planned     |
| Phase 4 | Modularize code and improve scalability                 | 🔜 Planned     |
| Phase 5 | Develop user-friendly GUI/web interface                 | 🔜 Planned     |
| Phase 6 | Add multi-language support beyond Persian and English   | 🔜 Planned     |
| Phase 7 | Deploy cloud API for real-time prescription recognition | 🔜 Planned     |

## 🔮 Future Enhancements

- Fine-tune OCR models specifically for Persian handwriting.
- Add data augmentation and semi-supervised labeling techniques.
- Integrate NLP-based semantic verification for prescription correctness.
- Create a web dashboard to visualize results and manage datasets.
- Enable API access for integration with hospital or pharmacy systems.

## 👩‍💻 Developers & Maintainers

Original project by [Nastaran Akbarian](https://github.com/NastaranAkbarian).
Currently maintained and extended by the open source community.

Contributions, issues, and feature requests are very welcome! Please submit pull requests or open issues on GitHub.

## 📜 License

This project is licensed under the **MIT License** — free for personal and commercial use with attribution.

## 📬 Contact

**Matin Shahabadi (متین شاه‌آبادی / متین شاه آبادی)**

* Website: [matinshahabadi.ir](https://matinshahabadi.ir)
* Email: [me@matinshahabadi.ir](mailto:me@matinshahabadi.ir)
* GitHub: [power0matin](https://github.com/power0matin)
* LinkedIn: [matin-shahabadi](https://www.linkedin.com/in/matin-shahabadi)

For questions or collaboration, please open an issue on GitHub or contact the maintainer via GitHub profile.

> ⭐ If you find this project useful, please give it a star and share with your peers!
> Thank you for supporting open-source AI-powered healthcare tools!
