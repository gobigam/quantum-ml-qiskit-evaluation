Experimental Evaluation of Quantum Machine Learning Algorithms Using Qiskit

Author
M. Gobiga
Master of Computer Applications (MCA)
PSNA College of Engineering and Technology, Dindigul
Anna University, Chennai — June 2025

Research Publication

ResearchGate: [View Full Thesis](https://www.researchgate.net/publication/404806017_EXPERIMENTAL_EVALUATION_OF_QUANTUM_MACHINE_LEARNING_ALGORITHMS_USING_QISKIT)
DOI: [10.13140/RG.2.2.33969.13921](https://doi.org/10.13140/RG.2.2.33969.13921)


About This Project
This project performs an experimental evaluation of Quantum Machine Learning (QML) algorithms using Qiskit on IBM Quantum hardware and simulators. It evaluates and compares:

Quantum Support Vector Machines (QSVM) vs Classical SVM
Quantum Neural Networks (QNN) vs Classical Neural Networks

Evaluated across 7 different datasets using various quantum feature maps.

Key Results
Algorithm ComparisonAccuracy ImprovementQSVM vs Classical SVM+3 to 4%QNN vs QSVM+5%QNN vs Classical Neural Network+7%
Dataset Results
DatasetAccuracyDiabetes Dataset80%Thyroid Dataset75%

Project Structure
quantum-ml-qiskit-evaluation/
│
├── README.md
│
├── QSVM (Quantum Support Vector Machine)
│   ├── classical_implimentation.ipynb   # Classical SVM on all datasets
│   ├── quantum_implimentation.ipynb     # Quantum SVM on simulator & IBM hardware
│   ├── feature_map.qasm                 # Quantum feature map circuit
│   ├── Helloworld.ipynb                 # Qiskit basics and setup
│   └── rain_dataset/                    # Rain dataset used for SVM
│
├── Neural Network
│   ├── classical_nn.ipynb               # Classical Neural Network implementation
│   ├── quantum_nn.ipynb                 # Quantum Neural Network implementation
│   ├── vlds_dataset.xlsx                # VLDS dataset
│   └── diabetes_dataset/               # Diabetes dataset files

Tools & Technologies

Qiskit — IBM's Quantum Computing Framework
IBM Quantum Lab — Real Quantum Hardware execution
Jupyter Notebook — Code implementation
Python 3.x — Programming Language
VS Code — Development Environment
NumPy, Pandas, Scikit-learn — Classical ML libraries


How to Run
bash# Clone the repository
git clone https://github.com/gobigam/quantum-ml-qiskit-evaluation.git


# Install dependencies
pip install qiskit qiskit-machine-learning scikit-learn pandas numpy jupyter

# Open Jupyter Notebook
jupyter notebook

# Run QSVM → Open quantum_implimentation.ipynb
# Run QNN  → Open quantum_nn.ipynb

Datasets Used

Rain Dataset
Diabetes Dataset
VLDS Dataset
Iris Dataset
Wine Dataset
Breast Cancer Dataset
Moons Dataset


References
This project is an experimental improvement based on IEEE research on Quantum Machine Learning, with additional datasets (Diabetes, Thyroid) evaluated on both quantum simulators and real IBM Quantum hardware.
Contact
M. Gobiga
 
[ResearchGate](https://www.researchgate.net/publication/404806017)  
[LinkedIn](https://www.linkedin.com/in/gobiga-m)


 If you found this project helpful, please give it a star!
