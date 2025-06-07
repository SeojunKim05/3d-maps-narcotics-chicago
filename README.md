# 📍 Chicago Narcotics Arrests – 3D Mapping with Excel

This project visualizes **narcotics-related arrests in Chicago** using **interactive 3D Maps** in Excel. Built from publicly available data, it highlights patterns in drug activity across the city by substance type, arrest location, and demographics.

## 📁 Repository Contents

- `Chicago_Narcotics-2.xlsx`  
  Raw source data from the [City of Chicago Open Data Portal](https://cityofchicago.org).

- `Narcotics_3D_Maps.xlsx`  
  Main Excel file containing:
  - Pivot tables for filtering
  - Four interactive 3D Maps
  - Detailed data visualizations

- `Map_Chicago_Narcotics.mp4`  
  Video tour of the full Chicago narcotics map.

- `Map_Cocaine.png`  
  Static preview of Cocaine Arrests 3D Map.

- `Map_Delivery_Under_18.png`  
  Static preview of Drug Delivery by Minors 3D Map.

- `Map_Methamphetamines.png`  
  Static preview of Methamphetamine Arrests 3D Map.

---

## 🔍 About the Data

Sourced from the City of Chicago, the dataset includes real narcotics arrest records. Each entry contains:

- `Case Number`
- `Date`
- `IUCR` (Illinois Uniform Crime Reporting Code)
- `Location Description`
- `Beat`
- `Ward`
- `Latitude`
- `Longitude`

---

## 🌍 How to Open the Interactive 3D Maps

1. Open `Narcotics_3D_Maps.xlsx` in Excel.
2. On the top toolbar, click the **Search** box.
3. Type **"3D Map"**, then select **3D Map** from the dropdown.
4. Explore the interactive maps directly within Excel.

> ℹ️ These maps (and graphs) are **interactive**—hover to see detailed case info, drag to move and rotate the view, or use filters to customize what you see.

---

## 📊 Pivot Tables Overview

All pivot tables are housed in `Narcotics_3D_Maps.xlsx` and drive the corresponding 3D maps:

- **`Master PT`**  
  A pivot table version of the raw data to allow filtering and segmentation by drug type, location, and more.

- **`Methamphetamines`**  
  Filters for arrests involving methamphetamines.

- **`Cocaine`**  
  Filters for arrests involving cocaine.

- **`Drug Delivery < 18`**  
  Shows arrests for drug delivery by individuals under 18.

---

## 🗺️ 3D Map Descriptions

Each map is interactive and corresponds with one of the pivot tables.

### 1. **Chicago Narcotics Arrests Map**
- Based on `Master PT`
- Shows **all arrests across Chicago**
- **Scene 3:** Colored by arrest descriptions (e.g., possession, delivery)
- **Scene 4:** Colored by **arrest location type** (e.g., parking lot)
- Interactive graph included
- Available as video: `Map_Chicago_Narcotics.mp4`

### 2. **Methamphetamine Arrests Map**
- Based on `Methamphetamines`
- Colored by **arrest location type**
- Available as image: `Map_Methamphetamines.png`

### 3. **Cocaine Arrests Map**
- Based on `Cocaine`
- Colored by **arrest location type**
- Interactive graph included
- Image preview: `Map_Cocaine.png`

### 4. **Drug Delivery by Minors Map**
- Based on `Drug Delivery < 18`
- Focused on underage drug delivery arrests
- Colored by **arrest location type** 
- Image preview: `Map_Delivery_Under_18.png`

---

## 📌 Recommendation

While image previews and videos are provided, **the best experience is through Excel's built-in 3D Map tool**:

- Hover to see arrest details by location
- Use filters on the right panel to focus on specific location, date, or arrest type.
- Rotate, move, and zoom to explore data spatially

---

## 🎯 Learning Objectives

- Learn how to visualize geographic arrest data using Excel's 3D Maps
- Segment criminal activity by drug type and demographics
- Apply Pivot Tables to support spatial filtering and analysis

---

