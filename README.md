# 🚦 Toll Booth System Optimization

**Optimizing Toll Gate Operations Using Queuing Theory and Linear Programming**

## 👨‍🎓 Authors
- Raju Kartik N R  
- Vidyasagar L  
- April 20, 2025  

## 📌 Abstract
This research focuses on optimizing traffic flow at the **Sadahalli toll gate** on the Bengaluru–Bellary highway using **Queuing Theory** and **Linear Programming (LP)**. With a traffic load of over 90,000 vehicles/day, the toll plaza faces regular congestion, especially during airport peak hours. Our study combines mathematical modeling and real-time data analysis to recommend optimal lane allocations and reduce average wait time.

> 📥 **To read the full research paper**, please refer to the attached file [`Toll_Booth_system__OPTIMIZATION_.pdf`](./Toll_Booth_system__OPTIMIZATION_.pdf) available in this repository.

## 🧠 Methodology
1. **Data Collection** – Arrival & service rates, lane performance.
2. **Queuing Theory (M/M/c)** – To model traffic behavior and congestion.
3. **Linear Programming (LP)** – To optimize lane allocation for FASTag vs Manual.
4. **Simulation** – To validate results and compare pre/post optimization performance.

## 🔍 Key Highlights
- Used **M/M/c** queuing model to analyze system load and delays.
- Designed an LP model to minimize **total vehicle waiting time**.
- Optimization outcome:  
  - FASTag lanes increased: **1 ➝ 2**  
  - Manual lanes reduced: **2 ➝ 1**  
  - Average wait time dropped from **12 mins ➝ 5 mins**  
  - Queue length reduced from **25 ➝ 8 vehicles**

## 📊 Results
| Metric                 | Before Optimization | After Optimization |
|------------------------|---------------------|--------------------|
| Avg Waiting Time (Wq)  | 12 mins             | 5 mins             |
| Avg Queue Length (Lq)  | 25 vehicles         | 8 vehicles         |
| System Utilization (ρ) | 1.33 (overloaded)   | 0.89 (optimal)     |

## 📚 Keywords
`Queuing Theory`, `Linear Programming`, `Traffic Optimization`, `Toll Booth`, `FASTag`, `Sadahalli`, `Transportation`, `Bengaluru`, `Data Science`

## ✅ Use Case
This model can be applied to toll plazas across India facing congestion issues, especially during festivals, weekends, or near airports.

## 🙌 Acknowledgements
Special thanks to **Vidyashilp University** and our mentors for their guidance and support throughout this research journey.
