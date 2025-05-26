# IoT-23-dataset-for-multiclass-classification
IoT-23 Dataset for Network Traffic Classification

**📌 Overview**

The IoT-23 dataset provides labeled IoT network traffic, enabling cybersecurity research and machine learning models for malware detection. It contains 23 scenarios—20 malicious and 3 benign—captured from various IoT devices.

**📂 Data Format**

The dataset includes:
- Timestamp – Time of packet capture
- Source/Destination IP – Network connection details
- Protocol Type – TCP, UDP, ICMP, etc.
- Traffic Label – Benign or malicious classification
- PCAP Files – Raw network traffic data
- 
**🔧 Installation**
  
Clone the repository:
git clone https://github.com/yourusername/IoT-23-dataset.git
cd IoT-23-dataset


**📊 Usage Example**

Load and analyze labeled traffic in Python:
import pandas as pd
data = pd.read_csv("IoT23_labeled_flows.csv")
print(data.head())


**🤝 Contributions**

We welcome dataset improvements, feature extraction methods, and anomaly detection models. Submit a pull request if you'd like to contribute!

**📜 License**

This dataset is licensed under the MIT License, allowing open-source usage, modifications, and distributions. See the LICENSE file for details

