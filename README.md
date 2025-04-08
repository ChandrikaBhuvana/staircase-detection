# 🚀 StairDepth – A Novel Staircase Detection Approach

## 🧭 Overview

Detection of a staircase is an important task in the fields of both assistive technology and autonomous navigation, with the goal of significantly enhancing **safety and accessibility**—especially for individuals with visual impairments or mobility challenges.

---

## ⚠️ Challenges and Limitations of Classic Detection Methods

### ❌ Poor Performance in Challenging Conditions

Traditional methods struggle under difficult scenarios such as:

- Low lighting environments  
- Irregular or complex architectural layouts  
- Occluded or obstructed views  

### 📉 Limitations of Depth Sensor Integration

While physical depth sensors can improve accuracy, they introduce notable drawbacks:

- Increased system complexity  
- Higher hardware costs  
- Frequent and intensive maintenance  

---

## ✅ Our Contributions: Proposed Method Overview

> 🔍 **Introducing StairDepth** – a novel and efficient monocular-based depth estimation approach tailored for staircase detection.

- **Depth Estimation Without Sensors**  
  Our architecture estimates depth maps directly from RGB images—**no need for physical sensors**.

- **Robust Staircase Detection**  
  Accurately detects staircases by classifying:
  - **Stair lines** into **concave** or **convex**
  - **Surfaces** as **tread** or **riser**

  This enables **precise staircase localization**, even in complex environments.

---

## 📊 Performance Highlights

- **Stair Line Classification**  
  - Precision: **83.2%**  
  - Recall: **90.8%**  
  - IoU: **72.2%**  
  ➤ Outperforms existing methods in identifying stair edge geometry.

- **Stair Surface Classification**  
  - Pixel Accuracy: **97.1%**  
  - Mean Pixel Accuracy: **82.9%**  
  ➤ Demonstrates superior surface segmentation capability.

---

## 🧠 Literature Summary

Traditional staircase detection methods often struggle under conditions like poor lighting, irregular architecture, or occlusion. Though depth sensors have improved performance, they come at the cost of complexity, price, and maintenance.  
👉 Our solution bypasses these issues by leveraging **monocular RGB images** and a **pre-trained model** to generate accurate depth maps—**no hardware dependency**.

---

## 🏗️ Network Architecture of Our Proposed Methodology (StairDepth)

📌 *Insert architecture image here from the `images` folder*

![Architecture]([[images/architecture.jpg](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/Stairdepth_architecture_.png](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/Stairdepth_architecture_.png?raw=true)))

---

## 📈 Numerical Results

📌 *Insert numerical results image here from the `images` folder*

![Numerical Results](images/numerical_results.jpg)

---

## 🖼️ Visual Results

Below are comparative visualizations showcasing the effectiveness of our approach:

**Complication: Presence of obstructions**

| Original Image | StairNet V3 Method's Result | Our Method's Result |
|:--------------:|:------------------------:|:-------------------:|
| ![Input Image 1](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/input/clg_2.jpeg) | ![Previous Result 1](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/v3_results/clg_2.jpeg?raw=true) | ![Our Result 1](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/stairDepth_results/clg_2.jpeg?raw=true) |

**Complication: Presence of Shawdows**

| Original Image | StairNet V3 Method's Result | Our Method's Result |
|:--------------:|:------------------------:|:-------------------:|
| ![Input Image 2](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/input/clg_3.jpeg?raw=true) | ![Previous Result 2](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/v3_results/clg_3.jpeg?raw=true) | ![Our Result 2](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/stairDepth_results/clg_3.jpeg?raw=true) |

**Complication: Irregular Stairs**

| Original Image | StairNet V3 Method's Result | Our Method's Result |
|:--------------:|:------------------------:|:-------------------:|
| ![Input Image 3](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/input/clg_4.jpeg?raw=true) | ![Previous Result 3](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/v3_results/clg_4.jpeg?raw=true) | ![Our Result 3](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/stairDepth_results/clg_4.jpeg?raw=true) |

**On Display: Downstairs**

| Original Image | StairNet V3 Method's Result | Our Method's Result |
|:--------------:|:------------------------:|:-------------------:|
| ![Input Image 4](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/input/clg_6.jpeg?raw=true) | ![Previous Result 4](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/v3_results/clg_6.jpeg?raw=true) | ![Our Result 4](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/stairDepth_results/clg_6.jpeg?raw=true) |

**Complication: Presence of Obstacles or humans at distinct places I**

| Original Image | StairNet V3 Method's Result | Our Method's Result |
|:--------------:|:------------------------:|:-------------------:|
| ![Input Image 6](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/input/clg_13.jpeg?raw=true) | ![Previous Result 6](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/v3_results/clg_13.jpeg?raw=true) | ![Our Result 6](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/stairDepth_results/clg_13.jpeg?raw=true) |

**Complication: Presence of Obstacles or humans at distinct places II**

| Original Image | StairNet V3 Method's Result | Our Method's Result |
|:--------------:|:------------------------:|:-------------------:|
| ![Input Image 5](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/input/clg_18.jpeg?raw=true) | ![Previous Result 5](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/v3_results/clg_18.jpeg?raw=true) | ![Our Result 5](https://github.com/ChandrikaBhuvana/staircase-detection/blob/main/Images/stairDepth_results/clg_18.jpeg?raw=true) |

---

## 📚 Publication

For a detailed exposition of our methodology and results, please refer to our published paper:

**Title:** *StairDepth: A Novel Staircase Detection through Depth Maps Generated by Depth Anything V2*  
**Journal:** *International Journal of Information Technology*  
**DOI:** [10.1007/s41870-025-02438-8](https://doi.org/10.1007/s41870-025-02438-8)

---

## 📬 Contact

For further information or inquiries, please contact:

- **Avire Laxmi Chandra Shekar**: [avirelaxmichandrashekar@gmail.com](mailto:avirelaxmichandrashekar@gmail.com)  
- **Bhuvana Chandrika Mukkolla**: [mukkollabhuvanachandrika@gmail.com](mailto:mukkollabhuvanachandrika@gmail.com)  
- **Vakkalagadda Hemanth Naidu**: [hemanthvhn@gmail.com](mailto:hemanthvhn@gmail.com)  
- **Naresh Babu Muppalaneni**: [nareshmuppalaneni@gmail.com](mailto:nareshmuppalaneni@gmail.com)

---
