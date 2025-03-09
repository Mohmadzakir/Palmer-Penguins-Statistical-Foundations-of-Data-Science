# Statistical Analysis of Palmer Penguins 🐧

## 📌 Project Overview
This project explores **Palmer Penguins**, analyzing physical characteristics and their relationships across species, islands, and sexes. The dataset provides insight into body mass, bill dimensions, and flipper lengths of penguins observed on **Biscoe, Dream, and Torgersen** islands. The study also investigates **sex-based differences** and **island effects** on morphology.

## 📊 Dataset
The **Palmer Penguins** dataset consists of **200 samples** with **key physical attributes**:
- **Species**: Adelie, Chinstrap, Gentoo
- **Island**: Biscoe, Dream, Torgersen
- **Bill Length (mm)**
- **Bill Depth (mm)**
- **Flipper Length (mm)**
- **Body Mass (g)**
- **Sex**: Male, Female
- **Year**: 2007–2009

## 🏗 Methodology
### 1️⃣ Exploratory Data Analysis (EDA)
- **Summary Statistics**: Mean, Median, Standard Deviation
- **Visualization**: Boxplots, Density Plots, Scatter Plots
- **Correlation Analysis**: Identifying feature relationships

### 2️⃣ Distribution Fitting for Body Mass
- **Normal Distribution**
- **Log-Normal Distribution**
- **Gamma Distribution**
- **Akaike Information Criterion (AIC) Comparison** for best fit

### 3️⃣ Sex-Based Variable Analysis
- **Body Mass Differences**
- **Flipper Length Variation**
- **Bill Measurements** (Length & Depth)

### 4️⃣ Impact of Island Origin
- **ANOVA Tests**: Checking if physical traits vary significantly across islands
- **Boxplots**: Comparing physical characteristics by island

## 📈 Key Results
### 🔹 Distribution of Body Mass
| **Distribution** | **AIC Value** |
|-----------------|--------------|
| Normal          | 3243.132      |
| Log-normal      | **3232.673**  |
| Gamma          | 3823.526      |

The **Log-normal** distribution best fits penguin **body mass**, confirming its right-skewed nature.

### 🔹 Sex-Based Differences
| **Sex**  | **Mean Body Mass (g)** | **Mean Flipper Length (mm)** | **Mean Bill Length (mm)** | **Mean Bill Depth (mm)** |
|---------|-----------------|--------------------|----------------|----------------|
| Female  | **3928.96**  | **198.15**  | **42.69**  | **16.33**  |
| Male    | **4534.34**  | **204.81**  | **45.76**  | **17.88**  |

- **Male penguins** are significantly **larger** in all physical traits.
- **Body mass and flipper length** are the strongest indicators for distinguishing **male vs female**.

### 🔹 Island-Based Variation
| **Island**  | **Mean Body Mass (g)** | **Mean Flipper Length (mm)** | **Mean Bill Length (mm)** |
|------------|----------------|-----------------|----------------|
| Biscoe     | **4700**  | **210**  | **45**  |
| Dream      | **4200**  | **200**  | **43**  |
| Torgersen  | **3700**  | **190**  | **40**  |

- Penguins on **Biscoe** Island are **heaviest** and have **longest flippers**.
- **Torgersen** penguins are **lighter** with **shorter flippers** but have **deeper bills**.

## 📂 Project Structure
