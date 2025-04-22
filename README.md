
# 🧠 Synthetic Dataset Generator with DeepSeek, Qwen, and LLaMA

Generate high-quality synthetic datasets using powerful language models like DeepSeek, Qwen, and LLaMA. This notebook allows you to create customizable, large-scale datasets in CSV format using just a prompt — perfect for data science, machine learning, and AI research projects.

---



## 🚀 Features

- 📦 Generate structured datasets in CSV format  
- 🤖 Supports multiple cutting-edge LLMs: DeepSeek, Qwen, LLaMA  
- 🧠 Simple natural language prompt input  
- ⚙️ Easily configure number of rows and data structure  
- 🪄 Useful for training/testing ML models, data augmentation, and more  

---

## 📁 File Structure

```
synthetic_dataset_generator_deepseek_qwen_llama.ipynb   # Main notebook
README.md                                               # You're here!
```

---

## 🧪 How to Use

### 1. Clone the repository
```bash
git clone https://github.com/your-username/synthetic-dataset-generator.git
cd synthetic-dataset-generator
```

### 2. Install dependencies
```bash
pip install -U bitsandbytes
# Include any additional dependencies as needed
```

### 3. Run the notebook
```bash
jupyter notebook synthetic_dataset_generator_deepseek_qwen_llama.ipynb
```

### 4. Customize and generate your dataset
Modify the prompt, choose your model, and set the desired number of samples.

Example usage:
```python
res = generate_dataset(
    'The Business: A retail store selling Nike and Adidas shoes.',
    'CSV',
    'DeepSeek',
    100
)
```

---

## 📦 Output

The dataset will be generated in CSV format based on the business description or prompt you provide. Here's a simplified preview:

| Name             | Brand   | Category | Price  |
|------------------|---------|----------|--------|
| Air Max 90       | Nike    | Sneakers | $120   |
| Ultraboost 21    | Adidas  | Running  | $180   |
| Air Jordan 1 Low | Nike    | Casual   | $110   |

---

## 🛠 Dependencies

- Python 3.8+  
- [`bitsandbytes`](https://github.com/TimDettmers/bitsandbytes)  
- Jupyter Notebook  
- HuggingFace Transformers or any LLM wrapper depending on models used  

---

## 📄 License

This project is licensed under the **MIT License**. Feel free to use, modify, and share it.

---

## 🤝 Contributing

Contributions are welcome!  
If you'd like to improve this project, feel free to:

- ⭐ Star the repo  
- 🛠️ Submit a pull request  
- 🐛 Open an issue  

---



