# 🚗 Washington State Electric Vehicle Dashboard (Tableau)

This project explores the adoption of electric vehicles (EVs) across **Washington State**, using real-world data sourced from [data.gov](https://catalog.data.gov). The interactive dashboard was built in **Tableau** and visualizes trends related to EV type, manufacturer, geography, and model year.

## 📊 Dashboard Overview

The dashboard includes multiple components to help visualize different aspects of EV adoption:

- **Pie Chart – EV Type Split**  
  Categorizes all registered electric vehicles into **Battery Electric Vehicles (BEV)** and **Plug-in Hybrid Electric Vehicles (PHEV)**.

- **Bar Chart – Vehicle Brands**  
  Shows distinct **DOL Vehicle IDs** for each manufacturer (e.g., Tesla, Chevrolet, Nissan), reflecting brand popularity.

- **Bar Chart – Top 10 Counties**  
  Highlights the counties with the highest number of EVs registered, with **King County** leading by a wide margin.

- **Map – Vehicles by Postal Code**  
  A geographic visualization that shows EV distribution based on postal code, with strong clusters around urban areas like **Seattle**.

- **Bar Chart – Model Year Distribution**  
  Visualizes the count of distinct vehicles by **manufacturing year**, helping to track trends over time.

### 🎛 Interactive Filter
An interactive **brand filter** (Make) allows users to focus the entire dashboard on a specific car manufacturer, dynamically updating all visualizations.

## 🧾 Dataset Details

The dataset was obtained from [data.gov.EV-data](https://catalog.data.gov/dataset/electric-vehicle-population-data) and contains information about electric vehicles registered in the U.S., with a focus on Washington State.  

While the dataset contains several columns, I’ve mainly focused on the ones that tell the clearest story about EV adoption in Washington:

- **DOL Vehicle ID** – Unique identifier from the Department of Licensing  
- **VIN** – Vehicle Identification Number  
- **County, City, and Postal Code** – Registration location  
- **Make & Model** – Manufacturer and specific model  
- **Model Year** – Year of manufacture  
- **Electric Vehicle Type** – BEV or PHEV

📌 **Note:** The source dataset is regularly updated, so future visualizations may differ depending on when the data is downloaded.

## 📦 Data File Included

- ✅ `electric_vehicle_data.zip` – A zipped CSV file containing the exact version of the dataset used to build this dashboard.

## 🎥 Project Walkthrough Video

I’ve recorded a full video walkthrough of the dashboard creation process in Tableau:  
🔗 [Watch the video here](https://drive.google.com/file/d/1xKWU8C52dgEfxEuAN-yqzX7VbmNwosN-/view?usp=sharing)


## 📸 Dashboard Screenshot

![Screenshot 2025-04-30 at 17 57 35](https://github.com/user-attachments/assets/d4b5af32-6589-49f5-a16a-4b1ae9959c54)
![2025-04-3017-53-04-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/7b21b456-41c3-4d90-b4a4-d36aea12ab10)



## 📁 Files Included

- Tableau Dashboard Screenshot  
- `README.md`
- `electric_vehicle_data.zip`  
- Tableau Workbook File (`.twb`)  
- Dataset link reference
- Video link reference

## 📌 Notes

- All data is public and sourced from a U.S. government open data portal.
- The dashboard is designed for educational and analytical purposes.

---

**Enjoy exploring the dashboard! 🙂**  
Feel free to reach out with any questions or feedback.
