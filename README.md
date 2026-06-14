# 🌿 PlantVillage Dataset Setup

## ⚠️ Important Notice

The **PlantVillage dataset (~980 MB)** has been intentionally excluded from this repository and project submission package due to upload size limitations.

To successfully run the notebook, you must download and place the dataset manually by following the instructions below.

---

## 📥 Dataset Download

### Source Repository

Download the PlantVillage dataset from the following GitHub repository:

**Repository URL**

https://github.com/techannu/PlantVillage

---

## 🚀 Download Instructions

### Step 1: Open the Repository

Visit:

https://github.com/techannu/PlantVillage

### Step 2: Download the Dataset

Click the **Code** button and select **Download ZIP**.

Alternatively, clone the repository using Git:

```bash
git clone https://github.com/techannu/PlantVillage.git
```

### Step 3: Extract the Dataset

If you downloaded the ZIP file:

1. Extract the ZIP archive.
2. Locate the extracted folder named:

```text
PlantVillage/
```

### Step 4: Place Dataset in Project Directory

Move or copy the `PlantVillage` folder into the project root directory as shown below.

---

## 📂 Required Directory Structure

The dataset must be placed exactly as shown below:

```text
End-of-Program-Project-Solutions-Files-Plant-Disease-Detection/
│
├── Plant-Disease-Detection-Notebook.ipynb
├── README.md
│
└── PlantVillage/
    ├── Apple___Apple_scab/
    ├── Apple___Black_rot/
    ├── Corn_(maize)___Common_rust_/
    ├── Tomato___healthy/
    └── ... (39 disease classes)
```

---

## ✅ Expected Dataset Path

The notebook expects the dataset at:

```python
DATA_DIR = Path("PlantVillage")
```

Therefore, the following path must exist:

```text
./PlantVillage
```

relative to the notebook location.

---

## ❌ Common Mistakes

### Wrong Folder Structure

Do **NOT** place the dataset inside another directory such as:

```text
data/PlantVillage/
```

or

```text
dataset/PlantVillage/
```

or

```text
datasets/PlantVillage/
```

### Correct Folder Structure

```text
Project Root
│
├── Plant-Disease-Detection-Notebook.ipynb
└── PlantVillage/
```

---

## 🔍 Verification

Before running the notebook, verify that:

```text
PlantVillage/
```

exists in the project root and contains disease category folders such as:

```text
Apple___Apple_scab
Apple___Black_rot
Cherry___healthy
Corn_(maize)___Common_rust_
Tomato___healthy
```

If the dataset is not found at the expected location, the notebook will stop with an error similar to:

```python
AssertionError:
Dataset folder 'PlantVillage' not found
```

---

## 📊 Dataset Information

| Attribute    | Value                           |
| ------------ | ------------------------------- |
| Dataset Name | PlantVillage                    |
| Classes      | 39                              |
| Images       | ~54,000+                        |
| Size         | ~980 MB                         |
| Task         | Plant Disease Classification    |
| Domain       | Computer Vision / Deep Learning |

---

## 📝 Why the Dataset Is Not Included

The dataset has been excluded because:

* Large datasets significantly increase repository and submission size.
* The dataset is maintained separately for easier distribution and updates.
* Keeping the repository lightweight improves cloning and download performance.
* This follows standard machine learning project distribution practices.

---

## 📌 Dataset Repository

PlantVillage Dataset Repository:

https://github.com/techannu/PlantVillage

Please ensure the dataset is downloaded and placed in the correct directory structure before executing the notebook.
