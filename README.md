# Water Quality Assessment using Weighted Arithmetic Water Quality Index (WAWQI)

This project evaluates water quality based on multiple physico-chemical parameters using the Weighted Arithmetic Water Quality Index (WAWQI) method.

## 📊 Parameters Used

- **pH**
- **Dissolved Oxygen (DO)**
- **Biochemical Oxygen Demand (BOD)**
- **Total Dissolved Solids (TDS)**
- **Nitrate**
- **Turbidity**
- **Electrical Conductivity (EC)**

Each parameter is weighted based on its importance and compared against standard permissible values.

## 🧮 Formula Used

The WAWQI is calculated using:


Where:
- `Vn` = observed value
- `Sn` = standard permissible value
- `Qn` = quality rating
- `Wn` = unit weight for the parameter

## 📌 Classification of WAWQI

| WAWQI Range | Water Quality |
|-------------|----------------|
| 0–50        | Excellent       |
| 51–100      | Good            |
| 101–200     | Poor            |
| 201–300     | Very Poor       |
| >300        | Unsuitable      |

## 📂 Files

- [`code.ipynb`](code.ipynb): Main notebook for data processing and WAWQI calculation.
- [`wawqi_data.csv`](wawqi_data.csv): Processed output data including WAWQI values and quality class.
- [`wawqi_plot.png`](wawqi_plot.png): Visualization of WAWQI for each water sample.

## 🛠️ How to Run

1. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn
