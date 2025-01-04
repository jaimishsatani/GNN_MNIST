# GNN for MNIST Digit Classification  

This repository implements a **Graph Neural Network (GNN)** to classify digits from the MNIST dataset. The project demonstrates the use of graph-based learning for image data, transforming pixel relationships into graph structures for effective classification.  

---

## Table of Contents  
- [Features](#features)  
- [Requirements](#requirements)  
- [Installation](#installation)  
- [Usage](#usage)   
- [Contributing](#contributing)  
- [License](#license)  

---

## Features  
- Utilizes PyTorch and Deep Graph Library (DGL) for model implementation.  
- Graph representation of MNIST images for enhanced learning.  
- Easy-to-use training and evaluation pipeline.  

---

## Requirements  
- Python 3.x  
- [PyTorch](https://pytorch.org/)  
- [DGL (Deep Graph Library)](https://www.dgl.ai/)  
- numpy  
- matplotlib  

Install dependencies using the provided `requirements.txt`.  

---

## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/jaimishsatani/GNN_MNIST.git  
   cd GNN_MNIST  
   ```  

2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

---

## Usage  

To train the model on the MNIST dataset, run the following command:  
```bash  
python gnn_mnist.py  
```  

### Workflow:  
1. The script loads the MNIST dataset.  
2. Converts each image into a graph representation.  
3. Trains a Graph Neural Network on the graph-structured data.  
4. Outputs training progress and performance metrics.  

---

## Contributing  

Contributions are welcome! If you find any bugs or have feature suggestions:  
1. Fork the repository.  
2. Create a feature branch (`git checkout -b feature-name`).  
3. Commit your changes (`git commit -m "Add feature"`).  
4. Push to the branch (`git push origin feature-name`).  
5. Open a Pull Request.  

---

## License  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

---

This version leaves placeholders for performance metrics, ensuring the file remains clear and professional until you have the actual values to update.
